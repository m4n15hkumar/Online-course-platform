# Online-course-platform
A full-stack web-based learning platform that allows users to register, log in, update profiles, contact support, and explore available courses and tutors. Built with a focus on structured user experience, backend API architecture, and PostgreSQL database integration.

🚀 Features
👨‍🎓 User Registration & Login with secure password hashing using bcrypt

✏️ Profile Management: Update personal details, become a tutor, and manage your account

📚 Course & Tutor Browsing: View available courses and tutor listings

📩 Contact Support: Users can submit support or inquiry forms

🛡️ Backend Security: Password hashing, input validation, and error handling

📊 PostgreSQL Integration with efficient querying and relationship management

🛠️ Tech Stack
Layer	Technology
Frontend	HTML, CSS, JavaScript
Backend	Node.js, Express.js
Database	PostgreSQL
Security	bcrypt (password hashing)
Tools	REST API, Postman, pgAdmin

📂 Project Structure
bash
Copy code
/online-course-platform
│
├── /frontend              # Contains HTML, CSS files for UI
│   ├── index.html
│   ├── teachers.html
│   └── style.css
│
├── /backend               # Node.js + Express backend
│   ├── routes/
│   │   ├── auth.js        # Handles registration and login
│   │   ├── profile.js     # Update profile, become tutor
│   │   └── contact.js     # Contact support form
│   ├── db.js              # PostgreSQL DB connection
│   └── server.js          # Main server setup
│
├── .env                   # Environment variables (DB credentials)
└── package.json           # Dependencies
🔐 Functionality Overview
Register/Login: Create account and authenticate securely

Update Profile: Add bio, experience, subjects taught (if tutor)

View Tutors: Browse available tutors with detailed profiles

Course Listings: Explore subjects and descriptions

Contact Us: Send support or help requests directly from frontend

Environment Config: Secure .env usage for DB and port config

✅ Setup Instructions
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/online-course-platform.git
Install backend dependencies:

bash
Copy code
cd backend
npm install
Set up your .env file:

bash
Copy code
DB_HOST=localhost
DB_USER=youruser
DB_PASS=yourpass
DB_NAME=online_course
PORT=5000
Run the backend server:

bash
Copy code
node server.js
Open frontend in browser:
Open frontend/index.html manually or host it locally.

🧠 Future Enhancements
🧾 Add course enrollment & payment gateway

💬 Implement chat or messaging between student and tutor

🔍 Add course search and filter

📱 Make the frontend fully responsive

📈 Dashboard for admin and tutors
