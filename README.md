# Learning READ ME

#### By Joseph McMahon

## Technologies Used:

* HTML
* CSS
* Visual Studio Code
* Visual Studio
* Git

## Description:

Creating a read me to learn how to create a read me.

## Setup and Installation Guide:

### Prerequisites:
* .NET 6 SDK
* MySQL Server

1. Clone the repository to your local machine:
git clone https://github.com/ESC18/Dr-Sillystringz-s-Factory.git

2. Open the project folder in Visual Studio Code or Visual Studio.

3. Create the `appsettings.json` file in the `DrSillystringzFactory` directory and update it with your MySQL connection string:
{
  "ConnectionStrings": {
    "DefaultConnection": "Server=localhost;Port=3306;Database=factorydb;Uid=root;Pwd=your_password;"
  }
}

4. Open a terminal in Visual Studio Code or Visual Studio and navigate to the DrSillystringzFactory directory:

cd DrSillystringzFactory

5.Restore the project dependencies by running the following command:

dotnet restore

6. Apply the database migrations:

dotnet ef database update

7. Start the application by running the following command:

dotnet watch run

8. Access the application in your web browser at:
https://localhost:5001

## Known Issues
* no known issues at this time.

## License 
MIT License
Copyright © Elijah Shawn Cartwright 2023