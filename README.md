# Testing jams

Collect accessibility issues for public websites as part of A11ySea events.

## Get Started

If you don't have a Github account, you need to [create an account](https://github.com/join) to file issues. You will need an email address, and will be asked to create a username and password. Both the email address and password can be easily changed later.

For the testing jams, the only thing you will need to do is file issues, which is done directly through the github website. We have handy issue links from each project readme (viewed by clicking on the directory for the project or website, or one of the links below). All you need to do is click on the link to file a bug report or feature suggestion, and information and prompts will be pre-filled for you.

For more general information about filing issues, there is a [Github help page on creating issues](https://help.github.com/en/github/managing-your-work-on-github/creating-an-issue), and a [guide to mastering issues](https://guides.github.com/features/issues/).

### Projects
- [King County COVID-19 Website](KingCounty-COVID-19)
- [CDC COVID-19 Website](CDC-COVID-19)

## General Testing Tools

### Accessibility Insights for Web

[Accessibility Insights for Web](https://accessibilityinsights.io/docs/en/web/overview) is available as a browser plugin for Chrome or Edge, or as a desktop app for Windows. It has a [fast pass](https://accessibilityinsights.io/docs/en/web/getstarted/fastpass) tool for running a high level check of common issues, as well as a set of ad hoc tools, and a walkthrough for doing a full assessment.

### Keyboard

Before starting keyboard or screen reader testing on a Mac, go into **System Preferences  > Keyboard > Shortcuts** and make sure `All controls` is selected.

Here are the keystrokes you'll use the most to interact. See [WebAIM's Keyboard Accessibility guide](https://webaim.org/techniques/keyboard/) for more.

|Action|Keystroke|
|---|---|
|Move focus to the next focusable element| `tab`|
|Move focus to the previous focusable element|`shift` + `tab`|
|Activate a link|`return`|
|Activate a button|`return` or `space`|
|Check or uncheck a checkbox|`space`|
|Change a radio button selection|`↑` or `↓`|
|Change a select/popup selection|`↑` or `↓`|

## Screen Reader Testing

Before testing with a screen reader:

1. Get out some headphones if you've got them.
1. Adjust the speaking rate in the screen reader settings until it's easy to understand

### Modes in Windows screen readers

All Windows screen readers use an interaction model with different "modes" that a user can switch between, and that are sometimes triggered automatically by different UI elements.

In virtual mode (also called scan mode, browse mode, or virtual PC cursor mode), most keystrokes including arrow keys and alphanumeric keys are captured by the screen reader and used to navigate. They are not passed through to the underlying web page so, for example, it is not possible to type into a text field in this mode.

In forms or application mode, all keystrokes are passed through to the web page. In this mode, you can type or use arrow keys to move between tab items or options in a listbox. However, you cannot use arrows or keyboard shortcuts to quickly navigate between form fields, links, headings, and so on.

[More on screen reader modes](https://tink.uk/understanding-screen-reader-interaction-modes/) from Léonie Watson.

### NVDA on Windows

[NVDA can be downloaded from NV Access](https://www.nvaccess.org/download/). On a full keyboard, the default modifier key is `Insert`, and on a standard laptop keyboard, the default modifier key is `Capslock`.

|Action|Keystroke|
|---|---|
|Stop reading|`Control`|
|Start reading|`Insert` + `↓`|
|Elements list|`Insert` + `F7`|
|Toggle browse mode|`Insert` + `Space`|
|Read next or previous item|`↓` or `↑`|
|Next form field|`F`|
|Next heading|`H`|
|Next table|`T`|
|Navigate cells in a table|`Ctrl` + `Alt` + `↓`/`↑`/`←`/`→`|

[more NVDA commands](https://dequeuniversity.com/screenreaders/nvda-keyboard-shortcuts)

### Narrator on Windows

Narrator can be turned on in **Settings > Ease of Access > Narrator**, or by pressing **Ctrl + Windows Key + Enter**.

|Action|Keystroke|
|---|---|
|Stop reading|`Control`|
|Start reading|`Capslock` + `M`|
|Toggle scan mode|`Capslock` + `Space`|
|Read next or previous item|`↓` or `↑`|
|Next form field|`F`|
|Next heading|`H`|
|Next table|`T`|
|Navigate cells in a table|`Ctrl` + `Alt` + `↓`/`↑`/`←`/`→`|

[more Narrator commands](https://dequeuniversity.com/screenreaders/narrator-keyboard-shortcuts)

### JAWS on Windows

JAWS requires a license, or is limited to testing for 45 minutes before requiring a restart to continue. [JAWS can be downloaded from Freedom Scientific](https://support.freedomscientific.com/Downloads/JAWS).

|Action|Keystroke|
|---|---|
|Stop reading|`Control`|
|Start reading|`Insert` + `↓`|
|Elements list|`Insert` + `F3`|
|Toggle virtual PC cursor|`Insert` + `Z`|
|Read next or previous item|`↓` or `↑`|
|Next form field|`F`|
|Next heading|`H`|
|Next table|`T`|
|Navigate cells in a table|`Ctrl` + `Alt` + `↓`/`↑`/`←`/`→`|

[more JAWS commands](https://dequeuniversity.com/screenreaders/jaws-keyboard-shortcuts)

### VoiceOver on macOS

A few Voiceover tips:

- Try the tutorial under **System Preferences > Accessibility > VoiceOver > Open VoiceOver Training...**.
- **VoiceOver uses `Control` + `Option` as its main set of modifier keys.** These will be used to perform most commands for reading the page.
- **VoiceOver sometimes puts chunks of content into what it identifies as "groups".** You can use the drill down/drill up commands to enter and exit groups. When you've reached the end of a group, or the end of a web page, you'll hear a knocking noise.

|Action|Keystroke|
|---|---|
|Turn VO on or off| `command` + `f5`, or `command` + Touch ID button 3 times|
|Stop reading|`control`|
|Open menu|`control` + `option` + `U`|
|Close menu|`esc`|
|Next/previous item in the current menu|`↑` or `↓`|
|Next/previous menu|`←` or `→`|
|Jump from the selected menu item to that element on the page|`return`|
|Read the next element in the page|`control` + `option` + `→`|
|Read the previous element in the page|`control` + `option` + `←`|
|Move down into a group|`control` + `option` + `↓`|
|Move up out of a group|`control` + `option` + `↑`|

[macOS VoiceOver user guide](https://help.apple.com/voiceover/mac/)

### VoiceOver on iOS

To turn on VoiceOver for the first time, go to **Settings > General > Accessibility > VoiceOver**, and toggle the switch. To make typing easier, you can set **Typing Style** to _Direct Touch Typing_. You can also assign a home button shortcut to turn VoiceOver and other accessibility tools on and off under **Settings > General > Accessibility > Accessibility Shortcut**.

|Action|Gesture|
|---|---|
|Select and speak|Tap or touch|
|Select the next item|Swipe right|
|Select the previous item|Swipe left|
|Speak everything from the current selection|Two-finger swipe down|
|Pause or continue speaking|Two-finger tap|
|Scroll|Three-finger swipe|
|Activate the selection|Double tap|
|Standard double tap|Triple tap|
|Drag a slider|Swipe up or down with one finger|
|Turn the rotor|Mime turning a knob on the screen with two fingers|
|Cycle through the item type selected with the rotor|Swipe down or up|

[Full list of iOS VoiceOver gestures](https://support.apple.com/guide/iphone/learn-voiceover-gestures-iph3e2e2281/ios)

### TalkBack on Android

All TalkBack gestures use one finger. To bypass TalkBack and interact directly with an app, use two fingers.

|Action|Gesture|
|---|---|
|Select and speak|Tap or touch|
|Select the next item|Swipe right|
|Select the previous item|Swipe left|
|Scroll forward|Swipe right then left|
|Scroll backward|Swipe left then right|
|Activate the selection|Double tap|
|Drag a slider higher|Swipe right then left|
|Drag a slider lower|Swipe left then right|
|Open local context menu|Swipe up then right|
|Open global context menu|Swipe down then right|
|Activate the home button|Swipe up then left|

[TalkBack gestures](https://support.google.com/accessibility/android/answer/6151827?hl=en)

### Contrast tools

To test Windows High Contrast Mode, go to **Settings > Ease of Access > High Contrast** and turn high contrast mode on. Check that text, links, and disabled items all have adopted the color defined in System Settings. Additionally, check that focus states and selected states are visible.

[More display color modes](https://a11yproject.com/posts/operating-system-and-browser-accessibility-display-modes/)