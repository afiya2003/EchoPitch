🧠 EchoPitch – Business Idea Sharing and Pitching Platform
📋 Overview

EchoPitch is an interactive web platform built by The Idea Crew that allows users to share, contribute, and pitch innovative business ideas.
It provides a space for entrepreneurs, students, and innovators to collaborate, while ensuring confidentiality through a common Non-Disclosure Agreement (NDA) link.

Users can also choose to make their ideas public using the “Public Domain Pitch” option.

🚀 Features

✅ User-Friendly Interface – Built using HTML, CSS, and Bootstrap
✅ Secure Login & Registration System – User authentication via PHP & MySQL
✅ Idea Submission Form – Users can pitch ideas securely
✅ Common NDA Access – All ideas link to a shared NDA page
✅ Public Domain Pitch Option – Share ideas openly for collaboration
✅ Dynamic Dashboard – Displays submitted ideas and user activity

| Layer    | Technology             |
| -------- | ---------------------- |
| Frontend | HTML, CSS, Bootstrap   |
| Backend  | PHP                    |
| Database | MySQL (via phpMyAdmin) |
| Server   | Apache (through XAMPP) |

⚙️ Installation & Setup
1️⃣ Install XAMPP
2️⃣ Start Apache and MySQL
3️⃣ Move Project to htdocs
4️⃣ Create Database

Open phpMyAdmin
Click New → create database

5️⃣ Configure Database Connection

Check your PHP connection file (e.g., db_connect.php):

<?php
$conn = mysqli_connect("localhost", "root", "", "echopitch_db");
if (!$conn) {
    die("Connection failed: " . mysqli_connect_error());
}
?>

6️⃣ Run the Project

Open your browser and visit:
👉 http://localhost/EchoPitch/


<img width="1918" height="1017" alt="image" src="https://github.com/user-attachments/assets/39168e1e-9ea8-4b71-a3ac-a6e4e4a2ca39" />

<img width="942" height="511" alt="image" src="https://github.com/user-attachments/assets/819af85c-d91c-4a20-816f-41d556e22599" />

<img width="942" height="470" alt="image" src="https://github.com/user-attachments/assets/2057c216-06c0-43b3-844d-6f37cb8e818d" />

<img width="911" height="480" alt="image" src="https://github.com/user-attachments/assets/2efb75fc-abed-4cfd-bcbf-f11f40bd7c25" />


