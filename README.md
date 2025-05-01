# Dance-School-Management web App

This is a web-based application developed using React.js for managing dance school activities. The system allows users to explore various dance courses, view course details, enroll, and access static informational pages like Terms, FAQ, and About Us. It is designed to be responsive and beginner-friendly.

---

## 📌 Table of Contents

- [📌 Table of Contents](#-table-of-contents)
- [🚀 Features](#-features)
- [🧰 Technologies Used](#-technologies-used)
- [📁 Project Structure](#-project-structure)
- [📦 Installation & Setup Instructions](#-installation--setup-instructions)
- [📲 Access on Mobile](#-access-on-mobile)
- [📷 Screenshots](#-screenshots)
- [📈 Future Enhancements](#-future-enhancements)
- [🙋‍♂️ Author](#-author)

---



## 🚀 Features

- 🏠 Home page with welcome image and CTA
- 📋 View available dance courses
- 🧾 Course description, duration, and pricing
- 🖱️ Enroll button with local storage handling
- 📄 Pages: Terms & Conditions, Privacy Policy, Contact Us, FAQ, About Us
- 📱 Responsive layout (mobile-friendly)
- 🔒 Basic login/signup navigation (static)
- 🧠 LocalStorage used to store enrollments

---

## 🧰 Technologies Used

- **Frontend**: React.js, React Router
- **Styling**: CSS3, Flexbox
- **Storage**: Browser `localStorage`
- *(Optional backend support with MongoDB and Node.js can be added later)*

- ## 📁 Project Structure
dance-school-management/
│
├── public/
│   ├── index.html                → Main HTML template
│   └── favicon.ico               → Site icon
│
├── src/
│   ├── assets/                   → Static images
│   │   └── home-bg.png           → Background image for home page
│
│   ├── components/               → Reusable UI components
│   │   ├── Navbar.js             → Navigation bar component
│   │   ├── Navbar.css            → CSS for Navbar
│   │   └── Footer.js             → (Optional) Footer if used
│
│   ├── pages/                    → Pages that map to routes
│   │   ├── Home.js               → Home page with welcome message & image
│   │   ├── Home.css              → Styles for Home page
│   │   ├── Courses.js            → Displays all courses with enroll option
│   │   ├── Courses.css           → Styles for Courses page
│   │   ├── AboutUs.js            → About Us page
│   │   ├── ContactUs.js          → Contact info (static)
│   │   ├── FAQ.js                → Frequently Asked Questions
│   │   ├── PrivacyPolicy.js      → Static privacy content
│   │   ├── TermsAndConditions.js → Static terms content
│   │   ├── Login.js              → Login form (or button redirecting to courses)
│   │   └── Signup.js             → Signup page (e.g. "Create an Account")
│
│   ├── App.js                    → Main app with all route definitions
│   ├── index.js                  → Root file (renders App.js)
│   └── index.css                 → Global styles
│
├── .gitignore                    → Git ignore rules
├── package.json                  → Project metadata and dependencies
├── README.md                     → Project introduction and usage guide
└── package-lock.json             → Dependency lock file

 Suggested Routing in App.js
<Route path="/" element={<Home />} />
<Route path="/courses" element={<Courses />} />
<Route path="/about-us" element={<AboutUs />} />
<Route path="/contact-us" element={<ContactUs />} />
<Route path="/faq" element={<FAQ />} />
<Route path="/terms-and-conditions" element={<TermsAndConditions />} />
<Route path="/privacy-policy" element={<PrivacyPolicy />} />
<Route path="/login" element={<Login />} />
<Route path="/signup" element={<Signup />} />

2. Install Dependencies
npm install

3. Start the Development Server
npm start
  Visit: http://localhost:3000 in your browser

📲 Access on Mobile
To open the site on your phone (on same Wi-Fi):

Find your IP:

Windows: ipconfig

macOS/Linux: ifconfig

2.Use this format on your phone browser:
http://<your-ip>:3000

📈 Future Enhancements
Integrate payment gateway (e.g., Razorpay)

Add admin panel for managing courses

Link MongoDB for real user/course data

Profile section for enrolled users

Add contact form functionality

🙋‍♂️ Author
Name: Srinivasan
Branch: Information Technology (AI & DS)
Year: Pre-final year
College: Madras Institute of Technology, Anna University
Project: Dance School Management System
