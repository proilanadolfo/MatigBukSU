# Ahava Ecommerce System

The File Type is MatigBukSU.zip 

Developer

                PROILAN ADOLFO - WEB DEVELOPER 
                JOVANIE TORREGOSA - WEB DEVELOPER
                DANICA PAHANGIN - RESEARCHER
                CHRISTIAN REY  ADOLFO- WEB DESIGNER 

## Overview
Ahava Ecommerce is a robust online shopping platform designed to streamline the buying and selling process. It features user-friendly interfaces for customers, riders, and administrators, supporting product management, order processing, voucher systems, and more.

## Features
- User registration and authentication
- Product catalog and categories
- Shopping cart and checkout
- Order management and order history
- Voucher and rewards system
- Admin dashboard for inventory and analytics
- Rider module for order delivery
- File uploads (e.g., product images, categories)
- Special offers and promotions

## Technical Requirements
- PHP 7.4 or higher
- MySQL 5.7 or higher
- Apache Web Server
- XAMPP (recommended for local development)

## Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/proilanadolfo/MatigBukSU.git
   ```

2. **Set up your database:**
   - Create a new MySQL database (e.g., `matigbuksu`)
   - Import the provided SQL files (e.g., `matigbuksu (1).sql`, `database.sql`, etc.)

3. **Configure your web server:**
   - Place the project folder in your web server's root directory (e.g., `htdocs` for XAMPP)
   - Ensure the web server has permission to access the files

4. **Configure database connection:**
   - Edit the configuration files in the `config/` or `Users/config/` directory to match your database credentials

5. **Install dependencies (if any):**
   - If using Composer, run `composer install` in the project root

## Usage
1. **Access the system in your browser:**
   - Local: `http://localhost/MatigBukSU`
   - Production: Your deployed domain

2. **Login or register:**
   - Users can register or log in to shop
   - Admins and riders have separate login modules

3. **Shop, manage, and deliver:**
   - Browse products, add to cart, checkout
   - Admins manage products, categories, orders, and analytics
   - Riders manage deliveries

## Project Structure
```
MatigBukSU/
├── Admin/                # Admin dashboard, inventory, analytics, settings
│   ├── JsA/
│   ├── Img/
│   ├── CssA/
│   └── ...
├── Users/                # User-facing modules and logic
│   ├── models/           # Handlers for orders, products, cart, etc.
│   ├── uploads/
│   ├── JsA/
│   ├── Js/
│   ├── includes/
│   ├── Img/
│   ├── Css/
│   ├── config/
│   ├── api/
│   ├── admin/
│   └── ...
├── Rider/                # Rider/delivery module
├── assets/               # Static assets (e.g., sounds)
├── uploads/              # Uploaded files (e.g., categories)
├── vendor/               # Composer dependencies (if any)
├── lib/                  # Libraries
├── Img/                  # Global images
├── config/               # Global configuration
├── Css/                  # Global CSS
├── tcpdf/                # PDF generation library
├── *.php                 # Main PHP scripts (Login.php, Orders.php, etc.)
├── *.sql                 # Database schema and seed files
└── README.md             # Project documentation
```

## Contributing
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m 'Add your feature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a Pull Request

## License
This project is licensed under the MIT License - see the LICENSE file for details

## Contact
Proilan Adolfo - proilanadolfo@gmail.com
Project Link: https://github.com/proilanadolfo/MatigBukSU 
