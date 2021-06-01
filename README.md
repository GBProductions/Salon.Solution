# _Eau Claire's Salon_

#### _A program to allow Eau Claire's Salon to keep track of stylists and clients._
##### _Date Created: May 22nd 2021_
##### _Date Updated: May 31st 2021_

#### By _**Garrett Brown**_

## Description
_A program that allows Eau Claire's Salon to keep track of Stylists and Clients. Users can create stylists, clients, and assorted details. Users can also keep track of which clients are assigned to which stylists. Users can also edit or delete details._

### User Stories

<details>
    <summary>Expand</summary>

#### User Stories
* _As the salon owner, I need to be able to see a list of all stylists._
* _As the salon owner, I need to be able to select a stylist, see their details, and see a list of all clients that belong to that stylist._
* _As the salon owner, I need to add new stylists to our system when they are hired._
* _As the salon owner, I need to be able to add new clients to a specific stylist. I should not be able to add a client if no stylists have been added._

</details>

## Setup/Installation Requirements

### Required Programs
1. An internet browser.
2. Visual Code Studio (or another code editor).
3. .NET


### Installation of Program
* _Open the terminal on your local machine and navigate to "Desktop."_
* _Clone "Salon.Solution"" with the following git command `git clone https://github.com/GBProductions/Salon.Solution.git`_
* _Navigate to the top level of the repository with the command `cd Salon.Solution`_
* _Navigate into "HairSalon" with git command `cd HairSalon`_


### Recreate Database
![Schema](HairSalon/assets/images/tables.png)

1. Create a file in the root directory called `appsettings.json`. 
2. Add `appsettings.json` to `.gitignore`.
3. Insert the following code into `appsettings.json`:
    `{
        "ConnectionStrings": {
            "DefaultConnection": "Server=localhost;Port=3306;database=YOUR-DATABASE;uid=root;pwd=YOUR-PASSWORD;"
        }
    }`
4. Replace `YOUR-PASSWORD` with `epicodus`.
5. Replace `YOUR-DATABASE` with `garrett_brown`.

### Startup
* Navigate to HairSalon folder in project.
* Restore project with git command `dotnet restore`
* Build project with git command `dotnet build`
* To run program, run git command `dotnet run`
* In browser, navigate to http://localhost:5000 

## Known Bugs

_There are currently no known bugs._

## Support and contact details

_For assistance, please contact Garrett Brown <garrettpaulbrown@gmail.com>_

## Technologies Used

* _Github, VS Code_
* _Bootstrap, MarkDown_
* _Entity Framework_
* _C#_
* _.NET Core 5.0.1_
* _ASP.NE Core MVC_
* _ASP.NET Core Razor Pages_
* _HTML, CSS_
* _MySQL_
* _MyuSQL Workbench_


### License

*Available under MIT Licensing*

Copyright (c) 2021 **_Garrett Brown_**


