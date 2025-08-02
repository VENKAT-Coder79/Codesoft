# Codesoft
here is my level 1 task 1 completion 

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width,initial-scale=1">
    <title>simple landing page </title>
    <meta name="description"
        content="High-performance landing page inspired by Tigren PWA style. Clean layout, fast, mobile-friendly.">
    <link rel="stylesheet" href="style3.css">

</head>
<body>
    <header class="hero">
        <nav class="nav">
            <div class="logo">V<span>shirts</span></div>
            <ul class="nav-links">
                <li><a href="#features">Features</a></li>
                <li><a href="#products">Products</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
        <div class="hero-content">
            <h1>Welcome to VShirts</h1>
            <h2>Your search for the perfect shirt ends here. VShirts delivers clean designs, superior comfort, and a fit
                that feels custom-made. We cut out the noise and focus on what matters: creating premium shirts that
                empower you to look sharp and feel confident, effortlessly. VShirts: Master the Essential.</p>
                <a href="#products" class="btn">See More</a>
        </div>
    </header>
    <section id="features" class="features">
        <h1 style="color: rgb(239, 138, 7) ">Why Choose Us</h2>
            <div class="grid">
                <div class="card">
                    <h3>Light shirts </h3>
                    <p>light and inner cooling </p>
                </div>
                <div class="card">
                    <h3>first 3d printing Design</h3>
                    <p>3D printed images and memes.</p>
                </div>
                <div class="card">
                    <h3>CELEB-like Experience</h3>
                    <p>Models and celebrity like feeling.</p>
                </div>
            </div>
    </section>
    <section id="products" class="products">
        <h2 style="color: orangered">Top Products</h2>
        <div class="grid">
            <div class="card product-card">
                <img src="Tie-Front Wrap Shirt.jpg" alt="Product 1">
                <h3>Product 1</h3>
            </div>
            <div class="card product-card">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS0lzlv-e-43yheCb29jOeMdMu7aedNPKf-KQ&s" alt="Product 2">
                <h3>Product 2</h3>
            </div>
            <div class="card product-card">
                <img src="https://img.joomcdn.net/fe04b322460b3b90d09af04c76369b1702ca73d3_original.jpeg" alt="Product 3">
                <h3>Product 3</h3>
            </div>
        </div>
    </section>
    <footer id="contact" class="footer">
        <pre>Contact us at      
    <a href="mailto:info@vshirts.com">info@vshirts.com</a>
        © 2025 VShirts</pre>
    </footer>
</body>
</html>

css code-
* {
  margin:0; padding:0; box-sizing:border-box;
}
body {
    
  font-family: Arial, sans-serif;
  color: #333;
  line-height:1.4;
  background-image: url('Shirt.jpg');
  background-size:100%;
  
}
h1{
    color: yellow;
    font-style: italic;
    font-size: xx-large;
}
h2{
    color: rgb(23, 207, 50);
}

a { text-decoration:none; color:inherit; }
.hero {
  background: url('https://source.unsplash.com/1600x800/?technology,modern') center/cover no-repeat;
  color: #fff;
  height:90vh;
  display:flex;
  flex-direction:column;
  justify-content:space-between;
}
.nav {
  display:flex;
  justify-content:space-between;
  padding:2rem;
  background: rgba(0,0,0,0.5);
}
.logo { font-size:1.8rem; font-weight:bold; }
.logo span { color:#0ab; }
.nav-links { display:flex; gap:1.5rem; }
.nav-links a:hover { color:#0ab; }
.hero-content {
  text-align:center;
  padding-bottom:5rem;
}
.hero-content h1 { font-size:3rem; margin-bottom:0.5rem; }
.hero-content p { margin-bottom:1.5rem; font-size:1.2rem; }
.btn {
  background:#0ab;
  color:#fff;
  padding:.8rem 2rem;
  border-radius:25px;
  font-weight:bold;
  transition:background .3s;
}
.btn:hover { background:#08a; }

section {
  padding:4rem 2rem;
  text-align:center;
}
.features .grid,
.products .grid {
  display:flex;
  gap:2rem;
  flex-wrap:wrap;
  justify-content:center;
}
.card {
  background:#fff;
  padding:2rem;
  border-radius:8px;
  box-shadow:0 2px 6px rgba(0,0,0,0.1);
  max-width:300px;
}
.product-card img {
  width:100%;
  border-radius:6px;
  margin-bottom:1rem;
}
.footer {
  background:#222;
  color:#eee;
  padding:2rem 1rem;
}
.footer a { color:#0ab; }



