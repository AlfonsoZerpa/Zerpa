<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Motorcycle Haven</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #000000;
            color: #fff;
            padding: 2rem 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            background-color: #444;
            padding: 0.5rem 1rem;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 1rem;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .search-bar {
            display: flex;
            align-items: center;
        }
        .search-bar input {
            padding: 0.5rem;
            border-radius: 4px;
            border: 1px solid #ccc;
        }
        .search-bar button {
            padding: 0.5rem;
            border: none;
            background-color: #333;
            color: #fff;
            border-radius: 4px;
            cursor: pointer;
            margin-left: 0.5rem;
        }
        .hero {
            text-align: center;
            padding: 4rem 2rem;
    background: url('./Pictures/Cruizador-Ducatin-Panigale-V4.jpg') no-repeat center center/cover;
    background-size: 100%;
    color: #fff;
        }
        
        .hero h1 {
            font-size: 3rem;
            margin: 0;
        }
        .hero p {
            font-size: 1.5rem;
        }
        .content {
            padding: 2rem;
            text-align: center;
            background: url('./Pictures/') no-repeat center center/cover;
            background-size: cover;
        }
        .content h2 {
            margin-bottom: 1rem;
        }
        .footer {
            background: url('footer-background.jpg') no-repeat center center/cover;
            color: #fff;
            text-align: center;
            padding: 1rem 0;
            margin-top: 2rem;
        }
        .login {
            text-align: right;
        }
        .login a {
            color: #fff;
            text-decoration: none;
            margin-left: 1rem;
            background-color: #333;
            padding: 0.5rem 1rem;
            border-radius: 4px;
        }
        .login a:hover {
            background-color: #555;
        }
    </style>
</head>
<body>
    <header>
        <h1>Motorcycle Haven</h1>
        <p>Your one-stop shop for the best motorcycles</p>
    </header>
    <nav>
        <div>
            <a href="#home">Home</a>
            <a href="inventory.html">Brands</a> <!-- Link to the Inventory page -->
            <a href="#about">About Us</a>
            <a href="#contact">Contact</a>
        </div>
        <div class="search-bar">
            <form action="/search" method="GET">
                <input type="text" name="query" placeholder="Search motorcycles...">
                <button type="submit">Search</button>
            </form>
        </div>
        <div class="login">
            <a href="/login">Login</a>
            <a href="/register">Register</a>
        </div>
    </nav>
    <section class="hero">
        <h1>Find Your Dream Ride</h1>
        <p>Explore our wide range of motorcycles</p>
    </section>
    <section class="content">
        <h2>Featured Motorcycles</h2>
        <p>Check out our latest collection of motorcycles, from cruisers to sport bikes.</p>
    </section>
    <footer class="footer">
        <p>&copy; 2025 Motorcycle Haven. All rights reserved.</p>
    </footer>
</body>
</html>
