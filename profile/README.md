# LLG-Mapper

A comprehensive **school room availability management system** built for students and administrators. LLG-Mapper helps students find available classrooms and spaces in their high school, with an interactive map interface and advanced filtering capabilities.

Made for **students** by **students**.

**Competition:** Trophées NSI 2025 - [More info](https://trophees-nsi.fr/)

---

## 🎯 Project Overview

### Problem
- Students struggle to find available rooms during free periods or breaks
- No centralized system to check room availability in real-time
- Difficulty navigating which rooms have specific features (computers, projectors, etc.)
- Manual room booking processes are inefficient

### Solution
LLG-Mapper provides a **user-friendly platform** where students can:
- 🗺️ View a visual map of their high school buildings
- ⏰ Check room availability at specific times
- 🔍 Filter rooms by features, capacity, and location
- 📋 See detailed room information instantly
- 📅 Understand the class schedule for any room

---

## ✨ Key Features

### For Students
- **Interactive Map** - Visual representation of buildings and room layouts
- **Real-Time Availability** - Check if a room is free right now or at a specific time
- **Smart Filtering** - Find rooms by:
  - Building location
  - Floor number
  - Features (projector, computers, whiteboard, etc.)
  - Capacity
  - Availability status
- **Room Details** - See capacity, features, and class schedule
- **Quick Navigation** - Intuitive UI for fast room discovery

### For Administrators  
- **Complete Management System** - Manage all aspects via REST API:
  - Buildings and room configuration
  - Teacher and group management
  - Class scheduling
  - Subject and feature management
- **Robust Validation** - Prevent scheduling conflicts and data errors
- **Relationship Management** - Track complex relationships between entities

---

## Repositories
- **Web application**: [github.com/LLG-Mapper/web](web)
- **Backend API**: [github.com/LLG-Mapper/api](api)

---

## 🛠️ Technology Stack

### Frontend
- **HTML5** - Semantic markup
- **CSS3** - Responsive styling and layout
- **JavaScript (Vanilla)** - Interactive map and filtering

### Backend
- **Framework**: Flask 3.1.2
- **ORM**: SQLAlchemy 2.0.45
- **Database**: SQLite (development), configurable for production
- **Serialization**: Marshmallow 3.21.3
- **Migrations**: Flask-Migrate with Alembic
- **CORS**: Flask-CORS 6.0.2

---

## 📞 Support & Questions

For issues or questions about the API or project setup, please open an issue on the repository.

---

## 📝 License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
