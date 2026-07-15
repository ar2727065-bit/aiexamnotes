# 📚 AI Exam Notes

An AI-powered exam preparation platform that helps students generate, organize, and study high-quality notes. The application leverages AI to simplify learning, create structured study material, and improve exam preparation through an intuitive and modern interface.

---

## ✨ Features

* 🤖 AI-generated study notes
* 📝 Create and manage notes
* 📚 Subject-wise organization
* 📊 Interactive charts and analytics
* 📄 Export notes as PDF
* 🔐 Secure authentication with Firebase
* 💳 Stripe payment integration
* 📱 Fully responsive design
* ⚡ Fast and modern UI powered by React + Vite

---

## 🛠 Tech Stack

### Frontend

* React 19
* Vite
* React Router DOM
* Redux Toolkit
* Tailwind CSS v4
* Axios
* React Markdown
* Mermaid (Diagram Rendering)
* Motion (Animations)
* Recharts
* React Icons

### Backend

* Node.js
* Express.js
* MongoDB
* Mongoose
* JWT Authentication
* Cookie Parser
* CORS
* Dotenv
* PDFKit
* Stripe API

### Database

* MongoDB Atlas

### Authentication

* Firebase Authentication
* JSON Web Tokens (JWT)

---

## 📂 Project Structure

```
AIExamNotes/
│
├── client/
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── vite.config.js
│
├── server/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── index.js
│   └── package.json
│
└── README.md
```

---

## 🚀 Installation

### Clone the Repository

```bash
git clone https://github.com/ar2727065-bit/aiexamnotes.git

cd aiexamnotes
```

---

## Install Dependencies

### Client

```bash
cd client
npm install
```

### Server

```bash
cd ../server
npm install
```

---

## Environment Variables

Create a `.env` file inside the **server** directory.

```env
PORT=5000

MONGODB_URI=your_mongodb_connection_string

JWT_SECRET=your_jwt_secret

STRIPE_SECRET_KEY=your_stripe_secret_key

CLIENT_URL=http://localhost:5173
```

If Firebase configuration is required, create a `.env` file inside the **client** directory.

```env
VITE_FIREBASE_API_KEY=

VITE_FIREBASE_AUTH_DOMAIN=

VITE_FIREBASE_PROJECT_ID=

VITE_FIREBASE_STORAGE_BUCKET=

VITE_FIREBASE_MESSAGING_SENDER_ID=

VITE_FIREBASE_APP_ID=
```

---

## ▶️ Running the Project

### Start Backend

```bash
cd server
npm run dev
```

### Start Frontend

```bash
cd client
npm run dev
```

Open your browser and visit:

```
http://localhost:5173
```

---

## 📦 Available Scripts

### Client

```bash
npm run dev
npm run build
npm run preview
npm run lint
```

### Server

```bash
npm run dev
```

---

## 🔥 Key Technologies

* React 19
* Vite
* Express.js
* MongoDB
* Firebase Authentication
* Redux Toolkit
* JWT
* Stripe
* Tailwind CSS
* PDFKit

---

## 🎯 Future Improvements

* AI Quiz Generation
* Flashcards
* Smart Revision Planner
* Voice Notes
* Dark Mode
* Collaborative Notes
* Study Progress Tracking
* AI Chat Assistant
* Offline Support
* Mobile Application

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository.
2. Create a feature branch.
3. Commit your changes.
4. Push your branch.
5. Open a Pull Request.

---


---

## 👨‍💻 Author

**Abhay Verma**

If you found this project helpful, consider giving it a ⭐ on GitHub.
