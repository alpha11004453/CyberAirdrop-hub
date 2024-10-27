<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cybernetic Links</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
            color: #fff;
            background: linear-gradient(135deg, #0f0c29, #302b63, #24243e);
            background-size: cover;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            overflow: hidden;
        }
        
        .container {
            text-align: center;
            max-width: 500px;
        }
        
        h1 {
            font-size: 2.5em;
            text-transform: uppercase;
            color: #00ffbf;
            text-shadow: 0 0 10px #00ffbf, 0 0 20px #00ffbf;
            margin-bottom: 20px;
        }

        .button-container {
            display: flex;
            flex-direction: column;
            gap: 15px;
        }

        .cyber-button {
            text-decoration: none;
            color: #00e5ff;
            font-size: 1.2em;
            font-weight: bold;
            padding: 15px;
            border: 2px solid #00e5ff;
            border-radius: 10px;
            background: transparent;
            transition: all 0.3s;
            position: relative;
            overflow: hidden;
        }

        .cyber-button:hover {
            background: #00e5ff;
            color: #111;
            box-shadow: 0 0 10px #00e5ff, 0 0 20px #00e5ff;
        }

        .cyber-button::before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(0, 229, 255, 0.2), transparent);
            transition: 0.6s;
        }

        .cyber-button:hover::before {
            left: 100%;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Abdulwehab Jemal</h1>
        <div class="button-container">
            <a href="https://testnet.humanity.org/login?ref=dune2" class="cyber-button">Humanity Login</a>
            <a href="https://app.gradient.network/signup?code=NUKI0P" class="cyber-button">Gradient Network Signup</a>
            <a href="https://t.me/Tomarket_ai_bot/app?startapp=0002t8Ek" class="cyber-button">ToMarket Bot</a>
            <a href="https://app.nodepay.ai/register?ref=IPbXxRdYeghzDhT" class="cyber-button">NodePay Register</a>
        </div>
    </div>
</body>
</html>
