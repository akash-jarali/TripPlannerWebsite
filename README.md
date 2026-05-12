# TripPlannerWebsite

A Django MVT project for planning holidays, booking hotels, choosing travel options, and requesting trip packages. It uses SQLite by default, so it is easy to run in a local environment.

---

# ✨ Features

- Destination, hotel, transport, package, and booking models
- Responsive pages using Django templates
- Professional service search for flights, hotels, trains, buses, cabs, and packages
- Search results page with left-side filters
- Domestic and international demo inventory
- Custom TravelMate logo
- Mobile navigation with JavaScript
- Live card search and sorting
- Transport table filtering
- Trip checklist progress bar
- Booking form helper summary
- Local saved trips using browser storage
- Signup, login, logout, and remember-me option
- Private user booking history and explored-plan history
- Demo data command for quick setup

---

# 🛠️ Technologies Used

| Technology | Purpose |
|------------|----------|
| Python | Backend programming |
| Django | Web framework |
| HTML5 | Frontend structure |
| CSS3 | Styling |
| JavaScript | Interactive features |
| SQLite | Database |
| Bootstrap | Responsive UI |

---

# 📂 Project Structure

```bash
TripPlannerWebsite/
│
├── manage.py
├── requirements.txt
├── db.sqlite3
│
├── TripPlannerWebsite/
│
├── templates/
├── static/
├── media/
│
└── README.md
```

---

# 📸 Project Screenshots

<img width="1906" height="778" alt="1" src="https://github.com/user-attachments/assets/75d6c53a-30af-4840-b567-b82d4daa793a" />
<img width="1778" height="894" alt="2" src="https://github.com/user-attachments/assets/71fdfc61-f4f7-408d-8ff6-bda507a0517a" />
<img width="1892" height="903" alt="3" src="https://github.com/user-attachments/assets/b45f24fd-5cef-47ca-b80d-93512bc8dc95" />
<img width="1709" height="900" alt="4" src="https://github.com/user-attachments/assets/ab6ebd7a-0edc-45ee-9402-f6dcd7507530" />

---

# ⚙️ Setup

```powershell
python -m venv .venv
.\.venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py seed_demo_data
python manage.py runserver
```

Open:

```text
http://127.0.0.1:8000/
```

in the browser.

---

# 🔑 Admin Login

Create an admin user with:

```powershell
python manage.py createsuperuser
```

Then visit:

```text
http://127.0.0.1:8000/admin/
```

---

# 🚀 Future Improvements

- Online payment integration
- Email notifications
- Real-time hotel API integration
- AI-based trip recommendations
- Google Maps integration
- User reviews and ratings

---

# 👨‍💻 Author

**Akash**

Django Full Stack Learning Project

---

# 📄 License

This project is created for learning and educational purposes.
