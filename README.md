# 🌱 EcoHabit Tracker + Reward System

A full-stack Spring Boot web application designed to encourage environmentally sustainable behavior by tracking eco-friendly activities and rewarding users with eco-points.

---

## 🚀 Features

- 👤 User Management (Create & View Users)
- 🌿 Eco Activity Tracking (Log daily sustainable actions)
- 🧮 Automatic Eco-Score Calculation
- 🏆 Leaderboard System (Top performers ranking)
- 📊 Dashboard with real-time statistics
- ⚡ Clean UI using Bootstrap 5

---

## 🏗️ Tech Stack

- **Backend:** Spring Boot (Java)
- **Database:** H2 In-Memory Database
- **ORM:** Spring Data JPA
- **Frontend:** JSP, JSTL, Bootstrap 5
- **Testing:** JUnit, Mockito

---

## 📂 Project Structure
src/
├── controller/
├── service/
├── repository/
├── entity/
└── resources/
├── templates/
└── application.properties

---

## 🔗 Entity Relationship

- One **User** can have multiple **EcoActivities**
- EcoActivity contains a foreign key `user_id`

---

## ⚙️ How to Run

1. Clone the repository:
git clone https://github.com/your-username/eco-habit-tracker.git

2. Open in IDE (IntelliJ / VS Code)

3. Run the application:mvn spring-boot:run

4. Open browser:http://localhost:8080

---

## 📸 Screenshots

- Dashboard Overview
- Users List
- Activity Tracking
- Leaderboard Ranking

*(Refer to project PDF for full screenshots)*

---

## 🎯 Project Objective

This project demonstrates how technology can be used to promote sustainable behavior by combining data tracking, gamification, and real-time analytics.

---

## 🧪 Testing

- Unit tests implemented for:
  - Repository layer
  - Service layer
- Exception handling included

---

## 📌 Future Enhancements

- Mobile app integration
- AI-based eco suggestions
- Cloud database support

---

## 👨‍💻 Author

**NENAVATH ABHISHEK NAIK**  
Roll No: 2024eb1825

---
