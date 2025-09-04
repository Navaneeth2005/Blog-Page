# 📝 Upgraded Blog - Flask Project

This is a clean and minimal blog application built using **Flask**. It allows users to create, edit, and view blog posts with a polished frontend. The app uses Jinja2 templates and stores blog data using SQLite.

---

## 🚀 Features

- 📰 Create and view blog posts  
- ✏️ Edit existing posts  
- 🎨 Styled with custom CSS and static assets  
- 🗃️ SQLite database for persistence  
- 📄 Jinja2 templating engine  

---

## 📁 Project Structure

day-67-upgraded-blog-end/
├── main.py                 # Flask application entrypoint
├── requirements.txt        # Project dependencies
│
├── instance/
│   └── posts.db            # SQLite database
│
├── static/
│   ├── css/
│   │   └── styles.css      # Custom CSS
│   ├── js/
│   │   └── scripts.js      # JavaScript functionality
│   └── assets/
│       └── img/            # Background and icons
│
└── templates/
    ├── index.html          # Home page
    ├── post.html           # Blog post view
    ├── make-post.html      # New/edit post
    ├── about.html          # About page
    ├── contact.html        # Contact page
    ├── header.html         # Common header
    └── footer.html         # Common footer


---

## ⚙️ Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
2.**Install Dependencies**
   pip install -r requirements.txt

run app - python main.py

🧪 Requirements
Python 3.x

Flask

SQLite3

