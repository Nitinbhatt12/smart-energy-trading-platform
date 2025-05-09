# smart-energy-trading-platform
This C program implements a comprehensive energy trading system that manages transactions between sellers and buyers of energy. The system tracks energy transactions, calculates revenues, identifies regular buyers, and provides various reporting features.

---

## 🚀 Features

### ✅ Transaction Management
- Add new energy transactions (Buyer ↔ Seller)
- Update existing transactions
- View all transactions in tabular format

### 📊 Reporting & Analytics
- View transactions grouped by seller or buyer
- Filter by timestamp ranges
- Calculate revenue earned by each seller
- Identify regular buyers for sellers

### 🔃 Sorting Capabilities
- Sort transactions by:
  - Energy amount
  - Transaction timestamp
- Sort buyers by:
  - Total energy purchased
- Sort buyer-seller pairs by:
  - Number of transactions

### 💾 Data Persistence
- Automatic loading and saving of:
  - Transactions (`energytrading.txt`)
  - Sellers (`sellertable.txt`)
- Human-readable, editable file format

### 🔐 Input Validation
- Valid IDs: `TXXXX`, `SXXXX`, `BXXXX`
- Valid timestamps (`YYYY-MM-DD HH:MM`)
- Positive energy and price values
- Duplicate ID checking and consistent format enforcement

---

## 🧠 Implementation Highlights

- **Dynamic Linked Lists** for all entity types
- **Merge Sort** for efficient transaction sorting
- **Modular Architecture** for maintainability
- **Smart Memory Management** to prevent leaks
- **Menu-Driven Console UI** for easy navigation

---

## 🛠️ Build and Run

