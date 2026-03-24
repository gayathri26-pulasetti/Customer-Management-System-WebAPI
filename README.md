# Customer Management REST API

## 📌 Project Overview
A complete 3-tier ASP.NET Core Web API application demonstrating real-world architecture and RESTful service design. The project includes API development and multiple client-side integrations for consuming the API.

## 🚀 Features
- RESTful API with CRUD operations (GET, POST, PUT, DELETE)
- 3-tier architecture for better scalability and maintainability
- Dependency Injection using interface-based design (ICustomerDAL)
- Cross-Origin Resource Sharing (CORS) configuration
- API testing and documentation using Swagger UI
- Multiple API consumers (jQuery Ajax and C# HttpClient)

## 🛠️ Tech Stack
- Backend: ASP.NET Core Web API, C#
- Data Source: XML
- Frontend: jQuery, HTML, CSS
- Client: C# HttpClient with MVC Razor Views
- Tools: Swagger UI

## ⚙️ Key Concepts Implemented
- REST API Design
- Dependency Injection and Loose Coupling
- 3-Tier Architecture
- CORS Configuration
- JSON Serialization and Data Handling

## 📂 Project Structure
- **CoreWebApiService** – API backend with REST endpoints
- **CoreWebApiConsumer1** – Frontend using jQuery Ajax
- **CoreWebApiConsumer2** – MVC application using C# HttpClient

## 🔗 API Endpoints (Sample)
- GET /api/customers → Get all customers
- GET /api/customers/{id} → Get customer by ID
- POST /api/customers → Add new customer
- PUT /api/customers/{id} → Update customer
- DELETE /api/customers/{id} → Delete customer

## ▶️ How to Run
1. Clone the repository
2. Open solution in Visual Studio
3. Run CoreWebApiService project
4. Access Swagger UI to test APIs
5. Run consumer projects to interact with API

## 👩‍💻 Author
Gayathri Pulasetti
