# Hahn.ApplicatonProcess.Application

The zip file contains a solution, which there are four diffrent projects.

**The list of projects are as follows**

> - Hahn.ApplicatonProcess.December2020.Data
    
    This project contains all stuff related to data repository.
    
> - Hahn.ApplicatonProcess.December2020.Domain

    This project contains all classes related to system core business.
    
> - Hahn.ApplicatonProcess.December2020.Web

    This project is ASP.NET core project, that is contain APIs.
    
> - Hahn.ApplicatonProcess.December2020.Web.Aurelia
    
    This project is just a container for the Aurelia app, to include the frontend app in the solution.
    note that, it is not required to build this project using dotnet build, and it is completely been
    excluded from the build.
    
**Steps to run the app**
> - Download the zip file and extract.
> - run `dotnet bulid` on Hahn.ApplicatonProcess.December2020.Web
> - run `npm install` on Hahn.ApplicatonProcess.December2020.Web.Aurelia
> - run `dotnet run` on Hahn.ApplicatonProcess.December2020.Web, so you can access it on `http://localhost:5050/swagger`
> - run `npm start` on Hahn.ApplicatonProcess.December2020.Web.Aurelia, so you can access it on `http://localhost:8080`


