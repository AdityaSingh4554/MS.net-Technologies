 <div id="header" align="center">
  <img src="https://media.giphy.com/media/M9gbBd9nbDrOTu1Mqx/giphy.gif" width="100"/>
</div>

<h1 align="center">Employee Management API with SQL Server and Swagger Integration</h1>
  
<h3 align="center">A CRUD-based Employee Management API using ASP.NET Core, integrated with SQL Server and Swagger for seamless API management and documentation.</h3>


- 🚀 *How to Run*  
  1. Clone the repository:  
     
     git clone [https://github.com/username/repository.git](https://github.com/AdityaSingh4554)
     cd repository
     
  2. Install dependencies:
     
     Install-Package Microsoft.EntityFrameworkCore
     Install-Package Microsoft.EntityFrameworkCore.SqlServer
     Install-Package Microsoft.EntityFrameworkCore.Tools
     Install-Package Microsoft.EntityFrameworkCore.Design
     
  3. Configure the database in appsettings.json:
     
     "ConnectionStrings": {
       "EmployeeDBConnection": "Data Source=(localdb)\\ProjectModels;Initial Catalog=DemoData;Integrated Security=True"
     }
     
  4. Run migrations:
     
     Add-Migration InitialCreate
     Update-Database
     
  5. Start the project:  
     
     dotnet run
     

- 🌐 *API Endpoints*  
  - *GET* /api/Employee: Fetch all employees.  
  - *GET* /api/Employee/{id}: Fetch an employee by ID.  
  - *POST* /api/Employee: Add a new employee.  
  - *PUT* /api/Employee/{id}: Update an employee.  
  - *DELETE* /api/Employee/{id}: Delete an employee.  

---

<h3 align="left">Technologies Used:</h3>
<p align="left">
  <a href="https://dotnet.microsoft.com/" target="_blank" rel="noreferrer"> 
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/dot-net/dot-net-original-wordmark.svg" alt="dotnet" width="40" height="40"/> 

  <a href="https://www.microsoft.com/en-us/sql-server" target="_blank" rel="noreferrer"> 
    <img src="https://www.svgrepo.com/show/303229/microsoft-sql-server-logo.svg" alt="sqlserver" width="40" height="40"/> 
  </a>

</p>



<h3 align="left">📜 License</h3>
This project is open-source and licensed under the MIT License.

<p align="center">💻 Built with ❤️ by Aditya Singh 💻</p>
