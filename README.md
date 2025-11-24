# fast-moving-cms
courier management system 
बिलकुल Mali 👍 — आपने सही कहा कि आपके **Fast Moving Courier Management System** में **branch management** भी शामिल है।  
मैं आपके professional `README.md` में अब **branch features** को भी जोड़ देता हूँ ताकि GitHub पर पूरा documentation complete लगे।

---

## 📄 Updated README.md (with Branch Management)

```markdown
# Fast Moving 🚚📦

**Fast Moving** is a Courier Management System designed to streamline delivery operations, staff coordination, and administrative control. Built with HTML and backend integration (Flask/Django recommended), it offers a responsive interface for both admin and staff users.

---

## 🧭 Overview

This system helps courier companies manage:
- Parcel tracking and status updates
- Staff activity and delivery assignments
- Admin control over packages, pricing, booking, and branches
- Real-time updates and booking history

---

## 🛠️ Tech Stack
- **Frontend:** HTML, CSS, Bootstrap
- **Backend:** Python (Flask or Django)
- **Database:** SQLite / MySQL
- **Version Control:** Git & GitHub

---

## 🖥️ Admin Panel Features
Accessible via `admin_login.html`, `adminNavbar.html`, etc.

- Add/Edit/Delete courier packages (`addCourier.html`, `editStaff.html`)
- View courier details (`viewCourierDetails.html`)
- Manage staff and branches (`branches.html`)
- Generate sales reports (`salesReport.html`)
- Monitor booking and pricing (`booking.html`, `pricing.html`)
- Dashboard overview (`dashboard.html`)

---

## 🏢 Branch Management
- Add new branches with location and contact details
- Assign staff to specific branches
- View branch-wise courier activity
- Monitor performance and booking volume per branch
- Accessible via `branches.html` and integrated into admin dashboard

---

## 👨‍💼 Staff Panel Features
Accessible via `staff_login.html`, `staffNavbar.html`, etc.

- View assigned couriers (`staffcouriers.html`)
- Update delivery status (`staffoutforDelivery.html`, `staffshipped.html`, `staffarriveatDestination.html`)
- Search and view courier details (`searchCourier.html`, `staffviewCourierDetails.html`)
- Change password (`staffchangePassword.html`)
- Track inward/outward movement (`staffinward.html`, `stafftotal.html`)
- Profile management (`profile.html`)

---

## 📂 File Structure
```
fast-moving/
│── admin_login.html
│── staff_login.html
│── dashboard.html
│── addCourier.html
│── viewCourierDetails.html
│── booking.html
│── pricing.html
│── branches.html
│── searchCourier.html
│── staffNavbar.html
│── adminNavbar.html
│── courier01.png
│── index.html
│── contact.html
│── README.md
```

---

## ⚙️ Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/maliVishal01/Fast-Moving.git
   cd Fast-Moving
   ```

2. Set up backend (Flask/Django):
   - Create virtual environment
   - Install dependencies
   - Connect HTML files to backend routes

3. Configure database:
   - Create courier, staff, and branch tables
   - Link booking and delivery status

4. Run the server:
   ```bash
   python app.py   # Flask
   python manage.py runserver   # Django
   ```

5. Access in browser:
   ```
   http://127.0.0.1:5000/   # Flask
   http://127.0.0.1:8000/   # Django
   ```

---

## 🔐 Security
- Admin and staff login pages are password protected
- Passwords should be hashed using `werkzeug.security` (Flask) or Django's auth system
- Access control ensures only authorized users can modify data

---

## 📜 License
This project is licensed under the MIT License.

---

## 👨‍💻 Author
**Fast Moving Courier System** developed by *malivishal01*
```

