# Unit Converter
### Click project live below:
[![Unit Converter](https://github.com/will-s-205/unit-converter/blob/main/wwwroot/images/2026-07-03%20unit%20converter%20cover.png)](https://unit-converter-p6pb.onrender.com/)
Unit Converter is a simple web application built with C# and Minimal API that converts miles to kilometers and Fahrenheit to Celsius. The application uses an HTML interface with JavaScript to send user input to C# API endpoints, where the calculations are performed on the server. The results are returned as JSON and displayed on the webpage. This project demonstrates the basics of creating endpoints, handling HTTP requests, and connecting a frontend with a C# backend.
## Goal
Build a simple web application that performs unit conversions by connecting an HTML frontend with a C# backend using Minimal APIs.
## Learned and practiced
* Serving static HTML and CSS files.
* Creating GET API endpoints in C#.
* Sending HTTP requests using the JavaScript fetch() API.
* Processing user input and returning JSON responses.
* Performing server-side calculations in C#.
* Displaying API results dynamically in the browser.
* Connecting a frontend interface with a backend application.
## How to run locally:
Win11
* Make sure to install dotnet8 SDK https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/sdk-8.0.422-windows-x64-installer
* open your terminal and find folder with project
* make sure to comment line of code "builder.WebHost.UseUrls("http://0.0.0.0:5000");" in Programm.cs
* run "dotnet clean; dotnet build; dotnet run;"
* run "start http://localhost:5000" or manualy copy in your browser "http://localhost:5000"
## Run remotely:
If hosted on Render: https://render.com/
## C# and gitattributes
In a C# project, a .gitattributes file is essential for maintaining consistent line endings across different operating systems and improving Git diffs for your code.Because C# developers often collaborate across Windows (which uses CRLF) and macOS or Linux (which use LF), omitting this file can cause phantom modifications in your Git history, failing builds, or formatting issues.