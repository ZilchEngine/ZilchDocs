Many code editors offer some form of code completion that suggests token or line options based on the characters that have already been typed on the current line. Zilch offers both code completion and basic word completion.

 # Common Uses

 - Reduces amount of typing
 - Encourages proper code formatting
 - Reduces chance for simple typing, spelling, and character case errors
 - Reduces the immediate API knowledge needed
 - Provides an avenue for code base exploration

 # Using Code Completion
While writing code in Zilch, one will often see the code/word completion window pop up. This window will suggest possible ways to complete the token that is currently being typed.



![image](https://raw.githubusercontent.com/ZilchEngine/ZilchFiles/master/doc_files/47411.png)


 ## Navigation and Activation
The code completion window will appear when a `.` is typed following a valid identifier, if that identifier has any members or functions that can be shown in a code completion window. The code completion list is populated by members and functions of the identifier before the `.`.

`Tab` or `Enter` can be used to complete the current token as the highlighted suggestion.

If the first suggestion is not the desired member, the suggestion list box can be navigated with the `up` and `down` keys and the mouse cursor.



![TabSuggestions](https://raw.githubusercontent.com/ZilchEngine/ZilchFiles/master/doc_files/47413.gif)



(NOTE)**Event Connection Suggestion**: Upon initial inspection of the partial line `Zilch.Connect`, one may not expect typing the partial token `Connect` to cause the tab completion menu to display the suggestions `Connect`, `Disconnect`, and `DisconnectAll`. However, upon looking again, it can be seen that all of the suggestions contain `Connect`, even if they do not start with `Connect`. ![LoopedDelayedEvents](https://raw.githubusercontent.com/ZilchEngine/ZilchFiles/master/doc_files/93931.gif)

 ## Word Completion
While the code completion window is open, one may notice it will occasionally have a red border:



![TabTypedSuggestions](https://raw.githubusercontent.com/ZilchEngine/ZilchFiles/master/doc_files/47415.gif)


This indicates that the menu has switched to **word completion** mode. If it is enabled (it can be disabled in the [ TextEditorConfig](https://github.com/ZilchEngine/ZilchDocs/blob/master/zilch_editor_documentation/zilchmanual/editor/texteditor/texteditorconfig.md)), the word completion window pops up any time an alphabetical character is typed and there isn't already a code or word completion window open. The word completion list is populated by every whole word it can find in the current file. In addition, it also lists all keywords (such as `if` and `foreach`), special words (like `this` and `value`), and all bound type names (like `Transform` and `Event`).

 ## Script Errors
Occasionally when using the code editor, the user may find that class types that they defined are not available in code completion options. This usually happens when trying to declare a variable of a type that was just defined and indicates that there is another error somewhere in the project. Since Nada is a statically compiled language, each file must individually compile in order for the whole project to do so. This allows all contexts within the user's code to be aware of all definitions within the project. However, it means that since code completion depends on a clean project compilation, a single error will prevent code completion options from being correctly generated. In this case, the word completion menu will appear.

 # Related Materials
 ## Manual Pages
- [Text Editor Hotkeys](https://github.com/ZilchEngine/ZilchDocs/blob/master/zilch_editor_documentation/zilchmanual/editor/texteditor/texteditorhotkeys.md)
- [Text Editor Config](https://github.com/ZilchEngine/ZilchDocs/blob/master/zilch_editor_documentation/zilchmanual/editor/texteditor/texteditorconfig.md)

 ## Code Reference
- [TextEditorConfig](https://github.com/ZilchEngine/ZilchDocs/blob/master/zilch_editor_documentation/code_reference/class_reference/texteditorconfig.md) 

 ## Tasks
- T442 

 