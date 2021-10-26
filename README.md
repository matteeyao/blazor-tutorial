# Blazor Tic-Tac-Toe Web Application

Blazor is an open source .NET web front-end framework that allows us to create client-side applications using C# and HTML.

## I. App Setup 

ASP.NET web application consuming built-from-scratch tic-tac-toe engine hosted on GitHub packages and integrating CI workflows and test coverage

Create and run your first Blazor WebAssembly (client-side) app by running:

```
dotnet new blazorserver -o tic-tac-toe
cd tic-tac-toe
dotnet watch run
```

Once a change is saved, the `dotnet watch run` command will restart the app and refresh it in the browser so that any changes show up on the page.

If strictly viewing the application w/o making any changes, run the command `dotnet run`

Head to `https://localhost:portNumber` to see your first Blazor WebAssembly app!

> [!NOTE]
> You can find your port number in the `TicTacToe/Properties/lanchSetting.json` file, it's often 5000/5001 unless you are using IIS.

Take a quick look at the contents of the `BlazorApp` directory. Several files were created in the `BlazorApp` directory, to give you a simple Blazor app that is ready to run:

* `Program.cs` is the entry point for the app that starts the server

* `Startup.cs` is where you configure the app services and middleware

* `App.razor` is the root component for the app

* The `BlazorApp/Pages` directory contains some example web pages for the app

* `BlazorApp.csproj` defines the app project and its dependencies

## II. Build a Tic-Tac-Toe board razor component

1. Rename the `Counter.razor` file in the `Pages` directory to `TicTacToe.razor`
