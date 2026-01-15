# 📈 StockTrad-Z  
### Stock Trading Management System

StockTrad-Z is a web-based stock trading management system developed to simulate essential stock market operations such as viewing available stocks, placing buy/sell orders, and calculating transaction values along with broker commissions.  
The project follows a clean **MVC architecture** and integrates frontend, backend, and database components to demonstrate full-stack development skills.

---

## 🚀 Features

- 📊 Display a list of stocks with their current share prices  
- 💱 Buy and sell stocks by specifying quantity  
- 🧮 Automatic calculation of order value and brokerage commission  
- 📜 View previously executed trade orders  
- 🎨 Responsive and user-friendly UI built with Bootstrap & Thymeleaf  

---

## 🖥️ Application Screens

### Landing Page
The landing page is built using **HTML**, **CSS**, **Bootstrap**, and **Thymeleaf**, providing a clean entry point to the application.

![Landing Page](Share-Data/snippets/landingPage.png)

---

### Welcome Page
A static welcome page designed for future integration with live stock market news APIs.

![Welcome Page](Share-Data/snippets/welcomePage.png)

---

### Stocks Page
Displays stock data retrieved from the database.  
(Current implementation uses static data; can be extended to use live stock APIs.)

![Stocks Page](Share-Data/snippets/stocksPage.png)

---

### Orders Page
Shows all executed buy/sell orders.  
Order data is persisted using **Spring Data JPA** with **MySQL**.

![Orders Page](Share-Data/snippets/ordersPage.png)

---

## 🛠️ Tech Stack

### Backend
- Java  
- Spring Boot  
- Spring MVC  
- Spring Data JPA  

### Frontend
- HTML  
- CSS  
- Bootstrap  
- Thymeleaf  
- JavaScript  

### Database
- MySQL (MySQL Workbench)

---

## ⚙️ Setup Requirements

- JDK 10 or higher  
- JRE (latest version)  
- Eclipse / IntelliJ IDEA  
- Apache Tomcat  
- Web Browser (Chrome / Firefox / Edge)

---

## ▶️ Running the Project

1. Clone the repository as a **Maven project**
2. Import all required dependencies
3. Configure the database in `application.properties`
4. Run `Application.java`
5. Open a browser and navigate to:

