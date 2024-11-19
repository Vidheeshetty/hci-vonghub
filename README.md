# hci-vonghub

# Vong Hub - Learning Management Tool

Vong Hub is a fully developed Learning Management System (LMS) built on the Moodle framework. It is designed to provide an intuitive and feature-rich platform for educators, students, and administrators to streamline online learning and collaboration.

---

## Features

- **User Management**: Manage students, teachers, and administrative roles efficiently.
- **Course Management**: Create, update, and manage courses with ease.
- **Interactive Learning**: Tools for quizzes, assignments, forums, and real-time interaction.
- **Analytics & Reports**: Generate insightful analytics and reports on user progress and system performance.
- **Modular Plugins**: Extend functionality with modular plugins and extensions.
- **Security**: Robust security features to protect user data and ensure privacy.
- **Customization**: Fully customizable themes and user interfaces.

---

## Getting Started

### Prerequisites
To set up Vong Hub, you need:
- PHP 7.4 or higher
- MySQL 5.7 or higher / MariaDB
- Web server (Apache/Nginx)
- Node.js (optional, for plugin development)

### Installation

1. **Download Vong Hub**:
   Clone the repository to your server:
   ```bash
   git clone https://github.com/your-repo/vong-hub.git

Set Up Database:

Create a new database (e.g., vong_hub_db) in MySQL/MariaDB.
Import the provided mariadb-backup.sql file into the database.
Configure Settings:

Open config.php in the root directory.
Update the database credentials and web root settings.
Install Dependencies: Install required dependencies using Composer:


composer install
For frontend development, run:


npm install
Set Permissions: Set appropriate permissions for moodledata and other writable directories:

bash
Copy code
chmod -R 755 moodledata
Run Installation: Access your Vong Hub installation via the browser and follow the installation wizard:


Project Structure
admin/: Admin-specific configurations and tools.
auth/: Authentication modules.
backup/: Backup and restore functionalities.
course/: Course management files.
mod/: Modular activities and plugins.
theme/: Themes and UI customization files.
user/: User management and profile data.
Development
Setting Up Development Environment
To start developing with Vong Hub:

Ensure your local server meets the prerequisites.
Use a code editor like VS Code or PHPStorm.
Follow Moodle's plugin development guide for custom modules.
Testing
Run tests using PHPUnit:


phpunit
Contributing
We welcome contributions! To contribute:

Fork the repository.
Create a new branch for your feature/bugfix.
Submit a pull request with a detailed description of your changes.

License
This project is licensed under the GPL License. See the COPYING.txt file for details.

Support
For support or queries, contact us at support@vonghub.com.
