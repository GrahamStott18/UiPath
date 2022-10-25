# UiPath Repository for Bots Created in Studio/StudioX

# Keyboard Shortcuts

## File Management:

`Ctrl + Shift + N`      - Creates a new **Blank Process**.

`Ctrl + C`      - Copies a file from the **Project** panel into clipboard. Use `Ctrl + V` too paste it anywhere in the tree. 

`Ctrl + O`      - Open a previously created workflow (The `.xaml` or `project.json` file).

`Ctrl + L`      - Opens the folder where the Log files are stored.

`Ctrl + S`      - Saves the currently opened workflow.

`Ctrl + Shift + S`      - Saves ALL open workflows.

`Ctrl + V`      - Pastes a file from the clipboard into the **Project** panel.

`Ctrl + Tab / Alt + F7`     - Move focus between open workflow files / Studio panels. When you hold the modifier key (`Ctrl` or `Alt` respectively), a window appears, allowing you to switch between files and panels.
<br></br>

## Search:

`F3` or `Ctrl + Shift + P`      - Opens the **Command Palette**.

**`Ctrl + Shift + T`**      - Opens the **Add an Activity** search bar.

`Ctrl + Shift + F`      - Opens the **Go to file** search bar.

`Ctrl + F`      - Opens the **Universal Search** bar.

`Ctrl + J`      - Opens the **Jump to activity** search bar.

`Ctrl + 1`      - Switches to the **Current File** tab in the **Universal Search** bar.

`Ctrl + 2`      - Switches to the **All Files** tab in the **Universal Search** bar.

`Ctrl + 3`      - Switches to the **Activities** tab in the **Universal Search** bar.

`Ctrl + 4`      - Switches to the **Variables** tab in the **Universal Search** bar.

`Ctrl + 5`      - Switches to the **Arguments** tab in the **Universal Search** bar.

`Ctrl + 6`      - Switches to the **Imports** tab in the **Universal Search** bar.

`Ctrl + 7`      - Switches to the **Project Files** tab in the **Universal Search** bar.

`Ctrl + 8`      - Switches to the **Dependencies** tab in the **Universal Search** bar.

`Ctrl + 9`      - Switches to the **Snippets** tab in the **Universal Search** bar.

`Ctrl + Alt + A`      - Opens and focuses the **Properties** panel.

`Ctrl + Alt + F`      - Sets the focus to the search box in the **Activities** panel.

`Ctrl + Alt + O`      - Sets the focus to the search box in the **[UI Objects Browser](https://docs.uipath.com/studio/v2020.10/docs/about-object-repository)** panel.

`Ctrl + Alt + P`      - Opens and focuses the search bar in the **Project** panel.

`Ctrl + Alt + S`      - Opens and focuses the search bar in the **Snippets** panel.

`Tab`       - Navigates to the next item in the panel or the next element in the activity.
<br></br>

## Comment:

`Ctrl + D`      - Ignores the activity that is currently selected by placing it into a **Comment Out** container.

`Ctrl + E`      - Removes the activity from the **Comment Out** container it was placed in. 
<br></br>

## Debugging:

`F9`		- Marks the selected activity with a breakpoint.

`Ctrl + Shift + B`		- Opens the **Breakpoints** panel.

`Ctrl + Alt + E`		- Opens the **Error List** panel. 

`F10`		- When debugging, steps over the execution of a block of activities in the currently selected workflow. 

`F11`		- When debugging, enables you to step into a block of activities and executes the first one. 

`Shift + F11`		- When debugging, steps out of the current container after its last activity is executed. 
<br></br>

## Recording:

`Ctrl + Alt + B`		- Opens the **Basic Recording** toolbar.

`Ctrl + Alt + C`		- Opens the **Citrix Recording** toolbar.

`Ctrl + Alt + D`		- Opens the **Desktop Recording** toolbar.

`Ctrl + Alt + W`		- Opens the **Web Recording** toolbar.

`F2`		- Adds delay during a recording activity. 

`F3`		- Lets you specify a custom recording region.

`F4`		- Lets you choose the UI Framework to record, which can be **Default, AA,** and **UIA**.
<br></br>

## Workflow Analysis and Execution:

`F5`		- Runs the current project in debugging mode, starting with the `.xaml` file set as Main.

`Ctrl + F5`		- Runs the current project. 

`F6`		- Runs the currently opened `.xaml` file in debugging mode. 

`Ctrl + F6`		- Runs the currently opened `.xaml` file. 

`F7`		- Checks the file for validation errors and **Workflow Analyzer** violations.

`Shift + F7`		- Checks the whole project for validation errors and **Workflow Analyzer** violations. 

`F8`		- Checks the currently opened workflow for validation errors. 

`Shift + F8`		- Checks the whole project for validation errors. 

`Pause`		- Pauses the execution of the current workflow, in both normal and debug mode. 

`F12`		- Stops the execution of the current workflow, in both normal and debug mode. 
<br></br>

## Selected Activity:

`Ctrl + T`		- Places the activity inside the **Try** section of a **Try Catch** activity. 

`Ctrl + N`		- Creates a new **Sequence Diagram** in the current project. 

`Ctrl + C`		- Copies the selected activity or activities to the clipboard.

`Ctrl + V`		- Pastes the copied activity or activities inside the selected item. 

`Ctrl + K`		- Creates a variable of the same type as the required type of the activity when used in an input field or the **Expression Editor**. If an expression already exists in the field, before pressing (`Ctrl + K`), you can select that expression or a part of it to use the selected text as the name of the new variable. 

`Ctrl + M`		- Creates an **In** argument of the same type as the required type of the activity when used in an input field or the **Expression Editor**. If an expression already exists in the field, before pressing (`Ctrl + M`), you can select that expression or a part of it to use the selected text as the name of the new argument. 

`Ctrl + Shift + M`		- Creates an **Out** argument of the same type as the required type of the activity when used in an input field or the **Expression Editor**. If an expression already exists in the field, before pressing (`Ctrl + Shift + M`), you can select that expression or a part of it to use the selected text as the name of the new argument. 

`Ctrl + Shift + E`		- Opens the **Expression Editor** when used inside activity input fields. 

`Ctrl + Space`		- Opens the IntelliPrompt window.

`F2`		- Allows for renaming the selected activity.

`Shift + F2`		- Adds an annotation to a selected activity.

`Enter`		- Saves the data added in the activity input field. 

`Shift + Enter`		- Adds a new lline in the activity input field. 
<br></br>

## Miscellaneous:

`F1`        - Enables you to access a help topic associated with the currently selected element. 

`Ctrl + P`      - Opens the **Manage Packages** window. 

`Esc`       - Closes the **Publish, Manage Packages, File Diff** windows.

`Ctrl + F1`     - Minimizes or expands the ribbon. 

`Shift + Tab`       - Navigates to the previous activity or node in the **Activities** panel. 
<br></br>
<br></br>

# Expression Editor Notes 

`vbCrLf`  - Will let you start a new line while during an expression. Basically like pressing ENTER while displaying expression. 

		- Represents a carriage return character, for print and display functions (In Visual Basic) 

		