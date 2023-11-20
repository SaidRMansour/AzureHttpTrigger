# AzureHttpTrigger 
## Introduction to Azure Functions - A Basic Guide

Welcome! This repository is home to a straightforward Azure Function using an HTTP trigger. Designed to handle both HTTP GET and POST requests, it greets users with a friendly message upon invocation.

![.NET Badge](https://img.shields.io/badge/.NET-5C2D91?style=for-the-badge&logo=.net&logoColor=white)
![Azure Badge](https://img.shields.io/badge/azure-%230072C6.svg?style=for-the-badge&logo=microsoftazure&logoColor=white)
![macOS Badge](https://img.shields.io/badge/mac%20os-000000?style=for-the-badge&logo=macos&logoColor=F0F0F0)

## Features

Contained within is the `HttpExample` class, which hosts a function also named `HttpExample`. This function springs into action upon receiving HTTP requests, providing a log entry for each request along with a text-based response.

## Setup Requirements

To prepare for running this function in a local environment, please ensure the installation of:
- Visual Studio
- Azure Functions Core Tools

### Additional Setup for macOS
- The `Microsoft.Azure.Functions.Worker.Extensions.Http` package is essential for Azure Functions development on macOS.

Execute the following command with the .NET CLI to install the necessary package:

```sh
dotnet add package Microsoft.Azure.Functions.Worker.Extensions.Http
```
## Executing the Function on macOS

For those using macOS, the function can be executed locally by utilizing Visual Studio for Mac. Simply open the project and hit F5 to initiate the debugger and kickstart the Azure Functions host.

Alternatively, if you prefer using the terminal, run:

```sh
func start
```




