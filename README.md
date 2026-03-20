# 🚀 Java Advanced Framework - Spring Boot REST APIs (Week 4)

This repository contains multiple backend projects developed using **Spring Boot, JPA, and MySQL**, covering real-world business use cases and enterprise-level concepts.

---

## 📌 Projects Included

### 1️⃣ E-Commerce Order Management System

* Customer & Order Management (1:M Relationship)
* Soft Delete (isActive flag)
* Audit Tracking (createdAt, updatedAt)
* Optimistic Locking (@Version)
* Derived Field (totalAmount calculation)
* Revenue Summary API (custom query)
* Pagination & Filtering

---

### 2️⃣ Bank Account Management System

* Account CRUD Operations
* Deposit & Withdrawal APIs
* Business Rules:

  * No negative balance
  * No invalid transactions
  * Prevent overdraft
* Clean layered architecture (Controller → Service → Repository)

---

### 3️⃣ Hospital Management System

* Doctor & Appointment Management (1:M Mapping)
* Validation using DTOs
* Pagination for appointments
* Enum-based status handling
* Cascade delete + orphan removal

---

### 4️⃣ Library Book Borrowing System

* Book CRUD Operations
* Borrow & Return functionality
* Business rules:

  * Cannot borrow if no copies available
  * Cannot return if no borrowed copies
* Inventory tracking (availableCopies, borrowedCopies)

---

### 5️⃣ Online Food Order Management System

* Order CRUD APIs
* Soft delete using status (CANCELLED)
* Business validations:

  * Quantity must be > 0
  * Cannot update cancelled orders
* RESTful API design

---

## 🛠️ Tech Stack

* Java 17+
* Spring Boot
* Spring Data JPA (Hibernate)
* MySQL
* Maven
* REST APIs
* Postman (for testing)

---

## 🧠 Concepts Covered

* Layered Architecture (Controller → Service → Repository)
* JPA Relationships (One-to-Many, Many-to-One)
* DTO & Validation
* Exception Handling
* Pagination & Sorting
* Soft Delete
* Optimistic Locking
* Custom Queries
* Business Rule Enforcement

---

## 📁 Project Structure

```
src/main/java/com/project
 ├── controller
 ├── service
 ├── repository
 ├── model
 ├── dto
 ├── exception
```

---

## 🚀 How to Run

1. Clone the repository

```
git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
```

2. Open in IDE (IntelliJ / Eclipse)

3. Configure MySQL in `application.properties`

```
spring.datasource.url=jdbc:mysql://localhost:3306/your_db
spring.datasource.username=root
spring.datasource.password=your_password
```

4. Run the Spring Boot Application

---

## 🧪 API Testing

Use **Postman** to test APIs:

* POST → Create
* GET → Read
* PUT → Update
* DELETE → Delete
* PATCH → Partial Update

---

## 💡 Highlights

✔ Real-world backend systems
✔ Industry-level best practices
✔ Clean and scalable architecture
✔ Strong focus on business logic

---

## 👨‍💻 Author

**Gautam Saraswat**

---

## ⭐ If you like this repo

Give it a ⭐ on GitHub!
