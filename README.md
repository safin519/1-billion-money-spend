‎<!DOCTYPE html>
‎<html lang="en">
‎<head>DOCTYPE
‎  <meta charset="UTF-8">
‎  <title>Spend Billionaire's Money</title>
‎
‎  <!-- AdSense Auto Ads -->
‎  <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"
‎          data-ad-client="ca-pub-5517607129961668" crossorigin="anonymous"></script>
‎
‎  <style>
‎    body {
‎      font-family: Arial, sans-serif;
‎      background: #f4f4f4;
‎      margin: 0;
‎      padding: 0;
‎    }
‎
‎    .container {
‎      display: flex;
‎      flex-direction: row;
‎      padding: 20px;
‎      justify-content: center;
‎    }
‎
‎    .main-content {
‎      flex: 2;
‎      padding: 20px;
‎    }
‎
‎    .sidebar {
‎      flex: 1;
‎      padding: 20px;
‎    }
‎
‎    h1 {
‎      color: #333;
‎      text-align: center;
‎    }
‎
‎    #money {
‎      font-size: 28px;
‎      margin-bottom: 20px;
‎      text-align: center;
‎    }
‎
‎    .item {
‎      display: flex;
‎      justify-content: space-between;
‎      background: white;
‎      padding: 10px;
‎      margin: 10px auto;
‎      width: 90%;
‎      max-width: 500px;
‎      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
‎    }
‎
‎    .item button {
‎      padding: 5px 10px;
‎      background-color: #27ae60;
‎      border: none;
‎      color: white;
‎      cursor: pointer;
‎      font-weight: bold;
‎    }
‎
‎    .item button:disabled {
‎      background-color: gray;
‎    }
‎  </style>
‎</head>
‎<body>
‎
‎<h1>Spend a Billionaire's Money!</h1>
‎
‎<div class="container">
‎  <div class="main-content">
‎    <div id="money">$1,000,000,000</div>
‎
‎    <div class="item">
‎      <div>🍔 Burger - $5</div>
‎      <button onclick="buyItem(5)">Buy</button>
‎    </div>
‎    <div class="item">
‎      <div>📱 iPhone - $999</div>
‎      <button onclick="buyItem(999)">Buy</button>
‎    </div>
‎    <div class="item">
‎      <div>🚗 Tesla - $50,000</div>
‎      <button onclick="buyItem(50000)">Buy</button>
‎    </div>
‎    <div class="item">
‎      <div>🏠 House - $300,000</div>
‎      <button onclick="buyItem(300000)">Buy</button>
‎    </div>
‎    <div class="item">
‎      <div>🛥️ Yacht - $10,000,000</div>
‎      <button onclick="buyItem(10000000)">Buy</button>
‎    </div>
‎    <div class="item">
‎      <div>🚀 Private Jet - $50,000,000</div>
‎      <button onclick="buyItem(50000000)">Buy</button>
‎    </div>
‎  </div>
‎
‎  <div class="sidebar">
‎    <!-- Right Sidebar Ad -->
‎    <ins class="adsbygoogle"
‎         style="display:block"
‎         data-ad-client="ca-pub-5517607129961668"
‎         data-ad-slot="1234567891"
‎         data-ad-format="vertical"
‎         data-full-width-responsive="true"></ins>
‎    <script>
‎         (adsbygoogle = window.adsbygoogle || []).push({});
‎    </script>
‎  </div>
‎</div>
‎
‎<script>
‎  let money = 1000000000;
‎  const moneyEl = document.getElementById('money');
‎
‎  function formatMoney(amount) {
‎    return '$' + amount.toLocaleString();
‎  }
‎
‎  function buyItem(cost) {
‎    if (money >= cost) {
‎      money -= cost;
‎      moneyEl.textContent = formatMoney(money);
‎    } else 
‎alert("Not enough money!");
‎    }
‎  }
‎</script>
‎
‎</body>
‎</html>
‎
