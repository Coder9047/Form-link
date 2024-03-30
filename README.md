
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Order Form</title>
</head>
<body>

<h2>Order Form</h2>

<form id="orderForm">
  <label for="orderID">Order ID:</label><br>
  <input type="text" id="orderID" name="orderID"><br>
  
  <label for="customerID">Customer ID:</label><br>
  <input type="text" id="customerID" name="customerID"><br>
  
  <label for="gender">Gender:</label><br>
  <input type="radio" id="male" name="gender" value="Male">
  <label for="male">Male</label>
  <input type="radio" id="female" name="gender" value="Female">
  <label for="female">Female</label><br>
  
  <label for="date">Date:</label><br>
  <input type="date" id="date" name="date"><br>
  
  <label for="age">Age:</label><br>
  <input type="number" id="age" name="age" min="0"><br>
  
  <label for="quantity">Quantity:</label><br>
  <input type="number" id="quantity" name="quantity" min="1"><br>
  
  <label for="currency">Currency:</label><br>
  <select id="currency" name="currency">
    <option value="USD">USD</option>
    <option value="EUR">EUR</option>
    <option value="GBP">GBP</option>
  </select><br>
  
  <label for="amount">Amount:</label><br>
  <input type="number" id="amount" name="amount" min="0" step="0.01"><br>
  
  <label for="channel">Channel:</label><br>
  <select id="channel" name="channel">
    <option value="Online">Online</option>
    <option value="In-store">In-store</option>
    <option value="Phone">Phone</option>
  </select><br><br>
  
  <input type="submit" value="Submit">
</form>

</body
