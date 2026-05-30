# 🎓 College Management System

A fully **frontend** college management system built with **HTML, CSS, and JavaScript**, themed around *Stanford Institute of Technology*. The project simulates a real-world university portal with three separate role-based logins — Admin, Student, and Faculty — along with an admission management module, library access, notice board, and university news section. Deployed live on Vercel.

🔗 **Live Demo:** [college-management-system-html-css.vercel.app](https://college-management-system-html-css.vercel.app)

---

## 📸 Preview

> _Add a screenshot or GIF of the homepage here to help visitors get a feel for the UI._

---

## ✨ Features

### 🏠 Homepage (`index.html`)
- University header with contact, email, and social media dropdowns
- Navigation bar with Academics, Departments, Admission, Facilities, and Placements menus
- Auto-cycling image carousel showcasing campus photos
- Three prominent login entry points: Admin, Student, and Faculty
- Scrolling **Notice Board** with upcoming academic dates and events
- **University News** section with category cards (Medicine, Science & Technology, Arts, Social Sciences)
- **About Stanford** section with institution stats (founded 1891, 16,937 students, 2,288 faculty)
- Footer with quick links and social media icons

### 🔐 Role-Based Portals

| Portal | Path | Access |
|--------|------|--------|
| **Admin** | `Admin Home Page/Admin Home.html` | Student management, course management, faculty management, HOD management, exam management, fees management |
| **Student** | `Student Login/student.html` | CA marks, social activity, results, exam forms, fee payment |
| **Faculty** | `Faculty Login/Faculty.html` | Faculty-specific resources including library access |

### 📋 Admission Management
- Online admission form (`Admission Management/Admission Form.html`)
- Accessible directly from the homepage navigation

### 🏫 Departments
- **BCA** — Bachelor of Computer Applications
- **CSE** — Computer Science & Engineering

### 📚 Library
- Accessible from the Facilities menu and Faculty portal
- Located at `Faculty Login/Library/index/index.html`

### 🪟 Popup Notifications
- A `popup/` module for in-page alert or modal notifications

---

## 📁 Project Structure

```
College-Management-System-HTML-CSS-JAVASCRIPT/
├── index.html                      # Main homepage — entry point for the system
│
├── Admin Home Page/
│   └── Admin Home.html             # Admin dashboard & management portal
│
├── Student Login/
│   └── student.html                # Student portal
│
├── Faculty Login/
│   ├── Faculty.html                # Faculty portal
│   └── Library/
│       └── index/
│           └── index.html          # Library management page
│
├── Admission Management/
│   └── Admission Form.html         # Online student admission form
│
├── css file/
│   └── homepage1.css               # Main stylesheet for the homepage
│
├── img/                            # All images used across the system
│   ├── Stan.png
│   ├── Stan2.png
│   ├── adminlogin.png
│   ├── studlogin.png
│   ├── faclogin.png
│   └── ...
│
└── popup/                          # Popup / modal notification components
```

---

## 🛠️ Tech Stack

| Technology    | Role                                         |
|---------------|----------------------------------------------|
| HTML5         | Page structure and content                   |
| CSS3          | Custom styling and layout                    |
| JavaScript    | Interactive UI behaviour and DOM manipulation|
| Bootstrap 4   | Responsive grid, navbar, carousel, cards     |
| jQuery        | DOM utilities (via Bootstrap dependency)     |
| Font Awesome 6| Icons throughout the UI                      |

> No backend or database — this is a **pure frontend** project. All data is static and UI-driven.

---

## 🚀 Getting Started

Since this is a static frontend project, no installation or build step is required.

### Option A — Open Directly in Browser

```bash
# Clone the repository
git clone https://github.com/Mdmufid/College-Management-System-HTML-CSS-JAVASCRIPT.git

# Navigate into the project folder
cd College-Management-System-HTML-CSS-JAVASCRIPT

# Open the homepage
open index.html       # macOS
start index.html      # Windows
xdg-open index.html   # Linux
```

Or simply double-click `index.html` in your file explorer.

### Option B — Use a Local Server (Recommended)

For the best experience (to avoid relative path issues), serve the project with a local HTTP server:

```bash
# Using VS Code Live Server extension
# Right-click index.html → "Open with Live Server"

# Using Python
python -m http.server 8080
# Then open http://localhost:8080
```

### Option C — View Live Demo

Visit the deployed version directly:
👉 [https://college-management-system-html-css.vercel.app](https://college-management-system-html-css.vercel.app)

---

## 🧭 Navigation Guide

| What you want to do            | Where to go                                             |
|--------------------------------|---------------------------------------------------------|
| View the main portal           | Open `index.html`                                       |
| Log in as Admin                | Click **Admin Login** on homepage                       |
| Log in as Student              | Click **Student Login** on homepage                     |
| Log in as Faculty              | Click **Faculty Login** on homepage                     |
| Submit an admission form       | Navbar → Admission → Admission Form                     |
| Browse departments             | Navbar → Departments → BCA or CSE                       |
| Access the library             | Navbar → Facilities → Library                           |

---

## 🌐 Deployment

This project is already deployed on **Vercel**. To deploy your own fork:

1. Fork this repository
2. Go to [vercel.com](https://vercel.com) and import your forked repo
3. Set the **root directory** to the repo root and leave build settings blank (static site)
4. Click **Deploy**

You can also deploy to **GitHub Pages**:

1. Go to your repo → Settings → Pages
2. Set source to the `master` branch and root (`/`) folder
3. Click Save — your site will be live at `https://<your-username>.github.io/College-Management-System-HTML-CSS-JAVASCRIPT`

---

## 🤝 Contributing

Contributions are welcome! This project is a great base for adding a real backend.

1. Fork the repository
2. Create a new branch: `git checkout -b feature/your-feature`
3. Make your changes and commit: `git commit -m "Add your feature"`
4. Push to your branch: `git push origin feature/your-feature`
5. Open a Pull Request

Some ideas for extending the project:
- Add a backend with Node.js/Express or Django
- Connect to a database (MongoDB or MySQL) for real data persistence
- Implement actual authentication for the three login portals
- Add form validation with JavaScript for the admission form

---

## 📄 License

This project is open source and free to use.

---

## 👤 Author

**Md Mufid**
GitHub: [@Mdmufid](https://github.com/Mdmufid)
