# 🌍 Wanderlust — Travel Listing Web Application

Wanderlust is a full-stack travel listing platform that allows users to explore, share, and review travel destinations from around the world. Built with **Node.js**, **Express.js**, **MongoDB**, and **EJS**, this application follows the **MVC architecture** to ensure scalable and maintainable code.

It provides a seamless user experience with robust **authentication**, **CRUD functionality**, **image uploads via Cloudinary**, and **interactive maps powered by Mapbox**.

## ✨ Features

- 🧭 **Travel Listings**: Users can add, edit, and delete destination listings with descriptions, images, and location data.
- 🔐 **User Authentication**: Secure login, logout, and session management using **Passport.js**.
- 📝 **Reviews**: Users can add and delete reviews for each listing.
- ⚙️ **Account Management**: Users can update their profile information and reset/change passwords.
- 🔒 **Security**: Passwords are securely hashed and stored using encryption techniques.
- 🗺️ **Interactive Maps**: Each listing includes a dynamic map location using **Mapbox**.
- ✅ **Validations**: Both client-side and server-side form validations ensure data integrity.

---

## 🚀 Wanderlust Web Project Installation Guide

This guide will walk you through the installation process for the Wanderlust web project. Follow the steps below to set up the project locally on your machine.

### ✅ Prerequisites

Before you begin, make sure you have the following installed on your system:

- **Node.js** (version 18 recommended)
- **MongoDB**
- **Nodemon** (installed globally)

Install Nodemon globally if not already done:
```bash
npm install -g nodemon
```

---

### 🛠️ Installation Steps

1. **Clone the Wanderlust repository from GitHub:**

   ```bash
   git clone https://github.com/gawandeabhishek/Wanderlust-Major-Project.git
   cd Wanderlust-Major-Project
   ```

2. **Set up the database:**
   - Create a `.env` file in the root directory of the project.
   - Add the following line to the `.env` file:

     ```env
     ATLASDB_URL=mongodb://127.0.0.1:27017/wanderlust
     ```

3. **Set up Cloudinary:**
   - Go to [Cloudinary](https://cloudinary.com/) and sign up for a free account.
   - Once logged in, obtain your Cloudinary credentials:
     - `CLOUD_NAME`
     - `CLOUD_API_KEY`
     - `CLOUD_API_SECRET`
   - Add these to your `.env` file:

     ```env
     CLOUD_NAME=your_cloud_name
     CLOUD_API_KEY=your_api_key
     CLOUD_API_SECRET=your_api_secret
     ```

4. **Set the secret for your Cloudinary storage:**
   - Add a `SECRET` key to your `.env` file and set it to a secure value:

     ```env
     SECRET=your_cloudinary_secret
     ```

5. **Install project dependencies using npm:**

   ```bash
   npm install
   ```

6. **Run the application using Nodemon:**

   ```bash
   nodemon app.js
   ```

7. **Access the project:**
   - Once the server is running, go to [http://localhost:8080](http://localhost:8080) in your browser.

---

## 🙋 Support

If you encounter any issues during the installation process, feel free to open an issue or contact the project maintainer.

Happy traveling! 🌍✈️
