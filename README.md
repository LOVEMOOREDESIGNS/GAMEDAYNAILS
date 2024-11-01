# GAMEDAYNAILS
SHOW YOUR TEAM SPIRIT- PERFECT NAILS FOR GAME DAY
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Order Form</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }
        label {
            display: block;
            margin-top: 10px;
        }
        input, select {
            margin-top: 5px;
            width: 100%;
            max-width: 300px;
        }
        button {
            margin-top: 20px;
            padding: 10px 15px;
            font-size: 16px;
        }
    </style>
</head>
<body>
    <h1>Order Form</h1>
    <form action="/submit" method="POST">
        <label for="team">Select Team/School:</label>
        <select id="team" name="team" required>
            <option value="">--Select Team/School--</option>
            <option value="High School 1">High School 1</option>
            <option value="High School 2">High School 2</option>
            <option value="High School 3">High School 3</option>
            <!-- Add more high schools as needed -->
        </select>

        <label for="sport">Select Sport:</label>
        <select id="sport" name="sport" required>
            <option value="">--Select Sport--</option>
            <option value="Football">Football</option>
            <option value="Baseball">Baseball</option>
            <option value="Volleyball">Volleyball</option>
            <!-- Add more sports as needed -->
        </select>

        <label for="playerNumber">Player Number:</label>
        <input type="number" id="playerNumber" name="playerNumber" min="0" required>

        <label>Bling Rhinestones (Upgrade +$10):</label>
        <select id="bling" name="bling" required>
            <option value="No Bling">No Bling</option>
            <option value="With Bling">With Bling (+$10)</option>
        </select>

        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required>

        <label for="address">Address:</label>
        <input type="text" id="address" name="address" required>

        <label for="orderDate">Order Date:</label>
        <input type="date" id="orderDate" name="orderDate" required>

        <label for="billingNumber">Billing Number:</label>
        <input type="text" id="billingNumber" name="billingNumber" required>

        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>

        <label for="nailSizing">Nail Sizing:</label>
        <select id="nailSizing" name="nailSizing" required>
            <option value="S">Small</option>
            <option value="M">Medium</option>
            <option value="L">Large</option>
            <option value="XL">Extra Large</option>
            <option value="Unsure">Unsure, please contact me for help</option>
        </select>

        <label for="nailLength">Nail Length (from natural nails):</label>
        <textarea id="nailLength" name="nailLength" rows="4" placeholder="Please describe how long you want the nails. You may also refer to the length chart." required></textarea>

        <button type="submit">Submit Order</button>
    </form>
</body>
</html>
