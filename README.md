# MERN Chat App

A real-time chat application built using the MERN stack with Socket.io for real-time communication and styled with Tailwind CSS and Daisy UI.

## 🚀 Features
- **Real-Time Messaging** with Socket.io.
- **Responsive UI** with Tailwind CSS and Daisy UI.
- **MongoDB for Data Persistence**.

## 🛠️ Tech Stack
- **Frontend:** React.js, Tailwind CSS, Daisy UI
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Real-Time Communication:** Socket.io

---

## 🏗️ Setup Instructions

### Prerequisites
Ensure you have the following installed:
- **Node.js** (v14+)
- **MongoDB** (Local or Cloud)

---

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/mern-chat-app.git
   cd mern-chat-app
2. **Configuration**
   
   Create a .env file in the server directory with the following variables
   ```bash
   MONGODB_URI=...
   PORT=5001
   JWT_SECRET=...

   CLOUDINARY_CLOUD_NAME=...
   CLOUDINARY_API_KEY=...
   CLOUDINARY_API_SECRET=...

   NODE_ENV=development
   ```
3. **Bulid and Start the App**

   Frontend:
   ```bash
   cd client
   npm install
   npm start
   ```
   Backend:
   ```bash
   cd ../server
   npm install
   npm start
   ```

