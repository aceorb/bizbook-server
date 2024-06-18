# ASP.NET Web API Server Project of BizBook365 ERP
The server repository of bizbook server.


## Installing

A step by step series of examples that tell you how to get a development env running.

1. Clone the repository
2. Go to the BizBook directory
3. Open `BizBook.sln` file using Visual Studio 2017
4. Open Package Manager Console
4. Run `Update-Package -Verbose` to install required dependencies.
5. From above `Default project` dropdown, select `Server.Identity` project and run `Update-Database -Verbose`
6. From above `Default project` dropdown, select `Model` project and run `Update-Database -Verbose`
7. Go to sql folder of the repository and execute `001_Permission_Seed_Data_Insert.sql` and then `002_SuperAdmin_Data_Insert.sql` against your newly created `BizBookDb` database. 
8. For rest of the step, please follow this video.

### Deployment

[Details will be added soon]

## Technologies used / Built with
I have used .NET Framework 4.6.2 along with,
* ASP.NET Web API 
* Entity Framework
* SQL Server 2017 Express 



## Versioning

We will use [SemVer](http://semver.org/) for versioning. 

## License

This project is licensed under the GNU GENERAL PUBLIC LICENSE - see the [LICENSE.md]

## Sponsorship

Currently I am not actively looking for a sponsorship. But if you have a big shop and want to automate it using BizBook System, I will be glad and feel proud to help you in this regard.
