<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Egg Order Form</title>
</head>
<body>
    <h2>Order Your Fresh Eggs</h2>
    <form action="submit_order.php" method="post">    
        <!-- Select Chicken Type -->
        <label for="chickenType">Select Chicken Type:</label>
        <select id="chickenType" name="chickenType" required>
            <option value="rhode_island_red">Rhode Island Red</option>
            <option value="leghorn">Leghorn</option>
            <option value="plymouth_rock">Plymouth Rock</option>
        </select>
        <br><br>
        
        <!-- Select Number of Eggs -->
        <label for="numEggs">Number of Eggs:</label>
        <input type="number" id="numEggs" name="numEggs" min="1" required>
        <br><br>
        
        <!-- Select Pickup Date -->
        <label for="pickupDate">Pickup Date:</label>
        <input type="date" id="pickupDate" name="pickupDate" required>
        <br><br>
        
        <!-- Select Payment Method -->
        <label for="paymentMethod">Payment Method:</label>
        <select id="paymentMethod" name="paymentMethod" required>
            <option value="cash">Cash</option>
            <option value="credit_card">Credit Card</option>
            <option value="paypal">PayPal</option>
        </select>
        <br><br>
        
        <!-- Submit Form -->
        <button type="submit">Place Order</button>
    </form>
</body>
</html>
