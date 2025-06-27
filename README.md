
# 💬 Secure Chatting Application  
Secure Chatting Application developed using **PHP**, **JavaScript**, and **MySQL**.

---

## 🔐 Algorithms Used
• DES *(Not Fully Functional)*  
• AES  
• RSA  
• Diffie-Hellman *(Key Exchange for DES and AES)*  
• ElGamal  

✅ **All algorithms are implemented from scratch**

---

## 📦 Included Files
• Documentation – Detailed descriptions for each algorithm  
• SQL File – `sp_chat.sql` for database setup

---

## ✨ Extra Feature
• All uploaded files are encrypted using their **Base64 arrayBuffer** — not by encrypting the path (as required)

---

## 🛠️ How to Set Up and Run

### 1. 📁 Extract or Clone the Project  
If you downloaded a ZIP or cloned the repository:
- Move the project folder into:
  ```
  C:\xampp\htdocs\
  ```
- Rename it if needed (e.g., `secure-chat`)

---

### 2. ⚙️ Start XAMPP
- Open **XAMPP Control Panel**
- Start the following:
  - ✅ Apache
  - ✅ MySQL

---

### 3. 🗄️ Import the Database
1. Open your browser and go to:  
   ```
   http://localhost/phpmyadmin
   ```
2. Click **New**, then create a database named:  
   ```
   sp_chat
   ```
3. Click **Import**, choose the `sp_chat.sql` file from the project, and import it

---

### 4. 🔧 Configure Database Connection
1. Open the project folder in **VSCode**
2. Locate the database config file (like `db.php` or inside `includes/`)
3. Ensure these credentials are set:

   ```php
   $host = 'localhost';
   $user = 'root';
   $password = '';  // default for XAMPP
   $database = 'sp_chat';
   ```

---

### 5. 🚀 Run the Project
- Open your browser and go to:
  ```
  http://localhost/secure-chat/
  ```

---

## 📩 Contact
**• Asrithtumpudi@gmail.com**
