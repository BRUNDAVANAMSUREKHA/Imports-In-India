<div align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=DM+Sans&size=32&duration=3000&pause=1000&color=0EA5E9&center=true&vCenter=true&width=600&lines=Imports+In+India+🇮🇳;Explore+State-wise+Trade+Data;Built+with+PHP+%2B+MySQL" alt="Typing SVG" />

<br/>

# Imports In India

### *A comprehensive web platform to explore, visualize, and understand India's import landscape*

<br/>

![PHP](https://img.shields.io/badge/PHP-8.x-777BB4?style=for-the-badge&logo=php&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-Database-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-5-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Chart.js](https://img.shields.io/badge/Chart.js-Planned-FF6384?style=for-the-badge&logo=chartdotjs&logoColor=white)
![License](https://img.shields.io/badge/License-Proprietary-red?style=for-the-badge)

<br/>
</div>

---

## 📌 Overview

**Imports In India** is a PHP-based web application that maps and visualizes the landscape of goods imported across Indian states and product categories. It transforms complex trade data into an intuitive, browsable interface — making it useful for students, researchers, developers, and policy analysts alike.

> 💡 *India is one of the world's largest importers — yet there's no simple platform to explore **what** is imported, **where**, and **how much**. This project bridges that gap.*

---

## ✨ Features

<table>
<tr>
<td>

- 🗺️ Browse imports by **Indian state**
- 📦 Explore **product categories** and trade partners
- 🔄 Dynamic content rendering with PHP
- 📱 Fully **mobile-responsive** layout via Bootstrap
- 🎨 Modular CSS and JS per page
- 🧩 Extendable modular architecture

</td>
</tr>
</table>

---

## 🎯 Who Is This For?

| User | How They Benefit |
|---|---|
| 🎓 **Students** | Research India's trade patterns with a clean, browsable interface |
| 👩‍💻 **Developers** | A ready-made PHP-MySQL project to extend or experiment with |
| 📊 **Policy Analysts** | Quickly identify state-wise import dependencies |
| 🏫 **Educators** | Use as a teaching tool for web development and trade economics |

---

## 🛠️ Tech Stack

| Layer | Technology | Purpose |
|---|---|---|
| **Frontend** | HTML5, CSS3, Bootstrap 5 | Responsive UI layout |
| **Interactivity** | JavaScript (ES6) | Dynamic page behaviour |
| **Backend** | PHP 8.x | Server-side rendering & logic |
| **Database** | MySQL | Import data storage (optional) |
| **Visualization** | Chart.js *(planned)* | Trade data charts & graphs |
| **Dev Tools** | VS Code, XAMPP/WAMP | Local development & testing |

---

## 🏗️ How It Was Built

```
💡 Idea → 📐 Architecture → 💻 Coding → 🧪 Testing → 🚀 Deploy
```

- **Modular PHP pages** — each route (home, states, categories, imports) is its own clean PHP file
- **Separate CSS/JS per page** — no conflicts, easy to maintain and extend
- **Dynamic includes** — header, footer, and config are shared via PHP includes
- **Incremental Git commits** — built during a hackathon with version-controlled progress
- **Bootstrap grid system** — ensures responsiveness across all screen sizes

---

## 📁 Project Structure

```
imports-in-india/
│
├── 📂 config/
│   └── config.php                # Global DB & app configuration
│
├── 📂 includes/
│   └── db_connect.php            # Database connection logic
│
├── 📂 pages/
│   ├── home.php                  # Main dashboard / landing page
│   ├── states.php                # Browse all Indian states
│   ├── import.php                # Import details view
│   └── categories.php            # Product category explorer
│
├── 📂 public/
│   ├── 📂 css/
│   │   ├── home.css              # Home page styles
│   │   ├── states.css            # States page styles
│   │   └── import.css            # Import details styles
│   │
│   ├── 📂 js/
│   │   ├── home.js               # Home page interactions
│   │   ├── states.js             # States page interactions
│   │   └── import.js             # Import details interactions
│   │
│   └── 📂 images/
│       ├── home/                 # Home page assets
│       ├── states/               # State images and icons
│       └── categories/           # Category images
│
├── 📄 LICENSE
└── 📄 README.md
```

---

## ⚙️ Installation & Setup

### Prerequisites

| Tool | Download |
|---|---|
| XAMPP or WAMP | https://www.apachefriends.org/ |
| Git | https://git-scm.com/ |
| Web Browser | Chrome / Firefox / Edge |

---

### Step 1 — Clone the Repository

```bash
git clone https://github.com/BRUNDAVANAMSUREKHA/Imports-In-India.git
```

---

### Step 2 — Move to Server Root

Place the `imports-in-india/` folder inside your local server root:

```bash
# XAMPP (Windows)
C:\xampp\htdocs\imports-in-india\

# WAMP (Windows)
C:\wamp64\www\imports-in-india\

# XAMPP (Mac/Linux)
/Applications/XAMPP/htdocs/imports-in-india/
```

---

### Step 3 — Start Local Server

Open **XAMPP Control Panel** and start:
- ✅ **Apache**
- ✅ **MySQL**

---

### Step 4 — Configure Database

Edit your database credentials in:

**`config/config.php`**
```php
define('DB_HOST', 'localhost');
define('DB_USER', 'root');        // your MySQL username
define('DB_PASS', '');            // your MySQL password
define('DB_NAME', 'india_imports');
```

**`includes/db_connect.php`**
```php
$conn = mysqli_connect(DB_HOST, DB_USER, DB_PASS, DB_NAME);
```

---

### Step 5 — Import Database (Optional)

If a sample SQL file is provided:

1. Open **phpMyAdmin** → http://localhost/phpmyadmin
2. Create a new database named `india_imports`
3. Click **Import** → select `database/india_imports.sql`
4. Click **Go**

> If no SQL file is provided, the app runs with static/sample data by default.

---

### Step 6 — Open in Browser

```
http://localhost/imports-in-india/pages/home.php
```

---

## 🗺️ Pages & Routes

| Page | URL | Description |
|---|---|---|
| Home | `/pages/home.php` | Dashboard overview |
| States | `/pages/states.php` | Browse all Indian states |
| Categories | `/pages/categories.php` | Explore import product categories |
| Import Details | `/pages/import.php` | View detailed import data |

---

## 🔭 Roadmap

```
v1.0  ✅  Static pages with PHP + Bootstrap
v1.1  🚧  MySQL integration for dynamic data
v1.2  📅  Chart.js visualizations
v1.3  📅  Admin dashboard + login
v1.4  📅  Live trade API integration
v2.0  📅  Full deployment + user authentication
```

---

## 🤝 Contributing

This was originally built as a **hackathon submission**. The modular architecture makes it easy to extend.

If you'd like to contribute:
1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

For bugs or suggestions, use [GitHub Issues](https://github.com/BRUNDAVANAMSUREKHA/Imports-In-India/issues).

---

## 👩‍💻 Author

<div align="center">

**Surekha Brundavanam**

[![GitHub](https://img.shields.io/badge/GitHub-BRUNDAVANAMSUREKHA-181717?style=for-the-badge&logo=github)](https://github.com/BRUNDAVANAMSUREKHA)

</div>

---

## 📄 License

> ⚠️ **Proprietary License** — All rights reserved © 2025 **Surekha Brundavanam**
>
> This project and its source code **not** be used, copied, modified, or distributed without explicit written permission from the author.

---

<div align="center">

**Built with ❤️ during Dpurpose foundation Internship**

*If you found this project useful, consider giving it a ⭐ on GitHub!*

</div>
