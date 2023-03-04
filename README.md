# Laravel 10 + Inertia.js + Vue 3 -> single page application
### Used - Laravel Jetstream

The application is designed to provide a smooth and interactive user experience. This SPA offers an all-in-one solution for managing users and roles, featuring an easy-to-use dashboard for administrators.

## Installation

To get started with the installation, follow these steps:

1. Clone the repository
``git clone https://github.com/perisicnikola37/laravel-inertia-vue-spa.git``

2. Enter project directory
``cd laravel-inertia-vue-project``

3. Install/update composer
``composer install | composer update``

4. Install npm
``npm install``

3. Set up the environment variables
``cp .env.example .env``

4. Generate an application key
``php artisan key:generate``

5. Configure the database
``php artisan migrate``

6. Start the development server
``npm run dev``

7. Visit the application at [http://localhost:8000](http://localhost:8000)

## Features

This application includes the following features:

- User authentication and authorization
- CRUD operations for users and roles
- Real-time updates using Inertia.js and Vue.js

## Contributing

If you would like to contribute to this project, please follow these steps:

1. Fork the repository
2. Create a new branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

## License

This project is licensed under the MIT License. See the [LICENSE.md](LICENSE.md) file for details.
