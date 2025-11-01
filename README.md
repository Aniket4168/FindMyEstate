# FindMyEstate 🏠

Welcome to FindMyEstate, a full-stack property listing website developed as our final year project. This application is built using the MERN (MongoDB, Express.js, React.js, Node.js) stack and provides a modern, user-friendly platform for real estate.

## Project Team

This project was developed by:

* **Paras Mani Paterya**
* **Aniket Agrawal**
* **Amit Kumar Shivhare**

We are final year Information Technology & Computer Engineering students from the **Institute of Engineering and Technology (IET), DAVV, Indore**.

---

## Overview

FindMyEstate is a comprehensive web application designed to bridge the gap between property owners, buyers, and renters. It serves as a centralized platform where users can browse a wide array of property listings, filter them based on specific criteria, and get detailed information. Property owners can also register to create, manage, and update their own listings.

The project's goal is to demonstrate a practical, real-world application of MERN stack technologies, focusing on creating a secure, scalable, and responsive application.

---

## Key Features

* **User Authentication:** Secure user registration and login system using JSON Web Tokens (JWT) for session management and password encryption using `bcrypt.js`.
* **Property Listings (CRUD):** Full Create, Read, Update, and Delete functionality for property listings.
* **Dynamic Search & Filtering:** Allows users to search for properties and filter them based on key parameters such as location, price range, property type (e.g., Sale, Rent), and number of bedrooms/bathrooms.
* **Image Uploads:** Functionality for users to upload multiple images for their property listings.
* **User Dashboard:** A personalized dashboard where registered users can view and manage their own property listings.
* **Responsive UI:** The application is built with a mobile-first, responsive design to ensure a seamless experience across all devices, from desktops to mobile phones.
* **RESTful API:** A robust backend API built with Express.js and Node.js to handle all business logic and data manipulation.

---

## 🛠️ Technology Stack

This project is built using the MERN stack and other key technologies:

* **Frontend:**
    * **React.js:** A JavaScript library for building dynamic user interfaces.
    * **React Router:** Used for client-side routing and navigation within the single-page application.
    * **Axios:** A promise-based HTTP client for making API requests to the backend.
    * **(Add your styling method):** e.g., CSS Modules, Sass, Styled-Components, or Tailwind CSS.

* **Backend:**
    * **Node.js:** A JavaScript runtime environment for executing the server-side code.
    * **Express.js:** A minimal and flexible Node.js web application framework used to build the RESTful API.
    * **Mongoose:** An Object Data Modeling (ODM) library for MongoDB, used to manage relationships between data and provide schema validation.
    * **jsonwebtoken (JWT):** For generating and verifying access tokens for user authentication.
    * **bcrypt.js:** For securely hashing user passwords before storing them in the database.

* **Database:**
    * **MongoDB:** A NoSQL, document-based database used for storing all application data (e.g., users, listings). We utilized **MongoDB Atlas** for cloud-based database hosting.

---

## 🚀 Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing.

### Prerequisites

* [Node.js](https://nodejs.org/en/) (v16 or later recommended)
* [npm](https://www.npmjs.com/) (Node Package Manager)
* [MongoDB](https://www.mongodb.com/) (A local instance or a cloud-based MongoDB Atlas account)

### Installation Guide

1.  **Clone the repository:**
    ```sh
    git clone [https://github.com/your-username/FindMyEstate.git](https://github.com/your-username/FindMyEstate.git)
    cd FindMyEstate
    ```

2.  **Set up the Backend (Server):**
    ```sh
    # Navigate to the server directory
    cd server

    # Install backend dependencies
    npm install

    # Create a .env file in the /server directory
    touch .env
    ```
    You will need to add the following environment variables to your `.env` file:
    ```
    # Your MongoDB connection string (local or from Atlas)
    MONGO_URI=your_mongodb_connection_string

    # A secret key for signing JWT tokens
    JWT_SECRET=your_secret_key_for_jwt

    # The port for the server to run on
    PORT=8000
    ```
    ```sh
    # Run the backend server
    npm start
    ```
    The server will start on `http://localhost:8000` (or your specified PORT).

3.  **Set up the Frontend (Client):**
    ```sh
    # Open a new terminal and navigate to the client directory
    cd client

    # Install frontend dependencies
    npm install

    # Run the client
    npm start
    ```
    The React development server will start on `http://localhost:3000`.

4.  Open [http://localhost:3000](http://localhost:3000) in your browser to view the application. The frontend will proxy API requests to the backend server.

---

## 📄 License

This project is licensed under the MIT License. See the `LICENSE` file for more details.
