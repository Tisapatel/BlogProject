# 📖 Blog Project

A modern **Blog Application** built with **Node.js, Express, and MongoDB**, featuring authentication, post management, and dynamic rendering using templating.  
This project demonstrates scalable folder structuring, middleware usage, and environment variable configuration for production-ready deployment.

---

## 🚀 Features

- 📝 Create, edit, and delete blog posts  
- 🔐 User authentication (Login/Signup)  
- 📂 Organized MVC architecture  
- ⚡ RESTful APIs  
- 🎨 Dynamic views with EJS  
- 🌍 Environment variables for secure config  
- 📑 Middleware-based request handling  
- 📊 MongoDB for data persistence  

---

## 🛠️ Tech Stack

- **Backend:** Node.js, Express.js  
- **Database:** MongoDB (Mongoose ODM)  
- **Templating Engine:** EJS  
- **Environment Management:** dotenv  
- **Others:** Middleware, Controllers, Routers  

---

## 📂 Project Structure

```bash
BlogProject/
│── .env.example        # Environment variable template
│── configs/            # Database & app configs
│── controller/         # Controllers for handling logic
│── index.js            # Main entry point
│── middlewares/        # Custom middlewares
│── models/             # Database schemas
│── node_modules/       # Dependencies
│── package.json        # Project metadata
│── public/             # Static assets (CSS, JS, Images)
│── routers/            # Route definitions
│── views/              # EJS templates
```

---

## ⚙️ Installation

### 1️⃣ Clone the repository
```bash
git clone https://github.com/Tisapatel/BlogProject
cd BlogProject
```

### 2️⃣ Install dependencies
```bash
npm install
```

### 3️⃣ Setup environment variables
- Rename `.env.example` to `.env`
- Add your MongoDB URI and other required keys

Example:
```env
MONGODB_URI="mongodb+srv://tisapatel1204:12345@cluster0.iqhac3d.mongodb.net/BlogProject"
PORT = 3003
```

### 4️⃣ Run the project
```bash
npm start
```

---

## 🧪 Scripts

- `npm start` → Run the project  
- `npm run dev` → Run in development mode (nodemon)  

---

## 📸 Screenshots
 
Example:  
![screenshot0.1](public/images/ss0.1.png)
![screenshot0.2](public/images/ss0.2.png)
![screenshot1](public/images/ss1.png)
![screenshot2](public/images/ss2.png)
![screenshot3](public/images/ss3.png)
![screenshot4](public/images/ss4.png)



---

## 🤝 Contributing

1. Fork this repository  
2. Create your feature branch (`git checkout -b feature-name`)  
3. Commit your changes (`git commit -m 'Add feature'`)  
4. Push to the branch (`git push origin feature-name`)  
5. Open a Pull Request  

---


## 👨‍💻 Author

- **Tisa Patel**  
  🔗 [GitHub](https://github.com/Tisapatel.com)  
---
