### Diego Grisales

# Tutorials followed:
### https://dotnet.microsoft.com/learn/aspnet/blazor-tutorial/intro
### https://devblogs.microsoft.com/aspnet/azure-static-web-apps-with-blazor/
### https://docs.microsoft.com/en-us/aspnet/core/tutorials/build-a-blazor-app?view=aspnetcore-5.0&pivots=server
### https://sites.google.com/site/profvanselow/programming/languages/c_1/blazor


# Deployed website URL:
### https://happy-desert-06cd1f610.azurestaticapps.net/

# updates:

Added an IPO tab, meal price calculator tab, and a todo item list. 

# Blazor Starter Application

This template contains an example [Blazor WebAssembly](https://docs.microsoft.com/aspnet/core/blazor/?view=aspnetcore-3.1#blazor-webassembly) client application, a C# [Azure Functions](https://docs.microsoft.com/azure/azure-functions/functions-overview) and a C# class library with shared code.

## Getting Started

Create a repository from the [GitHub template](https://docs.github.com/en/enterprise/2.22/user/github/creating-cloning-and-archiving-repositories/creating-a-repository-from-a-template) and then clone it locally to your machine.

Once you clone the project, open the solution in [Visual Studio Code](https://code.visualstudio.com/) or [Visual Studio](https://visualstudio.microsoft.com/vs/preview/vs2022/) and follow these steps:

- In the **API** folder, copy `local.settings.example.json` to `local.settings.json`
- Press **F5** to launch both the client application and the Functions API app. In Visual Studio, you can right click the solution and select both API project and client project as startup projects. 

_Note: If you're using the Azure Functions CLI tools, refer to [the documentation](https://docs.microsoft.com/azure/azure-functions/functions-run-local?tabs=windows%2Ccsharp%2Cbash) on how to enable CORS._

## Template Structure

- **Client**: The Blazor WebAssembly sample application
- **API**: A C# Azure Functions API, which the Blazor application will call
- **Shared**: A C# class library with a shared data model between the Blazor and Functions application

## Deploy to Azure Static Web Apps

This application can be deployed to [Azure Static Web Apps](https://docs.microsoft.com/azure/static-web-apps), to learn how, check out [our quickstart guide](https://aka.ms/blazor-swa/quickstart).
