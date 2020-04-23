# Testing jams

Collect accessibility issues for public websites as part of A11ySea events.

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
