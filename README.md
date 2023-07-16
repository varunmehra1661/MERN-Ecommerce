# MERN eCommerce Platform

> eCommerce platform built with the MERN stack & Redux.

## Features

- Full featured shopping cart
- Product reviews and ratings
- Product pagination
- User profile with orders
- Checkout process (shipping, payment method, etc)
- Admin user management
- Admin product management
- Admin Order details page
- Mark orders as paid and delivered option (admin)
- Database seeder (products & users)
- Top products carousel
- Product search feature

## Usage

### Env Variables

Create a .env file in then root and add the following

```
NODE_ENV = development
PORT = 5000
MONGO_URI = your mongodb uri
JWT_SECRET = 'abc123'
```

### Install Dependencies (frontend & backend)

```
npm install
cd frontend
npm install
```

### Run

```
# Run frontend (:3000) & backend (:5000)
npm run dev

# Run backend only
npm run server
```

### Seed Database

You can use the following commands to seed the database with some sample users and products as well as destroy all data

```
# Import data
npm run data:import

# Destroy data
npm run data:destroy
```

```
Sample User Logins

admin@example.com (Admin)
123456

john@example.com (Customer)
123456

jane@example.com (Customer)
123456
```

## Screenshots

- Home Screen

  ![HomeScreen](https://i.imgur.com/UnluhBX.png)

- Product Screen

  ![Product Screen](https://i.imgur.com/rztBxmD.png)

- Cart Screen

  ![Cart Screen](https://i.imgur.com/r1l4e7p.png)

- Register Screen

  ![Register Screen](https://i.imgur.com/G7AoTWl.png)

- User Profile Screen

  ![User Profile Screen](https://i.imgur.com/RjHMD0U.png)

- Order Screen

  ![Order Screen](https://i.imgur.com/0NwMfhU.png)

- Admin Users Screen

  ![Admin Users Screen](https://i.imgur.com/qPoHlFp.png)

- Admin Orders Screen

  ![Admin Orders Screen](https://i.imgur.com/D0TCAhX.png)

- Admin Products Screen

  ![Admin Products Screen](https://i.imgur.com/ISlHdBg.png)
# MERN-Ecommerce
