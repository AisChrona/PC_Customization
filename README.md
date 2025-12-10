🖥️ PC Customization
A web-based platform to build your own custom PC

🚀 Project Overview
PC Customization is a web application that allows users to select and assemble their own desktop PC using various hardware components.
Users can browse parts, compare options, create a custom build, and place orders. The system includes modules for Admin, User, Service Centre, and Delivery Boy, ensuring smooth workflow from customization → assembly → delivery.


Mini Project pc customization-…
🧩 Component Library (Short Version)
The system supports a large collection of PC components, but only the main categories are shown here for readability:
🔹CPUs
🔹GPUs
🔹RAM
🔹Storage (SSD/HDD)
🔹Power Supplies
🔹Cabinets
🔹Motherboards
🔹Cooling Systems
🔹Accessories

💡 Note:
Since the actual system contains many detailed models, brands, and variations, not all components are listed here to avoid a very lengthy README.
(All full details exist inside the database and user interface.)


Mini Project pc customization-…

📦 Tech Stack
🔹Category	Technologies
🔹Frontend	HTML, CSS, JavaScript
🔹Backend	PHP
🔹Database	MySQL
🔹Server	WAMP
🔹Tools	phpMyAdmin

🎯 Features

👤 User
🔹Register / Login
🔹Browse components
🔹Add to cart
🔹Request custom builds
🔹Place orders
🔹Track delivery
🔹Add ratings & reviews

Mini Project pc customization-…

🛠️ Service Centre
🔹View user requirements
🔹Assemble systems
🔹Update build status

🚚 Delivery Boy
🔹View assigned deliveries
🔹Update delivery status

🛡️ Admin
🔹Manage users, products, and service centres
🔹Approve/reject accounts
🔹Assign delivery tasks


| Category     | Technologies          |
| ------------ | --------------------- |
| **Frontend** | HTML, CSS, JavaScript |
| **Backend**  | PHP                   |
| **Database** | MySQL                 |
| **Server**   | WAMP                  |
| **Tools**    | phpMyAdmin            |



| Field    | Type    | Description   |
| -------- | ------- | ------------- |
| uid      | int     | User ID       |
| uname    | varchar | Username      |
| uemail   | varchar | Email         |
| uphone   | varchar | Phone         |
| uaddress | varchar | Address       |
| uimage   | varchar | Profile image |
|          |         |               |


| Field     | Type    | Description    |
| --------- | ------- | -------------- |
| pid       | int     | Product ID     |
| pname     | varchar | Product name   |
| pbrand    | varchar | Brand          |
| price     | varchar | Price          |
| processor | varchar | Processor type |
| display   | varchar | Display spec   |
| desc      | varchar | Description    |
| p_image   | varchar | Image          |
|           |         |                |


| Test Case         | Expected Output         | Result |
| ----------------- | ----------------------- | ------ |
| Empty form fields | Validation errors       | ✔ Pass |
| Incorrect login   | Error message           | ✔ Pass |
| Admin login       | Redirect to Admin panel | ✔ Pass |
|                   |                         |        |


/pc_customization
│── /ADMIN
│── /USER
│── /DELIVERY_BOY
│── /CUS_CENTRE
│── connection/
│── login.php
│── user_reg.php
│── index.php

⚙️ How to Run
🔹Install XAMPP/WAMP
🔹Place the project folder into:
🔹htdocs (XAMPP)
🔹www (WAMP)
🔹Import the SQL database into phpMyAdmin
🔹Update DB configuration in connect.php
🔹Start Apache + MySQL

Open browser:
http://localhost/pc_customization


🏁 Conclusion
This system provides a complete platform for users to customize PCs, validate components, place orders, and track assembly and delivery.
It ensures a smooth experience across all user roles.


📌 Important Note
🔹 This GitHub repository does not include all files, because the full project folder is very large.
🔹 Only the essential files and structure are uploaded.
🔹 The system also contains many component models and sub-components, but only the major categories are shown here to keep the README clean.
