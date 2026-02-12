## 📖 About

**Bibliotrack** is an online bookstore and library-management application that allows:

- Browsing and searching books
- Managing orders and user accounts
- Personalized book recommendations
- Automatic book cover media support

This project demonstrates a complete web service with backend logic, frontend templates, and AI recommendations.

---

## ⭐ Features

✔ User registration & login  
✔ Book catalog browsing  
✔ Order creation & tracking  
✔ Recommendation engine  
✔ Chat and chatbot features  
✔ Static assets like book covers  
✔ Admin controls for inventory management

*(Add more feature descriptions as needed)*

---

## 🧠 Tech Stack

This project uses the following technologies:

- Python (likely Django) backend
- SQLite (local database)
- HTML, CSS and JavaScript templates
- AI/ML models (under `store/ai_models`)
- Frontend assets in `static/css`
- Python dependency management via `requirements.txt`

*(Tailor this section with exact versions and frameworks after inspection)*

---

## 🗂 Project Structure
├── accounts/ # User accounts and authentication
├── bibliotrack/ # Core application logic
├── books/ # Book models, views & templates
├── orders/ # Order management
├── recommendations/ # Recommendation engine code
├── chat/ # Chat support views
├── chatbot/ # Chatbot & AI integration
├── static/ # CSS / JS / assets
├── templates/ # HTML view templates
├── media/book_covers # Stored book images
├── manage.py # Django project runner
├── db.sqlite3 # Local database (development)
├── requirements.txt # Python dependencies
├── README.md # Project readme (this file)
└── TODO*.md # Planned improvements


*(Customize with real info after reviewing files locally)*

---

## 🚀 Installation

### Prerequisites

Make sure you have:

- Python >= 3.x
- `pip` package manager

### Setup

1. Clone the repo
   ```bash
   git clone https://github.com/acbasavaraj224-sys/bookstore_project.git
   cd bookstore_project
   git checkout merge/bibliotrack


Create and activate a virtual environment:

python -m venv venv
source venv/bin/activate   # macOS/Linux
venv\Scripts\activate      # Windows


Install dependencies:

pip install -r requirements.txt


Apply database migrations:

python manage.py migrate


Run the app:

python manage.py runserver

🧪 Usage

Once running, open a browser and go to:

http://localhost:8000


Use the signup/login interface to create users, browse books, place orders, and explore recommendations.

https://youtu.be/xIi8xLIAfA0?si=MHS4cv1HtVIl333G

