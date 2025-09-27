# Expense Tracker with Category Insights

A full-stack expense tracker platform that allows users to log daily expenses, categorize them, and view insights on their spending.

---

## Table of Contents

- [Project Overview](#project-overview)  
- [Features](#features)  
- [Tech Stack](#tech-stack)  
- [Folder Structure](#folder-structure)  
- [Setup & Installation](#setup--installation)  
- [Usage](#usage)  
- [API Endpoints](#api-endpoints)  
- [Optional Enhancements](#optional-enhancements)  

---

## Project Overview

The Expense Tracker enables users to:

- Add daily expenses with:
  - Amount  
  - Category (predefined: Food, Travel, Shopping, or user-defined)  
  - Date  
- View a summary of spending:
  - Total spend  
  - Category-wise breakdown (e.g., Food – ₹1200, Travel – ₹800)  
- Update existing expenses (amount, category, date)  
- Optional: filter by date range and visualize category-wise charts  

---

## Features

**Frontend (React)**

- Clean homepage for adding and updating expenses.  
- Dynamic summary of total spend and category-wise breakdown.  
- Optional charts for visual insights.  

**Backend (FastAPI)**

- REST API with endpoints for:
  - Adding, updating, and fetching expenses  
  - Generating spending summary  
  - Deleting expenses (optional)  
- Stores data in SQLite database  

---

## Tech Stack

- Frontend: React.js  
- Backend: FastAPI (Python)  
- Database: SQLite  
- HTTP Client: Axios  
- Package Manager: npm & pip  

---

## Folder Structure

