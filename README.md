# VsCode DotNet Settings

## To reset default settings *in Windows*

* Delete folder: C:\Users\username\AppData\Roaming\Code\User
* Delete folder: C:\Users\username\.vscode\extensions

## Install useful extensions for working with .NET

* C# (https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csharp)
* C# Format Usings (https://marketplace.visualstudio.com/items?itemName=gaoshan0621.csharp-format-usings)
* .NET Core Test Explorer (https://marketplace.visualstudio.com/items?itemName=formulahendry.dotnet-test-explorer)
* EditorConfig for VS Code (https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)
* Markdown All in One (https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)
* XML Red Hat (https://marketplace.visualstudio.com/items?itemName=redhat.vscode-xml)
* OpenAPI (Swagger) Editor (https://marketplace.visualstudio.com/items?itemName=42Crunch.vscode-openapi)
* vscode-icons (https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons)
* Docker (https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker)

## Settings to improve explorer view

* explorer.sortOrder **equals** type
* files.exclude **add**
  * **/bin
  * **/obj
  * **/.vscode
    
## Settings to increase productivity

* editor.formatOnSave **set** to enable
* files.trimFinalNewlines **set** to enable (specifically for .cs classes of the c#)
* csharpFormatUsings.splitGroups **set** to disable

## The editor config

Use the [.editorconfig](.editorconfig) file in this repository to preserve your style of identations and code

## Removing unnecessary alert warnings

* in **.csproj**, into a property group, **add** NoWarn tag CS8618, for remove alerts of nullable fields
