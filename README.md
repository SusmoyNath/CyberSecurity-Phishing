# 🎣 Phishing Simulation Project

> **Disclaimer:** This project is for educational and ethical penetration testing purposes **only**. Do **not** use this for unauthorized or malicious activities. The author assumes no responsibility for any misuse.

---

## 📌 About the Project

**Phishing** is a simulation of how attackers can disguise malicious websites as legitimate ones to collect sensitive credentials from unsuspecting users. This project showcases two different phishing setups:

1. **Without PHP (Node.js-based)** – A local simulation for ethical demonstration and learning.
2. **With PHP** – An online deployable version for educational experiments on phishing behavior.

---

## 🛠️ Technologies Used

### 🔹 Node.js Version (Without PHP)
- **Node.js**
- **Express.js**
- **EJS** (Templating Engine)
- **Body-Parser**

### 🔹 PHP Version
- Pure HTML + PHP for basic credential capture simulation.

---

## 🚀 Getting Started

### 🧩 Prerequisites

#### For Node.js Version:
- Node.js installed on your machine: [Download Node.js](https://nodejs.org/en/download/)
- Required packages: Express, EJS, Body-parser

### 🔧 Installation & Run (Node.js Version)


git clone https://github.com/SusmoyNath/CyberSecurity-Phishing.git
cd CyberSecurity-Phishing
npm install express ejs body-parser
node app.js


- The server will run at `http://localhost:3000/`
- Credentials submitted on the form are saved to `logs.json`

### 🌐 Deployment (PHP Version)

1. Host the files on a free hosting service like [000Webhost](https://in.000webhost.com/).
2. Create the following files:
   - `phishing.html` – Your fake login form (customized)
   - `login_details.php` – Script to capture and store credentials

3. In your HTML, **ensure the `<form>` action points to**:
   
<form action="login_details.php" method="POST">


4. Customize the HTML as desired. You can copy source code of real login pages via:
   - Right-click → View Page Source → Copy → Modify for phishing.html

---

## ⚠️ Warning & Legal Notice

This project is **strictly for educational purposes**. Hosting or using phishing pages to collect real user data without consent is illegal and unethical. Always practice responsible coding and penetration testing. Make sure to comply with all local laws and regulations.
