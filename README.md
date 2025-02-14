# macdo


<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Luxury Burger</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #111;
            color: white;
            text-align: center;
        }
        header {
            background: black;
            padding: 20px;
        }
        h1 {
            color: gold;
            font-size: 3em;
        }
        .menu {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 20px;
            padding: 40px;
        }
        .menu-item {
            background: #222;
            padding: 20px;
            border-radius: 10px;
            width: 300px;
        }
        .menu-item img {
            width: 100%;
            border-radius: 10px;
        }
        .order-btn {
            background: gold;
            color: black;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
            font-size: 1.2em;
            margin-top: 10px;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Luxury Burger</h1>
    </header>
    <section class="menu">
        <div class="menu-item">
            <img src="burger1.jpg" alt="Burger Deluxe">
            <h2>Burger Deluxe</h2>
            <p>Steak Wagyu, truffe, fromage affiné.</p>
            <button class="order-btn">Commander</button>
        </div>
        <div class="menu-item">
                <img src="burger2.jpg" alt="Burger Royal">
                <h2>Burger Royal</h2>
                <p>Poulet bio, sauce maison, caviar.</p>
            <button class="order-btn">Commander</button>
        </div>
    </section>
</body>
</html>

