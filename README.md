# Project-One-Website
Project ONE
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Little Italy Pizzeria</title>
</head>
<body style="font-family: Arial, sans-serif; background-color: white; text-align: center; margin: 0; padding: 20px;">

    <header>
        <h1 style="color: red;">Little Italy Pizzeria</h1>
    </header>

    <section id="menu">
        <h2 style="color: green;">Our Menu</h2>
        <div class="pizza" style="border: 2px solid black; padding: 10px; margin: 10px; display: inline-block;">
            <h3 style="color: red;">Margherita Pizza</h3>
            <p>Classic tomato, basil, and mozzarella.</p>
        </div>
        <div class="pizza" style="border: 2px solid black; padding: 10px; margin: 10px; display: inline-block;">
            <h3 style="color: red;">Pepperoni Pizza</h3>
            <p>Loaded with spicy pepperoni and cheese.</p>
        </div>
        <div class="pizza" style="border: 2px solid black; padding: 10px; margin: 10px; display: inline-block;">
            <h3 style="color: red;">Veggie Delight Pizza</h3>
            <p>Fresh bell peppers, olives, mushrooms, and onions.</p>
        </div>
    </section>

    <section id="story">
        <h2 style="color: green;">Our Story</h2>
        <p>Little Italy Pizzeria is a family-owned restaurant that has been serving authentic Italian pizzas for over three generations. Our recipes have been passed down, ensuring every slice brings the true flavors of Italy to your table.</p>
        <img src="https://assets.simpleviewinc.com/simpleview/image/fetch/c_limit,q_75,w_1200/https://assets.simpleviewinc.com/simpleview/image/upload/crm/eauclaire/Johnny-s-Pizza-Shop2-d930d3e25056a36_d930d4f1-5056-a36a-068ca787d55dd265.jpg" alt="Little Italy Pizzeria" style="width: 50%; margin-top: 10px;">
    </section>

    <section id="order">
        <h2 style="color: green;">Order Online</h2>
        <form style="margin-top: 20px;">
            <label for="name">Your Name:</label>
            <input type="text" id="name" required>

            <label for="pizza">Choose a Pizza:</label>
            <select id="pizza" required>
                <option>Margherita Pizza</option>
                <option>Pepperoni Pizza</option>
                <option>Veggie Delight Pizza</option>
            </select>

            <button type="submit" style="background-color: red; color: white; padding: 10px; border: none; cursor: pointer;">Place Order</button>
        </form>
    </section>

</body>
</html>
