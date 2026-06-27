# WanderLust

WanderLust is a full-stack web application inspired by Airbnb where users can browse, create, edit, and review property listings. The project was built to gain hands-on experience with backend development, authentication, databases, and RESTful web applications using the MERN ecosystem (without React).

# Features

* User registration and login
* Authentication using Passport.js
* Create, edit, and delete listings
* Upload listing images with Cloudinary
* Add and delete reviews
* Authorization for listings and reviews
* Flash messages for better user experience
* Responsive UI using Bootstrap

# Tech Stack

**Frontend**

* HTML
* CSS
* Bootstrap
* EJS

**Backend**

* Node.js
* Express.js

**Database**

* MongoDB
* Mongoose

**Authentication & Other Tools**

* Passport.js
* Express Session
* Cloudinary
* Multer
* Joi
* Connect Flash

## Installation

Clone the repository:

```bash
git clone https://github.com/EklavyaSharma14/WanderLust.git
```

Install dependencies:

```bash
npm install
```

Create a `.env` file and add the required environment variables for MongoDB, Cloudinary, and session configuration.

Start the server:

```bash
node app.js
```

The application runs on:

```
http://localhost:8080
```

## Project Structure

```
WanderLust
├── controllers
├── models
├── public
├── routes
├── utils
├── views
├── app.js
├── middleware.js
├── schema.js
└── package.json
```

## Future Improvements

* Search and filter listings
* Interactive maps
* Wishlist feature
* Booking functionality
* User profiles
* Payment integration

## Author

**Eklavya Sharma**
