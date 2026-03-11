# 💰 Expense Tracker – Marketing Mojito Assignment

A modern **Expense Tracker Web Application** built using **React.js and Tailwind CSS**.  
This application allows users to track expenses, categorize spending, view summaries, and convert totals into multiple currencies using real-time exchange rates.

The project demonstrates modern **frontend development practices**, including React Hooks, component-based architecture, API integration, and responsive UI design.

---

# 🚀 Features

### ➕ Add Expenses
Users can add new expenses with:
- Expense name
- Amount
- Category

### ✏️ Edit Expenses
Existing expenses can be edited and updated easily.

### 🗑 Delete Expenses
Users can remove unwanted expenses from the list.

### 📊 Expense Summary
The application provides:
- Total spending
- Category-wise breakdown
- Highest spending category
- Visual progress bars

### 🌍 Currency Conversion
The total expense amount can be converted into different currencies using **live exchange rates API**.

Supported currencies:
- USD
- EUR
- GBP
- INR
- JPY

### 💾 Local Storage Persistence
All expense data is stored in **browser localStorage**, so the data remains even after refreshing the page.

### 📱 Responsive UI
The interface is responsive and works smoothly on:
- Desktop
- Tablet
- Mobile

---

# 🛠 Tech Stack

Frontend technologies used:

- **React.js (via CDN)**
- **React Hooks**
  - useState
  - useEffect
  - useCallback
  - useMemo
- **Tailwind CSS**
- **JavaScript (ES6)**
- **HTML5**
- **CSS3**

---

# 🧩 Project Components

### App
Main root component responsible for:
- Managing application state
- Handling expense operations
- Connecting all components

### ExpenseForm
Handles:
- Adding new expenses
- Editing existing expenses

### ExpenseList
Displays all expenses and provides:
- Edit option
- Delete option

### SummaryPanel
Displays:
- Total spending
- Category breakdown
- Highest spending category

### CurrencyConverter
Converts total expense amount to different currencies using **exchange rate API**.

---

# ⚙️ Custom React Hooks

### useLocalStorage
A custom hook that:
- Saves expenses to localStorage
- Loads saved data automatically

### useExchangeRates
Fetches real-time exchange rates from: https://api.exchangerate-api.com


Also provides fallback rates if API fails.

---

# 🎨 UI Features

- Glassmorphism design
- Animated background mesh
- Grid background pattern
- Smooth animations
- Category badges
- Custom scrollbar
- Loading spinner
- Responsive grid layout

---

# 📁 Project Structure
Expense-Tracker
│
├── index.html
└── README.md

The project is implemented inside a **single HTML file**, which includes:
- React components
- Custom hooks
- Styling
- Application logic

---

# ▶️ How to Run the Project

## Method 1 – Directly Open

1. Download the project
2. Open `index.html` in any browser

The application will run instantly.

---

## Method 2 – Using Live Server (Recommended)

1. Open the project in **VS Code**
2. Install **Live Server extension**
3. Right-click `index.html`
4. Click **Open with Live Server**

---

# 🎯 Learning Outcomes

This project demonstrates:

- React component architecture
- React Hooks usage
- Custom hooks creation
- API integration
- State management
- Data persistence using localStorage
- Responsive UI development

---

# 🔮 Future Improvements

Possible improvements:

- Add expense filtering
- Add date-based tracking
- Add charts using Chart.js
- Add monthly expense reports
- Add backend database
- Add authentication system

---

# 👨‍💻 Author

**Ashad Ahmad**

Frontend Developer | React Learner | Web Development Enthusiast

Skills:
- HTML
- CSS
- Tailwind CSS
- JavaScript
- React
- Git & GitHub

### useExchangeRates
Fetches real-time exchange rates from:
