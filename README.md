# Library_Management_System
Library Management System is a Online Library Web Application made using **ASP.NET MVC**. It is a simple, user-friendly and easy to navigate.
### Features
> For Admin
 * Can *Approve* or *Reject* the request for any book that is requested.
 * Can perform *CRUD* operations on Account, Book, Author, Publisher tables.
 * Can View all the past *Records* of each user.
> For User
* Can views all the books and *Request* it.
* Can view all the issued books and *Return* it.
* Can view all his past *Records*.

> Landing Page

![Screenshot (13)](https://user-images.githubusercontent.com/109417065/184586767-abf63457-8d92-4038-8891-5298462bc32a.png)

> Login Page

![Screenshot (14)](https://user-images.githubusercontent.com/109417065/184586807-bf4eaca1-b5dc-40aa-ad89-e5bf9b9aeda7.png)

> View Books Page

![Screenshot (15)](https://user-images.githubusercontent.com/109417065/184586844-1dd204b1-53ab-43dd-a9b3-246f185425a5.png)
## To get Started
### Softwares
* Microsoft Visual Studio Community 2022 (64-bit) Version **17.3.0**
* Microsoft SQL Server Management Studio Version **18.2.1**
* .NET Framework Version **5.0.17**

### Packages
> Inside your Visual Stdio Navigate to 
**Tools** > **NuGet Package Manager** > **Manage NuGet Packages for Solution.**
and install these packages

* Microsoft.EntityFrameworkCore Version **5.0.17**
* Microsoft.EntityFrameworkCore.Design Version **5.0.17**
* Microsoft.EntityFrameworkCore.Tools Version **5.0.17**
* Microsoft.EntityFrameworkCore.SqlServer Version **5.0.17**

### Commands
> Inside your Visual Stdio Navigate to 
**Tools** > **NuGet Package Manager** > **Package Manager Console**
and enter these commands
```sh
Add-Migration <Migration Name>
```
```sh
Update-Database
```
Make sure to update [appsettings.json](https://github.com/KDI-pulkit/Library_Management_System/blob/master/LibraryManagementSystem/appsettings.json) with the **Database Name** you want to give.
```sh
"DBConnection": "Server=localhost;Database=<Database Name>;Trusted_Connection=True;"
```

> Schema Diagram

![Schema_Diagram_page-0001](https://user-images.githubusercontent.com/109417065/184586305-f2e178b2-43ed-4d48-84ca-ecf3a1f06998.jpg)
