# 🍔 Food Delivery Management System

## 📌 Project Overview

The **Food Delivery Management System (FDMS)** is a mini-project designed to demonstrate the practical implementation of database management concepts through a food delivery platform.

The project consists of a relational database design using MySQL and an interactive web-based Activity Feed developed using HTML, CSS and JavaScript.

The Activity Feed provides a centralized interface to monitor food orders, payments, delivery activities and customer reviews. It also allows users to place new orders, cancel eligible orders and track different activities through a simple and user-friendly interface.

## 🎯 Objectives

- To design a relational database for a food delivery platform.
- To understand entities, attributes, relationships and keys.
- To create an Entity Relationship (ER) diagram.
- To convert the ER model into relational tables.
- To implement database concepts using MySQL.
- To develop an interactive Food Delivery Activity Feed.
- To demonstrate order placement and cancellation functionality.
- To display order, payment, delivery and review activities.
- To implement searching, filtering and sorting functionalities.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Structure of the Activity Feed |
| CSS3 | Styling, layout and responsive design |
| JavaScript | Interactive functionality and dynamic updates |
| MySQL | Relational database management |
| SQL | Database creation and query execution |
| MySQL Workbench | Database design and execution |

## 🗂️ Database Structure

The project consists of the following 10 tables:

| Sr. No. | Table Name | Description |
|---|---|---|
| 1 | RESTAURANT | Stores restaurant details |
| 2 | CUSTOMER | Stores customer information |
| 3 | MENU_ITEM | Stores food items and prices |
| 4 | ORDERS | Stores customer order details |
| 5 | ORDER_ITEM | Stores items included in each order |
| 6 | DELIVERY_PARTNER | Stores delivery partner information |
| 7 | DELIVERY | Stores delivery assignment and status |
| 8 | PAYMENT | Stores payment details |
| 9 | REVIEW | Stores customer reviews and ratings |
| 10 | COUPON | Stores discount coupon information |

## ✨ Key Features

### 1. Interactive Dashboard
- Displays the total number of orders.
- Shows the number of delivered orders.
- Calculates delivered revenue.
- Displays cancelled orders.
- Shows pending payments.
- Calculates the average customer rating.

### 2. Order Management
- Place new food orders.
- Select customers and restaurants.
- Display menu items according to the selected restaurant.
- Select food quantities.
- Automatically calculate the total order amount.
- Enter delivery addresses.
- Select payment methods such as UPI, Card, Wallet and Cash.

### 3. Order Cancellation
- Cancel orders with eligible statuses such as Placed and Preparing.
- Display a confirmation dialog before cancellation.
- Automatically update the order status.
- Update the associated payment status.
- Mark previously paid orders as Refunded when cancelled.

### 4. Activity Feed
Displays different activities in chronological order, including:

- Order placement.
- Payment records.
- Delivery partner assignment.
- Order pickup.
- Successful delivery.
- Customer reviews and ratings.

### 5. Search and Filter
- Search activities by customer name.
- Search by restaurant name.
- Search by food item.
- Search by delivery partner.
- Filter activities into Orders, Payments, Deliveries and Reviews.
- View all activities together.

### 6. Sorting
- Display activities from newest to oldest.
- Switch to oldest-to-newest order.

### 7. User Interface
- Clean and user-friendly interface.
- Responsive layout.
- Light and dark theme support.
- Status indicators for delivered, pending, cancelled and other activities.
- Popup dialogs for placing and cancelling orders.

## 💻 SQL Operations Performed

The database project demonstrates 10 SQL test queries covering:

1. INNER JOIN – Displaying menu items with restaurant names.
2. WHERE Clause – Finding orders delivered to Pune.
3. LEFT JOIN and GROUP BY – Counting menu items in each restaurant.
4. Nested Subquery – Finding orders above the average order amount.
5. Aggregate Functions – Generating sales summaries.
6. AND Condition – Finding delivered orders after a specified date.
7. WHERE Condition – Finding menu items above ₹100.
8. CONCAT Function – Displaying customer names and contact details.
9. GROUP BY – Counting orders according to their status.
10. Multiple Conditions – Finding orders above ₹300 with Pune delivery addresses.

## ⚙️ How to Run the Project

### Step 1: Database Setup
1. Install MySQL Server.
2. Open MySQL Workbench.
3. Create the `food_delivery` database.
4. Create the required tables.
5. Insert the sample records.
6. Execute the SQL queries.

### Step 2: Run the Activity Feed
1. Open the provided HTML file.
2. Open it using a web browser such as Google Chrome.
3. The Food Delivery Activity Feed dashboard will appear.
4. Use the available options to place orders, cancel eligible orders, search activities and apply filters.

**Note:** The currently provided Activity Feed uses JavaScript arrays and sample data within the HTML file. Its order and payment updates are maintained in browser memory and reset when the page is reloaded. It is not yet connected directly to the MySQL database.

##  Screenshots
<img width="1900" height="1018" alt="Screenshot 2026-11-02 201124" src="https://github.com/user-attachments/assets/36f8d2d5-7a90-4184-a245-8cf31cc8b24e" />

<img width="1411" height="893" alt="Screenshot 2026-11-02 201147" src="https://github.com/user-attachments/assets/eb03fb54-b535-4325-9dac-b6cce7fc06a3" />

<img width="1520" height="1022" alt="Screenshot 2026-11-02 201226" src="https://github.com/user-attachments/assets/716c6876-1a69-46a0-9061-4ccb9231cae2" />

<img width="1356" height="792" alt="Screenshot 2026-11-02 201255" src="https://github.com/user-attachments/assets/461c3b0e-0c1c-4bc7-875a-eef3d95c3905" />

## 🚀 Future Enhancements

- Connect the Activity Feed directly to the MySQL database using a backend.
- Implement real-time order tracking.
- Add customer and restaurant login functionality.
- Integrate online payment gateways.
- Store new orders permanently in the database.
- Add automated notifications for order status changes.
- Implement advanced restaurant analytics.
- Add refund and coupon management.

