<p align="center">
  <img src="client/src/assets/logo.png" alt="Leyo Logo" width="120"/>
</p>

<h1 align="center">Leyo Full Stack Ecommerce</h1>

<p align="center">
  <b>Modern, scalable, and feature-rich ecommerce platform built with React, Node.js, Express, and MongoDB.</b><br/>
  <i>Premium UI, robust admin panel, secure authentication, and seamless deployment.</i>
</p>

---

## 🚀 Features

- User Authentication (Register, Login, OTP, JWT, Password Reset)
- Product, Category & Subcategory Management (Admin & User)
- Cart & Checkout (Stripe Integration)
- Order Management (User & Admin)
- Address Book (Multiple Addresses)
- Profile Management (Edit, Avatar Upload)
- Admin Dashboard (Users, Products, Orders, Categories)
- Mobile Responsive Design
- Image Uploads (Cloudinary)
- Email Notifications (Registration, Orders, Password Reset)
- Secure, Scalable, and Production Ready

---

## 🏗️ Tech Stack

| Frontend                | Backend                | Database   | Cloud & Tools      |
|-------------------------|------------------------|------------|--------------------|
| React (Vite)            | Node.js, Express.js    | MongoDB    | Cloudinary         |
| Tailwind CSS            | JWT Auth, Stripe API   |            | Vercel/Render      |
| Redux Toolkit           | Nodemailer/Resend      |            | GitHub Actions     |

---

## 📦 Project Structure

```
Leyo-Full-Stack-Ecommerce/
  ├── client/         # React frontend (Vite)
  ├── server/         # Node.js backend (Express)
  ├── .gitignore
  ├── readme.md
  └── ...             # Demo GIFs, thumbnails, etc.
```

---

## ⚡️ Quick Start

### 1. Clone the Repository
```bash
git clone https://github.com/NarenderSD/leyo-full-stack-ecommerce.git
cd leyo-full-stack-ecommerce
```

### 2. Setup Environment Variables
- Create `.env` files in both `client/` and `server/` directories as per your environment.
- **Never commit your `.env` files to GitHub!**

### 3. Install Dependencies

**Frontend:**
```bash
cd client
npm install
```

**Backend:**
```bash
cd ../server
npm install
```

### 4. Run Locally

**Start Backend:**
```bash
cd server
npm run dev
```

**Start Frontend:**
```bash
cd ../client
npm run dev
```

- Frontend: [http://localhost:5173](http://localhost:5173)
- Backend: [http://localhost:8080](http://localhost:8080)

---

## 🌐 Deployment

- **Frontend:** Deploy on [Vercel](https://vercel.com/) or [Netlify](https://netlify.com/)
- **Backend:** Deploy on [Render](https://render.com/), [Railway](https://railway.app/), or [Vercel Serverless](https://vercel.com/)
- **Environment Variables:** Set all secrets (DB URI, JWT, Stripe, Cloudinary, etc.) in the deployment dashboard.

---

## 📸 Demo

![Demo 1](Demo%201.gif)
![Demo 2](Demo%202.gif)

---

## 🛡️ Security & Best Practices

- All sensitive data is managed via environment variables
- Passwords are hashed and never stored in plain text
- JWT-based authentication for secure sessions
- Input validation and error handling throughout

---

## 🙋‍♂️ Author

**Narender Singh**  
[LinkedIn](https://www.linkedin.com/in/narendersingh1/) | [Portfolio](https://www.linkedin.com/in/narendersingh1/)

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

---

## 📄 License

This project is licensed under the MIT License.

---

> <p align="center"><b>Premium Quality | Modern UI | Production Ready | Scalable Architecture</b></p> 