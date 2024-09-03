# Wanderlust
Wanderlust is a web application designed to serve as a rental home platform, similar to Airbnb. Users can sign up, list their properties, and review other listings.
The project is built using Node.js, Express.js, MongoDB, and Bootstrap, following the MVC architecture.

## Features
* **User Authentication**: Users can sign up and log in to manage their properties and reviews.
* **Property Listings**: Users can list their rental properties with details like price, description, and images.
* **Reviews**: Users can add and view reviews for listed properties.
* **Responsive Design**: The app is fully responsive, providing a seamless experience across all devices.

## Technologies Used
* **Frontend**: HTML, CSS, EJS, Bootstrap
* **Backend**: Node.js, Express.js
* **Database**: MongoDB
* **Additional Libraries**:
  
  * **EJS Mate**: For layout management and partials in EJS.
  * **Cloudinary**: For image storage and management.
  * **Passport.js**: For user authentication with Local Strategy.
  * **Mongoose**: For MongoDB object modeling.
  * **Express-Session**: For managing user sessions.

## Project Structure
* **app.js**: Main application file.
* **routes/**: Contains route files for handling various endpoints.
* **models/**: Database schemas for users, properties, and reviews.
* **views/**: EJS templates for rendering the UI, using EJS Mate for layout management.
* **public/**: Static files like CSS, images, and JavaScript.
* **middlewares.js**: Custom middleware for handling user authentication and other features.
