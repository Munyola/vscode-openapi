# OpenAPI extension for Visual Studio Code

This [Visual Studio Code](https://code.visualstudio.com/) (VS Code) [extension](https://marketplace.visualstudio.com/items?itemName=42Crunch.vscode-openapi) adds rich support for the [OpenAPI Specification](https://github.com/OAI/OpenAPI-Specification) (OAS) (formerly known as Swagger Specification) in JSON or YAML format. The features include, for example, IntelliSense, linting, schema enforcement, code navigation, definition links, snippets, and more!

Both OAS v2 and v3 are supported.

## Quick start

After installing the plugin, open any JSON or YAML file that contains an API definition following OAS v2 or OAS v3 in VS Code. The plugin automatically detects that this is an OpenAPI file, and the OpenAPI button <img src="https://raw.githubusercontent.com/42Crunch/vscode-openapi/master/images/OpenAPI%20button.PNG" width=20 height=19> is shown in the left-hand panel.

<img src="https://github.com/42Crunch/vscode-openapi/blob/master/images/OpenAPI%20Explorer.PNG?raw=true" width=400 height=389>

## Create new OpenAPI files

1. Press **Ctrl+Shift+P** on Windows or Linux, or **Cmd+Shift+P** on a Mac.   
2. In the command prompt, start typing `new openapi`, and click the corresponding command to create either an OAS v2 or v3 template file.
3. Use the OpenAPI explorer to populate the template with new paths and other elements as needed.
4. Save the file to your disk to fully enable intellisense.

![Create new OpenAPI file from a template](https://github.com/42Crunch/vscode-openapi/blob/master/images/New%20OpenAPI%20file.gif?raw=true)

## OpenAPI navigation
1. Open an OpenAPI file.
2. Click the OpenAPI button to switch to the OpenAPI explorer view.
3. Expand the sections and elements in the file as needed, and click the ones you want to jump to in the editor.

![Navigation inside the OpenAPI file](https://github.com/42Crunch/vscode-openapi/blob/master/images/Naviation.gif?raw=true)

## Add new elements in the OpenAPI explorer
1. In OpenAPI explorer pane, go to the section where you want to add a new element, and click the **...** menu.
2. Click the item you want to add from the dropdown list.

![Add new API path and verb](https://github.com/42Crunch/vscode-openapi/blob/master/images/Add%20paths%20and%20verbs.gif?raw=true)

## IntelliSense

As you start typing OpenAPI elements or their values, the context-sensitive list of available options is displayed in the IntelliSense menu. In JSON OpenAPI files, just type double-quote (`"`) to show the menu, and type further to filter the list. In YAML OpenAPI files, start typing the property name.

You can also use the corresponding VS Code hotkey (**Ctrl+Space** on Windows, **Cmd+Space** on Mac) to forse-open the IntelliSense menu.

![IntelliSense for OpenAPI editing](https://github.com/42Crunch/vscode-openapi/blob/master/images/Intellisense.gif?raw=true)

## Go to definition

To jump to view the definition from a reference in your API, either **Ctrl+click** a reference, or right-click a reference and click **Go to Definition** in the shortcut menu.

![Go to definition](https://github.com/42Crunch/vscode-openapi/blob/master/images/Go%20to%20Definition.gif?raw=true)

## Known issues


- For new files, IntelliSense does not work until you save the file. File extension needs to be .json or .yaml.
- When you expand the sections and elements in the OpenAPI explorer, if the the left-hand panel gets very long, VS Code may push the last sections out of the UI. To view the sections that got pushed out, minimize the sections and elements you do not need. There is no scroll bar (yet) for the explorer section.

## Feedback

When you have a minute **PLEASE** submit your feedback and feature requests at [this superquick survey](https://www.surveymonkey.com/r/H3C8VC6).

Submit your bug reports at [GitHub project Issues](https://github.com/42Crunch/vscode-openapi/issues).

Add needless to say that your reviews at [VS Code marketplace](https://marketplace.visualstudio.com/items?itemName=42Crunch.vscode-openapi&ssr=false#review-details) mean the world to us.
