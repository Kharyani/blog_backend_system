# Blog Backend Data Management System

A Python-based Blog Backend Management System developed using SQLite database and modular programming concepts. This project simulates a real-world backend system used in blogging platforms where users can register, login, create blog posts, manage comments, and perform CRUD operations.

---

# Features

## User Management
- User Registration
- Secure Login System
- Password Hashing using SHA-256
- User Profile Viewing
- Track Total User Posts

## Blog Post Management
- Create Blog Posts
- View All Posts
- Edit Existing Posts
- Delete Posts
- Search Posts by Keyword
- Filter Posts by Category

## Comment System
- Add Comments on Posts
- View Comments Under Posts

## Like/Dislike System
- Like Posts
- Dislike Posts

## Security & Validation
- Password Encryption
- Input Validation
- Error Handling
- Invalid Post ID Handling

---

# Technologies Used

- Python 3
- SQLite3
- Hashlib
- Modular Programming

---

# Project Structure

```bash
blog_backend_system/
│
├── main.py
├── database.py
├── auth.py
├── posts.py
├── comments.py
├── users.py
├── utils.py
├── sample_data.py
├── requirements.txt
├── README.md
├── blog.db
│
└── exports/
```

---

# Database Tables

## Users Table
- ID
- Username
- Email
- Password
- Created Date

## Posts Table
- Post ID
- Title
- Content
- Author
- Category
- Created Date
- Likes
- Dislikes

## Comments Table
- Comment ID
- Post ID
- Commenter Name
- Message
- Created Date

---

# Installation & Setup

## Step 1: Clone Repository

```bash
git clone https://github.com/your-username/blog_backend_system.git
```

## Step 2: Open Project Folder

```bash
cd blog_backend_system
```

## Step 3: Install Requirements

```bash
pip install -r requirements.txt
```

## Step 4: Create Database

```bash
python database.py
```

## Step 5: Insert Sample Data

```bash
python sample_data.py
```

## Step 6: Run Project

```bash
python main.py
```

---

# Default Login Credentials

```text
Username: admin
Password: admin123
```

---

# Application Menu

```text
1. Register
2. Login
3. Create Post
4. View Posts
5. Edit Post
6. Delete Post
7. Add Comment
8. View Comments
9. Search Posts
10. Filter by Category
11. Like Post
12. Dislike Post
13. View Profile
14. Exit
```

---

# Sample Functionalities

## Register User
Users can create accounts securely.

## Login System
Users can login using encrypted passwords.

## Create Blog Posts
Authenticated users can create blog posts.

## Search Feature
Posts can be searched using keywords.

## Category Filter
Users can filter posts by category.

## Comment System
Users can add and view comments on posts.

---

# Error Handling

The system handles:
- Empty Inputs
- Invalid Post IDs
- Unauthorized Editing
- Invalid Login Credentials
- Missing Records

---

# Future Improvements

- Admin Panel
- GUI Version
- Pagination
- PDF Export
- REST API Integration
- Image Upload Support

---

# Learning Outcomes

This project demonstrates:
- CRUD Operations
- SQLite Database Integration
- Backend Logic Development
- User Authentication
- File Modularization
- Error Handling
- Secure Password Storage

---

# Author

Kashish Haryani

---

# License

This project is developed for educational and internship purposes.
