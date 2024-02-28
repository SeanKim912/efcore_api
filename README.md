https://learn.microsoft.com/en-us/training/modules/build-web-api-minimal-database/3-exercise-add-entity-framework-core

Use Swagger to test your api endpoints at "localhost:{PORT}/swagger/"

To upgrade to sqlite:

dotnet add package Microsoft.EntityFrameworkCore.Sqlite --version 8.0
dotnet tool install --global dotnet-ef
dotnet add package Microsoft.EntityFrameworkCore.Design --version 8.0

After code is added:

dotnet ef migrations add InitialCreate
dotnet ef database update
