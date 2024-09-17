# PRODIGY_FS_04

# Local Store E-commerce Platform

This project is a *Local Store E-commerce Platform* designed to help local businesses bring their products online. The platform allows customers to browse products, place orders, and make payments while providing store owners with a simple interface to manage inventory, orders, and customer details.

## Features

- *Product Catalog*: Browse products with detailed descriptions and pricing.
- *Cart and Checkout*: Add items to the cart and complete the checkout process.
- *Inventory Management*: Store owners can manage stock, add new products, and update listings.
- *Order Management*: View and manage customer orders, update order statuses, and track deliveries.
- *Payment Integration*: Secure payment handling for customer transactions.
- *User Authentication*: Secure login and registration for both customers and store owners.
- *Responsive Design*: Optimized for both desktop and mobile devices.

## Technologies Used

- *Ruby on Rails*: Backend framework to build the entire application.
- *HTML & CSS*: Frontend for creating user interfaces.
- *JavaScript*: Enhancing user experience with dynamic behavior.
- *SQLite3*: Default database for local development.
- *PostgreSQL*: For production deployment.
- *Devise*: Authentication system for users.

## Installation

1. Clone the repository:
   bash
   git clone https://github.com/yourusername/local-store-ecommerce.git
   
2. Navigate to the project directory:
   bash
   cd local-store-ecommerce
   
3. Install required gems:
   bash
   bundle install
   
4. Set up the database:
   bash
   rails db:create
   rails db:migrate
   
5. Start the Rails server:
   bash
   rails server
   

## Usage

1. Open your browser and visit http://localhost:3000/.
2. Register as a customer or store owner.
3. As a customer, browse through the product catalog, add items to the cart, and place an order.
4. As a store owner, manage product listings, update inventory, and track orders.

## Future Enhancements

- Add customer reviews and ratings for products.
- Introduce a product recommendation system based on user preferences.
- Support multiple local stores with individual admin access.
