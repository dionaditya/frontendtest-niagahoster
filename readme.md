# Niagahoster Front End Dev Test

Hi! I'm Dion Aditya. This is my assignment for front end developer position at Niagahoster.co.id

# Stack

 - Laravel (Backend Rest API)
 - MongoDB (Database)
 - Vue JS + Tailwind (Frontend)

## Preview Apps

![Preview Apps](./assets/preview/preview.gif)

![Preview Apps](./assets/preview/screenshot-light.png)

![Preview Apps](./assets/preview/screenshot-dark.png)


## Installation

### Requirement
- Node JS 
- Yarn or NPM
- PHP
- Composer
- MongoDB


## Backend


```bash
git clone git@github.com:dionaditya/frontendtest-niagahoster
cd backend
composer install
mv .env.example .env
mongoimport --db niagahoster --collection package --drop --file /home/user/frontendtest-niagahoster/backend/data.json
php artisan serve
```
Server listening on port 8000


## Frontend

```bash
git clone git@github.com:dionaditya/frontendtest-niagahoster
cd frontend 
yarn or npm install
yarn serve
``` 

Now you can access the frontend apps in port 8080

## Troubleshooting

```
    If you have problem with this project you can contact me via email at dionjatingaleh@gmail.com. I can respond you ASAP.
```