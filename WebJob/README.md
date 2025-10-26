# 🌟 Project_SE_Nhom_10

![Project Banner](https://github.com/tuilatoan15/Project_SE_Nhom_10/blob/main/img/home.png)  
A comprehensive student project for Software Engineering course – Team 10.

---

## 🚀 About The Project

Project_SE_Nhom_10 is a web application built for learning and demonstrating software engineering principles, from requirement analysis to deployment. The system focuses on managing tasks/jobs in a structured environment with a .NET Core backend and modern frontend technologies.

**Key Highlights:**
- Clear architecture following MVC pattern
- Backend with .NET Core
- Frontend using JavaScript, HTML, CSS
- SQL Server database integration
- User-friendly interface with validation and dynamic content

---

## 🖼️ Screenshots & Demo

![Dashboard](https://github.com/tuilatoan15/Project_SE_Nhom_10/blob/main/img/admin.png)  
*Dashboard showcasing main functionalities*

> GIF demo (optional): `./img/demo.gif`

---

## 🛠️ Built With

- [![.NET Core](https://img.shields.io/badge/.NET-Core-blue)](https://dotnet.microsoft.com/)
- [![JavaScript](https://img.shields.io/badge/JavaScript-yellow)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
- [![SQL Server](https://img.shields.io/badge/SQL-Server-green)](https://www.microsoft.com/en-us/sql-server)

---

## ⚡ Features

- User authentication and authorization
- Job/task management
- Dynamic data display
- Form validation
- Reporting and search functionalities

---

## 📝 Getting Started

### Prerequisites

- Visual Studio 2019 or higher
- .NET Core SDK
- SQL Server

### Installation & Database Setup

1. **Setup SQL Server**  
   - Open SQL Server on your machine.  
   - Copy the **server name** and paste it into the `web.config` file in the project to configure the database connection.

2. **Initialize the Database**  
   - Open the project in Visual Studio.  
   - Go to **Tools → NuGet Package Manager → Package Manager Console**.  
   - Run the following commands:

     ```powershell
     add-migration CreateDatabase
     update-database
     ```

   - Wait for the commands to execute. Then check in SQL Server to confirm that the database has been created.

3. **Run the Project**  
   - Start the website in Visual Studio (`F5`).  
   - To access the admin panel, add `/Admin/Home` to the localhost URL in your browser.

---

## 📊 Usage

1. Register or login to access the system
2. Add, update, delete jobs or tasks
3. View reports and search data
4. Admin can manage users and permissions

---

## 🛡️ Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repo
2. Create your branch (`git checkout -b feature-name`)
3. Commit your changes (`git commit -m 'Add feature'`)
4. Push to the branch (`git push origin feature-name`)
5. Open a Pull Request

---

## 📚 References

- [Software Engineering Principles](https://en.wikipedia.org/wiki/Software_engineering)
- [Microsoft .NET Documentation](https://docs.microsoft.com/en-us/dotnet/)
- [JavaScript Documentation](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

---

## 👥 Team 10

| STT | Họ và tên          | MSSV        |
|:---:|:-------------------|:------------|
|  1  | Trần Khôi Nguyên   | 6351071049  |
|  2  | Nguyễn Hữu Toàn    | 6351071071  |
|  3  | Nguyễn Thành Luân  | 6351071073  |

---

## 📄 License

This project is licensed under **CC0 1.0 Universal (CC0 1.0) Public Domain Dedication**.
