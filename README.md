# 🔗 MERN URL Shortener

A full-stack URL Shortener built using the MERN stack that converts long URLs into short, shareable links. The application also generates QR codes for every shortened URL, allowing users to quickly access links from any device.

## 🌐 Live Demo

**Frontend:**  
https://mern-url-shortener-eta.vercel.app

**Backend API:**  
https://akshay-url-shortener-api.onrender.com

---

## ✨ Features

- 🔗 Shorten any valid URL
- 🚀 Instant redirection using short links
- 📱 QR Code generation for each shortened URL
- 📥 Download QR Code
- 📋 One-click copy to clipboard
- 🌍 Accessible from any device
- 💾 Stores URLs in MongoDB
- ⚡ Responsive and clean UI

---

## 🛠️ Tech Stack

### Frontend
- React.js
- Vite
- Axios
- QRCode Library

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- NanoID

### Deployment
- Frontend: Vercel
- Backend: Render
- Database: MongoDB Atlas

---

## 📂 Project Structure

```
mern-url-shortener/
│
├── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── backend/
│   ├── models/
│   ├── routes/
│   ├── server.js
│   └── package.json
│
└── README.md
```

---

## ⚙️ Installation

### Clone the repository

```bash
git clone https://github.com/Akshay05191/mern-url-shortener.git
```

```bash
cd mern-url-shortener
```

---

### Backend Setup

```bash
cd backend
npm install
```

Create a `.env` file inside the backend folder.

```env
MONGO_URI=your_mongodb_connection_string
BASE_URL=http://localhost:5000
FRONTEND_URL=http://localhost:5173
```

Start the backend server

```bash
npm start
```

---

### Frontend Setup

```bash
cd frontend
npm install
```

Create a `.env` file inside the frontend folder.

```env
VITE_API_URL=http://localhost:5000
```

Run the frontend

```bash
npm run dev
```

---

## 📖 Usage

1. Open the application.
2. Paste any valid URL.
3. Click **Shorten**.
4. Copy the generated short URL.
5. Scan or download the generated QR code.
6. Share the shortened link with anyone.

---

## 📸 Screenshots

### Home Page

> Add a screenshot here

### Generated Short URL

> Add a screenshot here

### QR Code

> Add a screenshot here

---

## 🚀 Future Improvements

- 👤 User Authentication
- 📊 Click Analytics
- 📅 Link Expiration
- 📝 URL History
- 🔍 Custom Short URLs
- 🌙 Dark Mode
- 📱 Progressive Web App (PWA)

---

## 👨‍💻 Author

**Akshay S**

GitHub:  
https://github.com/Akshay05191

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub!
