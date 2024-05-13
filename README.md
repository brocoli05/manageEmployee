# Employee Management App - ASP.NET

## Overview

The Employee Management App is a web application developed using ASP.NET for efficient management of employee information within an organization. This application allows users to perform various tasks such as adding, updating, and deleting employee records, along with additional features for enhanced human resources management.

## Skills

![Static Badge](https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=csharp&labelColor=black)
![Static Badge](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&labelColor=black)
![Static Badge](https://img.shields.io/badge/MSSQL-CC2927?style=for-the-badge&logo=microsoftsqlserver&labelColor=black)

## Features

- **Employee CRUD Operations**: Create, Read, Update, and Delete employee records.
- **Application of the MVC Model**: Design and build applications in a structured and organized way using the MVC architectural pattern.

## Prerequisites

- [.NET SDK](https://dotnet.microsoft.com/download) installed on your machine.
- [Visual Studio](https://visualstudio.microsoft.com/) or [Visual Studio Code](https://code.visualstudio.com/) for development.
- SQL Server for database storage.

## Notice

Create a SQL Server database and update the connection string in `appsettings.json` in this project.

```bash
{
  "ConnectionStrings": {
    "DefaultConnection": "Server=your_server;Database=your_database;Trusted_Connection=True;MultipleActiveResultSets=true"
  },
  // ...
}

