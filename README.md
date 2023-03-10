Peter Leconte 3AD r0830684

# CS Dotnet Project

This school project consists of 3 parts:

- [MAUI](https://github.com/DrunkenToast/cs-dotnet-maui)
- [API](https://github.com/DrunkenToast/cs-dotnet-api)
- [Testing MAUI](https://github.com/DrunkenToast/cs-dotnet-maui-testing)

## Setup

```
git clone --recurse-submodules https://github.com/DrunkenToast/cs-dotnet-project.git
cd cs-dotnet-project

# If already cloned
git submodule update --recursive --remote
```

After cloning follow the setup for API.

## Requirements

- [X] Use .NET MAUI for a mobile application (Android and/or IoS)
- [X] Use the MVVM design pattern (MAUI data binding)
- [X] Your application should have at least 2 pages with navigation
- [X] Add at least 2 Unit tests to your project
- [X] Communicate with an ASP.NET web application (API) (E.g. load and save app data)
- [X] The ASP.NET API must run in a Docker Container
- [X] The ASP.NET API must store data in a MySQL database
