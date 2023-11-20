# AzureHttpTrigger 
## Welcome to Azure Func - Simple Tutorial

This repository contains a simple Azure Function with an HTTP trigger. The function responds to HTTP GET and POST requests with a welcome message.

![.NET Badge](https://img.shields.io/badge/.NET-5C2D91?style=for-the-badge&logo=.net&logoColor=white)
![Azure Badge](https://img.shields.io/badge/azure-%230072C6.svg?style=for-the-badge&logo=microsoftazure&logoColor=white)
![macOS Badge](https://img.shields.io/badge/mac%20os-000000?style=for-the-badge&logo=macos&logoColor=F0F0F0)

## Functionality

The `HttpExample` class defines a single function named `HttpExample` that is triggered by HTTP requests. When invoked, it logs the request and returns a simple text response.

## Prerequisites

Before running this function locally, ensure that you have the following installed:
- Visual Studio for Mac
- The Azure Functions Core Tools
- The `Microsoft.Azure.Functions.Worker.Extensions.Http` package, which is required specifically for Azure Functions development on Mac.

## Running the Function Locally on Mac

To run the function locally on a Mac, you'll need to open the project in Visual Studio for Mac. You can start the function by pressing `F5`, which will launch the debugger and start the Azure Functions host.

Here's how to install the required package using the .NET CLI:

```sh
dotnet add package Microsoft.Azure.Functions.Worker.Extensions.Http
```
For command-line interface:
```sh
func start
```
