# Task Manager

An application developed in .NET Core Web API to allow users to efficiently organize and monitor tasks.

## Key Features

1. CRUD Operations: Users can create, read, update, and delete tasks through the API.
2. Query by ID: Obtain details of a specific task based on its ID.
3. Query by Title: Search for tasks by title.
4. Query by Date: Retrieve tasks based on creation date.
5. Query by Status: Filter tasks by status.
6. Data Storage: Utilize SQL Server to store task information.

## Prerequisites

1. Visual Studio 2019 or higher
2. .NET Core SDK 3.1 or higher
3. SQL Server (or another compatible database provider)
4. Basic knowledge of ASP.NET Core Web API and Entity Framework Core

## Installation and Execution

1. Clone this repository.
2. Open the project in Visual Studio.
3. Configure the database connection string in the appsettings.json file.
4. In the Package Manager Console, execute Update-Database to apply migrations and create the database.
5. Press F5 to start the application.

## Contribution

Contributions are welcome! For suggestions, improvements, or fixes, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License.
