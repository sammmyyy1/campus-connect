# 🎓 Campus Connect – Student Event Engagement Web App

## 📌 Project Overview
Campus Connect is a **full-stack web-based information system** designed to improve student engagement on campus.  
It serves as a **one-stop platform** for students to discover events, RSVP, and provide feedback, while allowing admins and event organizers to manage events effectively.  

- **Course:** INSY 4325 – Information Systems  
- **Project Type:** Option 1 – Full-stack Information System  
- **Team Members:** Samikshya,Rikita,Shraju,Sujan,Suraj 
- **Tech Stack:** Java (Servlets/JSP or Spring Boot), HTML/CSS/JavaScript, MySQL  

---

## 🚀 Features
- 🔑 **User Authentication** – Secure login for Students and Admins  
- 📅 **Event Management** – Browse, search, and RSVP to campus events  
- 📝 **Feedback System** – Students can rate and comment on events  
- 👨‍💻 **Admin Dashboard** – Create, update, and delete events  
- 🔔 **Notifications** – Reminders and updates for users  

---

## 🗂️ Project Structure
CampusConnect/
│──backend/  # Java backend (Servlets/JSP or Spring Boot)

│──frontend/  # HTML/CSS/JavaScript for UI

│──database/  # SQL scripts (schema, sample data)

│──docs/      # UML diagrams, ERD, mockups, reports

│──README.md    # Project documentation

---

## 📊 Database Design (Draft ERD)
- **Users** (user_id, name, email, password, role)  
- **Events** (event_id, title, description, date, location, organizer_id)  
- **RSVP** (rsvp_id, user_id, event_id, status)  
- **Feedback** (feedback_id, user_id, event_id, rating, comments)  
- **Notifications** (notif_id, user_id, message, date_sent)  

## 🛠️ Tools & Technologies
- **Frontend:** HTML, CSS, JavaScript (optional React for advanced UI)  
- **Backend:** Java (Servlets/JSP or Spring Boot)  
- **Database:** MySQL (via JDBC)  
- **Server:** Apache Tomcat (if JSP/Servlet) OR Spring Boot embedded server  
- **Version Control:** Git + GitHub  

## 📅 Project Timeline
- **Phase 1 (Design – Midterm 9/29–10/8):**  
  Problem Domain, Functional Requirements, UI Mockups, UML Class Diagram, Database ERD  

- **Phase 2 (Implementation – Final Demo 11/10–11/19):**  
  Working web app with login, event browsing, RSVP, feedback, and admin dashboard  

- **Phase 3 (Final Report – Due 12/8):**  
  Written report including design, implementation, and screenshots of working system  

## 📖 How to Run (Setup Instructions)
1. Clone this repository:  
   ```bash
   git clone https://github.com/sammmyyy1/campus-connect.git
   cd campus-connect
   
CREATE DATABASE campus_connect;
mvn spring-boot:run
http://localhost:8080/

---

## 📌 Future Enhancements
- Event recommendations based on student interests  
- Push notifications (email/SMS)  
- Analytics dashboard for admins (participation trends)  

---

## 📜 License
This project is for **educational purposes** (INSY 4325). Licensed under the MIT License.


