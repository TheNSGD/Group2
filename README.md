# INFO 3305 Web Application Development Sem 2, 2022/2023 Group Project, Section 2 - Group 2
<h3> Group Members</h3>
<table>
    <tr>
      <th>Name</th>
      <th>Matric Number</th>
    </tr>
    <tr>
      <td>Sharul Irfan bin Sharul Isram</td>
      <td>1921825</td>
    </tr>
    <tr>
      <td>Mazin Muhammed Anes</td>
      <td>2116025</td>
    </tr>
    <tr>
      <td>Muhammad Aiman bin Hisyam</td>
      <td>1917799</td>
    </tr>
    <tr>
      <td>Salmaan Mohammad Hanif Bhat</td>
      <td>2114727</td>
    </tr>
    <tr>
      <td>Muhammad Zafran bin Zamani</td>
      <td>2110893</td>
    </tr>
</table>

# Title
**Restaurant Inventory System**

# Introduction
A lot of restaurants and cafes nowadays have ways to manage their inventories. Some use the traditional method of keeping a book or ledger to keep track. Others may use a system like what our application is offerring

# Objective
The objective of the application is to allow restaurants and cafe owners to keep track of their inventories without all the downsides of a physical copy.

# Features and Functionalities 

1. User Authentication and Authorization:

Allow restaurant and cafe owners to register and create accounts.
Implement role-based access control to manage user permissions and restrict access to certain functionalities.

2. Dashboard:

Provide an intuitive dashboard that gives an overview of the inventory status.
Display key metrics such as total items, low stock items, and recent activity.

3. Inventory Management:

Allow users to add, edit, and delete items from their inventory.
Track information about each item, including name, description, quantity, category, price, and supplier details.
Implement search and filter options to quickly find specific items.
Set low stock alerts to notify users when the quantity of an item falls below a specified threshold.

4. Sales and Order Management:

Allow users to create and manage sales orders for customers.
Track order details, including customer information, order date, and payment status.
Deduct sold items from the inventory and update the quantity accordingly.

5. Responsive Design:

Develop a responsive user interface that works seamlessly on various devices, including desktops, tablets, and mobile phones.

# ER Diagram
**Restaurant Inventory System ER Diagram**

![erd webapp](erdrestinv3.png)

# Sequence Diagram
**Restaurant Inventory System Sequence Diagram**

![erd webapp](chatuml-diagram.svg)

# Code

![erd webapp](home.jpg)
This is the page that will first greet our visitors. If the visitor does not have a account, the screen will show below.

![erd webapp](create.jpg)
This page is where users create an account. They can fill in their details.

![erd webapp](welcome.jpg)
This page is what shows up when someone creates an account

![erd webapp](login.jpg)
If the user has an account, they can enter their details in the page.

![erd webapp](inventory.jpg)
In this image, we have the inventory menu. By pressing the add button it will transfer to the screen below.

![erd webapp](additem.jpg)
In this image, we can add the Item ID, Item Name, Quantity, Supplier Details and a Low Stock Alert. Clicking add will add the data into the table.

# Challenges Faced
Some challenges that we faced for the project is that errors with the XAMPP that we eventually resolved due to our lecturer's help and solutions on the Internet. We also faced some difficulties due to not knowing how to use PHP, Laravel and XAMPP but this got better over time as we began to learn more about each language.
