# 🌿 Connect with Your Roots

**Connect with Your Roots** is a heritage-focused web project designed to showcase the rich legacy of the **Maratha Empire**.  
The platform presents detailed information about Maratha forts, warriors, and traditional weapons, secured behind a user authentication system.

---

## 📌 Project Purpose

The goal of this project is to:
- Preserve Indian history digitally
- Educate users about Maratha heritage
- Provide a secure, structured, and interactive learning experience

---

## 🛠️ Tech Stack

### Frontend
- HTML5
- CSS3
- JavaScript (Vanilla)

### Backend
- Node.js
- Express.js

### Database
- PostgreSQL

### Security
- bcrypt (Password hashing)
- CORS
- Session-based authentication

---

## ✨ Key Features

- 🔐 User Registration & Login
- 🏰 Detailed Maratha Forts module
- ⚔️ Traditional Weapons section
- 🛡️ Great Maratha Warriors module
- 🔒 Protected access (Login required)
- 🎨 Dark heritage-themed UI

---

## 📂 Project Modules

1. **Authentication Module**
   - User registration
   - Secure login using PostgreSQL
   - Password hashing

2. **Maratha Forts**
   - Historical details
   - Strategic importance
   - Image-based UI cards

3. **Great Maratha Warriors**
   - Life history
   - Military contributions
   - Leadership roles

4. **Weapons of Maratha Empire**
   - Weapon descriptions
   - Usage in warfare
   - Cultural significance

---

## 📁 Folder Structure

```text
Connect-with-your-Roots/
│
├── assets/
│   ├── battles/
│   ├── forts/
│   ├── maps/
│   ├── warriors/
│   ├── weapons/
│   └── index-wallpaper.jpg
│
├── backend/
│   ├── db.js              # PostgreSQL database connection
│   └── server.js          # Express server & authentication logic
│
├── connect-with-your-roots/
│   ├── .gitattributes
│   ├── index.html         # Landing page
│   ├── main.html          # Main dashboard after login
│   │
│   ├── login.html         # User login page
│   ├── register.html      # User registration page
│   │
│   ├── profile.html       # Historical personality profile
│   ├── warrior-profile.html
│   ├── fort-profile.html
│   ├── battle-profile.html
│   ├── weapon-profile.html
│   │
│   ├── warriors.html      # Great Maratha Warriors module
│   ├── forts.html         # Forts of Maratha Empire
│   ├── battles.html       # Battles of Maratha Empire
│   ├── weapons.html       # Traditional weapons module
│   └── maps.html          # Maps & territorial expansion
│
└── README.md
```
## 🔐 Security Notes
-Passwords are hashed using bcrypt
-Sensitive files are excluded using .gitignore
-Backend access required for protected content

## 🎯 Learning Outcomes
-Understood full-stack web application flow
-Designed responsive and themed web pages
-Implemented user login and registration
-Worked with PostgreSQL database
-Used Node.js and Express for backend
-Applied basic web security concepts
-Learned Git and GitHub project hosting
-Improved debugging and problem-solving skills

## 📌 Future Enhancements
-Admin dashboard
-JWT authentication
-User activity tracking
-Hosting on cloud (Render / Railway)

## 👤 Author
Shiv Koli
B.E. Information Technology
University of Mumbai
