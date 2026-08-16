# currency-exchange-calculator
currency exchange calculator
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Currency Exchange Calculator</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

    <div class="calculator">
        <h1>Currency Exchange Calculator</h1>

        <label for="amount">Amount</label>
        <input type="number" id="amount" placeholder="Enter amount">

        <label for="fromCurrency">From</label>
        <select id="fromCurrency">
            <option value="GBP">GBP - British Pound</option>
            <option value="USD">USD - US Dollar</option>
            <option value="EUR">EUR - Euro</option>
            <option value="JPY">JPY - Japanese Yen</option>
        </select>

        <label for="toCurrency">To</label>
        <select id="toCurrency">
            <option value="USD">USD - US Dollar</option>
            <option value="GBP">GBP - British Pound</option>
            <option value="EUR">EUR - Euro</option>
            <option value="JPY">JPY - Japanese Yen</option>
        </select>

        <button onclick="convertCurrency()">Convert</button>

        <div id="result"></div>
    </div>

    <script src="script.js"></script>

</body>
</html>