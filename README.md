# 🏦 Personal Finance Tracker

An interactive, full-stack-style React application built with **TypeScript**. This project serves as a comprehensive "Personal Finance Tracker Web Application," allowing users to track their financial health through a real-time dashboard with integrated external data.

---

## 🔗 Project Deliverables
- **Live Web App:** https://java-script-project-personal-financ.vercel.app/
- **GitHub Repository:** https://github.com/Nutkub4/JavaScript_project_personal_finance_tracker

---

## 📖 Project Description
The Personal Finance Tracker is a data-management tool designed for professional-grade personal accounting. It allows users to input income and expenses, calculates real-time balances, and provides a searchable history of all transactions. To fulfill the "External Data" requirement, the app connects to an external API to deliver daily motivational financial wisdom.

---

## ✨ Core Features & Requirements Satisfaction

### 1. Interactive Functionality
- **Event Handling:** Managed through React form submissions and click events for adding and deleting transactions.
- **Asynchronous Programming:** Demonstrated using `Async/Await` and `Promises` to fetch live data from the ZenQuotes API.

### 2. API Integration & External Data
- **Data Fetching:** Implements the `Fetch API` inside a `useEffect` hook to retrieve JSON data.
- **Search & Filter:** A real-time filter system allows users to search their history by description keyword.

### 3. React Architecture
- **Reusable Components:** Modular design with separate logic for the Transaction Form, Dashboard, and Global Context.
- **State & Props:** Utilizes local state for forms and search, and global state for transaction data.

### 4. Advanced State Management
- **Context API:** Implemented a `FinanceProvider` to share data across the component tree, avoiding "Prop Drilling."
- **Add/Delete System:** A full CRUD-style logic for managing items within the state.

### 5. Optimization & TypeScript
- **TypeScript:** Integrated via custom interfaces (`Transaction`, `FinanceContextType`) to ensure type safety and prevent runtime errors.
- **React Hooks:** Extensive use of `useState` for UI state and `useEffect` for side effects.

---

## 🛠️ Installation Steps

To run this project locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Nutkub4/JavaScript_project_personal_finance_tracker.git

2. **Clone the repository:**
   ```bash
   cd JavaScript_project_personal_finance_tracker

3. **Install the necessary dependencies:**
   ```bash
   npm install

4. **Launch the local development server:**
   ```bash
   npm start

---

## Author

This project is created by Watchapon Wongapinya for JavaScript project.