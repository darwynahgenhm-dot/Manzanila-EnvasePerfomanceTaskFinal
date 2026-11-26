<!DOCTYPE html>
<html> 
<head>
    <title>Our Website for Our Product</title>

    <style>
        body {
            background-color: lightpink; font-family: Arial; text-align: center;
        }

        h1 {
            color: white; background-color: deeppink; padding: 20px;
        }

        button {
            background-color: hotpink; color: white; border: none; padding:
            10px; margin: 5px; cursor: pointer;
        }

        .page {
            display: none; background-color: white; padding: 20px; margin: 20px;
        }

        home {
            display: block;
        }

        input, select {
            padding: 8px; margin: 5px;
        }
    </style>
</head>

<body>

    <h1>DONUT Eats Website!</h1>

    <button onclick="home()">Home</button> 
    <button onclick="menu()">Menu</button> <button onclick="contact()">Contact</button>
    <button onclick="settings()">Settings</button>

    <div id="home" class="page">
        <h2>Welcome to Our Shop!</h2> <p>Welcome to our product website!</p>
        <p>We offer affordable and delicious products.</p> <p>Thank you for
        visiting our website!</p>
    </div>

    <div id="menu" class="page">
        <h2>Our Menu</h2>

        <h3>Flavors</h3>
        <p>Strawberry</p>
        <p>Chocolate</p>
        <img src="https://images.unsplash.com/photo-1551024601-bec78aea704b?w=500" 
     alt="Donut">
        <p>Vanilla</p>
        <p>Mango</p>

        <h3>Prices and Sizes</h3> <p>Small - ₱25</p> <p>Medium - ₱40</p>
        <p>Large - ₱55</p>

        <h3>Available Stocks</h3> 
        <p>Small - 20 pieces</p>
        <p>Medium - 15
        <p><!DOCTYPE html>
<html> 
<head>
    <title>Our Product</title>

    <style>
        body {
            background-color: lightpink; font-family: Arial; text-align: center;
        }

        h1 {
            color: white; background-color: deeppink; padding: 20px;
        }

        button {
            background-color: hotpink; color: white; border: none; padding:
            10px; margin: 5px; cursor: pointer;
        }

        .page {
            display: none; background-color: white; padding: 20px; margin: 20px;
        }

        home {
            display: block;
        }

        input, select {
            padding: 8px; margin: 5px;
        }
    </style>
</head>

<body>

    <h1>DONUT Eats Website!</h1>

    <button onclick="home()">Home</button> <button
    onclick="menu()">Menu</button> <button onclick="contact()">Contact</button>
    <button onclick="settings()">Settings</button>

    <div id="home" class="page">
        <h2>Welcome to Our Shop!</h2> <p>Welcome to our product website!</p>
        <p>We offer affordable and delicious products.</p> <p>Thank you for
        visiting our website!</p>
    </div>

    <div id="menu" class="page">
        <h2>Our Menu</h2>

        <h3>Flavors</h3>
        <p>Strawberry</p>
        <p>Chocolate</p>
        <img src="https://images.unsplash.com/photo-1551024601-bec78aea704b?w=500" 
     alt="Donut">
        <p>Vanilla</p>
        <p>Mango</p>

        <h3>Prices and Sizes</h3>
        <p>Small - ₱25</p> 
        <p>Medium - ₱40</p>
        <p>Large - ₱55</p>

        <h3>Available Stocks</h3> 
        <p>Small - 20 pieces</p>
        <p>Medium - 15 pieces</p>
        <p>Large - 10 pieces</p>
    </div>

    <div id="contact" class="page">
        <h2>Order Here!</h2>

        <p>Enter your information to order.</p>

        <input type="text" id="name" placeholder="Your Name">
            
        <br>

        <select id="flavor">
            <option>Strawberry</option>
            <option>Chocolate</option>
            <option>Vanilla</option> 
            <option>Mango</option>
        </select>
        <br>

        <select id="size">
            <option>Small</option>
            <option>Medium</option>
            <option>Large</option>
        </select>
        <br>

        <input type="number" id="quantity" placeholder="Quantity"> <br>

        <button onclick="order()">Submit Order</button>
    </div>

    <div id="settings" class="page">
        <h2>Settings</h2> <p>Change the background color.</p>

        <button onclick="pink()">Pink</button>
        <button onclick="white()">White</button>
        <button onclick="purple()">Purple</button>
    </div>

    <script>

        function home() {
            hide(); document.getElementById("home").style.display = "block";
        }

        function menu() {
            hide(); document.getElementById("menu").style.display = "block";
        }

        function contact() {
            hide(); document.getElementById("contact").style.display = "block";
        }

        function settings() {
            hide(); document.getElementById("settings").style.display = "block";
        }

        function hide() {
            document.getElementById("home").style.display = "none";
            document.getElementById("menu").style.display = "none";
            document.getElementById("contact").style.display = "none";
            document.getElementById("settings").style.display = "none";
        }

        function order() {
            let name = document.getElementById("name").value;

            alert("Thank you " + name + "! Your order is received.");
        }

        function pink() {
            document.body.style.backgroundColor = "lightpink";
        }

        function white() {
            document.body.style.backgroundColor = "antiquewhite";
        }

        function purple() {
            document.body.style.backgroundColor = "plum";
        }

    </script>

</body>
</html>
images.unsplash.com

        <p>Large</p> - 10 pieces</p>
    </div>

    <div id="contact" class="page">
        <h2>Order Here!</h2>

        <p>Enter your information to order.</p>

        <input type="text" id="name" placeholder="Your Name">
            
        <br>

        <select id="flavor">
            <option>Strawberry</option>
            <option>Chocolate</option>
            <option>Vanilla</option> 
            <option>Mango</option>
        </select>
        <br>

        <select id="size">
            <option>Small</option>
            <option>Medium</option>
            <option>Large</option>
        </select>
        <br>

        <input type="number" id="quantity" placeholder="Quantity"> <br>

        <button onclick="order()">Submit Order</button>
    </div>

    <div id="settings" class="page">
        <h2>Settings</h2> <p>Change the background color.</p>

        <button onclick="pink()">Pink</button>
        <button onclick="white()">White</button>
        <button onclick="purple()">Purple</button>
    </div>

    <script>

        function home() {
            hide(); document.getElementById("home").style.display = "block";
        }

        function menu() {
            hide(); document.getElementById("menu").style.display = "block";
        }

        function contact() {
            hide(); document.getElementById("contact").style.display = "block";
        }

        function settings() {
            hide(); document.getElementById("settings").style.display = "block";
        }

        function hide() {
            document.getElementById("home").style.display = "none";
            document.getElementById("menu").style.display = "none";
            document.getElementById("contact").style.display = "none";
            document.getElementById("settings").style.display = "none";
        }

        function order() {
            let name = document.getElementById("name").value;

            alert("Thank you " + name + "! Your order is received.");
        }

        function pink() {
            document.body.style.backgroundColor = "lightpink";
        }

        function white() {
            document.body.style.backgroundColor = "antiquewhite";
        }

        function purple() {
            document.body.style.backgroundColor = "plum";
        }

    </script>

</body>
</html>

