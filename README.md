💼 Full Stack .NET Web API Project - E-Commerce Order Management
✅ Project Type: RESTful API for e-commerce product and order management

🧠 Technologies Used:

Backend: ASP.NET Core 8 Web API, C#

Authentication & Authorization: JWT, ASP.NET Identity

Database: SQL Server + Entity Framework Core

Design Pattern: Repository Pattern & Unit of Work

File Handling: Uploading and saving images via wwwroot/uploads

API Security: Role-based access control using claims in JWT

Documentation: Swagger UI

Others: Auto-migration setup, clean layered architecture (Controller, Service, DAL, DTO)

🧩 Key Features:

Register/Login with token-based authentication

Admin can add, update, delete products

Users can browse products and create orders

Orders flow through states: Pending, Shipped, Cancelled

Upload product images and link them to items

Full separation of concerns using layered architecture:

Controllers → Services → Repositories → DB

🛡️ Security:

JWT Token includes user info and roles

Role claims are used to restrict admin/user privileges

Token expiration, issuer, and audience validation

⚙️ Tools & Frameworks:

Visual Studio, SQL Server, Postman, Swagger, Git/GitHu

