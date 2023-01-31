# dotnet-assessment

**Background:**
We are building a product pricing module for sellers.
For your assessment, we'd like you to develop a rest API and APP using C#.NET and Angular based on the requirements below.

**Pre-requisites:**
- IDE which supports .NET 6  (i.e., Visual Studio 2022 Community/Professional/Enterprise Edition)
- GitHub account
- NodeJS
- AngularCLI
- MS SQL Server

**Non-functional requirements:**
- Using the following technologies / patterns:
  - .NET 6
  - EntityFramework code-first
  - Angular
  - Repository-Service pattern or CQRS pattern
  
**Functional requirements:**
- Domain Information
  - Product
    - Id, Name, Description
  - Seller
    - Id, Name
  - ProductMarketData
    - About a specific product
    - Provided by multiple sellers
    - Can have a multiple prices per day per seller
- Task:
  - Add a page to view the list of product (with searching and pagination)
    - Add the ability to create/update product name and description.
  - Add a page to view the detail of product including the list of prices of each seller per day.
    - Add the ability to create/update price for a seller for specific date(add a validation that can only set the price of product per day per seller)
  - Implement api endpoints for the pages needed
  - You may add a database seed data for the Sellers, and you can use this when creating product prices.

**Nice to have:**
- Build server-side pagination functionality
- Implement login capability
- Addition of a secured page (only logged in users can access)

**Setup Instructions:**
- Since you are seeing this, the assumption is you've managed to access the repository
- Create a "development" branch and you may use the initial solution web project.
- Commit whatever you've done regardless if you've completed the requirements or not on or before the deadline.

