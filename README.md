# Imports-In-India

**Imports in India** is a comprehensive PHP-based web application designed to showcase and explore the landscape of goods imported into the country across various states and product categories. The platform aims to provide meaningful insights by organizing data in a visually structured and interactive way.

Whether you're a student researching trade, a developer experimenting with PHP-MySQL integration, or a policymaker analyzing state-wise import patterns — this project offers a foundation to understand how imports contribute to the Indian economy.

The application features dynamic content rendering using PHP, modular and responsive layouts with CSS, and JavaScript-powered interactivity. It's built with scalability in mind and can be extended into a data-driven dashboard or integrated with APIs and visualization libraries like Chart.js or D3.js in the future.

---

## 🌟 Inspiration

India is a massive importer of essential goods, but there’s no simple platform that shows **what is imported**, **where**, and **how much**. This project was inspired by the need to **visualize state-wise imports** for researchers, students, and policy analysts in an intuitive, clean interface.

---

## 💡 What It Does

- Users can browse through states and explore what goods are imported into each one.
- The app provides structured import categories and highlights their trade partners.
- It features dynamic charts, responsive pages, and an extendable backend.
- Future versions will allow live data through APIs and user-uploaded datasets.

---

## 🛠️ Tech Stack

- **Frontend**: HTML, CSS (Bootstrap), JavaScript  
- **Backend**: PHP  
- **Database**: MySQL (optional for dynamic content)  
- **AI Tools**: ChatGPT (for guided code generation)  
- **Visualization**: Chart.js (planned)

---

## 🧠 How We Built It

- **Editor**: Visual Studio Code  
- **Tools Used**: ChatGPT for function templates, XAMPP for local testing  
- **Architecture**: Modular PHP pages, dynamic include logic, external JS/CSS  
- All code was written during the hackathon timeframe with incremental Git commits.

---

## 📦 Features

- ✅ Dynamic home, states, categories, and import details pages  
- ✅ Structured CSS and JavaScript files per page  
- ✅ Mobile-responsive layout using Bootstrap  
- 🚧 Chart.js visualizations (planned but not fully implemented)

---

## 🎥 Demo Video

Click below to watch the demo of the project:

[![Watch the Demo](https://img.youtube.com/vi/KN635aCdZdI/0.jpg)](https://youtu.be/KN635aCdZdI)

---

## 📁 File Structure

```
imports-in-india/
├── config/
│   └── config.php                # Global DB & app config
├── includes/
│   └── db_connect.php            # DB connection logic
├── pages/
│   ├── home.php                  # Main dashboard
│   ├── states.php                # List of Indian states
│   ├── import.php                # Import details view
│   └── categories.php            # Product category view
├── public/
│   ├── css/
│   │   ├── home.css
│   │   ├── states.css
│   │   └── import.css
│   ├── js/
│   │   ├── home.js
│   │   ├── states.js
│   │   └── import.js
│   └── images/
│       ├── home/
│       ├── states/
│       └── categories/
├── LICENSE
└── README.md
```

---

## 📚 What's Next

- Implement dynamic data using MySQL or live trade API
- Add admin dashboard with login for data management
- Integrate Chart.js and export functions (PDF, Excel)
- Deploy online with user authentication

---

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/imports-in-india.git
```

### 2. Move to Server Root

Place the `imports-in-india/` folder inside your server root directory:

- For **XAMPP**: `htdocs/`
- For **WAMP**: `www/`

### 3. Start Local Server

Make sure Apache and MySQL are running via XAMPP/WAMP.

### 4. Database Configuration

Edit the following files to set your database credentials:

- `config/config.php`
- `includes/db_connect.php`
- `database/india_imports.sql`

**Optional**: If you have a sample database file, Use it inplace of the "india_imports.sql".

---

## 🤝 Collaboration & Contribution

This was an individual hackathon submission. However, the modular architecture is open to further development or integration in collaboration with research/academic projects.

---

## 📬 Contact

Maintained by [@BRUNDAVANAMSUREKHA](https://github.com/BRUNDAVANAMSUREKHA)  
For issues, please use the [GitHub Issues](https://github.com/BRUNDAVANAMSUREKHA/Imports-In-India/issues) section.

---

## 📄 License

> ⚠️ This is a **proprietary project**. All rights reserved © 2025 **Surekha Brundavanam**.  
> Usage, reproduction, or distribution without permission is strictly prohibited.

---
