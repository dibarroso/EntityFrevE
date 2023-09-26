# DATABASE REVERSE ENGINEERING
Thos project includes database reverse engineering database --> code

In VSCode run:
```
dotnet new console -o EFrevE
```
```
cd EFrevE
```
```
dotnet add package Microsoft.EntityFrameworkCore.DEsign
dotnet add package Microsoft.EntityFrameworkCore.SqlServer
dotnet add package Microsoft.EntityFrameworkCore.Tools
```
```
dotnet ef dbcontext scaffold "Data Source="URL"; Database="DBName"; Integrated Security=false; User ID="id";Password="password";" Microsoft.EntityFrameworkCore.<Provider> -context -dir Data --output-dir Models
```
