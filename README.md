<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>IKO Rent - Connecting Landlords and Tenants</title>
    <link rel="stylesheet" href="styles.css">
    <script src="https://kit.fontawesome.com/a076d05399.js"></script>
</head>
<body>
    <header>
        <div class="logo">
            <h1>IKO Rent</h1>
        </div>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#contact">Contact</a></li>
                <li><a href="#signup" class="btn">Sign Up</a></li>
            </ul>
        </nav>
    </header>

    <section id="home" class="landing-section">
        <div class="overlay">
            <h2>Welcome to IKO Rent</h2>
            <p>Your trusted platform for seamless rent payments and landlord-tenant connections</p>
            <a href="#signup" class="cta-btn">Get Started</a>
        </div>
    </section>

    <section id="about" class="info-section">
        <h2>About Us</h2>
        <p>IKO Rent is an online platform that simplifies rent collection, loan management, and tenant referrals. Connecting landlords and tenants in Nairobi and beyond, we make the rental process effortless and transparent.</p>
    </section>

    <section id="services" class="info-section">
        <h2>Our Services</h2>
        <div class="services-container">
            <div class="service">
                <h3>Landlord Dashboard</h3>
                <p>Manage your properties, approve or reject tenant registrations and loans, and track payments with ease.</p>
            </div>
            <div class="service">
                <h3>Tenant Services</h3>
                <p>Apply for rent loans, get approval notifications, and refer other tenants for a seamless rental experience.</p>
            </div>
            <div class="service">
                <h3>Seamless Transactions</h3>
                <p>Collect and pay rent directly on the platform with secure payment methods.</p>
            </div>
        </div>
    </section>

    <section id="contact" class="contact-section">
        <h2>Contact Us</h2>
        <p>If you have any questions or need support, reach out to us:</p>
        <p>Phone: <strong>+254 757 187 802</strong></p>
        <p>Email: <strong>info@ikorent.com</strong></p>
    </section>

    <section id="signup" class="signup-section">
        <h2>Join IKO Rent Today</h2>
        <p>Sign up as a landlord or tenant and experience the future of rentals.</p>
        <form action="#" method="POST">
            <input type="text" placeholder="Full Name" required>
            <input type="email" placeholder="Email" required>
            <input type="password" placeholder="Password" required>
            <button type="submit" class="cta-btn">Sign Up</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2025 IKO Rent | All rights reserved</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>

/* General Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Body and Font */
body {
    font-family: 'Arial', sans-serif;
    line-height: 1.6;
    background-color: #f4f4f4;
}

/* Header */
header {
    background: #333;
    color: #fff;
    padding: 20px 0;
    text-align: center;
}

header .logo h1 {
    margin: 0;
    font-size: 2.5em;
}

header nav ul {
    list-style: none;
    padding: 0;
}

header nav ul li {
    display: inline;
    margin: 0 15px;
}

header nav ul li a {
    color: #fff;
    text-decoration: none;
    font-size: 1.2em;
}

/* Landing Section */
.landing-section {
    background: url('https://example.com/urban-nairobi.jpg') no-repeat center center/cover;
    color: #fff;
    padding: 100px 0;
    text-align: center;
}

.landing-section .overlay {
    background: rgba(0, 0, 0, 0.5);
    padding: 50px 20px;
}

.landing-section h2 {
    font-size: 3em;
    margin-bottom: 20px;
}

.landing-section p {
    font-size: 1.2em;
    margin-bottom: 30px;
}

.landing-section .cta-btn {
    background: #28a745;
    color: #fff;
    padding: 15px 30px;
    text-decoration: none;
    font-size: 1.2em;
    border-radius: 5px;
}

/* Info Sections */
.info-section {
    padding: 50px 20px;
    text-align: center;
}

.info-section h2 {
    font-size: 2.5em;
    margin-bottom: 20px;
}

.info-section p {
    font-size: 1.2em;
    margin-bottom: 30px;
}

/* Services */
.services-container {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
}

.service {
    background: #fff;
    padding: 20px;
    margin: 10px;
    width: 30%;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    border-radius: 5px;
    text-align: center;
}

.service h3 {
    font-size: 1.5em;
    margin-bottom: 10px;
}

.service p {
    font-size: 1.1em;
}

/* Contact Section */
.contact-section {
    background: #28a745;
    color: #fff;
    padding: 50px 20px;
    text-align: center;
}

.contact-section h2 {
    font-size: 2.5em;
    margin-bottom: 20px;
}

.contact-section p {
    font-size: 1.2em;
    margin-bottom: 30px;
}

/* Signup
::contentReference[oaicite:0]{index=0}
 
