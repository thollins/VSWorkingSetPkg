VSWorkingSetPkg
===============

This vsix extension package offers a Recently Used and Frequently Used list of source files in a dockable tool window, on a per-solution basis. 

This extension uses C# code to demonstrate the following:

    Create a dockable custom tool window in Visual Studio
    Access the tool window via the Tools menu
    Add a context menu item to any file in the Solution Explorer window
    Invoke an operation in the extension for the selected file (.cpp currently)
    Handle various Visual Studio events (opening/closing solutions and documents, etc)
    Open a file in the editor and autoscroll to the last active line (mostly working)
    Load/Save serialized XML user data to/from AppData folder 
