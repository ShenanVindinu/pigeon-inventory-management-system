# Stock Management System (CLI) 🥬📃🧦

## Overview
This is a **Stock Management System** developed as part of the coursework for the **GDSE ITS1010** module. The system enables users to manage stock efficiently by handling supplier details, item categories, and inventory while ensuring data security through a login system.

## Features
### 1. **User Authentication**
- Secure login with username and password validation.
- Ability to change login credentials.
- Continuous prompting until valid credentials are entered.
- Logout and exit options.

### 2. **Supplier Management**
- Add new suppliers with unique IDs.
- Update supplier details.
- Delete supplier records.
- View all suppliers in a tabular format.
- Search for suppliers by ID.

### 3. **Stock Management**
- Manage item categories (add, update, delete categories).
- Add new items with category and supplier association.
- Prevent adding items without prior category or supplier registration.
- View stock details grouped by item category.
- View items supplier-wise.
- Rank items based on unit price in ascending order.

## Technologies Used
- **Java SE (Standard Edition)**
- **Multi-Dimensional Arrays** for data storage
- **Scanner** for user input handling
- **Random** for generating random values

## Constraints & Guidelines Followed
- Used **arrays** (multi-dimensional) as the primary data structure.
- No **ArrayList, LinkedList**, or other Java Collection Framework classes used.
- No **third-party libraries** were used.
- Only **one class** with multiple methods was created.
- Custom **sorting algorithms** were implemented manually.
- CLI clearing function included for better user experience.

## Setup & Execution
1. **Compile the project:**  
   ```sh
   javac CourseWork.java
   ```
2. **Run the project:**  
   ```sh
   java CourseWork
   ```
## Additional Notes
- Implemented complete input **validation**.
- Ensured **error handling** for invalid inputs.
- Implemented CLI navigation for an **interactive user experience**.
- Demonstrated knowledge in **CLI-based software development**.

## Conclusion
This project showcases fundamental programming skills by implementing a **fully functional** stock management system with **multi-dimensional arrays**, **sorting algorithms**, and **efficient data management** using CLI. The system is structured to be user-friendly and secure, fulfilling all coursework requirements.

🚀 **Developed by:** _Shenan_
