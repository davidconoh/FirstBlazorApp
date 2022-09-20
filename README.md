# FirstBlazorApp
Trying out Blazor for the first time? Demo this app for first-time introduction. Dedicated to all Blazor-first events in Nigeria 🇳🇬

![firstblazorapp.gif](https://res.cloudinary.com/davidconoh/image/upload/v1663602485/firstblazorapp.gif)

## 💡 Introduction
<a href="https://dotnet.microsoft.com/en-us/apps/aspnet/web-apps/blazor" target="_blank">Blazor</a> is a feature of <a href="https://dotnet.microsoft.com/en-us/apps/aspnet" target="_blank">ASP.NET</a>, the popular web development framework that extends the .NET developer platform with tools and libraries for building interactive web UIs using C# instead of JavaScript. Both client and server code is written in C#, allowing you to share code and libraries.

## 📑 Getting started
<a href="https://dotnetfoundation.org/" target="_blank">.NET Foundation</a> projects are well maintained, easy to adopt, and have great documentation. However, Javascript can be a subtle language for .NET teams to take on in a short time-frame for building out rapidly scaling modern web apps. <a href="https://dotnet.microsoft.com/en-us/apps/aspnet/web-apps/blazor" target="_blank">Blazor</a> can be quite the alternative.

## ❇️❇️❇️ Prerequisites
Before continuing to run this project on your local workstation, make sure you have the following Software setup:
- <a href="https://dotnet.microsoft.com/en-us/download" target="_blank">.NET SDK 6.0x</a> (preferred)
- <a href="https://code.visualstudio.com" target="_blank">Visual Studio Code</a>
- <a href="https://code.visualstudio.com/docs/languages/dotnet" target="_blank">.NET Extension Pack for VS Code</a> (optional)


For more information, visit <a href="https://dotnet.microsoft.com/en-us/learn/aspnet/blazor-tutorial/intro" target="_blank">Blazor Tutorial - Build your first Blazor app</a>.

## 🕯️ Requirements
- Fork the <a href="https://github.com/davidconoh/FirstBlazorApp" target="_blank">FirstBlazorApp GitHub repo</a> to your GitHub account.
- Clone on your local machine: Replace `<yourusername>` with your GitHub username
  ```
  git clone https://github.com/<yourusername>/FirstBlazorApp.git
  ```
- The following details are the file structure of your cloned repository:
  ```
  -| BlazorApp
    -| bin
    -| Data
    -| obj
    -| Pages
      -| _Host.cshtml
      -| Counter.razor
      -| Error.cshtml
      -| Error.cshtml.cs
      -| FetchData.razor
      -| Index.razor
    -| Properties
    -| Shared
      -| MainLayout.razor
      -| MainLayout.razor.css
      -| NavMenu.razor
      -| NavMenu.razor.css
      -| SurveyPrompt.razor
    -| wwwroot
    -| _Imports.razor
    -| App.razor
    -| appsettings.Development.json
    -| appsettings.json
    -| BlazorApp.csproj
    -| Program.cs
  -| LICENSE
  -| README.md
  ```
- Open with VS Code
  ```
  cd FirstBlazorApp
  code .
  ```
- Open a new Terminal in VS Code. You are looking for the `BlazorApp` folder:
  - Enter the directory
    ```
    cd BlazorApp
    ```
  - Run the application
    ```
    dotnet watch
    ```
    If you installed the extension, you can run `debug mode` by pressing `F5` on your keyboard.


## ✔️ License
Licensed under the Apache License, Version 2.0. See <a href="https://github.com/davidconoh/FirstBlazorApp/blob/main/LICENSE" target="_blank">here</a>

## ✔️✔️✔️ Attribution
To be able to achieve this, you need to have completed the following modules on Microsoft Learn:
- <a href="https://learn.microsoft.com/en-us/training/modules/blazor-introduction/" target="_blank">Build a web app with Blazor</a>
- <a href="https://learn.microsoft.com/en-us/training/modules/build-blazor-webassembly-visual-studio-code/" target="_blank">Introduction to Web Development with Blazor</a>

## ⚠️ Caution
This repository is meant to be utilized by the instructor/facilitator for educational purposes. Participants are meant to follow along the instructor's guide during the event.

## 📖 Author
- <a href="https://github.com/davidconoh" target="_blank">Chika Onoh</a>

## 📥 Version
```
Version: 0.0.2
```
