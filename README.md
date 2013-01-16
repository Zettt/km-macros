My favorite Keyboard Maestro macros. Some of these are meant to be executed in a certain app only. This is normally the case when there is a "general" shortcut set like F1, ↑, or ↓. I have every one of these as separate groups (separated by app they're available in). 

### Clipboard ###

* Append Selection to Clipboard: Puts selected text on clipboard (⌘C) and appends it to the previous entry.
* Manipulate Clipboard: Displays the clipboard contents in a text field for manipulation. Saves changes back to clipboard.

### Finder ###

* Symbolic Link: Shows Create symbolic links using Keyboard Maestro. 

### Final Cut Pro X ###

* Find…: This macro clicks some 200px away from the bottom right corner to highlight the search field in the effects browser. (which, annoyingly, can't be a shortcut assigned to)
* Switch Media: Two macros (activated with F1 and F2) to switch between proxy and high-quality/original media. Essentially what happens is the preference window opens, the second icons gets clicks, and then one of the two radio buttons before the window closes again.

### General Use ###

* Switch back to frontmost app: I'm using this in my [Markdown library](https://github.com/Zettt/km-markdown-library) so the user can search for information somewhere else while the macro is running. This has no purpose other than showing how to do it. It's a demonstration for your own inspiration.

### Mail ###

* Copy Message URL to clipboard: Copies the message URL of a selected message to the clipboard. Useful for OmniFocus. Create a task that links back to the original message.
* Print iTunes Receipt: Macro to print mail as PDF. **Note**: Requires you to have [⌘P set as "Save as PDF…" in System Preferences](http://macsparky.com/blog/2008/3/19/keyboard-shortcut-for-save-as-pdf-in-os-x.html). 

### Markdown ###

[My Markdown library](https://github.com/Zettt/km-markdown-library) is now part of this repository. Read the other readme on how to use these.

### OmniFocus ###
	
* Copy OmniFocus Item URL to Clipboard: Copies OmniFocus URL to clipboard for reference somewhere else. 
* Day Projects: I use a folder labelled "Day Projects", where I have one project for each day of the week. I assign tasks that I want to do over the week to this projects. The projects start on each respective day at 10am. See [this Gist](https://gist.github.com/1401813) for complete history.
* Mark projects active, completed, dropped, on hold: Press ⌃A, ⌃C, ⌃D, ⌃H.

### Special Characters ###

Various macros to insert special or uncommon characters easily, such as Emojis or control characters like ⌘, ⌃ and ⇧.

### System ###

* Keyboard Cleaner Maestro: See [this post](http://mosx.tumblr.com/post/29045607939/keyboard-cleaner-maestro) for thorough explanation and context. Once executed this will launch TextEdit, maximize the window and **block all input (mouse and keyboard)**. This way you can safely clean your Mac and keyboard. Once done press ⇧⌃⌘ and wait a little. The window will close itself and TextEdit will quit. **Be careful with this!**
* Login sombody…: Quickly login as someone else.

### Text ###

Macros which use the "Filter Clipboard" action. Possibilities: calculate selected text, count characters/words/lines, encode/decode HTML Entities, Percent Encode text, lowercase/UPPERCASE/TitleCase text, smarten/straighten quotes, remove style from text.

### TextExpander ###

* Change expansion mode of a selected TextExpander snippet. It's an example on how to create shortcuts for a menu that is otherwise not reachable via shortcuts. Default shortcut is F1, F2, and F3. Set to separate macro group to be only available in TextExpander!

### Windows ###

Manipulate windows with Keyboard Maestro:

* Move by 1px or 25px.
* Resize horizontally/vertically by ± 1px or 25px.
* Resize proportionally
* Several example resize presets
* Measure window: for use in previous resize presets or in the following Set Window Size macro.
* Set Window Size: First measures the frontmost window, then prompts the user for new size.
* Center/maximize window
* Where's my mouse?: Draws a circle on the screen in case you can't find your cursor anymore.

Best practice tip: Set macro group to activate and deactivate on shortcut. (I've set this to ⌃⌥W)

### Participate ###

Feel free to send me Pull Requests with your Keyboard Maestro macros.  
*Please* put the macros in a group named "Keyboard Maestro Macros Repo" first, *before* exporting. When someone downloads/clones this repo and double-clicks a macro, they will be added to that group. This will help to keep this repo more consistent.

If there are numerous macros you want to contribute, then make a separate group, e.g. "Special Characters" in this repository.