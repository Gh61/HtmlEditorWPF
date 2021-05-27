# EasyHtmlEditor
This is a fork of [HtmlEditorWPF](https://github.com/LBRNZ/HtmlEditorWPF) wich is a fork of [SmithHtmlEditor](https://github.com/adambarath/SmithHtmlEditor).

## Improvements
- migrated to .NET 4.5

## Discontinued
After testing the current functionality, I decided not to use this component and write my own.
- During the testing it crashed a few times (exceptions coming from commands, other exceptions comming from WinFormsIntegration)
- New ENTER functionality doesn't work as expected (is inserting 2 new lines)
- After changing font style (Bold, Italic, ...), after moving the cursor back to editor it selects all text
- *maybe some other problems. At this point I stopped testing and started on working on custom Editor from scratch*

## Preview
![](Readme/preview.PNG?raw=true)
