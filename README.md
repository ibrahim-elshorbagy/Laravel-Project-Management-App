# Project-Management-App

Project-Management-App is a web application built with Laravel and Inertia.js, providing a simple and easy-to-use project management system. This application is intended to be a simple and easy-to-use application for managing projects, tasks, and users.


## Features

- Projects
  - Create, Update, and Delete projects
  - View project details
  - Assign tasks to projects
  - Filter projects by status (pending, in progress, complete)

- Tasks
  - Create, Update, and Delete tasks
  - View task details
  - Assign tasks to users
  - Filter tasks by status (pending, in progress, complete)

- Users
  - Create, Update, and Delete users
  - Assign tasks to users


## Installation

### Installation

1. Clone the repository
2. Copy `.env.example` to `.env`
3. Run `composer install` to install dependencies
4. Generate a new application key with `php artisan key:generate`
5. Set up your database credentials in the `.env` file
6. Run `php artisan migrate` to create the database tables
7. Run `php artisan db:seed` to seed the database with some dummy data
8. Run `npm install` to install the frontend dependencies
9. Run `npm run dev` or `npm run watch` to compile the frontend assets
10. Start the development server with `php artisan serve`

Now you should be able to visit `http://localhost:8000` and see the project management app in action.



