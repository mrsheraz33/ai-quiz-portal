# AI Quiz Portal

A simple quiz portal where teachers generate AI-powered quizzes and students attempt them via a shared link.

---

## Features (Planned)

- Teacher Signup / Login
- AI Quiz Generation (using Gemini API)
- Unique quiz link sharing
- Student registration (Name + Student ID + Password)
- Timer-based quiz
- Auto-submit on tab switch or time up
- Student progress dashboard
- Teacher records panel

---

## Tech Stack

- Frontend: HTML, CSS, JavaScript
- Backend: Node.js + Express (coming soon)
- Database: localStorage (for now) -> MongoDB (later)
- AI: Google Gemini API

---

## Project Structure

```text
quiz-portal/
├── frontend/
│   ├── index.html       # Landing page
│   ├── css/
│   │   └── style.css    # Landing page styles
│   └── teacher/
│       ├── signup.html  # Teacher signup
│       └── login.html   # Teacher login
│
└── README.md
```

---

## Progress

| Page | Status |
|------|--------|
| Landing Page | Done |
| Teacher Signup | Done |
| Teacher Login | Done |
| Teacher Dashboard | Pending |
| Generate Quiz | Pending |
| Student Register | Pending |
| Student Quiz | Pending |
| Result Page | Pending |
| Teacher Records | Pending |

---

## Teacher Flow

1. Signup (Name, Email, Password)
2. Login
3. Generate quiz (Topic, Difficulty, Time)
4. Share quiz link with students
5. View all students records

---

## Student Flow

1. Open quiz link (shared by teacher)
2. Register (Name + Student ID + Password)
   - Student ID format: 24-Arid-4836
3. Attempt quiz (timer starts)
4. Auto-submit if tab switched or time up
5. View result + AI feedback

---

## Roles

| Role | Signup | Login |
|------|--------|-------|
| Teacher | Yes | Yes |
| Student | Yes (once) | Yes |

---

## Notes

- Data is currently stored in localStorage (browser only).
- Backend integration (Node.js + MongoDB) will be added later.
- Gemini API will be used for automatic quiz generation.

---

## Status

In Development - Frontend phase