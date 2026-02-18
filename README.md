<!doctype html>
<html lang="sv">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>LUZARA</title>

<style>
body{
  margin:0;
  font-family:Arial, sans-serif;
  background:#0f0f0f;
  color:white;
}

header{
  display:flex;
  justify-content:space-between;
  align-items:center;
  padding:20px 40px;
  background:black;
  position:sticky;
  top:0;
}

header h1{
  margin:0;
  letter-spacing:4px;
  font-weight:900;
}

nav a{
  color:white;
  text-decoration:none;
  margin-left:25px;
  font-size:14px;
  opacity:0.8;
}

nav a:hover{
  opacity:1;
}

.hero{
  height:95vh;
  display:flex;
  flex-direction:column;
  justify-content:center;
  align-items:center;
  text-align:center;
  background:url('https://images.unsplash.com/photo-1520974735194-08f9c0d5b7b2?auto=format&fit=crop&w=1400&q=80') center/cover;
}

.hero h2{
  font-size:60px;
  margin:0;
  background:rgba(0,0,0,0.6);
  padding:10px 25px;
}

.hero p{
  margin-top:15px;
  background:rgba(0,0,0,0.6);
  padding:8px 20px;
  letter-spacing:2px;
}

.btn{
  margin-top:30px;
  padding:14px 35px;
  background:white;
  color:black;
  border:none;
  cursor:pointer;
  font-weight:bold;
  transition:0.3s;
}

.btn:hover{
  background:#ddd;
}

.products{
  padding:80px 60px;
  display:grid;
  grid-template-columns:repeat(auto-fit, minmax(280px,1fr));
  gap:40px;
}

.product{
  background:#1a1a1a;
  padding:20px;
  text-align:center;
  border-radius:15px;
  transition:0.4s;
}

.product:hover{
  transform:translateY(-10px);
}

.product img{
  width:100%;
  border-radius:15px;
}

.product h3{
  margin-top:15px;
}

footer{
  text-align:center;
  padding:50px;
  background:black;
  font-size:13px;
  opacity:0.6;
}
</style>
</head>

<body>

<header>
  <h1>LUZARA</h1>
  <nav>
    <a href="#">Hoodies</a>
    <a href="#">Tröjor</a>
    <a href="#">Kontakt</a>
  </nav>
</header>

<section class="hero">
  <h2>NY KOLLEKTION</h2>
  <p>Minimalism • Stil • Attityd</p>
  <button class="btn">Se kollektionen</button>
</section>

<section class="products">

  <div class="product">
    <img src="https://images.unsplash.com/photo-1521572163474-6864f9cf17ab?auto=format&fit=crop&w=800&q=80">
    <h3>Oversize Hoodie Svart</h3>
    <p>229 kr</p>
  </div>

  <div class="product">
    <img src="https://images.unsplash.com/photo-1512436991641-6745cdb1723f?auto=format&fit=crop&w=800&q=80">
    <h3>Basic Tröja Vit</h3>
    <p>119 kr</p>
  </div>

  <div class="product">
    <img src="https://images.unsplash.com/photo-1503342217505-b0a15cf70489?auto=format&fit=crop&w=800&q=80">
    <h3>Street Hoodie Grå</h3>
    <p>249 kr</p>
  </div>

</section>

<footer>
  © 2026 LUZARA. Alla rättigheter förbehållna.
</footer>

</body>
</html>
