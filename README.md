# EShop_Establish_solution
Web based E-Shop management system

In the open network environment, based on the browser/server application, buyers and sellers are not met for various business activities, realize consumer online shopping, online transactions between merchants and online electronic payment, as well as a variety of business activities, trading activities, a kind of financial activities and related comprehensive service activities of business model. So the design concept is built around this goal.

To solve the problem of merchants' costly software outsourcing, the proposed solution is for the government to provide a website construction plan. This would allow merchants to establish their own e-shop platform, customize their shopping mall and management system, and quickly establish their online shop with basic site information. The work is to design a system that enables the government to provide this solution to merchants in need.

# Objectives
* To study the different characteristics of the store or shop in real life and analyze what kind of features could be extracted and combined with a web system
* To establish an online platform for buyers to buy and administrators to manage, then they can interact with each other
* To provide different businesses during the pandemic a low-cost, efficient online mall establishing solution

# Tech Stack
The entire project is built using the **MVC** architecture and **Agile** methodology, allowing for efficient, flexible, and scalable development that can accommodate a wide range of user needs and requirements.
<img width="650" alt="image" src="https://user-images.githubusercontent.com/94055197/226950653-4c89b552-e982-43f0-8b5b-83b7a7913f5a.png">

# System Modules
This is a list of modules for an eshop platform, divided into Admin and Buyer sides. The Admin side includes modules for managing products, transactions, accounts, and site settings. The Buyer side includes modules for shopping, managing orders, viewing information and tracking orders.

- Admin Side
    - **Product Management Module**
        - Manage categories and lists of products
        - View or reply to buyers' inquiries or comments on products
    - **Transaction Module**
        - View orders generated by customers and edit relevant information
        - View payment methods chosen by buyers
    - **Information Module**
        - Edit or post commodity articles based on classification for users to read
        - Edit article classification for users to view by different classes
    - **Accounts Module**
        - Manage buyer's and admin's account information
    - **Control Panel Module**
        - Edit site logo, web title, and more
        - Edit friendship links for buyers to extend reading
        - Edit advertisements
- Buyer(Customer) Side
    - **Eshop Platform(Index Module)**
        - View shop and purchase products
        - View product details and admin settings
    - **My Order(Products Management) Module**
        - Manage purchase of goods and adjust relevant details
    - **Information Module**
        - View articles posted by admin
        - View article class
    - **Myself(Account Management) Module**
        - Manage own account information
        - Edit user basic information such as address
    - **Shopping Cart Module**
        - Hold commodity user chooses
        - Add items to shopping cart and jump to payment screen
    - **Order Tracking Module**
        - Track progress of order using order reference number and phone number
        - Login customers can view order states at My Order page

# Use Case
Below is the use case diagram of the project
<img width="742" alt="image" src="https://user-images.githubusercontent.com/94055197/226957314-0a1c5ea4-522b-4b5c-8605-e387ce8f90cc.png">

# System Structure
This document describes the two divisions of the E-shop management system: foreground for buyers and background for admins. The foreground allows buyers to browse, search, and buy goods, while the background allows admins to manage information and goods, process orders, and manage registered users.

The general components
<img width="798" alt="image" src="https://user-images.githubusercontent.com/94055197/226957993-6119ad23-bea6-4893-929e-57de284ffe02.png">








