# Personal Portfolio Web App

This is a **dynamic personal portfolio web application** built with **HTML, Tailwind CSS, and Vanilla JavaScript**.  
It allows users to customize their profile, manage services/skills, toggle dark & light mode, and persist data using **LocalStorage**.

---

## 🚀 Features Overview

### 1. Profile Management
- Edit **Profile Name** and **Bio** using prompts
- Automatically saves data to **LocalStorage**
- Profile information persists after page reload
- Default profile image is applied on edit

**Stored Data:**
- `name`
- `Bio`
- `defaultImage`

---

### 2. Non-Functional Buttons (Placeholder Actions)
Some buttons are intentionally non-functional and show an alert:
- Download CV
- Services
- Recent Work
- Get In Touch
- Contact Form Submit
- “Get the Service” buttons

> These display:
Item or information not available, pls check back later



---

### 3. Work Process Interactive Section
- Hover effects on circular icons
- Updates process text dynamically
- Processes displayed:
  - Research
  - Layout
  - System Design
  - Documentation
- Visual changes on hover (background, border, icon color)

---

### 4. Services / Skills Management

#### ➕ Add Skill / Service
- Add new skills dynamically using prompts
- Each skill includes:
  - Icon
  - Title
  - Description
  - Get Service button
  - Delete button
- Skills are stored in **LocalStorage**
- Automatically loaded on page refresh

#### ❌ Delete Skill
- Deletes both default and user-added skills
- Deleted items are remembered using LocalStorage
- Removed items stay deleted even after reload

**Stored Data:**
- `addedSkills`
- `deletedItems`

---

### 5. Dark Mode & Light Mode
- Toggle between **Dark Mode** and **Light Mode**
- Fully styled transitions across:
  - Navigation
  - Profile section
  - Services
  - Projects
  - Testimonials
  - Contact section
  - Footer
- Mode preference saved in **LocalStorage**

**Stored Data:**
- `toggleMode` (`on` / `off`)

---

### 6. Persistent UI State
On page reload:
- Profile info is restored
- Added skills reload automatically
- Deleted skills remain removed
- Selected theme (Dark / Light) is restored

---

### 7. Dynamic Year Update
- Footer year updates automatically to the current year using JavaScript

---

## 🧠 Technologies Used
- HTML5
- Tailwind CSS
- Vanilla JavaScript
- Browser LocalStorage

---

## 📁 LocalStorage Keys Used
| Key Name | Purpose |
|--------|--------|
| `name` | Profile name |
| `Bio` | Profile bio |
| `defaultImage` | Profile image path |
| `addedSkills` | User-added services |
| `deletedItems` | Removed default services |
| `toggleMode` | Dark/Light mode state |

---

## ⚠️ Notes
- This project does **not** include backend functionality
- All data is stored locally in the browser
- Clearing browser storage will reset the app

---

---

## 👨‍💻 A4DEV_5831
Built as a **frontend portfolio project** demonstrating:
- DOM manipulation
- LocalStorage usage
- UI state management
- Dynamic component creation
- Theme toggling

---

## 📄 License
This project is open-source and free to use for learning and personal portfolios.
