# Airbnb Hotel Booking Website

The **Airbnb Hotel Booking Website** is an online platform designed to simulate the features and functionalities of the popular Airbnb service. The project aims to offer users the ability to search, view, and book hotel rooms, providing a seamless booking experience with user-friendly features. The website is built with modern technologies like **Node.js**, **Express**, and **MongoDB** for the backend, and **EJS** for templating, making it both dynamic and interactive.

The website includes both user and admin functionalities. Users can search for hotels, check availability, and book rooms, while administrators can manage hotel listings, update room availability, and handle bookings. The project leverages **Passport.js** for secure user authentication and **Cloudinary** for storing and displaying hotel images.

## Features

- **User Authentication**: Secure login and signup functionality.
- **Hotel Listings**: Browse a variety of hotels with images, descriptions, and pricing.
- **Search and Filter**: Find hotels based on location, price, and amenities.
- **Booking System**: Users can book rooms after signing in.
- **Admin Panel**: Admins can manage hotel listings and bookings.

## Technologies Used

- **Backend**: Node.js, Express
- **Frontend**: EJS (Embedded JavaScript Templating)
- **Database**: MongoDB with Mongoose
- **Authentication**: Passport.js
- **File Storage**: Cloudinary (for hotel images)
- **Sessions**: Express-session for session management
- **Form Validation**: Joi

## Setup Instructions

1. **Clone the Repository**

   Clone this repository to your local machine:

 git clone https://github.com/NeetuShaw/Major-Project.git
 
2. **Install Dependencies**

Navigate to the project directory and install the required dependencies:

cd Major-Project
npm install

3. **Create a .env File**
Create a .env file in the root directory with the following variables:

MONGO_URI=your_mongodb_connection_uri
CLOUDINARY_URL=your_cloudinary_url
SESSION_SECRET=your_session_secret

4. **Run the Application**

After installing the dependencies and configuring the .env file, start the application:

npm start
This will start the app on http://localhost:3000.

## License
This project is licensed under the MIT License.


### Steps to Add This File to GitHub:
1. Go to your GitHub repository: `https://github.com/NeetuShaw/Major-Project`.
2. Navigate to the folder where you want to add the README file.
3. Click **Add file** → **Create new file**.
4. Paste the above content into the editor.
5. Name the file `README.md`.
6. Commit the file by clicking **Commit new file**.
