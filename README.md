# 🎬 Movie Review System 

A full-stack **movie review platform** where users can write reviews for movies. Built with a frontend in **HTML/CSS/JavaScript**, and a backend powered by **PHP** and **MySQL**, hosted locally using **XAMPP**.

---

## 🌟 Features

- 📝 Users can submit reviews via a clean, user-friendly form  
- 📄 Reviews are stored securely in a **MySQL database**  
- 🖼️ Department-wise or category-based review sections (if added)  
- 🌐 Responsive frontend built using **HTML, CSS, JS**  
- ⚙️ Backend handled using **PHP** and **MySQL (XAMPP)**
- Entered reviews stored in csv file for the building of dataset for recommendation model.

---

## 💡 Project Overview

- **Frontend:** HTML, CSS, JavaScript  
- **Backend:** PHP  
- **Database:** MySQL (via phpMyAdmin on XAMPP)  
- **Hosting:** Localhost using XAMPP

---

## 🛠️ Technologies Used

| Technology | Purpose            |
|------------|--------------------|
| HTML5      | Page structure     |
| CSS3       | Styling            |
| JavaScript | Interactivity      |
| PHP        | Backend scripting  |
| MySQL      | Database storage   |
| XAMPP      | Local server setup |

---
## Screenshots

![image](https://github.com/user-attachments/assets/4c12be99-aa39-4e0e-b99d-69ffbe7ec1fa)


## ⚙️ How to Run the Project Locally

### ✅ Prerequisites

- Install [XAMPP](https://www.apachefriends.org/index.html)
- PHP and MySQL are included in XAMPP

### 🧪 Steps to Run:

1. Clone or download the repository:
   ```bash
   git clone https://github.com/Vikas717-creator/movie-review-system.git

2. Move the project folder into htdocs (inside your XAMPP directory)

3. Start Apache and MySQL from the XAMPP control panel

4. Open phpMyAdmin (http://localhost/phpmyadmin) and:

5. Create a database (e.g., movie_reviews)

6. Import the provided .sql file (if included) or create the required reviews table:

sql
Copy
Edit
---MYSQL Queries
CREATE TABLE reviews (
  id INT AUTO_INCREMENT PRIMARY KEY,
  movie_title VARCHAR(255),
  user_review TEXT,
  timestamp TIMESTAMP DEFAULT CURRENT_TIMESTAMP
);
Open the project in your browser:

perl
Copy
Edit
http://localhost/movie-review-system
📝 Example Table Format (MySQL)
ID	Movie Title	User Review	Timestamp
1	Inception	Mind-blowing plot! Loved it.	2025-04-11 10:43:12
2	Titanic	Beautiful story. Timeless.	2025-04-11 10:45:19
## 🔮 Future Plans
🔎 Add search and filter functionality by movie or rating

🧠 Apply sentiment analysis on stored reviews

🎯 Build a movie recommendation engine using user reviews

🖼️ Integrate with TMDB API to show movie posters and metadata

🔐 Add user authentication system
