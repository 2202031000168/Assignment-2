# Assignment-2
HTMLCODE;
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Beauty App</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Beauty App</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#login">Login</a></li>
                <li><a href="#signup">Sign Up</a></li>
                <li><a href="#account">Account</a></li>
            </ul>
        </nav>
    </header>
    <section id="home" class="section">
        <h2>Welcome to Beauty App</h2>
        <p>Discover the latest beauty products and deals.</p>
        <a href="#buy" class="btn">Buy Now - 3 Products for $10.99</a>
    </section>
    <section id="login" class="section">
        <h2>Login</h2>
        <form>
            <label for="username">Username:</label>
            <input type="text" id="username" name="username">
            <label for="password">Password:</label>
            <input type="password" id="password" name="password">
            <button type="submit" class="btn">Login</button>
        </form>
    </section>
    <section id="signup" class="section">
        <h2>Sign Up</h2>
        <form>
            <label for="newUsername">Username:</label>
            <input type="text" id="newUsername" name="newUsername">
            <label for="newPassword">Password:</label>
            <input type="password" id="newPassword" name="newPassword">
            <button type="submit" class="btn">Sign Up</button>
        </form>
    </section>
    <section id="buy" class="section">
        <h2>Buy Now - 3 Products for $10.99</h2>
        <p>Select any three products from our collection.</p>
        <!-- Product selection will go here -->
        <a href="#payment" class="btn">Proceed to Payment</a>
    </section>
    <section id="account" class="section">
        <h2>Account</h2>
        <p>Manage your account information here.</p>
        <!-- Account management options will go here -->
    </section>
    <footer>
        <p>&copy; 2024 Beauty App. All rights reserved.</p>
    </footer>
</body>
</html>
CSS CODE:
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #f7f7f7;
    padding: 20px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

nav ul {
    list-style-type: none;
    padding: 0;
    margin: 0;
}

nav ul li {
    display: inline;
    margin-right: 20px;
}

nav ul li a {
    text-decoration: none;
    color: #333;
}

.section {
    padding: 50px 20px;
    text-align: center;
}

.btn {
    background-color: #ff7f50;
    color: #fff;
    padding: 10px 20px;
    border-radius: 5px;
    text-decoration: none;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 20px;
}
