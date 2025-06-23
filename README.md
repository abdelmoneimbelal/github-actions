# 🚀 Laravel GitHub Actions CI/CD Project

<div align="center">

![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)

**A comprehensive Laravel application demonstrating CI/CD workflows with GitHub Actions**

[View Demo](https://github.com/abdelmoneimbelal/github-actions) · [Report Bug](https://github.com/abdelmoneimbelal/github-actions/issues) · [Request Feature](https://github.com/abdelmoneimbelal/github-actions/issues)

</div>

---

## 📋 Table of Contents

- [About The Project](#about-the-project)
- [Built With](#built-with)
- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [GitHub Actions Workflows](#github-actions-workflows)
- [Testing](#testing)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## 🎯 About The Project

This Laravel application serves as a comprehensive example of implementing modern CI/CD practices using GitHub Actions. It includes authentication, user management, and automated testing workflows that demonstrate best practices for continuous integration and deployment.

### ✨ Key Features

- 🔐 **Authentication System** - Complete user authentication with email verification
- 👤 **User Profile Management** - Update profile information and password
- 🧪 **Automated Testing** - PHPUnit and Pest testing frameworks
- 🚀 **CI/CD Pipeline** - GitHub Actions workflows for testing and deployment
- 📱 **Responsive Design** - Modern UI with Tailwind CSS
- 🔒 **Security Features** - Password confirmation and email verification

---

## 🛠️ Built With

### Backend
- **[Laravel](https://laravel.com/)** - PHP web application framework
- **[PHP](https://www.php.net/)** - Server-side scripting language
- **[MySQL](https://www.mysql.com/)** - Relational database management system

### Frontend
- **[Blade Templates](https://laravel.com/docs/blade)** - Laravel's templating engine
- **[Tailwind CSS](https://tailwindcss.com/)** - Utility-first CSS framework
- **[Vite](https://vitejs.dev/)** - Build tool and development server

### DevOps & Testing
- **[GitHub Actions](https://github.com/features/actions)** - CI/CD automation
- **[PHPUnit](https://phpunit.de/)** - PHP testing framework
- **[Pest](https://pestphp.com/)** - Testing framework with expressive syntax

---

## 🚀 Getting Started

Follow these steps to get your development environment set up.

### Prerequisites

Make sure you have the following installed on your system:

- **PHP** >= 8.1
- **Composer** - Dependency manager for PHP
- **Node.js** >= 16.x
- **npm** or **yarn** - Package manager
- **MySQL** or **PostgreSQL** - Database server
- **Git** - Version control system

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/abdelmoneimbelal/github-actions.git
   cd github-actions
   ```

2. **Install PHP dependencies**
   ```bash
   composer install
   ```

3. **Install Node.js dependencies**
   ```bash
   npm install
   ```

4. **Set up environment variables**
   ```bash
   cp .env.example .env
   ```

5. **Configure your database in `.env`**
   ```env
   DB_CONNECTION=mysql
   DB_HOST=127.0.0.1
   DB_PORT=3306
   DB_DATABASE=your_database_name
   DB_USERNAME=your_database_username
   DB_PASSWORD=your_database_password
   ```

6. **Generate application key**
   ```bash
   php artisan key:generate
   ```

7. **Run database migrations**
   ```bash
   php artisan migrate
   ```

8. **Seed the database (optional)**
   ```bash
   php artisan db:seed
   ```

9. **Build frontend assets**
   ```bash
   npm run build
   ```

10. **Start the development server**
    ```bash
    php artisan serve
    ```

Your application will be available at `http://localhost:8000`

---

## 💻 Usage

### Development

For development with hot reloading:
```bash
npm run dev
```

### Production Build

To build assets for production:
```bash
npm run build
```

### Running Tests

Execute the test suite:
```bash
php artisan test
```

Or using Pest:
```bash
./vendor/bin/pest
```

---

## 🔄 GitHub Actions Workflows

This project includes several GitHub Actions workflows:

### 🧪 Continuous Integration
- **Automated Testing** - Runs on every push and pull request
- **Code Quality Checks** - PHP CS Fixer and static analysis
- **Security Scanning** - Dependency vulnerability checks

### 🚀 Continuous Deployment
- **Staging Deployment** - Auto-deploy to staging environment
- **Production Deployment** - Manual deployment to production
- **Database Migrations** - Automated migration running

### 📊 Workflow Status

![CI](https://github.com/abdelmoneimbelal/github-actions/workflows/CI/badge.svg)
![Deploy](https://github.com/abdelmoneimbelal/github-actions/workflows/Deploy/badge.svg)

---

## 🧪 Testing

This project uses both PHPUnit and Pest for testing:

```bash
# Run all tests
php artisan test

# Run specific test file
php artisan test tests/Feature/AuthenticationTest.php

# Run tests with coverage
php artisan test --coverage
```

### Test Structure
- **Feature Tests** - Test complete user workflows
- **Unit Tests** - Test individual components
- **Browser Tests** - End-to-end testing (if configured)

---

## 🤝 Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Coding Standards

- Follow [PSR-12](https://www.php-fig.org/psr/psr-12/) coding standards
- Write meaningful commit messages
- Add tests for new features
- Update documentation as needed

---

## 📄 License

Distributed under the MIT License. See `LICENSE` file for more information.

---

## 📞 Contact

**Your Name** - [abdobelal069@gmail.com](mailto:abdobelal069@gmail.com)

**Project Link**: [https://github.com/abdelmoneimbelal/github-actions](https://github.com/abdelmoneimbelal/github-actions)

---

## 🙏 Acknowledgments

- [Laravel Documentation](https://laravel.com/docs)
- [GitHub Actions Documentation](https://docs.github.com/en/actions)
- [Tailwind CSS](https://tailwindcss.com/)
- [Choose an Open Source License](https://choosealicense.com)
- [Img Shields](https://shields.io)

---

<div align="center">
  <strong>⭐ Star this repository if you found it helpful! ⭐</strong>
</div>
