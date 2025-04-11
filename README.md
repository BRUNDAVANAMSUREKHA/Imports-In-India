# Imports-In-India

**Imports in India** is a dynamic PHP-based web application that provides users with detailed information on goods imported into India. The data is organized by Indian states and product categories, displayed through an interactive, user-friendly interface.

---

## 📸 Demo


---

## 🧩 Features

- ✅ Explore import data by **Indian States**
- ✅ View categorized imports based on **product type**
- ✅ Clean and responsive **UI** with modular CSS
- ✅ Page-specific **JavaScript** interactivity
- ✅ Neatly organized structure for scalability and maintenance

---

## 📁 Project Structure

```
IMPORT/
├── config/
│   └── config.php                  # Global configuration settings
├── includes/
│   └── db_connect.php              # Database connection logic
├── pages/
│   ├── home.php                    # Landing page
│   ├── states.php                  # List of Indian states
│   ├── import.php                  # Import details view
│   └── categories.php              # Product category listings
├── public/
│   ├── css/
│   │   ├── home.css
│   │   ├── states.css
│   │   ├── import.css
│   │   └── categories.css
│   ├── js/
│   │   ├── home.js
│   │   ├── states.js
│   │   ├── import.js
│   │   └── categories.js
│   └── images/
│       ├── home/
│       ├── states/
│       ├── imports/
│       ├── categories/
│       └── home.jpg
└── README.md
```

---

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/imports-in-india.git
```

### 2. Move to Server Root

Place the `IMPORT/` folder inside your server root directory:

- For **XAMPP**: `htdocs/`
- For **WAMP**: `www/`

### 3. Start Local Server

Make sure Apache and MySQL are running via XAMPP/WAMP.

### 4. Database Configuration

Edit the following files to set your database credentials:
- `config/config.php`
- `includes/db_connect.php`

**Optional**: Import a sample SQL file if available (you can add `database.sql` and mention it here).

### 5. Launch the App

Open your browser and go to:

```
http://localhost/IMPORT/pages/home.php
```

---

## 💻 Tech Stack

- **PHP** – Server-side scripting
- **HTML/CSS** – Markup and styling
- **JavaScript** – Page interactivity
- **MySQL** – (Optional) for dynamic data
- **XAMPP / WAMP** – Local development environment

---

## 🚀 Future Enhancements

- 📈 Chart-based data visualization (e.g., Pie & Bar charts)
- 🌐 API integration for live trade statistics
- 🔐 Admin login and user authentication
- 🗃️ Data upload and management interface

---

## 📃 License

This project is licensed under the MIT License. You are free to use, modify, and distribute it.

---
