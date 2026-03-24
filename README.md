<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Malvika's Luxe - Reviews</title>

<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500;700&family=Poppins:wght@300;400&display=swap" rel="stylesheet">

<style>
body {
    margin: 0;
    font-family: 'Poppins', sans-serif;
    background: linear-gradient(135deg, #0f0f0f, #1c1c1c);
    color: #fff;
}

/* HEADER */
.header {
    text-align: center;
    padding: 50px 20px 20px;
}
.header h1 {
    font-family: 'Playfair Display', serif;
    font-size: 48px;
    color: #d4af37;
    letter-spacing: 2px;
}
.header p {
    color: #ccc;
}

/* SECTION */
.container {
    max-width: 900px;
    margin: auto;
    padding: 20px;
}

/* REVIEW CARDS */
.review {
    background: rgba(255,255,255,0.05);
    padding: 25px;
    margin: 20px 0;
    border-radius: 15px;
    border: 1px solid rgba(212,175,55,0.3);
    backdrop-filter: blur(10px);
    transition: 0.3s;
}
.review:hover {
    transform: translateY(-5px);
}

.stars {
    color: gold;
    font-size: 18px;
}

/* CTA BUTTON */
.button {
    display: block;
    text-align: center;
    background: linear-gradient(45deg, gold, #d4af37);
    color: black;
    padding: 15px;
    margin: 40px auto;
    border-radius: 40px;
    text-decoration: none;
    font-weight: bold;
    width: 80%;
}

/* FOOTER */
.footer {
    text-align: center;
    padding: 30px;
    font-style: italic;
    color: #aaa;
}

/* IMAGE SECTION */
.gallery {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(120px, 1fr));
    gap: 10px;
}
.gallery img {
    width: 100%;
    border-radius: 10px;
}
</style>
</head>

<body>

<div class="header">
    <h1>Malvika’s Luxe 💎</h1>
    <p>Where Elegance Meets Trust</p>
</div>

<div class="container">

<h2 style="text-align:center;">⭐ What Our Customers Say</h2>

<div class="review">
    <p class="stars">★★★★★</p>
    <p>Absolutely loved the quality! Looks premium and elegant.</p>
    <p>— Riya, Mumbai</p>
</div>

<div class="review">
    <p class="stars">★★★★★</p>
    <p>Got so many compliments at a wedding 😍</p>
    <p>— Pooja, Delhi</p>
</div>

<div class="review">
    <p class="stars">★★★★★</p>
    <p>Packaging was beautiful and delivery was fast.</p>
    <p>— Sneha, Pune</p>
</div>

<h2 style="text-align:center;">📸 Styled by Our Customers</h2>

<div class="gallery">
    <img src="https://via.placeholder.com/150">
    <img src="https://via.placeholder.com/150">
    <img src="https://via.placeholder.com/150">
</div>

<a class="button" href="https://wa.me/919372265858?text=Hi%20Malvika%E2%80%99s%20Luxe%2C%20I%20want%20to%20share%20my%20review.">
💬 Leave Your Review on WhatsApp
</a>

<div class="footer">
✨ Thank you for choosing elegance ✨
</div>

</div>

</body>
</html>
