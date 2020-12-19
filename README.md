#TODOLIST

## Repositories
- Api 
```bash
https://github.com/rafatga/todo-list-api
```
- App 
```bash
https://github.com/rafatga/todo-list-app.git
```

## Installation
```bash
git clone --recurse-submodules -j8 https://github.com/rafatga/todo-list-nuxt-laravel.git
```

## API Installation
```bash
# install dependencies
$ composer install

# Copy .env.example and name it .env
$ cp .env.example .env

# Add database configuration
$ DB_DATABASE=todo-api
$ DB_USERNAME=root
$ DB_PASSWORD=root

# Define api url
$ APP_URL=http://todo-list-api.loc

# Create tables and data
$ php artisan migrate:fresh --seed
```

## APP Installation
```bash
# install dependencies
$ npm install

# (IMPORTANT) add APP_URL to nuxt.config.js
env: {
    baseUrl: 'http://todo-list-api.loc/api/v1'
}

# serve with hot reload at localhost:3000
$ npm run dev
```

## 
![task-list](./screenshots/task-list.png?raw=true "task list")
![task-list-responsive](./screenshots/task-list-responsive.png?raw=true "task list responsive")
![task-create](./screenshots/task-create.png?raw=true "task create")
![task-edit](./screenshots/task-edit.png?raw=true "task edit")
![task-delete](./screenshots/task-delete.png?raw=true "task delete")


