**README.txt**
**Grading System App**
GitHub Repository: [https://github.com/jayimillena/grading-system](https://github.com/jayimillena/grading-system)

---

### 📌 Project Overview

The **Grading System App** is a simple and intuitive web-based system developed using **Laravel 12**, **TailwindCSS**, and **MySQL**. It allows administrators and teachers to manage students, subjects, and grades efficiently.

---

### ⚙️ Technologies Used

* **Laravel 12** – PHP web framework for backend logic and routing
* **TailwindCSS** – Utility-first CSS framework for modern, responsive UI
* **MySQL** – Relational database for storing users, grades, and class data

---

### 🚀 Features

* User authentication (Admin and Teachers)
* Manage students, classes, and subjects
* Add and edit student grades
* View student report cards
* Simple and clean user interface
* Role-based access control

---

### 🔧 Installation Instructions

1. **Clone the repository**

   ```bash
   git clone https://github.com/jayimillena/grading-system.git
   cd grading-system
   ```

2. **Install dependencies**

   ```bash
   composer install
   npm install && npm run build
   ```

3. **Create environment file**

   ```bash
   cp .env.example .env
   ```

4. **Configure your `.env` file**
   Set your database credentials and other environment variables.

5. **Generate application key**

   ```bash
   php artisan key:generate
   ```

6. **Run migrations and seed database**

   ```bash
   php artisan migrate --seed
   ```

7. **Start the development server**

   ```bash
   php artisan serve
   ```

---

### 🧑 Default Credentials

After seeding, you can log in using the default credentials:

* **Admin**

  * Email: `admin@example.com`
  * Password: `password`

---

### 📸 Screenshots

Visit the GitHub repository to view screenshots of the system in action.

---

### 📝 License

This project is open-source and free to use under the [MIT License](https://opensource.org/licenses/MIT).

---

### 🙌 Credits

Created by [@jayimillena](https://github.com/jayimillena)

---


