# Smart Column Indenter

This extension adds support for indenting code into columns, to make your code more beautiful, readable, clear and with fewer lines of code.

**This extensions is not finished yet. Please, wait for the first release (version 1.0.0) to rate or write a review. I only published it because it's my first one and I had to learn how to publish it.**

The work is in progress at the github repository: https://github.com/lmcarreiro/smart-column-indenter

## Features

### With column indentation

```ts
{ label: 'Id'          , name: 'id'          , hidden: true                                                                                      },
{ label: 'Name'        , name: 'name'        , hidden: false, width: 25, align: 'left' , editable: true , edittype: 'text'                       },
{ label: 'Description' , name: 'description' , hidden: false, width: 50, align: 'left' , editable: false, edittype: 'text'                       },
{ label: 'Value'       , name: 'value'       , hidden: false, width: 25, align: 'right', editable: true , edittype: 'text', formatter: 'number'  }
```

### Without column indentation

```ts
{ label: 'Id', name: 'id', hidden: true },
{ label: 'Name', name: 'name', hidden: false, width: 25, align: 'left', editable: true, edittype: 'text' },
{ label: 'Description', name: 'description', hidden: false, width: 50, align: 'left', editable: false, edittype: 'text' },
{ label: 'Value', name: 'value', hidden: false, width: 25, align: 'right', editable: true, edittype: 'text', formatter: 'number' }

//or

{
    label: 'Id',
    name: 'id',
    hidden: true
}, {
    label: 'Name',
    name: 'name',
    hidden: false,
    width: 25,
    align: 'left',
    editable: true,
    edittype: 'text'
}, {
    label: 'Description',
    name: 'description',
    hidden: false,
    width: 50,
    align: 'left',
    editable: false,
    edittype: 'text'
}, {
    label: 'Value',
    name: 'value',
    hidden: false,
    width: 25,
    align: 'right',
    editable: true,
    edittype: 'text',
    formatter: 'number'
}

```

Describe specific features of your extension including screenshots of your extension in action. Image paths are relative to this README file.

For example if there is an image subfolder under your extension project workspace:

\!\[feature X\]\(images/feature-x.png\)

> Tip: Many popular extensions utilize animations. This is an excellent way to show off your extension! We recommend short, focused animations that are easy to follow.

## Requirements

If you have any requirements or dependencies, add a section describing those and how to install and configure them.

## Extension Settings

Include if your extension adds any VS Code settings through the `contributes.configuration` extension point.

For example:

This extension contributes the following settings:

* `myExtension.enable`: enable/disable this extension
* `myExtension.thing`: set to `blah` to do something

## Known Issues

Calling out known issues can help limit users opening duplicate issues against your extension.

## Release Notes

Users appreciate release notes as you update your extension.

### 1.0.0

Initial release of ...

### 1.0.1

Fixed issue #.

### 1.1.0

Added features X, Y, and Z.

-----------------------------------------------------------------------------------------------------------

## Working with Markdown

**Note:** You can author your README using Visual Studio Code.  Here are some useful editor keyboard shortcuts:

* Split the editor (`Cmd+\` on OSX or `Ctrl+\` on Windows and Linux)
* Toggle preview (`Shift+CMD+V` on OSX or `Shift+Ctrl+V` on Windows and Linux)
* Press `Ctrl+Space` (Windows, Linux) or `Cmd+Space` (OSX) to see a list of Markdown snippets

### For more information

* [Visual Studio Code's Markdown Support](http://code.visualstudio.com/docs/languages/markdown)
* [Markdown Syntax Reference](https://help.github.com/articles/markdown-basics/)

**Enjoy!**