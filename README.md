# Intro

Starter .NET (C#) solution, containing a single project with an HTTP triggered Azure Function for the DMNStudio hackathon.

# Requirements

- [Azure Functions core tools](https://github.com/Azure/azure-functions-core-tools#installing-the-cli)
- [.NET10](https://dotnet.microsoft.com/en-us/download/dotnet/10.0)
- [Visual Studio Code](https://code.visualstudio.com/download)

# Setup

After opening the root directory in VSCode, a prompt should appear to install recommended extensions.

If no popup is shown, go to **Extensions** in the left menu and expand the **Recommended** tab and install them from there.

Or go to the [`extensions.json`](.vscode/extensions.json) file in the `.vscode` directory.

# Running the project

Open one of the `.cs` files. A play button (▶️) should appear, press it to start the project.

The function app itself can also be started from the CLI/command line:

1. Select **Terminal** > **New Terminal** on the top.
2. Change directory to `SynTouch.DMNStudio.Hackathon.FunctionApp` (project folder)
3. run `func start`.
