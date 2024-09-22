#restaurant menu
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Restaurant Menu</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        <h1>Restaurant Menu</h1>
    </header>

    <!-- Navigation for Categories -->
    <nav>
        <ul>
            <li><a href="#" onclick="filterMenu('all')">All</a></li>
            <li><a href="#" onclick="filterMenu('starters')">Starters</a></li>
            <li><a href="#" onclick="filterMenu('mains')">Main Courses</a></li>
            <li><a href="#" onclick="filterMenu('desserts')">Desserts</a></li>
        </ul>
    </nav>

    <!-- Menu Items -->
    <div class="menu-container">

        <div class="menu-item starters">
            <h3>Tomato Soup</h3>
            <p>A delicious starter made with fresh tomatoes.</p>
            <span class="price">$5.99</span>
        </div>

        <div class="menu-item mains">
            <h3>Grilled Chicken</h3>
            <p>Succulent grilled chicken served with veggies.</p>
            <span class="price">$12.99</span>
        </div>

        <div class="menu-item mains">
            <h3>Pasta Carbonara</h3>
            <p>Classic Italian pasta with a creamy sauce.</p>
            <span class="price">$10.99</span>
        </div>

        <div class="menu-item desserts">
            <h3>Chocolate Cake</h3>
            <p>Rich and moist chocolate cake with a side of ice cream.</p>
            <span class="price">$6.99</span>
        </div>

        <div class="menu-item desserts">
            <h3>Cheesecake</h3>
            <p>Light and creamy cheesecake with berry topping.</p>
            <span class="price">$7.49</span>
        </div>

        <div class="menu-item starters">
            <h3>Bruschetta</h3>
            <p>Toasted bread topped with fresh tomatoes and basil.</p>
            <span class="price">$4.99</span>
        </div>

    </div>

    <script src="script.js"></script>

</body>
</html>
