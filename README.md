# Inventory App (Android)

## Overview

The Inventory App is a mobile application designed to help users keep track of items for personal use or small business management. The main goal of this app is to give users a simple and organized way to manage inventory without making it overly complicated.

Users are able to create an account, log in securely, add items, update quantities, delete items, and view all stored inventory in one place. The app also includes an optional SMS notification feature that alerts users when inventory is low. This helps users stay aware of their stock and avoid running out of important items.

---

## User Needs & Goals

This app was designed for users who need a straightforward way to track inventory. This could include students, small business owners, or anyone managing supplies at home.

The main user needs addressed were:
- Keeping track of items in one place
- Easily adding, updating, and removing inventory
- Viewing item quantities clearly
- Receiving alerts when inventory is low

The goal was to make everything simple, fast, and easy to understand without requiring technical knowledge.

---

## Screens & Features

To support user needs, the app includes the following screens:

- **Login Screen**
  - Allows users to log in or create an account

- **Inventory Dashboard**
  - Add items
  - Update item quantities
  - Delete items
  - View inventory list

- **SMS Permission Screen**
  - Allows users to enable or deny SMS notifications

The UI was designed to be clean and consistent across all screens. Buttons are clearly labeled, layouts are simple, and everything is easy to navigate. This makes the app user-friendly and reduces confusion.

---

## Development Approach

When coding the app, I focused on building each feature step by step instead of trying to do everything at once. I used Java and SQLite to handle data storage and made sure each function (add, update, delete) worked properly before moving on.

I also kept the code organized by separating responsibilities into different classes, like using a DatabaseHelper for database operations. This made the app easier to manage and debug.

These strategies can be used in future projects because breaking things down into smaller parts makes development more efficient and less overwhelming.

---

## Testing & Functionality

To test the app, I used the Android Emulator in Android Studio. I tested all major features including:

- Logging in and creating accounts
- Adding items to the database
- Updating item quantities
- Deleting items
- SMS permission handling (allow and deny)

Testing is important because it helps catch errors early and ensures everything works as expected. During testing, I was able to confirm that the app continues to function even if SMS permission is denied, which improves user experience.

---

## Challenges & Problem Solving

One challenge I faced was handling SMS permissions properly. I had to make sure the app would still work even if the user denied permission. To solve this, I implemented logic that allows the app to continue running normally without notifications.

Another challenge was making sure the UI stayed consistent across different screens. I solved this by keeping the layout design simple and reusing similar styles for buttons and text.

---

## Key Strengths

The part of the app I was most successful with was the full CRUD functionality (Create, Read, Update, Delete). The app allows users to manage inventory smoothly, and all operations update correctly in the database.

I also did well implementing user-centered design by keeping the interface simple, clean, and easy to use. The app focuses on functionality while still providing a good user experience.

---

## Conclusion

This project demonstrates my ability to design and develop a functional mobile application using Android Studio, Java, and SQLite. It shows my understanding of user-centered design, problem solving, and building real-world applications.
