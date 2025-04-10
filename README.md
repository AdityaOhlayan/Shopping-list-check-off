# Shopping-list-check-off
# 🛒 Shopping List Check Off App

This project is a simple AngularJS-based web application that allows users to manage their shopping list by moving items from the **"To Buy"** list to the **"Already Bought"** list. It visually represents the process of checking off items when shopping.

## 📋 Features

- Two lists:
  - ✅ **To Buy**: Pre-filled with items and quantities.
  - 🛍️ **Already Bought**: Populates as you click "Bought".
- AngularJS architecture:
  - Uses **2 controllers**: `ToBuyController` and `AlreadyBoughtController`
  - Shares data using a **singleton service** (`ShoppingListCheckOffService`)
- Bootstrap 3 styling for responsive and clean layout
- Conditional messages:
  - “Everything is bought!” when all items are checked off
  - “Nothing bought yet.” when no items are moved

## 📦 Technologies Used

- HTML5
- CSS3
- Bootstrap 3
- AngularJS 1.8.x

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/module2-solution.git
