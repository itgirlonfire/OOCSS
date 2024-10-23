index.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>OOCSS Example</title>
</head>
<body>
    <header class="header">
        <h1 class="header__title">OOCSS Example Page</h1>
    </header>
    
    <main class="main-content">
        <section class="card">
            <h2 class="card__title">Card Title</h2>
            <p class="card__description">This is a description of the card.</p>
            <button class="button button--primary">Primary Button</button>
            <button class="button button--secondary">Secondary Button</button>
        </section>

        <section class="card">
            <h2 class="card__title">Another Card Title</h2>
            <p class="card__description">Another description for a different card.</p>
            <button class="button button--primary">Primary Button</button>
        </section>
    </main>
</body>
</html>

style.css
/* Base Styles */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

.header {
    background-color: #4CAF50;
    color: white;
    text-align: center;
    padding: 20px;
}

.main-content {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    padding: 20px;
}

/* Card Component */
.card {
    background-color: white;
    border: 1px solid #ddd;
    border-radius: 4px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    margin: 10px;
    padding: 20px;
    width: 300px;
}

.card__title {
    font-size: 1.5em;
    margin: 0 0 10px;
}

.card__description {
    font-size: 1em;
    margin: 0 0 20px;
}

/* Button Component */
.button {
    display: inline-block;
    padding: 10px 15px;
    margin: 5px;
    border: none;
    border-radius: 3px;
    cursor: pointer;
    text-align: center;
    text-decoration: none;
}

.button--primary {
    background-color: #4CAF50;
    color: white;
}

.button--secondary {
    background-color: #ddd;
    color: #333;
}
