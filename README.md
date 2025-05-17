# 📬 Quick Chat

A real-time chat application built with the MERN stack and Socket.IO. Users can sign up, browse a sidebar of other users, and start chatting instantly. Media files and user info are accessible in a neat right sidebar.

---

## 🚀 Features

* 🔥 Real-time one-on-one chat using Socket.IO
* 🧍 User authentication and account creation
* 📑 Sidebar with searchable list of users
* 💬 Chat container that opens on user click
* 🖼 Right sidebar shows media files, display picture, and bio
* ☁️ Cloudinary integration for storing media files

---

## 🛠 Tech Stack

* **Frontend:** React (Vite) + Tailwind CSS
* **Backend:** Node.js, Express.js
* **Database:** MongoDB
* **Real-Time:** Socket.IO
* **Media Storage:** Cloudinary

---

## ⚙️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/Venkataramana-hegde/chat-app.git
cd chat-app
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Environment Variables

Create two `.env` files:

#### 🔧 For Backend (`/server/.env`):

```
MONGODB_URI=your_mongo_uri
NODE_ENV=development
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
```

#### 🌐 For Frontend (`/client/.env`):

```
VITE_BACKEND_URL=https://your-backend-url.vercel.app
```

### 4. Start the App

If you're running locally:

```bash
cd server && npm run server
cd client && npm run dev
```

---

## 🌍 Deployment

Both frontend and backend are deployed on **Vercel**.

---

## 📸 Screenshots

![Screenshot from 2025-05-17 21-27-12](https://github.com/user-attachments/assets/b00ff225-392a-4e98-8e56-9ad0c839725b)

![Screenshot from 2025-05-17 21-27-36](https://github.com/user-attachments/assets/83239e90-e7c1-4014-87cd-126ab99893c6)

![Screenshot from 2025-05-17 21-35-31](https://github.com/user-attachments/assets/b92d2420-fbce-4277-a131-05388b7ff8cb)






