# 📋 Employee Management Portal

A **CRUD-based HR management application** built with **Spring Boot** and **Thymeleaf** to manage employee records efficiently.  
This project is designed for beginners to learn **Spring Boot**, **Thymeleaf**, and **basic CRUD operations** with a clean and classic CSS-based UI.

---

## 📸 Screenshots

**Home Page**
![Home Page](screenshots/home.png)

**Add Employee**
![Add Employee](screenshots/add-employee.png)

**Update Employee**
![Update Employee](screenshots/update-employee.png)

---

## ✨ Features

- ➕ **Add New Employee**
- 📝 **Update Employee Details**
- ❌ **Delete Employee**
- 📄 **View All Employees**
- 🎨 **Beautiful Classic UI** (CSS only, no Bootstrap)
- 📦 **Maven Wrapper** included for easy setup

---

## 🛠 Tech Stack

| Layer          | Technology           |
|----------------|----------------------|
| **Frontend**   | Thymeleaf, HTML, CSS |
| **Backend**    | Spring Boot (Java)   |
| **Database**   | MySQL                |
| **Build Tool** | Maven                |
| **IDE**        | IntelliJ IDEA        |

---

## 📂 Project Structure

```
employee-management-portal/
│
├── src/
│   ├── main/
│   │   ├── java/com/example/employee/   # Java source code
│   │   ├── resources/
│   │   │   ├── static/                  # CSS files
│   │   │   ├── templates/               # Thymeleaf HTML templates
│   │   │   └── application.properties
│   └── test/                             # Unit tests
│
├── mvnw / mvnw.cmd                       # Maven wrapper scripts
├── .mvn/                                 # Maven wrapper settings
├── pom.xml                               # Maven dependencies
├── README.md
└── .gitignore
```

---

## ⚙️ Setup Instructions

### 1️⃣ Clone the repository
```bash
git clone https://github.com/yourusername/employee-management-portal.git
cd employee-management-portal
```

### 2️⃣ Open in IntelliJ IDEA
- Go to **File → Open**
- Select the project folder
- IntelliJ will auto-import Maven dependencies

### 3️⃣ Configure MySQL Database
Create a new MySQL database:
```sql
CREATE DATABASE employee_db;
```

### 4️⃣ Update `application.properties`
```properties
spring.datasource.url=jdbc:mysql://localhost:3306/employee_db
spring.datasource.username=YOUR_DB_USERNAME
spring.datasource.password=YOUR_DB_PASSWORD
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
```

### 5️⃣ Run the Application
```bash
./mvnw spring-boot:run
```
Or in IntelliJ:
- Open `EmployeeManagementPortalApplication.java`
- Click **Run ▶**

---

## 🚀 How to Use

1. **Go to:** `http://localhost:8080`
2. **Add** employees using the "Add New Employee" button
3. **Update** details from the Employee List
4. **Delete** employees when needed

---

## 💡 Future Enhancements

- 🔍 Search employee by name/department
- 📊 Employee statistics dashboard
- 📥 Export employee list as PDF/Excel
- 👤 User authentication & roles

---

## 👨‍💻 Author

**Akash Suryawanshi**  
📧 [akashsuryawanshi1344@gmail.com](mailto:akashsuryawanshi1344@gmail.com)  
💼 [LinkedIn Profile](https://linkedin.com/in/akashsuryawanshi04)  
🌐 [GitHub Profile](https://github.com/akashsuryawanshi04)

---

⭐ If you like this project, don't forget to **star the repo** on GitHub!
