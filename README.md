<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hirexa Global - Job Consultancy</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; }
        header { background: #004080; color: white; text-align: center; padding: 20px; }
        nav { background: #333; padding: 10px; text-align: center; }
        nav a { color: white; margin: 0 15px; text-decoration: none; }
        .container { padding: 20px; text-align: center; }
        footer { background: #004080; color: white; text-align: center; padding: 10px; margin-top: 20px; }
        .logo { max-width: 150px; }
        .founder { max-width: 200px; border-radius: 10px; margin-top: 10px; }
        .clients { display: flex; overflow: hidden; white-space: nowrap; margin-top: 20px; }
        .clients img { max-width: 150px; margin: 0 20px; animation: scroll 10s linear infinite; }
        @keyframes scroll {
            0% { transform: translateX(100%); }
            100% { transform: translateX(-100%); }
        }
    </style>
</head>
<body>
    <header>
        <img src="LOGO.jpg" alt="Hirexa Global Logo" class="logo">
        <h1>Hirexa Global</h1>
        <p>Your Trusted Job Consultancy</p>
    </header>
    <nav>
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="container" id="about">
        <h2>About Us</h2>
        <p>Hirexa Global is a premier job consultancy offering expert recruitment services in Tech, Non-Tech, Blue Collar, White Collar, and Retail sectors.</p>
        <img src="Founder.jfif" alt="Founder" class="founder">
        <p><strong>Our Founder:</strong> Served in Delhi Administrative Services for 40 years and has been in the recruitment business for the past 6 years. 
        He holds a BCom from Delhi University and an MBA from FMS.</p>
    </div>
    <div class="container" id="services">
        <h2>Our Services</h2>
        <ul>
            <li>Tech Recruitment</li>
            <li>Non-Tech Recruitment</li>
            <li>Blue Collar Hiring</li>
            <li>White Collar Hiring</li>
            <li>Retail Sector Hiring</li>
        </ul>
    </div>
    <div class="container">
        <h2>Our Clients</h2>
        <div class="clients">
            <img src="hitachi.png" alt="Hitachi Payments">
            <img src="vango.png" alt="Vango Foods">
            <img src="zomato.png" alt="Zomato">
            <img src="urbanhomes.png" alt="Urban Homes">
            <img src="convergys.png" alt="Convergys BPO">
        </div>
    </div>
    <div class="container" id="contact">
        <h2>Contact Us</h2>
        <p>Email: <a href="mailto:manpowersolution14@gmail.com">manpowersolution14@gmail.com</a></p>
        <p>LinkedIn: <a href="https://www.linkedin.com/in/bharat-singh-32a404275" target="_blank">Connect with us</a></p>
    </div>
    <footer>
        <p>&copy; 2025 Hirexa Global | All Rights Reserved</p>
    </footer>
</body>
</html>
