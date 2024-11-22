# eBook Library Service

## Overview
The **eBook Library Service** is a web application designed to manage an online library. Built using the MVC (Model-View-Controller) pattern, this project allows administrators to oversee the library's operations while providing users with features to search, borrow, and buy eBooks. The project draws inspiration from platforms like Audible and Libby.

---

## Features

### User Roles
1. **Admin**:
   - Add/remove eBooks in various formats (epub, f2b, mobi, PDF).
   - Set and manage prices, including limited-time discounts.
   - Manage borrowing systems and waiting lists.
   - Oversee the library catalog and borrowing timeframes.
   - Handle user accounts and permissions.

2. **Users**:
   - Browse, search, borrow, and purchase eBooks.
   - Manage their personal eBook library.
   - Provide ratings and feedback for books and the platform.

---

## Functional Highlights

### For Admin
- **Library Management**:
  - Add or remove eBooks in multiple formats.
  - Adjust and display prices dynamically, including strike-through for discounts.
  - Limit borrowing availability for some books to "Buy Only."
  - Notify users when borrowed books are due (reminders sent 5 days before deadlines).
- **Borrowing Rules**:
  - Limit borrowing to 3 copies per book.
  - Handle waiting lists for unavailable books, with notifications when copies become available.

### For Users
- **Search and Browse**:
  - Search for books by title, author, or publisher (supports partial queries).
  - Filter and sort books by genre, popularity, publication year, or price.
- **Borrow/Buy**:
  - Borrow up to 3 eBooks at a time for a 30-day period.
  - Enter waiting lists for unavailable eBooks.
  - Purchase unlimited eBooks.
  - Borrowed books automatically disappear from the library after the due date.
- **Feedback and Ratings**:
  - Rate and review books that have been borrowed or purchased.
  - Share feedback about the borrowing/buying experience, displayed on the main page.
- **Notifications**:
  - Email notifications for borrowing deadlines and payment confirmations.

### eBook Gallery
- Display eBooks with:
  - Cover image, title, author(s), publisher, price (for borrowing and buying), and publication year.
  - Age restrictions (e.g., 18+, 8+, etc.).
- Show real-time inventory changes as books are added/removed.
- Filter books by:
  - Price (low to high or high to low).
  - Popularity and genre.

---

## Payment System
- Manage a shopping cart for easy transactions.
- Secure payment processing using SSL (with free SSL certificates).
- Support credit card and PayPal payment methods (via API redirection).
- Notify users of payment success or failure, followed by a redirect to the home page.

---

## Technical Requirements
1. **Framework**: MVC architecture.
2. **Database**: Securely store user and book data, adhering to logical constraints.
3. **Security**:
   - Use SSL for payment transactions.
   - Do not store credit card information in the database.
4. **Front-End**:
   - Provide dynamic, responsive user and admin interfaces.

---

## How to Run
1. Clone the repository:
   ```bash
   git clone <repository-url>

## Developed by:

[Ali Heib]
[Hasan Musa]
License
This project is licensed under the MIT License.

Good Luck!












