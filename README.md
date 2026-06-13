<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>BuyZone</title>

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial,sans-serif;
}

body{
background:#f5f5f5;
padding-bottom:70px;
}

.header{
background:#00A99D;
color:white;
padding:15px;
text-align:center;
}

.search{
padding:10px;
}

.search input{
width:100%;
padding:12px;
border:none;
border-radius:10px;
}

.banner{
background:#00A99D;
color:white;
margin:10px;
padding:20px;
border-radius:10px;
text-align:center;
}

.categories{
display:flex;
overflow-x:auto;
gap:10px;
padding:10px;
}

.category{
background:white;
padding:10px;
border-radius:10px;
min-width:100px;
text-align:center;
}

.products{
padding:10px;
}

.product{
background:white;
padding:10px;
border-radius:10px;
margin-bottom:10px;
}

.product img{
width:100%;
border-radius:10px;
}

.price{
color:#00A99D;
font-weight:bold;
}

.bottom-nav{
position:fixed;
bottom:0;
left:0;
right:0;
background:white;
display:flex;
justify-content:space-around;
padding:12px;
border-top:1px solid #ddd;
}
</style>
</head>

<body>

<div class="header">
<h2>BuyZone</h2>
</div>

<div class="search">
<input type="text" placeholder="Search Products">
</div>

<div class="banner">
🔥 Welcome to BuyZone
</div>

<div class="categories">
<div class="category">📱 Electronics</div>
<div class="category">👕 Fashion</div>
<div class="category">💄 Beauty</div>
<div class="category">🍔 Food</div>
</div>

<div class="products">

<div class="product">
<img src="https://via.placeholder.com/300">
<h3>Smart Watch</h3>
<p class="price">৳2500</p>
</div>

<div class="product">
<img src="https://via.placeholder.com/300">
<h3>Headphone</h3>
<p class="price">৳1500</p>
</div>

</div>

<div class="bottom-nav">
<span>🏠 Home</span>
<span>📦 Products</span>
<span>🎁 Promotion</span>
<span>👤 Profile</span>
</div>

</body>
</html>
