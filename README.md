dotnet new sln 

dotnet new mvc -o MyApp

dotnet sln add ./MyApp/MyApp.csproj

cd MyApp

dotnet add package MySql.data

dotnet build 

cd MyApp

dotnet run

copy the link in the browser

again in terminal
Ctrl + c

dotnet add package Microsoft.EntityFrameworkCore.Sqlite

dotnet add package Microsoft.EntityFrameworkCore.Tools

dotnet add package Microsoft.AspNetCore.Diagnostics.EntityFrameworkCore

go in appsettings.json
add this code 

 "ConnectionStrings": {
    "DefaultConnection": "DataSource=app.db; Cache=Shared"
  },
  
  
  dotnet build
  
  Create new folder named "Data"
  
  Create new file named "ApplicationDbContext.cs"
  
  



