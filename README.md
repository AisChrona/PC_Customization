🖥️ PC Customization
(A web-based platform to build your own custom PC)

🚀 Project Overview
-PC Customization is a web application that allows users to select and assemble their own desktop PC using various hardware components.
Users can browse parts, compare options, create a custom build, and place orders. The system includes modules for Admin, User, Service Centre, and Delivery Boy, ensuring smooth workflow from customization → assembly → delivery.


Mini Project pc customization-…
 🧩 Component Library-
  The system supports a large collection of PC components, but only the main categories are shown here for readability:

  
| Component Category | Description |
|--------------------|-------------|
| CPU               | Intel & AMD processors |
| GPU               | NVIDIA & AMD graphics cards |
| RAM               | DDR3 / DDR4 / DDR5 modules |
| Storage           | SSD, HDD, NVMe drives |
| Power Supply      | SMPS units of various wattages |
| Cabinet           | ATX, Micro-ATX, Mini-ITX cases |
| Motherboard       | Compatible with Intel & AMD |
| Cooling System    | Air coolers & Liquid coolers |
| Accessories       | Keyboard, Mouse, RGB items, etc. |




💡 Note:
Since the actual system contains many detailed models, brands, and variations, not all components are listed here to avoid a very lengthy README.
(All full details exist inside the database and user interface.)


Mini Project pc customization-…

📦 Tech Stack
| Category     | Technologies          |
| ------------ | --------------------- |
| **Frontend** | HTML, CSS, JavaScript |
| **Backend**  | PHP                   |
| **Database** | MySQL                 |
| **Server**   | WAMP                  |
| **Tools**    | phpMyAdmin            |






🎯 Features

👤 User
| Action                    | Description                         |
| ------------------------- | ----------------------------------- |
| **Register / Login**      | User authentication system          |
| **Browse components**     | View available PC parts             |
| **Add to cart**           | Add selected items to cart          |
| **Request custom builds** | Submit custom PC requirements       |
| **Place orders**          | Order selected components or builds |
| **Track delivery**        | Monitor delivery status             |
| **Add ratings & reviews** | Give feedback on products/services  |




Mini Project pc customization-…

🛠️ Service Centre
| Action                     | Description             |
| -------------------------- | ----------------------- |
| **View user requirements** | Check user requests     |
| **Assemble systems**       | Build the customized PC |
| **Update build status**    | Mark assembly progress  |



🚚 Delivery Boy
| Action                       | Description              |
| ---------------------------- | ------------------------ |
| **View assigned deliveries** | Check tasks assigned     |
| **Update delivery status**   | Mark progress/completion |




🛡️ Admin
| Action                                    | Description                      |
| ----------------------------------------- | -------------------------------- |
| **Manage users/products/service centres** | Add / edit / delete entries      |
| **Approve / reject accounts**             | Validate registrations           |
| **Assign delivery tasks**                 | Allocate orders to delivery boys |





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



⚙️# How to Run
- Install XAMPP or WAMP
- Place the project folder into:
  - htdocs (for XAMPP)
  - www (for WAMP)
- Import the SQL database into phpMyAdmin
- Update database configuration inside connect.php
- Start Apache and MySQL services
- 
- Open your browser and go to:
  http://localhost/your_project_folder



🏁 Conclusion
This system provides a complete platform for users to customize PCs, validate components, place orders, and track assembly and delivery.
It ensures a smooth experience across all user roles.


📌 Important Note
- This GitHub repository does not include all files, because the full project folder is very large.
- Only the essential files and structure are uploaded.
- The system also contains many component models and sub-components, but only the major categories are shown here to keep the README clean.
