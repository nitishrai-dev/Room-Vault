# Room Vault

Room Vault is a full-stack web application that allows users to list rooms/spaces, discover nearby locations on an interactive map, upload images, book listings, and manage user authentication and profiles.

---

## 🚀 Features

✔ User registration and login with secure session management  
✔ Location-based room discovery with interactive Mapbox map  
✔ Geospatial search using MongoDB coordinates  
✔ Image upload and management via Cloudinary  
✔ Room listing creation, viewing, and search  
✔ Flash messages for validation feedback and UX  
✔ Session persistence with connect-Mongo

---

## 🛠 Tech Stack

**Frontend / UI**  
- EJS (Embedded JavaScript Templates)

**Backend**  
- Node.js  
- Express.js  
- Passport.js (Authentication)

**Database**  
- MongoDB (Mongoose ODM)
- Location storage with geospatial indexing

**Cloud Services**  
- Cloudinary for image uploads
- Mapbox SDK for geolocation and map rendering

---

## 🚀 Installation

Make sure you have **Node.js** and **MongoDB** installed.

1. Clone the repository  
   ```bash
   git clone https://github.com/nitishrai-dev/Room-Vault.git
   cd Room-Vault


# Install dependencies
npm install

# Start 
npm start


# Project Structure
├── routes/              # Express route handlers
├── controllers/         # Business logic
├── models/              # MongoDB models
├── views/               # EJS templates
├── public/              # Static assets
├── uploads/             # Uploaded files
├── utils/               # Helper utilities
├── app.js               # Application entry point
├── middleware.js        # Custom middleware
└── cloudConfig.js       # Cloudinary/Mapbox config
