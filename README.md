# 🧠 GMH Detection Web App

This project is a web application that helps in the early detection of **Germinal Matrix Hemorrhages (GMH)** in premature infants using **YOLOv8 deep learning**. The model is implemented on a website using **Flask** to provide a simple interface for doctors and healthcare professionals.  

Early GMH detection is critical for better patient outcomes, and this app demonstrates how AI can transform neonatal care with precision and effectiveness. 🚼💻

---
## 📘 Publication

This project is based on the research paper:

**"Deep Learning Approaches for the Assessment of Germinal Matrix Hemorrhage Using Neonatal Head Ultrasound"**  
Ibrahim, N.M., Alanize, H., Alqahtani, L., Alqahtani, L.J., Alabssi, R., Alsindi, W., Alabssi, H., AlMuhanna, A., & Althani, H.  
*Published in Sensors, 2024, 24(21), 7052.*

👉 [Read the full paper](https://www.mdpi.com/1424-8220/24/21/7052)

---

## 🛠️ Features

- Detect GMH in ultrasound images using YOLOv8 ⚡  
- User-friendly web interface with Flask 🌐  
- Supports fast and predictions with  97% accuracy  🩺  
- Stores results in a connected SQL database 🗄️  

---
## 🚀 How to Use

1. 🌐 Open the web app in your browser.
2. 👤 Login with your doctor account.
3. 📤 Upload a cranial ultrasound image of the infant.
4. 🔍 Click **Upload**.
5. 🖼️ The Website gives you the results of the AI model Classification of potential GMH and its estimated Grade.

---

## 📸 Screenshots
<img width="1148" height="699" alt="Mainpage" src="https://github.com/user-attachments/assets/60678d17-0716-4872-aba8-1da5b3c0eef0" />
<img width="1148" height="690" alt="Mainpage2" src="https://github.com/user-attachments/assets/b3cef4f7-c78d-48cf-9d96-cd1f9b775065" />
<img width="1167" height="696" alt="aboutus1" src="https://github.com/user-attachments/assets/4a5ec50b-5700-4646-a0e8-ac8a37525ddf" />
<img width="1164" height="702" alt="aboutus2" src="https://github.com/user-attachments/assets/20d785b6-de8d-4a2b-8944-206b7f637164" />
<img width="1194" height="721" alt="signin" src="https://github.com/user-attachments/assets/d26cc12e-0fd7-48e9-afa8-4a6d39a2a38a" />
<img width="1182" height="715" alt="restpassword" src="https://github.com/user-attachments/assets/cb39e632-7429-4348-a9bb-3e9c6cce70b0" />
<img width="1210" height="730" alt="restpassword2" src="https://github.com/user-attachments/assets/5e7ba1be-66d9-4752-9d34-a3f8400078bc" />
<img width="1237" height="745" alt="admin" src="https://github.com/user-attachments/assets/9b1c2ef0-c790-4921-abe0-5eaaf07929b9" />
<img width="1210" height="733" alt="adduser" src="https://github.com/user-attachments/assets/ff392e18-04fd-470f-b22c-a2e2a75d716e" />
<img width="1234" height="742" alt="deleteuser" src="https://github.com/user-attachments/assets/98c9c315-cd41-4e70-948c-bc1a43e5159f" />
<img width="1313" height="818" alt="doctorpage" src="https://github.com/user-attachments/assets/04cffdc6-c6af-401e-ab90-2217bedc7767" />
<img width="1402" height="876" alt="results" src="https://github.com/user-attachments/assets/98096292-b7ee-4489-9c07-a6ff43ce7869" />


---

## 💾 Installation Guide

Follow these steps to set up the `Roxy.sql` database on your local machine.

## 1️⃣ Requirements
- MySQL or MariaDB server
- MySQL Workbench (optional, for GUI)
- Terminal/Command Prompt access

## 2️⃣ Create a Database
CREATE DATABASE roxy_db;

## 3️⃣ Import the `Roxy.sql` File

### Option 1: Using MySQL Workbench
1. Open MySQL Workbench and connect to your server.
2. Go to File → Open SQL Script and select `Roxy.sql`.
3. Click the Execute button to run the script and populate the database.

### Option 2: Using Command Line
1. Open your terminal or command prompt.
2. Navigate to the folder containing `Roxy.sql`.
mysql -u [username] -p roxy_db < Roxy.sql
> Replace [username] with your MySQL username. You will be prompted for your password.

## 4️⃣ Verify the Installation
mysql -u [username] -p
USE roxy_db;
SHOW TABLES;
You should see all the tables from `Roxy.sql` listed.

## 5️⃣ Next Steps
- Connect your application to the `roxy_db` database.
- Start building queries or integrating it with your project.



