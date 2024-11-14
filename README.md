
# Backend Developer Portfolio

Welcome to my portfolio repository! I am a backend developer with experience in various frameworks and technologies including Node.js, NestJS, Laravel, and Django.

## 🛠️ Technologies & Frameworks

- **Node.js** - JavaScript runtime built on Chrome's V8 JavaScript engine.
- **NestJS** - A progressive Node.js framework for building efficient, reliable, and scalable server-side applications.
- **Laravel** - A PHP framework for web artisans, providing an expressive and elegant syntax.
- **Django** - A high-level Python web framework that encourages rapid development and clean, pragmatic design.

## 📁 Project Structure

The repository is organized into folders for each technology, making it easy to navigate:

```
├── nodejs/         # Node.js specific projects or modules
├── nestjs/         # NestJS applications and services
├── laravel/        # Laravel projects and components
├── django/         # Django projects and applications
└── README.md       # This README file
```

## 🚀 Getting Started

Each framework has its own requirements and setup process. Below is a quick start guide for each one.

### Node.js

1. **Install Node.js** (recommended version: 14+).
2. Navigate to the `nodejs` folder and install dependencies:
   ```bash
   cd nodejs
   npm install
   ```
3. Run the application:
   ```bash
   npm start
   ```

### NestJS

1. **Install NestJS CLI**:
   ```bash
   npm install -g @nestjs/cli
   ```
2. Navigate to the `nestjs` folder and install dependencies:
   ```bash
   cd nestjs
   npm install
   ```
3. Start the NestJS application:
   ```bash
   npm run start
   ```

### Laravel

1. **Install PHP** (version 7.4+ is recommended) and **Composer**.
2. Navigate to the `laravel` folder and install dependencies:
   ```bash
   cd laravel
   composer install
   ```
3. Configure the `.env` file and generate an application key:
   ```bash
   cp .env.example .env
   php artisan key:generate
   ```
4. Run the Laravel development server:
   ```bash
   php artisan serve
   ```

### Django

1. **Install Python** (version 3.8+ recommended) and **pip**.
2. Navigate to the `django` folder and install dependencies:
   ```bash
   cd django
   pip install -r requirements.txt
   ```
3. Run migrations and start the Django development server:
   ```bash
   python manage.py migrate
   python manage.py runserver
   ```

## 🤝 Contributing

Feel free to contribute by submitting issues or pull requests!

## 📄 License

This project is licensed under the MIT License.
