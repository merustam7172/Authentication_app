
# Authentication App 🔒

A **full-stack authentication app** built with **MongoDB**, **Express.js**, **React.js**, and **Node.js** (MERN Stack). This app provides secure user authentication with Login, Signup, and Google OAuth functionality.

## 🚀 Features

- **User Authentication** - Secure Login and Signup functionality
- **Google OAuth** - Seamless authentication using Google credentials
- **Secure Tokens** - JWT implementation for robust security
- **Database Integration** - MongoDB for efficient user data storage

## 🛠️ Technologies Used

| Frontend    | Backend     | Database | Authentication    |
|------------|-------------|----------|-------------------|
| React.js ⚛️ | Node.js 🟩 | MongoDB 🍃 | JWT & Google OAuth 🔐 |

## 📋 Prerequisites

Before you begin, ensure you have:
- [Node.js](https://nodejs.org/) installed
- [MongoDB](https://www.mongodb.com/) connection URL
- [Google Cloud Console](https://console.cloud.google.com/) OAuth credentials

## 🚀 Installation

### Clone the Repository

```bash
git clone https://github.com/<your-username>/authentication-app.git
cd authentication-app
```

### Frontend Setup (React.js)

1. Navigate to the client directory:
```bash
cd client
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

### Backend Setup (Node.js + Express.js)

1. Navigate to the backend directory:
```bash
cd backend
```

2. Install dependencies:
```bash
npm install
```

3. Create `.env` file in the root directory:
```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
GOOGLE_CLIENT_ID=your_google_client_id
GOOGLE_CLIENT_SECRET=your_google_client_secret
```

4. Start the server:
```bash
npm run dev
```

## 🌐 Running the Application

1. Start the frontend (from client directory):
```bash
npm run dev
```

2. Start the backend (from backend directory):
```bash
npm run dev
```

### Access the Application:
- Frontend: [http://localhost:5173](http://localhost:5173)
- Backend: [http://localhost:5000](http://localhost:5000)

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## ⭐️ Show your support

Give a ⭐️ if this project helped you!

---

<p align="center">Made with ❤️ by <a href="https://github.com/<merustam7172>">Your Name</a></p>
