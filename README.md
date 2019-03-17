# fascript-lang README

VS Code syntax highlighting support for the Fascript micro-language.

Based on the [Syntax Highlight Guide](https://code.visualstudio.com/api/language-extensions/syntax-highlight-guide) and Python Language extension source.

# Modifying the Extension

* The extension folder contains all of the files necessary.
* `package.json` - this is the manifest file in which you declare your language support and define the location of the grammar file that has been copied into your extension.
* `syntaxes/fascript.tmLanguage.json` - this is the Text mate grammar file that is used for tokenization.
* `language-configuration.json` - this is the language configuration, defining the tokens that are used for comments and brackets.

## Get up and running straight away

* Make sure the language configuration settings in `language-configuration.json` are accurate.
* With `fascript.tmLanguage.json` open, press `F5` to open a new window with your extension loaded.
* Create a new file with a file name suffix matching your language.
* Verify that syntax highlighting works and that the language configuration settings are working.
* Use the [Scope Inspector](https://code.visualstudio.com/api/language-extensions/syntax-highlight-guide#scope-inspector) to debug new rules.

## Make changes

* You can relaunch the extension from the debug toolbar after making changes to the files listed above.
* You can also reload (`Ctrl+R` or `Cmd+R` on Mac) the VS Code window with your extension to load your changes.

## Install the extension

* To start using the extension with Visual Studio Code copy it into the `<user home>/.vscode/extensions` folder and restart Code.
* To share the extension with the world, read on https://code.visualstudio.com/docs about publishing an extension.

## Release Notes

### 1.0.0

Initial release.
