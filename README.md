# Leave Management System

This repository contains a comprehensive **Leave Management System** built using **ASP.NET Core (.NET 8/9)** and **Entity Framework Core**, with **SQL Server** as the database provider.

The system helps organizations streamline the process of leave request submission, approval workflows, and tracking leave balances for employees.

---

## 🔗 Related Udemy Course

This project is featured in the Udemy course:

**[Complete ASP.NET Core and Entity Framework Development](https://www.udemy.com/course/complete-aspnet-core-31-and-entity-framework-development/?referralCode=739749EF600855CEE34F)**

If you're interested in learning how to build modern web applications using ASP.NET Core and EF Core step-by-step, this course is for you!

---

## ✨ Features

### 👤 Employee Functionality
- Submit leave requests with type and duration
- View personal leave balances and request history
- Receive status notifications on leave requests

### 🛠️ Administrator Functionality
- Review and approve/reject leave requests
- Manage leave types and employee allocations
- View and filter leave records across the organization

---

## 🛠 Installation Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/trevoirwilliams/LeaveManagementSystem.git
cd LeaveManagementSystem
```

### 2. Open in Visual Studio
Open the solution file `LeaveManagementSystem.sln` using Visual Studio 2022 or later.

### 3. Configure the Database
- Go to `appsettings.json` in the `LeaveManagementSystem.Web` project.
- Update the `DefaultConnection` string with your SQL Server instance.

Example:
```json
"ConnectionStrings": {
  "DefaultConnection": "Server=YOUR_SERVER_NAME;Database=LeaveManagement;Trusted_Connection=True;MultipleActiveResultSets=true"
}
```

### 4. Apply Migrations
Using the Package Manager Console:
```powershell
Update-Database
```

Make sure the **Default Project** is set to `LeaveManagementSystem.Data`.

### 5. Run the Application
- Set `LeaveManagementSystem.Web` as the startup project.
- Press `F5` or click the **Run** button in Visual Studio.

### 6. Log In
Once the app is running, access it via:

```
https://localhost:5001/
```

**Default Admin Credentials:**
- **Username:** admin@localhost.com  
- **Password:** Password1234!

---

## 🙌 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you’d like to change.

---

## 📄 License

This project is for educational purposes as part of the associated Udemy course.

---
