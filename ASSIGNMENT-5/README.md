# 📝 ASSIGNMENT 5 — FastAPI (Day 6)

## 🔍 Features Implemented

### ✅ Q1 — Search Products
- Case-insensitive search
- Example:
  - `mouse` = `MOUSE`
- Handles no results properly

---

### ↕️ Q2 — Sort Products
- Sort by:
  - Price (asc / desc)
  - Name (A → Z / Z → A)
- Error handling for invalid fields

---

### 📄 Q3 — Pagination
- Page & limit supported
- Handles empty pages
- Default values applied

---

### 🔎 Q4 — Search Orders
- Search orders by customer name
- Case-insensitive
- Returns friendly message if no match

---

### 📊 Q5 — Sort by Category + Price
- First sorts by category (A → Z)
- Then by price within category

---

### 🔄 Q6 — Combined Browse Endpoint
- Supports:
  - Search
  - Sort
  - Pagination
- All params optional
- Applied in order:
  1. Filter
  2. Sort
  3. Paginate

---

### ⭐ Bonus — Orders Pagination
- Paginated orders list
- Same logic as products

---

## 🚀 How to Run

```bash
uvicorn main:app --reload
