# VBE Helper Addin
An addin for Excel 2007+ that does some nifty stuff in the code editor.

## VBE Helpers

### Exporting and Importing Code

The export and import options are stored in each module. These options start with a `'!`.  This can be changed to your liking in the config module.

Current options:
* `no-export`            - file is not exported. I use this in a lot of quick testing code.
* `no-reload`            - file will not be reloaded from the file path, even if the command if given
* `relative-path <path>` - path to save to/load from. This is relative to the current workbook's file location.

## ideas
* multiline option parsing: for documentation, etc
* array options: for references and requires