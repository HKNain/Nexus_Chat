# Nexus Chat

Nexus Chat is a real-time chat application built using the **MERN** stack, featuring **Socket.IO** for instant messaging and **DaisyUI** for a beautiful, responsive user interface.

## 🚀 Features

- 🔥 **Real-time messaging** with Socket.IO
- 👥 **User authentication** (Login/Register)
- 📜 **Chat rooms & direct messages**
- 🎨 **Modern UI with DaisyUI & TailwindCSS**
- 📡 **WebSocket-based communication**
- 🛡️ **Secure authentication with JWT**
- 🌍 **Responsive and mobile-friendly design**

## 🛠️ Tech Stack

- **Frontend**: React, TailwindCSS, DaisyUI
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (Mongoose)
- **Real-time Communication**: Socket.IO
- **Authentication**: JWT & bcrypt

## 📦 Installation

1. **Clone the repository**

   ```sh
   git clone https://github.com/your-username/nexus-chat.git
   cd nexus-chat
   ```

2. **Install dependencies**

   ```sh
   # Backend
   cd server
   npm install

   # Frontend
   cd ../client
   npm install
   ```

3. **Set up environment variables**
   Create a `.env` file in the `server` directory and add:

   ```env
   PORT=5000
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   ```

4. **Run the application**

   ```sh
   # Start the backend
   cd server
   npm start

   # Start the frontend
   cd ../client
   npm start
   ```

5. **Access Nexus Chat**
   Open `http://localhost:3000` in your browser.

## 🔧 API Endpoints

| Method | Endpoint             | Description       |
| ------ | -------------------- | ----------------- |
| POST   | `/api/auth/register` | User Registration |
| POST   | `/api/auth/login`    | User Login        |
| GET    | `/api/chats`         | Fetch User Chats  |
| POST   | `/api/messages`      | Send a Message    |

## 🤝 Contributing

Feel free to fork this repository and submit pull requests. Suggestions and improvements are always welcome!

---

💬 **Nexus Chat - Where Conversations Come to Life!**

