# Product Management Console App

## 📌 Overview
This is a **C# console application** that manages product data using **MySQL and Microsoft SQL Server databases**. The application allows users to perform CRUD operations such as creating, reading, updating, and deleting products.

## 🚀 Features
- Retrieve all products from the database  
- Get a product by its ID  
- Search for products by name  
- Count the total number of products  
- Insert, update, and delete products  
- Supports both **MySQL** and **Microsoft SQL Server**  

## 🛠️ Technologies Used
- **Language:** C#  
- **Framework:** .NET  
- **Databases:** MySQL, Microsoft SQL Server  
- **ORM:** ADO.NET  
- **Version Control:** Git, GitHub  

## 📂 Project Structure
```
📦 ConsoleApp
 ┣ 📜 Product.cs       # Product class definition
 ┣ 📜 Program.cs       # Main application logic
 ┣ 📜 README.md        # Project documentation
```

## 🔧 Installation & Setup

### 1️⃣ Clone the Repository
```sh
git clone https://github.com/your-username/your-repo.git
cd your-repo
```

### 2️⃣ Install Dependencies  
Make sure you have **.NET SDK**, **MySQL Connector**, and **SQL Server** installed.

- Install **MySQL Connector for .NET**  
```sh
dotnet add package MySql.Data
```

### 3️⃣ Configure Database Connections
Modify the database connection strings inside `Program.cs`:

#### MySQL:
```csharp
string connectionString = "server=localhost;port=3306;database=northwind;user=root;password=mysql1234;";
```

#### SQL Server:
```csharp
string connectionString = "Data Source=.\SQLEXPRESS;Initial Catalog=Northwind;Integrated Security=SSPI";
```

### 4️⃣ Run the Application
```sh
dotnet run
```

## 📜 Usage
- The application interacts with the database and manages product data.  
- CRUD operations are implemented in `ProductManager.cs`, `MySQLProductDal.cs`, and `MsSQLProductDal.cs`.  
- Modify the `Main()` method in `Program.cs` to call different functions as needed.  

## 🤝 Contributing
Contributions are welcome! Feel free to **fork** this repository and submit a **pull request**.  

## 📄 License
This project is licensed under the **MIT License**.  

---
🔥 Happy Coding! 🚀
