# Tharun Musical Palace - E-commerce Website

A full-stack e-commerce website for a music store featuring instrument listings, shopping cart functionality, and checkout system.

## Overview

Tharun Musical Palace is an online music store that offers various musical instruments and accessories. This project includes a responsive front-end interface built with HTML, CSS, and JavaScript, along with a MySQL database backend for product management and order processing.It was created within a 1-hour timeframe using simple resources and serves as a starting point that can be expanded upon.

## Features

- Responsive design that works on desktop and mobile devices
- Product browsing and filtering capabilities
- Shopping cart functionality
- User account management
- Secure checkout process
- Admin panel for inventory management

## Tech Stack

### Front-End
- **HTML5** - Structure and content
- **CSS3** - Styling and responsive design
- **JavaScript** - Interactive elements and client-side validation

### Back-End
- **MySQL** - Database for storing product info, user accounts, and orders
- **XAMPP** - Local development environment with Apache and MySQL

## Database Structure

The MySQL database includes the following main tables:
- `products` - Stores product information (name, description, price, etc.)
- `users` - Customer accounts and authentication details
- `orders` - Order information and status
- `order_items` - Individual items in each order
- `categories` - Product categorization

## Setup Instructions

### Prerequisites
- XAMPP installed on your system (includes Apache and MySQL)
- Web browser
- Git (for cloning the repository)

### Installation Steps

1. **Clone the repository**
   ```
   git clone https://github.com/yourusername/tharun-musical-palace.git
   cd tharun-musical-palace
   ```

2. **Set up the local server**
   - Start XAMPP Control Panel
   - Start Apache and MySQL services
   - Navigate to phpMyAdmin (http://localhost/phpmyadmin)
   - Create a new database named `music_store_db`
   - Import the database structure from `database/music_store_db.sql`

3. **Configure the database connection**
   - Open `config/db_connect.php`
   - Update the database credentials if needed:
     ```php
     $host = "localhost";
     $username = "root";  // default XAMPP username
     $password = "root";      // default XAMPP password
     $dbname = "music_store_db";
     ```

4. **Run the website**
   - Place the project files in XAMPP's htdocs directory
   - Access the website at http://localhost/tharun-musical-palace

## Project Structure

```
tharun-musical-palace/
│
├── css/                  # CSS stylesheets
│   ├── Home.css
│   ├── Product.css
│   └── ...
│
├── js/                   # JavaScript files
│   ├── cart.js
│   ├── checkout.js
│   └── ...
│
├── images/               # Image assets
│
├── database/             # Database scripts
│   └── music_store_db.sql
│
├── config/               # Configuration files
│   └── db_connect.php
│
├── Home.html             # Home page
├── Product page.html     # Products listing
├── About us.html         # About page
├── contact us.html       # Contact page
├── Cart.html             # Shopping cart
├── Checkout.html         # Checkout process
│
└── README.md             # Project documentation
```

## Current Implementation Status

- ✅ Front-end UI design complete
- ✅ Product listings and details
- ✅ Navigation and responsive design
- ⏳ Shopping cart functionality
- ⏳ User authentication
- ⏳ Database integration
- ⏳ Checkout process

## Future Enhancements

- User reviews and ratings
- Product search functionality
- Wishlist feature
- Email notifications
- Payment gateway integration

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

Tharun - [tharunk1915@gmail.com](mailto:tharunk1915@gmail.com)

Project Link: [https://github.com/yourusername/tharun-musical-palace](https://github.com/yourusername/tharun-musical-palace)