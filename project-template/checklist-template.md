# Accessibility testing jam

This worksheet doesn’t include _every_ test for accessibility, but it will get you on your way. It includes steps for testing:

1. Easy-to-automate tests
1. Color and contrast
1. Images and media
1. Language and structure
1. Motion
1. Keyboard support

The items here target [Web Content Accessibility Guidelines (WCAG) 2.1 Level A and AA success criteria](https://www.w3.org/WAI/WCAG21/quickref/?currentsidebar=%23col_customize&levels=aaa).

## Checklist

### 1. Easy-to-automate tests

Use Accessibility Insights for Web to get an idea for the type of tests that can be easily automated.

1. [Install Accessibility Insights for Web in Chrome](https://chrome.google.com/webstore/detail/accessibility-insights-fo/pbjjkligggfmakdaogkfomddhfmpjeni)
2. Go to **Ad hoc tools**, and turn on the **Automated checks** tool.

### 2. Color and contrast

- [ ] Normal-sized text has a contrast of at least 4.5:1 (*automated*, [1.4.3 Contrast (Minimum) — Level AA](https://www.w3.org/WAI/WCAG21/quickref/#contrast-minimum))
- [ ] Large text has a contrast of at least 3:1 (*automated*, [1.4.3 Contrast (Minimum) — Level AA](https://www.w3.org/WAI/WCAG21/quickref/#contrast-minimum))
- [ ] Informative icons have a contrast of at least 3:1 (*manual*, [1.4.11 Non-text Contrast — Level AA](https://www.w3.org/WAI/WCAG21/quickref/#non-text-contrast))
- [ ] User interface indicators have a contrast of at least 3:1 (*manual*, [1.4.11 Non-text Contrast — Level AA](https://www.w3.org/WAI/WCAG21/quickref/#non-text-contrast))
- [ ] Color alone isn't used to convey information (*manual*, [1.4.1 Use of Color — Level A](https://www.w3.org/WAI/WCAG21/quickref/#use-of-color))
- [ ] Information displays correctly in Windows High Contrast mode (*manual*, [1.4.1 Use of Color — Level A](https://www.w3.org/WAI/WCAG21/quickref/#use-of-color))

### 3. Images and media

- [ ] Images that convey information have a helpful text equivalent (*automated/manual*, [1.1.1 Non-text Content — Level A](https://www.w3.org/WAI/WCAG21/quickref/#non-text-content))
- [ ] Videos have captions or transcripts (*manual*, [1.1.1 Non-text Content — Level A](https://www.w3.org/WAI/WCAG21/quickref/#non-text-content), [1.2.1 Audio-only and Video-only (Prerecorded) — Level A](https://www.w3.org/WAI/WCAG21/quickref/#audio-only-and-video-only-prerecorded), [1.2.2 Captions (Prerecorded) — Level A](https://www.w3.org/WAI/WCAG21/quickref/#captions-prerecorded), [1.2.4 Captions (Live) — Level AA](https://www.w3.org/WAI/WCAG21/quickref/#captions-live))
- [ ] Audio has transcripts (*manual*, [1.1.1 Non-text Content — Level A](https://www.w3.org/WAI/WCAG21/quickref/#non-text-content), [1.2.1 Audio-only and Video-only (Prerecorded) — Level A](https://www.w3.org/WAI/WCAG21/quickref/#audio-only-and-video-only-prerecorded), [1.2.2 Captions (Prerecorded) — Level A](https://www.w3.org/WAI/WCAG21/quickref/#captions-prerecorded), [1.2.4 Captions (Live) — Level AA](https://www.w3.org/WAI/WCAG21/quickref/#captions-live))

### 4. Language and structure

- [ ] The page has a language (*automated*, [3.1.1 Language of Page — Level A](https://www.w3.org/WAI/WCAG21/quickref/#language-of-page))
- [ ] Headings help convey the page structure and use logical levels (*assisted*, [1.3.1 Info and Relationships — Level A](https://www.w3.org/WAI/WCAG21/quickref/#info-and-relationships), [2.4.6
Headings and Labels — Level AA](https://www.w3.org/WAI/WCAG21/quickref/#headings-and-labels))
- [ ] Lists are conveyed programmatically (*manual*, [1.3.1 Info and Relationships — Level A](https://www.w3.org/WAI/WCAG21/quickref/#info-and-relationships))
- [ ] Tables are used for tabular data (*manual*, [1.3.1 Info and Relationships — Level A](https://www.w3.org/WAI/WCAG21/quickref/#info-and-relationships))
- [ ] Forms have clear labels and instructions (*automated/manual*, [2.4.6
Headings and Labels — Level AA](https://www.w3.org/WAI/WCAG21/quickref/#headings-and-labels), [2.5.3
Label in Name — Level A](https://www.w3.org/WAI/WCAG21/quickref/#label-in-name), [3.3.2 Labels or Instructions — Level A](https://www.w3.org/WAI/WCAG21/quickref/#labels-or-instructions), [4.1.2 Name, Role, Value — Level A](https://www.w3.org/WAI/WCAG21/quickref/#name-role-value))
- [ ] Links have clear text (*automated/manual*, [2.4.4 Link Purpose (In Context) — Level A](https://www.w3.org/WAI/WCAG21/quickref/#link-purpose-in-context), [2.5.3
Label in Name — Level A](https://www.w3.org/WAI/WCAG21/quickref/#label-in-name), [4.1.2 Name, Role, Value — Level A](https://www.w3.org/WAI/WCAG21/quickref/#name-role-value))
- [ ] Errors are clearly conveyed (*manual*, [3.3.3 Error Suggestion — Level AA](https://www.w3.org/WAI/WCAG21/quickref/#error-suggestion))
- [ ] The page has a clear and logical title (*automated/manual*, [2.4.2 Page Titled — Level A](https://www.w3.org/WAI/WCAG21/quickref/#page-titled))

### 5. Motion

- [ ] Animations can be paused or stopped (*manual*, [2.2.2 Pause, Stop, Hide — Level A](https://www.w3.org/WAI/WCAG21/quickref/#pause-stop-hide))
- [ ] Animations do not cause seizures (*manaul*, [2.3.1 Three Flashes or Below Threshold — Level A](https://www.w3.org/WAI/WCAG21/quickref/#three-flashes-or-below-threshold))

### 6. Keyboard support

- [ ] Links, buttons, form fields and all other controls can get keyboard focus and be used with the keyboard (*assisted*, [2.1.1 Keyboard — Level A](https://www.w3.org/WAI/WCAG21/quickref/#keyboard), [2.5.4 Motion Actuation — Level A](https://www.w3.org/WAI/WCAG21/quickref/#motion-actuation))
- [ ] Keyboard focus order is logical (*assisted*, [2.4.3 Focus Order — Level A](https://www.w3.org/WAI/WCAG21/quickref/#focus-order))
- [ ] Keyboard focus doesn't get stuck (*assisted*, [2.1.2 No Keyboard Trap — Level A](https://www.w3.org/WAI/WCAG21/quickref/#no-keyboard-trap))
- [ ] Keyboard focus is visible (*manual*, [2.4.7 Focus Visible — Level AA](https://www.w3.org/WAI/WCAG21/quickref/#focus-visible))
- [ ] Custom keyboard inputs don't cause conflicts (*manual*, [2.1.4 Character Key Shortcuts — Level A](https://www.w3.org/WAI/WCAG21/quickref/#character-key-shortcuts))

## Tools

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

### VoiceOver on macOS

Before testing with VoiceOver on macOS:

1. Get out some headphones if you've got them.
1. Go into **System Preferences > Accessibility > VoiceOver > Open VoiceOver Utility... > Speech** and reduce the rate to around 40 (or wherever you feel comfortable).
1. Fire up the tutorial under **System Preferences > Accessibility > VoiceOver > Open VoiceOver Training...**.
1. Open up **Safari** to test your page.

A few Voiceover tips:

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