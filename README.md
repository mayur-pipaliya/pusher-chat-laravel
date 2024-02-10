# Laravel Vue 3 SPA - Real-time Chat

This project is a real-time chat application built with Laravel and Vue 3.

## Prerequisites

Before you start, make sure you meet the following requirements:

- [Node.js](https://nodejs.org/) installed
- [Composer](https://getcomposer.org/) installed
- [Laravel](https://laravel.com/) installed
- [Vue CLI](https://cli.vuejs.org/) installed

## Getting Started

Follow these steps to set up and run the application:

1. **Install PHP dependencies:**

    ```bash
    composer install
    ```

2. **Install JavaScript dependencies:**

    ```bash
    npm install
    ```

3. **Create a copy of the `.env` file:**

    ```bash
    cp .env.example .env
    ```

4. **Generate the application key:**

    ```bash
    php artisan key:generate
    ```

5. **Update your `.env` file:**

    - Set the necessary database information.
    - Add Pusher credentials.
    - Set `BROADCAST_DRIVER` to Pusher.

6. **Run database migrations and seeders:**

    ```bash
    php artisan migrate --seed
    ```

## Development

To start the development server, run:

```bash
npm run dev & php artisan serve
```

Now, your Laravel Vue 3 SPA is ready for development. Access it through [http://localhost:8000](http://localhost:8000) and enjoy real-time chat functionality.
