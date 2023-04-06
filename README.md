# dog-cafe
dog cafe
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Dog Clothes</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Dog Clothes</h1>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Shop</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <h2>Welcome to our store!</h2>
        <p>We offer a wide range of stylish and comfortable clothes for your furry friend.</p>
        <div class="products">
            <h3>Our Products</h3>
            <ul>
                <li>
                    <img src="https://via.placeholder.com/150x150" alt="Dog T-Shirt">
                    <h4>Dog T-Shirt</h4>
                    <p>$20</p>
                </li>
                <li>
                    <img src="https://via.placeholder.com/150x150" alt="Dog Hoodie">
                    <h4>Dog Hoodie</h4>
                    <p>$30</p>
                </li>
                <li>
                    <img src="https://via.placeholder.com/150x150" alt="Dog Sweater">
                    <h4>Dog Sweater</h4>
                    <p>$25</p>
                </li>
            </ul>
        </div>
    </main>
    <footer>
        <p>Copyright © Dog Clothes</p>
    </footer>
</body>
</html>
CSS:

css
Copy code
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #333;
    color: #fff;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px;
}

nav ul {
    list-style: none;
    margin: 0;
    padding: 0;
}

nav li {
    display: inline-block;
    margin-right: 20px;
}

nav a {
    color: #fff;
    text-decoration: none;
    font-size: 18px;
}

main {
    max-width: 800px;
    margin: 0 auto;
    padding: 20px;
}

.products {
    margin-top: 40px;
}

.products h3 {
    font-size: 24px;
}

.products ul {
    list-style: none;
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: space-between;
}

.products li {
    flex-basis: 30%;
    text-align: center;
    margin-bottom: 20px;
}

.products img {
    display: block;
    margin: 0 auto;
}

.products h4 {
    margin-top: 10px;
    font-size: 20px;
}

.products p {
    margin-top: 10px;
    font-size: 18px;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 20px;
    
