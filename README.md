# Event Reservation System

A Django REST Framework based backend project for managing events and seat reservations with validation, filtering, middleware logging, and custom cancellation APIs.

---

# Features

- Create and manage events
- Reserve seats for events
- Automatic seat deduction
- Prevent overbooking
- Cancel reservations
- Restore seats after cancellation
- Filter events by status and venue
- Filter reservations by event
- Custom DRF ViewSets and Routers
- Request logging middleware
- DRF Browsable API support

---

# Tech Stack

- Python
- Django
- Django REST Framework
- SQLite

---

# Project Structure

```text
event_reservation_project/
│
├── manage.py
│
├── config/
│   ├── settings.py
│   ├── urls.py
│
├── reservations/
│   ├── models.py
│   ├── serializers.py
│   ├── views.py
│   ├── middleware.py
│   ├── migrations/
│
├── db.sqlite3
