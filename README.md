# Cuban Bakery Management System Web App

## Overview

The Management System Application is a three-tier web application designed to streamline operations in a bakery. This application will provide functionalities for managing inventory, orders, and revenue, all while maintaining an intuitive user interface.

## Project Structure


- Front-end: The user interface is built using HTML and CSS, providing a clean and responsive layout that enhances user experience. JavaScript enhances interactivity functionality to manage products and orders. Bootstrap provides pre-built components and grid systems that enhance the layout and styling of the application.


- Back-end: The code begins by importing necessary libraries and modules. Several API end points are defined for various functionalities. Get UOM's retrieves unit of measurement (UOM) data from the database and returns it as JSON, allowing for client-side display. Get Products Fetches all products from the database and serves them to the frontend. Insert Product handles product addition by accepting data from the frontend, inserting it into the database, and returning the new product ID. Delete Product deletes a specified product and returns the ID of the deleted product.


- Database: A MySQL database is employed to manage data related to customers, products, and orders. 
Customers: Stores customer information, including IDs, names, and order details.
Products: Contains product details such as product IDs, names, prices, and available quantities.
Orders: Records order information, linking customers to their respective orders, including order IDs, product IDs, quantities, and total prices.


## Orders
![](orders.PNG)

## New Orders
![](neworder.PNG)

## Products Available
![](products.PNG)


I hope you enjoy this web app & happy baking! 🍞🥐
