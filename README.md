# 💎 Jewelify - Premium E-commerce Jewelry Platform

A sophisticated e-commerce platform dedicated to luxury jewelry shopping, featuring an elegant user interface and comprehensive admin management system.

## 🚀 Overview

Jewelify is a full-stack e-commerce solution designed specifically for jewelry retailers. It combines modern web technologies with intuitive design to deliver an exceptional online shopping experience for both customers and administrators.

## ✨ Features

### Customer Features

- **Product Catalog**: Browse extensive collections of rings, necklaces, earrings, bracelets, and more
- **Shopping Cart**: Seamless cart management with real-time updates
- **User Authentication**: Secure login and registration system
- **Product Reviews**: Customer feedback and testimonials
- **Responsive Design**: Optimized for all devices

### Admin Features

- **Inventory Management**: Add, edit, and remove products
- **Order Processing**: Track and manage customer orders
- **User Management**: Oversee customer accounts
- **Analytics Dashboard**: Sales reports and insights

## 🛠️ Technology Stack

### Frontend

- **HTML5**: Semantic markup and structure
- **CSS3**: Advanced styling with Flexbox, Grid, and animations
- **Bootstrap**: Responsive layouts for a polished UI
- **JavaScript**: Dynamic interactivity and real-time updates
- **IonIcons**: Custom icons for enhanced visual appeal

### Backend

- **PHP**: Server-side processing for dynamic content and user management
- **MySQL**: Reliable database for product and user data

## 📁 Project Structure

```
Jewelify-Ecommerce/
├── admin/                    # Admin panel and management
│   ├── ecommerce.sql        # Database schema
│   └── admin/               # Admin interface files
├── web/                     # Main web application
│   ├── shopping_cart1.sql   # Shopping cart database
│   └── jewelfinal/          # Frontend application
│       ├── Home Page/       # Landing page
│       ├── Cart/           # Shopping cart functionality
│       ├── Rings/          # Ring collections
│       ├── Necklace/       # Necklace collections
│       ├── Earrings/       # Earring collections
│       ├── Bracelet/       # Bracelet collections
│       ├── Reviews/        # Customer reviews
│       └── Testimonials/   # Customer testimonials
├── LICENSE                  # Apache 2.0 License
└── README.md               # Project documentation
```

## 🛠️ Installation Guide

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/SeneshFitzroy/Jewelify-Ecommerce.git
   cd Jewelify-Ecommerce
   ```

2. **Set Up Database**:

   - Import the database schema into MySQL:
     ```bash
     mysql -u root -p ecommerce < admin/ecommerce.sql
     mysql -u root -p ecommerce < web/shopping_cart1.sql
     ```

3. **Configure Database Connection**:

   - Update database credentials in configuration files
   - Ensure MySQL server is running

4. **Deploy to Server**:

   - Place the project in a PHP-enabled server directory (e.g., XAMPP's `htdocs/`)
   - Ensure proper file permissions

5. **Access the Application**:
   - Frontend: `http://localhost/Jewelify-Ecommerce/web/jewelfinal/Home Page/`
   - Admin Panel: `http://localhost/Jewelify-Ecommerce/admin/`

## 🎯 Usage

### For Customers

1. Browse the jewelry collections
2. Add items to your cart
3. Register or login to your account
4. Complete the checkout process
5. Leave reviews and testimonials

### For Administrators

1. Access the admin panel
2. Manage product inventory
3. Process customer orders
4. Monitor site analytics
5. Manage user accounts

## 👥 Contributors

We would like to thank the following contributors who made this project possible:

- **Dulni Mahara**
- **Sinethmi Kariyawasam**
- **Anumi Samaranayaka**
- **Senumi Samaranayaka**
- **Daranee Denipitiya**

## 🔒 License

This project is licensed under the Apache License, Version 2.0. See the [LICENSE](LICENSE) file for details.

## 🌟 Acknowledgments

- UI/UX inspired by modern e-commerce best practices
- Icons provided by IonIcons
- Responsive framework by Bootstrap

---

_Jewelify - Where elegance meets technology_ ✨
