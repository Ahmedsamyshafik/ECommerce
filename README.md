<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>E-Commerce Website</title>
</head>
<body>

<h1>E-Commerce Website</h1>
<p>This project is an e-commerce website built using the MVC architecture and N-Tier Architecture. The site has two main areas: Admin and Customer.</p>

<h2>Features</h2>

<h3>Customer Area</h3>
<ul>
    <li><strong>User Authentication:</strong>
        <p>Customers can register and log in using Scaffolding Identity.</p>
    </li>
    <li><strong>Product Browsing:</strong>
        <p>Customers can view all products and their details.</p>
    </li>
    <li><strong>Shopping Cart:</strong>
        <p>Customers can add products to the cart.</p>
    </li>
    <li><strong>Payment:</strong>
        <p>Customers can make payments using Stripe.</p>
    </li>
</ul>

<h3>Admin Area</h3>
<ul>
    <li><strong>Category Management:</strong>
        <p>Admins can add, edit, and delete product categories.</p>
    </li>
    <li><strong>Product Management:</strong>
        <p>Admins can add, edit, and delete products.</p>
    </li>
    <li><strong>User Management:</strong>
        <p>Admins can view all users and lock/unlock user accounts.</p>
    </li>
    <li><strong>Order Management:</strong>
        <p>Admins can view all orders and update their status.</p>
        <ul>
            <li>Orders can be processed, marked for shipping, canceled, or refunded.</li>
        </ul>
    </li>
</ul>

<h2>Architecture</h2>
<p>The project uses N-Tier Architecture, which includes the following layers:</p>
<ul>
    <li><strong>Presentation Layer:</strong> Handles the user interface and user interactions.</li>
    <li><strong>Business Logic Layer:</strong> Contains business rules and logic.</li>
    <li><strong>Data Access Layer:</strong> Manages data access and database operations.</li>
</ul>

<h2>Technologies Used</h2>
<ul>
    <li><strong>ASP.NET Core MVC:</strong> For building the web application.</li>
    <li><strong>Scaffolding Identity:</strong> For user authentication and authorization.</li>
    <li><strong>Stripe:</strong> For handling payments.</li>
    <li><strong>Entity Framework Core:</strong> For database operations.</li>
    <li><strong>SQL Server:</strong> For the database.</li>
</ul>

</body>
</html>
