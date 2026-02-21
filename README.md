# 🐾 PetShop Service Manager (Banho & Tosa)

## 📖 About the Project

**PetShop Service Manager** is a comprehensive management system designed for pet shops to streamline their grooming and bath service workflows. The application provides a centralized platform for service providers to monitor ongoing tasks, manage payments, and generate financial insights, ensuring a professional experience for both the business and the pet owners.

Unlike an API-only approach, this project utilizes a **Server-Side Rendering (SSR)** architecture, providing a fast and integrated experience for internal management.

---

## ✨ Key Features

* **Service Lifecycle Tracking:** Real-time monitoring of services in progress and completed tasks.
* **Payment Management:** Seamless registration of payments directly linked to the provided services.
* **Service Catalog:** Easy registration and management of different grooming and bath service types.
* **Financial Reporting:** Automated generation of financial reports for better business health assessment.
* **Role-Based Access Control (RBAC):** Secure user management where different profiles have specific permissions within the system.
---
## 🛠 Tech Stack

* **Backend:** Java with **Spring MVC**.
* **Frontend:** **Thymeleaf** for dynamic templating  and **Bootstrap** for responsive UI design.
* **Security:** **Spring Security** with session-based authentication.
* **Database:** **PostgreSQL** for reliable data persistence.
* **Data Access:** **Spring Data JPA** / Hibernate.
---

## 🏗 Architectural Highlights

This project follows the **Model-View-Controller (MVC)** pattern, ensuring a clean separation of concerns:

1. **Model:** Handles the business logic and database interactions via Spring Data JPA.
2. **View:** Rendered on the server using Thymeleaf, delivering ready-to-use HTML to the browser.
3. **Controller:** Manages the communication between the user and the system, handling HTTP requests and navigation flow.



---

## 🚦 Getting Started

### Prerequisites

* Java 21 or higher.
* Maven.
* PostgreSQL instance.

### Installation

1. **Clone the repository:**

```bash
git clone https://github.com/luan-carvalho/banho_e_tosa_mvc.git

```
2. **Database Configuration:**

Configure your `application.properties` with your PostgreSQL credentials.

3. **Run the application:**

```bash
mvn spring-boot:run

```

4. **Access the system:**

Open your browser and navigate to `http://localhost:8080`.
