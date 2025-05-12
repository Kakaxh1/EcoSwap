# EcoSwap – Local Barter and Exchange Platform 🌀

EcoSwap is a final-year BCA project developed to encourage sustainable living by enabling users to exchange goods without the use of money. It’s a simple, secure, and locally-deployable barter platform built using PHP and MySQL.

---

## 🚀 Project Description

EcoSwap is a web-based system designed to connect people within a local community (e.g., college, housing society) and allow them to upload, browse, and request items for exchange.

Instead of discarding unused but usable items, users can list them on the platform and swap them with others — promoting a waste-free and eco-conscious lifestyle.

---

## 🎯 Objectives

- Promote eco-friendly and zero-waste practices
- Build a local cashless exchange system
- Connect users through a simple and intuitive platform
- Reduce landfill waste and overconsumption

---

## 🛠️ Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript  
- **Backend**: PHP 7+  
- **Database**: MySQL  
- **Environment**: XAMPP/WAMP (localhost)  

---

### 🛠️ Setup Instructions

1. **📁 Clone or Download the Project**

   ```bash
   git clone https://github.com/kakaxh1/ecoswap.git
   ```

   Or download the ZIP and extract it.

2. **📂 Move to Server Directory**

   For XAMPP, move the folder into:
   ```
   C:\xampp\htdocs\
   ```

3. **🗃️ Create the Database**

   - Open `http://localhost/phpmyadmin`
   - Create a new database (e.g., `ecoswap`)
   - Import `ecoswap.sql` if provided

4. **⚙️ Configure Database Connection**

   Edit `config.php` (or `db.php`) and update:

   ```php
   $host = 'localhost';
   $db = 'ecoswap';
   $user = 'root';
   $pass = '';
   ```

5. **📂 Create Uploads Directory**

   Inside the main project folder:

   ```bash
   mkdir -p uploads/products
   ```

   Or manually:
   - Create `uploads/` folder
   - Inside it, create `products/`

   > This folder is used to store uploaded product images.

6. **👨‍💻 Add Default Admin User**

   Run this script once to add a default admin to your database:

   ```bash
   http://localhost/ecoswap/scripts/create_default_admin.php
   ```

   > Make sure the database is created before running this!

7. **🚀 Run the Project**

   Open your browser and go to:

   ```
   http://localhost/ecoswap
   ```

   You should see the home page of EcoSwap.

---


## 🔑 Core Features

- ✅ User Registration & Login  
- ✅ Item Upload with Image & Description  
- ✅ Search & Browse Listed Items  
- ✅ Exchange Request System  
- ✅ Admin Dashboard (user/item moderation)  
- ✅ Session Management & Validation  

---

## 📁 Modules

- **User Panel**: Register, Login, Upload Items, Send Requests  
- **Admin Panel**: Approve/Delete Listings, Manage Users  
- **Exchange System**: Handle barter requests with status update

---

## 🔒 Future Enhancements

- 📱 Android app version  
- 🌐 Multi-language support  
- 🧠 AI-based swap recommendations  
- ⭐ Rating & trust system for users  

---

## 👨‍🎓 Project Info

> 🎓 Developed as Final Year Project – BCA  
> 📍 Bhagwan Mahavir College of Computer Applications  
> 📅 Semester 6 (2025)  
> 👨‍💻 Team Size: 4 Members  
> 💼 Status: Completed and Deployed (Localhost)



---

## 📝 License

This project is created for academic purposes. You are free to fork and customize it for your own learning. Attribution appreciated.

---

## 💬 Contact

- Developer: Bhavya Ashokbhai Morvadiya  
- Email: bhavymorvadiya@gmail.com
- LinkedIn: bhavy morvadiya  
- GitHub: Kakaxh1

---

