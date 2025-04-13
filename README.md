---

# 🌐 Full Stack EJS App

A simple and secure **Node.js** backend application using **Express** and **EJS** templating. This project demonstrates user authentication, data storage with SQLite, and server-side rendering with EJS.

---

## 🚀 Features

- 🧑‍💻 User Authentication (Login & Signup)
- 🛡️ Secure password hashing with `bcrypt`
- 🔐 JWT-based session management via cookies
- 📄 Clean EJS templates for dynamic rendering
- 🧼 Input sanitization using `sanitize-html`
- 🗃️ SQLite database powered by `better-sqlite3`

---

## 🛠️ Tech Stack

| Layer            | Technology             |
|------------------|------------------------|
| Backend          | Node.js + Express      |
| Templating       | EJS                    |
| Database         | SQLite (via better-sqlite3) |
| Authentication   | JWT + Cookies          |
| Environment Vars | dotenv                 |

---

## 📂 Folder Structure

```
project-root/
├── views/               # EJS templates
├── public/              # Static assets (CSS, JS)
├── routes/              # Express route handlers
├── db/                  # Database connection & queries
├── server.js            # Main entry point
├── .env                 # Environment variables
```

---

## 📦 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/full-stack-ejs-project.git
cd full-stack-ejs-project
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Set Up Environment Variables

Create a `.env` file:

```env
PORT=3000
JWT_SECRET=your_secret_key
```

### 4. Run the App

```bash
npm run dev
```

Visit: `http://localhost:3000`

---

## 🔐 Authentication

- Uses **bcrypt** to hash user passwords before storing
- Generates **JWT tokens** for authentication
- Stores JWT in **HTTP-only cookies** for security

---

## 🧪 Sample Routes

| Method | Route       | Description         |
|--------|-------------|---------------------|
| `GET`  | `/`         | Home page           |
| `GET`  | `/login`    | Login form          |
| `POST` | `/login`    | Authenticate user   |
| `GET`  | `/register` | Register form       |
| `POST` | `/register` | Register new user   |
| `GET`  | `/dashboard`| Protected user view |
| `GET`  | `/logout`   | Destroy user session|

---

## ✨ Possible Enhancements

- 💬 Flash messages for form feedback
- 📩 Email verification
- 👮‍♂️ Admin dashboard with role-based views
- 🔁 Password reset functionality

---

## 👨‍💻 Author

**Chinedu Aguwa**  
📧 [neduaguwa443@gmail.com](mailto:neduaguwa443@gmail.com)  
📞 +234 810 547 1046  
[LinkedIn](https://www.linkedin.com/in/chinedu-aguwa-b1747a2b0) • [GitHub](https://github.com/chi2785443)

---
