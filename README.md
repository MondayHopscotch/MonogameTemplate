# Setting up MonoGame with vscode

### First-time setup
1. You will need to install dotnet core on here: https://www.microsoft.com/net/download/windows. You may have to restart your pc for the  `dotnet` command to appear in command prompt.
1. Install vscode here: https://code.visualstudio.com/
1. Open a command prompt
1. type: `dotnet new --install MonoGame.Template.CSharp` to add monogame template to dotnet core

### Creating individual projects
1. `cd` into a parent folder where you would like to store your project
1. type: `dotnet new mgdesktopgl -o <project name>`
1. type: `cd mygame`
1. type: `code .`

# Running the project
1. In VSCode, press F5 and select .NET Core as the runtime

# Publishing
- `dotnet publish -r linux-x64 -c release`
- `dotnet publish -r osx-x64 -c release`
- `dotnet publish -r win-x64 -c release`
- Extensions to get in vscode:
  - C#
  - C# Extensions
  - C# FixFormat
