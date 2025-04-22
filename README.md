# Software-Requirements-Documentation
 [Edit the shared Word doc](https://docs.google.com/document/d/1EFdwsVNnqteNODP9Nkrbn45r6-ieXBCB59l7KUTa6Vw/edit?usp=sharing)


# 🎓 Student Club Management System

A centralized Django-based platform to empower student clubs to manage **members**, **events**, **budgets**, and **venues** — integrated seamlessly with university financial systems and space reservation tools.

---

## 🧭 Project Vision

To streamline student club operations through a centralized digital platform that enhances transparency, reduces administrative burden, and increases student engagement.

---

## 📦 Features

### 🧑‍🤝‍🧑 Membership Management
- Register and manage club members with profiles and activity logs
- Role assignment (President, Secretary, Treasurer)
- Track attendance and participation
- Announcements, discussions, and group chats

### 📅 Event Planning
- Create/manage events with full descriptions, dates, and logistics
- Workflow for event proposals and approvals
- Input budget and expected attendance
- Tools for catering, equipment, volunteers

### 💸 Budget Integration
- Submit budget requests for events and general club operations
- Real-time tracking of allocated funds, expenses, and balances
- Upload receipts and expenditures
- Compliant with university financial policies

### 🏛️ Venue Integration
- Search available venues: classrooms, auditoriums, outdoor areas
- Booking requests with automated approvals
- Conflict detection for overlapping schedules
- Integration with campus space reservation system

### 🔔 Notifications & Reporting
- Alerts for deadlines, approvals, and changes
- Reports on budget usage, participation, and club activities

---

## 🧱 System Architecture (High-Level Entities)

- **Users**: Club Members, Club Officers, Admins, Finance Dept, Facilities
- **Entities**: Students, Clubs, Budgets, Events, Venues
- **Integrations**: 
  - 🏦 University Financial System
  - 🏢 Campus Venue Reservation System

---

## ⚙️ Tech Stack

- **Backend**: Django (Python)
- **Frontend**: HTML + Tailwind CSS
- **Database**: SQLite (can be scaled to PostgreSQL/MySQL)
- **Authentication**: Role-based access control
- **Notifications**: System alerts + optional push/email integrations

---

## 💡 Kano Model Features Breakdown

### ✅ Must-Haves (Dissatisfiers)
- User login & authentication
- Role-based access
- Event creation & approval
- Budget submission & tracking
- Venue booking with availability checks
- Notification system
- Secure data storage

### 📈 Performance Features (Satisfiers)
- Real-time dashboards
- Budget forecasting tools
- Integrated calendar
- Member attendance tracking
- Multi-level approval workflows
- Booking conflict detection

### 🎉 Delightful Extras (Exciters)
- AI suggestions for optimal event planning
- Mobile app with push notifications
- Gamified member engagement (badges)
- Social media integration for event promo
- Auto-reminders for renewals & reports
- Chatbot assistant for FAQs

---

## 🚀 Getting Started

### Prerequisites
- Python 3.10+
- Django 4.x
- pip + virtualenv

### Installation

```bash
git clone https://github.com/your-username/student-club-management.git
cd student-club-management
python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver


