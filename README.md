# E-Commerce WebShop

Welcome to the E-Commerce WebShop repository! This project is a comprehensive web application designed to provide a seamless online shopping experience, similar to platforms like Shopee.

## Project Link

You can access the project [here](https://github.com/davidchau21/E-Commerce-WebShop).

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Setup](#setup)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Class Diagram](#class-diagram)

## Overview

E-Commerce WebShop is an e-commerce platform that enables users to browse, search, and purchase a wide range of products. This application offers a user-friendly interface and ensures a secure and efficient shopping experience.

## Features

- **User Authentication**: Secure registration and login functionality.
- **Product Browsing**: Browse through a variety of product categories.
- **Search Functionality**: Search for products by name or category.
- **Product Details**: View detailed information about each product.
- **Shopping Cart**: Add products to the cart and manage selections.
- **Checkout Process**: Smooth checkout process with integrated payment systems.
- **Order Management**: Users can view and manage their orders.
- **Vendor Management**: Vendors can list and manage their products.

## Tech Stack

- **Backend**: Java, Spring MVC
- **Frontend**: JSP (JavaServer Pages)
- **Database**: MySQL
- **Build Tool**: Maven
- **Server**: Apache Tomcat

## Setup

Follow these steps to set up the project locally:

1. **Clone the repository**
    ```bash
    git clone https://github.com/davidchau21/E-Commerce-WebShop.git
    ```

2. **Navigate to the project directory**
    ```bash
    cd E-Commerce-WebShop
    ```

3. **Configure the database**
    - Ensure SQL Server is installed and running.
    - Create a database named `e_commerce_webshop`.
    - Update the `application.properties` file in the `src/main/resources` directory with your SQL Server credentials.

4. **Build the project**
    ```bash
    mvn clean install
    ```

5. **Deploy on Apache Tomcat Server**
    - Download and install [Apache Tomcat](https://tomcat.apache.org/).
    - Copy the generated WAR file from the `target` directory to the `webapps` directory of your Tomcat installation.
    - Start the Tomcat server.

## Usage

Once installed, you can access the application in your web browser at `http://localhost:8080/`. From there, you can register an account, browse products, add them to your cart, and proceed to checkout.

## Screenshots

Here are some screenshots of the web application:

### Home Page
![Home Page](path_to_home_page_screenshot)

### Product Page
![Product Page](path_to_product_page_screenshot)

### Shopping Cart
![Shopping Cart](path_to_shopping_cart_screenshot)


