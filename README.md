.NET 7.0 + MySQL

How to run :
- Open with Microsoft Visual Studio 2022 or Visual Studio Code
- Make sure you have MySQL instance (localhost or remote)
- Update the database credentials in Visual Studio within "appsettings.json" file to connect to your MySQL instance
- Start the API by running "dotnet run" from the command line in Visual Studio within "WebApi.csproj" file
- A new MySQL database (dotnet-7-dapper-crud-api) will be created after running the API
- URL configuration is set to http://localhost:4000
- Use Postman to execute CRUD operations with http://localhost:4000/users URL 
- This is the JSON body (with example value) for creating new user in Postman
   {
    "title": "Mr",
    "firstName": "Ben",
    "lastName": "Stone",
    "role": "User",
    "email": "ben@stone.com",
    "password": "ben-stone",
    "confirmPassword": "ben-stone"
   }
- Postman will return "200 OK" if succeed executing CRUD operations
- Check the result (after done in Postman) in MySQL Workbench for better information
