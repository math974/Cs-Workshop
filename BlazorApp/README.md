# Blazor, C#, and SQLite Workshop Activities

Welcome to the workshop! We'll be building a simple web application using **C#**, **.NET**, **Blazor**, and **SQLite**. This guide will walk you through each activity, focusing on C# concepts while using Blazor to display the results.

---

## **Activity 1: Retrieve and Display Data**
**Goal:** Connect to the SQLite database, retrieve the list of books, and display them in a Blazor table.

**Learning Points:**
- Setting up a **SQLite connection** in C# (`System.Data.SQLite` or `Microsoft.Data.Sqlite`).
- Creating a **Book class** to map the data.
- Displaying the data using simple **Blazor components** (`<table>` and data binding).

**Stretch Goal for Fast Learners:** Add basic styling to the table (optional).

---

## **Activity 2: Add, Edit, and Delete Books**
**Goal:** Implement basic **CRUD operations**.

**Learning Points:**
- Using **C# methods** to insert, update, and delete data in SQLite.
- Updating the **UI** after making changes (refreshing the data source in Blazor).
- Handling user input with basic **Blazor forms** (`<InputText>`, `<InputNumber>`).

---

## **Activity 3: Create Favorite Lists**
**Goal:** Allow users to mark books as favorites and create multiple favorite lists.

**Learning Points:**
- Adding a **bool property** (e.g., `IsFavorite`) to the `Book` class and updating the database.
- Using **C# collections** (`List<Book>`) to manage favorites in memory.
- Displaying favorites in a **separate table**.

---

## **Activity 4: View Book Details**
**Goal:** Click on a book to view its detailed information.

**Learning Points:**
- **Passing data between components** (e.g., using parameters in Blazor).
- Using **conditional rendering** in Blazor (`if` statements) to display details.
- Binding the selected book to a **class** and showing its properties.

---

## **Activity 5: Search and Filter Books**
**Goal:** Implement a simple **search bar** to filter books by title or author.

**Learning Points:**
- Using **LINQ** to filter data in C# (`Where`, `Contains`, etc.).
- Binding **user input** to a C# property in Blazor (`<InputText>`).
- Updating the displayed list **dynamically** based on the search query.

---

### **Happy Coding!** 🎉

Feel free to explore further by adding more features or improving the UI as you get comfortable with the concepts!

