<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Virtual Pet Adoption Centre</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>🐶 Virtual Pet Adoption Centre 🐱</h1>
    <nav>
      <a href="#home">Home</a>
      <a href="#adopt">Adopt</a>
      <a href="#about">About</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="home" class="hero">
    <h2>Adopt a Friend for Life</h2>
    <p>Welcome to the cutest corner of the internet. Find your furry friend today!</p>
    <a href="#adopt" class="btn">Meet Our Pets</a>
  </section>

  <section id="adopt" class="pets">
    <h2>Available Pets</h2>
    <div class="pet-card">
      <img src="https://place-puppy.com/200x200" alt="Puppy">
      <h3>Bruno</h3>
      <p>Breed: Labrador | Age: 2 Years</p>
      <button>Adopt Now</button>
    </div>
    <div class="pet-card">
      <img src="https://placekitten.com/200/200" alt="Kitten">
      <h3>Snowy</h3>
      <p>Breed: Persian Cat | Age: 1 Year</p>
      <button>Adopt Now</button>
    </div>
  </section>

  <section id="about" class="about">
    <h2>About Us</h2>
    <p>We help connect loving families with adorable pets for virtual adoption. Our mission is to spread smiles by making adoption easy and meaningful.</p>
  </section>

  <section id="contact" class="contact">
    <h2>Contact Us</h2>
    <form>
      <input type="text" placeholder="Your Name" required>
      <input type="email" placeholder="Your Email" required>
      <textarea placeholder="Your Message" required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Virtual Pet Adoption Centre | Made with ❤️</p>
  </footer>
</body>
</html>
body {
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  margin: 0;
  padding: 0;
  background-color: #fffaf2;
  color: #333;
}

header {
  background-color: #ffa500;
  padding: 20px;
  text-align: center;
  color: white;
}

nav a {
  color: white;
  text-decoration: none;
  margin: 0 10px;
  font-weight: bold;
}

.hero {
  background: url('https://images.unsplash.com/photo-1611078489935-b35557a3e4f2?auto=format&fit=crop&w=1470&q=80') no-repeat center center/cover;
  padding: 80px 20px;
  text-align: center;
  color: #fff;
}

.hero h2 {
  font-size: 3em;
  margin: 0;
}

.btn {
  display: inline-block;
  margin-top: 20px;
  padding: 10px 20px;
  background-color: #ff8c00;
  color: white;
  text-decoration: none;
  border-radius: 5px;
}

.pets {
  padding: 40px 20px;
  text-align: center;
  background-color: #fff0d9;
}

.pet-card {
  display: inline-block;
  width: 200px;
  margin: 10px;
  padding: 15px;
  background-color: white;
  box-shadow: 0 2px 10px rgba(0,0,0,0.1);
  border-radius: 10px;
}

.pet-card img {
  width: 100%;
  border-radius: 10px;
}

.about, .contact {
  padding: 40px 20px;
  background-color: #fff7e0;
  text-align: center;
}

form {
  max-width: 400px;
  margin: 0 auto;
}

form input, form textarea {
  width: 100%;
  margin: 10px 0;
  padding: 10px;
  border: 1px solid #ccc;
  border-radius: 5px;
}

form button {
  padding: 10px 20px;
  background-color: #ffa500;
  color: white;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}

footer {
  background-color: #ffa500;
  color: white;
  text-align: center;
  padding: 10px;
}

