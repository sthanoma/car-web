<html>
<head>
<title>Prativa Motors Dealership</title>

<style>
body {
    font-family: Arial;
    margin: 0;
    background: url('https://images.unsplash.com/photo-1503376780353-7e6692767b70') no-repeat center center fixed;
    background-size: cover;
}

/* Overlay */
.overlay {
    background: rgba(255,255,255,0.92);
    min-height: 100vh;
}

/* Header */
header {
    background: rgb(0, 0, 0);
    color: white;
    text-align: center;
    padding: 15px;
}

/* Navigation */
nav {
    background: gray;
    text-align: center;
    padding: 10px;
}

nav a {
    text-decoration: none;
    color: white;
    margin: 10px;
    padding: 8px 12px;
    background: black;
    border-radius: 5px;
}

/* Sections */
section {
    padding: 20px;
}

/* Grid */
.grid {
    display: flex;
    flex-wrap: wrap;
    gap: 15px;
}

/* Cards */
.card {
    background: white;
    width: 220px;
    padding: 10px;
    border-radius: 10px;
    box-shadow: 0 2px 6px rgba(0,0,0,0.2);
}

.card img {
    width: 100%;
    border-radius: 8px;

  width: 100%;
  height: 200px;
  object-fit: cover;
 
}

/* Form */
form {
    background: white;
    padding: 15px;
    max-width: 300px;
    border-radius: 10px;
}

input {
    width: 100%;
    padding: 8px;
    margin-bottom: 10px;
}
</style>
</head>

<body>

<div class="overlay">

<header>
    <h1>Car Dealership</h1>
</header>

<!-- Navigation using HTML only -->
<nav>
    <a href="#home">Home</a>
    <a href="#cars">Cars</a>
    <a href="#team">Team</a>
    <a href="#register">Register</a>
</nav>

<!-- HOME -->
<section id="home">
    <h2>Welcome</h2>
    <p>Find your dream car at the best price!</p>
</section>

<!-- CARS -->
<section id="cars">
    <h2>Cars</h2>

    <div class="grid">

        <div class="card">
            <img src="https://images.unsplash.com/photo-1542362567-b07e54358753">
            <h3>Toyota Corolla</h3>
            <p>$20,000</p>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1552519507-da3b142c6e3d">
            <h3>Honda Civic</h3>
            <p>$22,500</p>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1494905998402-395d579af36f">
            <h3>Ford Mustang</h3>
            <p>$35,000</p>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1606664515524-ed2f786a0bd6">
            <h3>Hyundai Tucson</h3>
            <p>$28,000</p>

        </div>

    </div>
</section>

<!-- TEAM -->
<section id="team">
    <h2>
     <b>Team in Business</b>
    </h2>

    <div class="grid">
        <div class="card">Kushal</div>
        <div class="card">Ayub</div>
        <div class="card">Sachin</div>
        <div class="card">Trishanka</div>
        <div class="card">Sushant</div>
    </div>
</section>

<!-- REGISTER -->
<section id="register">
    <h2>Register</h2>

    <form>
        Name:
        <input type="text">

        Email:
        <input type="text">

        Phone:
     <input type="number" >

        <input type="submit" value="Register">
    </form>
</section>

</div>

</body>
</html>
