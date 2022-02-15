
<div id="top"></div>

# Fleet Manager - Internal WEB Application API

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#developer-features">Developer Features</a></li>
        <li><a href="#integrated-services">Integrated Services</a></li>
        <li><a href="#built-with">Built With</a></li>
        <li><a href="#visuals">Visuals</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#development-team">Development Team</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

Fleet Manager is an Internal website built for managing a company's vehicle assets, their usage, maintenance and costs.

<p align="right"><a href="#top">Top ↑</a></p>


### Developer Features

- Entity CRUD
- Registration/Login with JWT Token
- Account Management
- User Roles
- File Import/Export (Excel, Images)
- Search
- Pagination
- Email notifications
- Error logging
<p align="right"><a href="#top">Top ↑</a></p>

### Built With

 Web API design pattern
React JS

* Back End:  [ASP .NET Core][asp-net-core],  [C#][c#],  [Entity Framework Core][ef-core],   [AutoMapper][auto-mapper],  [Office Open XML][office-open-xml]
* Security:  [Identity][identity-core]
* Front End:  [HTML][html],  [CSS][css],   [JavaScript][js],   [React.js][react],   [Bootstrap][bootstrap]
* Database Management:  [Microsoft SQL Server][msql-server],   [Microsoft SQL Server Management Studio][ssms]
* Code Editor:  [Microsoft Visual Studio Code][visual-studio-code]
* Deployment: [Docker][docker]
<p align="right"><a href="#top">Top ↑</a></p>

### Integrated Services

* Email:  [MailKit][mail-kit]
<p align="right"><a href="#top">Top ↑</a></p>

### Visuals

Login Page:

![login-page.png][page-login]

User Dashboard:

![user-dashboard.png][dashboard]

Car List Page with Search and Pagination:

![car-list.png][car-list]

Car Details:

![car-details.png][car-details]

User List Page:

![user-list.png][user-list]

<!-- GETTING STARTED -->
## Getting Started

### Installation

**This Project Requires _both_ [API][project-api] and [Client][project-client] app in order to run.**
_Also requires Node.js and npm_

- Clone the Repo on your machine and open it with **Visual Studio Code**.
- Install packages by running the following command in the terminal:
```cmd
	npm install
```

- Follow the [API][project-api] steps if you haven't already.
<p align="right"><a href="#top">Top ↑</a></p>



<!-- USAGE EXAMPLES -->
## Usage

Run by entering the following command in the terminal:
```cmd
	npm start
```

Login by using the following accounts:
```
Admin: john.doe@testing.com 
	Password: Pa$$w0rd
	
Employee: jane.smith@testing.com
	Password: Pa$$w0rd
```

<p align="right"><a href="#top">Top ↑</a></p>


## Development Team

* [Victor Nicolae's GitHub][victor-nicolae]
* [Adrian Deaconu's GitHub][adrian-deaconu]
* [Alex Buza's GitHub][alex-buza]

<p align="right"><a href="#top">Top ↑</a></p>

<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

Thanks for all the support to the [Codecool][codecool] mentors that have guided us!


<p align="right"><a href="#top">Top ↑</a></p>

<!-- MARKDOWN LINKS & IMAGES -->

[project-client]: https://github.com/red-victor/fleet-manager-client
[project-api]: https://github.com/red-victor/fleet-manager-api

[asp-net-core]: https://dotnet.microsoft.com/en-us/learn/aspnet/what-is-aspnet-core
[ef-core]: https://docs.microsoft.com/en-us/ef/core/
[auto-mapper]: https://automapper.org/
[c#]: https://docs.microsoft.com/en-us/dotnet/csharp/
[html]: https://html.com/
[css]: https://www.w3.org/Style/CSS/Overview.en.html
[js]: https://www.javascript.com/
[react]: https://reactjs.org/
[react-net]: https://reactjs.net/
[bootstrap]: https://getbootstrap.com
[jquery]: https://jquery.com
[msql-server]: https://www.microsoft.com/en-us/sql-server/sql-server-2019
[ssms]: https://docs.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver15
[visual-studio]: https://visualstudio.microsoft.com/
[visual-studio-code]: https://code.visualstudio.com/
[identity-core]: https://docs.microsoft.com/en-us/aspnet/core/security/authentication/identity?view=aspnetcore-6.0&tabs=visual-studio
[docker]: https://www.docker.com/

[victor-nicolae]: https://github.com/red-victor
[adrian-deaconu]: https://github.com/AdiDD
[alex-buza]: https://github.com/alexmarian99

[codecool]: https://codecool.com/en/

[mail-kit]: https://www.mailkit.com/
[office-open-xml]: https://epplussoftware.com/docs/5.0/api/OfficeOpenXml.html

[page-login]:https://res.cloudinary.com/dsanrttbt/image/upload/v1644154627/Fleet-Manager/login_nw3atx.png
[dashboard]: https://res.cloudinary.com/dsanrttbt/image/upload/v1644154628/Fleet-Manager/user-dashboard_l3omwn.png
[user-list]: https://res.cloudinary.com/dsanrttbt/image/upload/v1644154627/Fleet-Manager/user-list_rgt387.png
[car-details]: https://res.cloudinary.com/dsanrttbt/image/upload/v1644154627/Fleet-Manager/car-details_sz0olh.png
[car-list]: https://res.cloudinary.com/dsanrttbt/image/upload/v1644154627/Fleet-Manager/car-list-search-pagination_hd7rsx.png
