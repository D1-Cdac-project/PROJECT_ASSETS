# BookMyMandap Assets Server

The **BookMyMandap Assets Server** is part of the broader Mandap Booking Application developed using the **MERN Stack** (MongoDB, ExpressJS, ReactJS, NodeJS). This module is responsible for handling assets such as images, documents, or static content used across the application. It manages asset uploads, storage, and access control using Cloudinary and serves essential support to the main backend.

---

## 📁 File Structure

```
ASSETS_SERVER/
│
├── config/              # Configuration files for Cloudinary and other services
├── controllers/         # Logic for file upload, download, and access
├── middlewares/         # Middleware for authentication and upload handling
├── models/              # Models related to asset metadata
├── routes/              # API routes for asset management
│
├── .env.example         # Sample environment variables
├── .gitignore           # Git ignored files
├── README.md            # Documentation
├── package.json         # NPM package configuration
├── package-lock.json    # Locked dependency versions
└── server.js            # Entry point of the asset server
```

---

## 🛠️ Tech Stack

- **Server:** Node.js, Express.js  
- **Database:** MongoDB  
- **File Storage:** Cloudinary  
- **Authentication:** JWT  

---

## 🚀 Installation Guide

To set up the **Assets Server** for development on your local machine:

### Step-1: Clone the Repository

```bash
git clone https://github.com/D1-Cdac-project/ASSETS_SERVER.git
cd ASSETS_SERVER
```

### Step-2: Install Dependencies

```bash
npm install
```

### Step-3: Configure Environment Variables

Create a `.env` file by copying `.env.example` and filling in the following:

```env
PORT=4001
MONGODB_CONNECTION=your_mongodb_connection_string
SECRET_KEY=your_secret_key

CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
```

### Step-4: Start the Server

```bash
npm start
```

Once the server is up, you can access it via:

```
http://localhost:4001
```

---

## 📦 Features

- Asset Upload (Images, Documents, etc.)
- Asset Retrieval and Management
- Role-based Access for Upload/Delete
- Secure File Hosting with Cloudinary

---

## 👨‍💻 Contributors

- Developed by the D1 CDAC Team

---

## 📄 License

This project is licensed under the MIT License.
