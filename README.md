# Message Boardz

 ![Preview](https://images.unsplash.com/photo-1525255946160-aac47911684e?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1027&q=80)

### Latest version date 2020/08/14
### By Spencer Moody, Christine Augustine, Noel Kirkland

## Description

A message board API

## Specifications

## Setup/Installation Requirements
* .NET Core 2.2 will need to be installed, it can be found here https://dotnet.microsoft.com/download/dotnet-core/2.2
* For Mac users, download MySQL here: https://dev.mysql.com/downloads/file/?id=484914
* For Windows users, download MySQL here: https://dev.mysql.com/downloads/file/?id=484919
* Install MySQL and set the system path, more information on how to do that can be found here: https://www.learnhowtoprogram.com/c-and-net/getting-started-with-c/installing-and-configuring-mysql
* Enter the following commands to create the necessary database and tables:
* Clone the GitHub repository by running `https://github.com/christinereina/MessageBoardApiUpdate.Solution` in the terminal.
* Navigate to the `MessageBoardApiUpdate.Solution` folder.
* Navigate to the `MessageBoardApiUpdate.Solution` subfolder and run `dotnet restore`.
* Next run the command `dotnet ef database update` to update/create the schema using the most recent Migration.
* Then run `dotnet build` to build the application.
* The web app will now be available for you to view on `http://localhost:5000/`.

## Known Bugs and Support
No know bugs.

## Tech used

* C#
* .NET Core
* Entity Framework
* Identity
* MySQL

### License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

Copyright (c) 2020 Spencer Moody, Christine Augustine, Noel Kirkland
