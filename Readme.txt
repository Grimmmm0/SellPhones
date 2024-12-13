# SellPhones

SellPhones is a PHP-based web application designed to facilitate the trading of phones. It provides users with functionalities such as phone reservations, inventory management, user profiles, and a shopping cart. The project includes a user-friendly interface for buyers and an admin dashboard for managing products, reservations, and users.

# Features

### User Features:
- **Home Page** (`index.html`, `index1.php`):
  - Provides an overview of the website and its features.
- **Signup/Login** (`signup.php`, `login.php`):
  - Enables users to create an account or log in to access personalized features.
- **Profile Management** (`profile.php`, `profileEdit.php`, `profileUser.php`, `profileEditUser.php`):
  - Users can view and edit their profiles.
- **Products** (`products.php`):
  - Displays available phones for trading or purchase.
- **Shopping Cart** (`shoppingCart.php`, `shoppingCartDelete.php`):
  - Allows users to add phones to their cart and manage their selections.
- **Phone Reservation** (`reservePhone.php`, `reserveProduct.php`):
  - Lets users reserve phones for future purchase.
- **Forgot Password** (`forgot-password.php`):
  - Provides a way to reset forgotten passwords.

### Admin Features:
- **Admin Dashboard** (`adminDashboard.php`):
  - Centralized management of the website's functionalities.
- **User Management** (`userManagement.php`, `userCreate.php`, `userEdit.php`, `userLogss.php`):
  - Enables admins to manage user accounts and monitor user activities.
- **Inventory Management** (`inventory.php`, `inventoryCreate.php`, `inventoryEdit.php`, `inventoryDelete.php`):
  - Manage phone inventory, including adding, editing, and deleting products.
- **Reservation Management** (`adminReservation.php`, `adminReservationDelete.php`, `fetchingReservations.php`):
  - Handles user reservations and allows deletion if necessary.

### Additional Pages:
- **About Page** (`about.html`, `about1.php`):
  - Provides information about the website and its purpose.
- **Contact Page** (`contact.php`):
  - Enables users to reach out to the website's support team.

## Setup and Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/sellphones.git
   ```

2. Navigate to the project directory:
   ```bash
   cd sellphones
   ```

3. Set up the database:
   - Import the SQL file into your database management tool (e.g., phpMyAdmin).
   - Update the database credentials in `config.php`.

4. Start a local server (e.g., XAMPP or WAMP) and place the project folder in the server's root directory (e.g., `htdocs` for XAMPP).

5. Access the application in your browser:
   ```
   http://localhost/sellphones
   ```

## Technologies Used
- **Frontend:** HTML, CSS, JavaScript
- **Backend:** PHP
- **Database:** MySQL

## File Structure
Here is an overview of key files:
- **User Interface:**
  - `index.html`, `products.php`, `contact.php`
- **Authentication:**
  - `signup.php`, `login.php`, `forgot-password.php`
- **Admin Tools:**
  - `adminDashboard.php`, `userManagement.php`, `inventory.php`
- **Database Configuration:**
  - `config.php`
- **Logs:**
  - `db-log.txt`



