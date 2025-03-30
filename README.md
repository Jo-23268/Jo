<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Roue de la Fortune</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1>Roue de la Fortune</h1>
    
    <div class="game-container">
        <canvas id="wheelCanvas"></canvas>
        <button id="spinButton">Tourner la Roue</button>
    </div>

    <div class="bet-section">
        <label for="betAmount">Mise (€) :</label>
        <input type="number" id="betAmount" min="1" value="10">
        <button id="placeBet">Placer la Mise</button>
    </div>

    <div id="result"></div>

    <script src="script.js"></script>
</body>
</html>
<button id="payButton">Payer avec Stripe</button>
<script src="https://js.stripe.com/v3/"></script>
<script src="payment.js"></script>
