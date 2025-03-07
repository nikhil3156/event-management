<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Carry On Wedding & Event Management</title>
    
    <style>
        body { 
            font-family: 'Arial', sans-serif; 
            margin: 0; 
            padding: 0; 
            background: url('bgrd2.jpeg') center/cover no-repeat fixed;
        }
        header { 
            background: url("nyyy.jpg") center/cover no-repeat; 
            color: rgb(10, 120, 128); 
            padding: 100px 20px; 
            text-align: center; 
            font-size: 30px; 
            font-weight: bold; 
            text-shadow: 2px 4px 5px rgba(0, 0, 0, 0.7); 
            animation: fadeIn 2s ease-in-out;
        }
        nav { 
            background: rgba(22, 113, 90, 0.9); 
            padding: 15px; 
            text-align: center; 
            position: sticky; 
            top: 0; 
            width: 100%; 
        }
        nav a { 
            color: rgb(216, 148, 96); 
            margin: 0 20px; 
            text-decoration: none; 
            font-size: 20px; 
            font-weight: bold; 
            transition: color 0.3s ease-in-out;
        }
        nav a:hover { color: #ffcc00; }
        section { 
            padding: 50px; 
            text-align: center; 
            animation: slideIn 1.5s ease-in-out;
        }
        .services, .gallery { 
            display: flex; 
            justify-content: center; 
            gap: 20px; 
            flex-wrap: wrap; 
        }
        .service-card, .gallery-card { 
            border-radius: 10px; 
            overflow: hidden; 
            box-shadow: 0px 4px 15px rgba(0,0,0,0.3); 
            width: 350px; 
            background: rgb(240, 213, 229); 
            padding: 40px; 
            transition: transform 0.3s ease-in-out, box-shadow 0.3s ease-in-out;
        }
        .service-card:hover, .gallery-card:hover { 
            transform: scale(1.05); 
            box-shadow: 0px 8px 20px rgba(0,0,0,0.5);
        }
        .service-card img, .gallery-card img { 
            width: 100%; 
            height: 250px; 
            object-fit: cover; 
            border-radius: 10px; 
        }
        footer { 
            background: #222; 
            color: white; 
            text-align: center; 
            padding: 30px; 
            font-size: 18px; 
        }
        .contact-btn { 
            background: #ff4081; 
            color: white; 
            padding: 30px; 
            text-decoration: none; 
            border-radius: 5px; 
            font-size: 20px; 
            font-weight: bold; 
            transition: background 0.3s ease-in-out;
        }
        .contact-btn:hover { background: #e6005c; }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        @keyframes slideIn {
            from { transform: translateY(50px); opacity: 0; }
            to { transform: translateY(0); opacity: 1; }
        }
        #about h2 {
            font-size: 28px;
        }
        #about p {
            font-size: 28px;}
        #contact h2{
                font-size: 28px;
            }
        #about p{
            font-size: 28px;
        }

    </style>
</head>
<body>
    <header>
        <h1>Carry On Wedding & Event Management</h1>
        <p>Turning Your Dream Wedding into Reality</p>
    </header>
    
    <nav>
        <a href="#about">About Us</a>
        <a href="#services">Our Services</a>
        <a href="#gallery">Gallery</a>
        <a href="#contact">Contact Us</a>
    </nav>
    
    <section id="about">
        <h2>About Us</h2>
        <p>We specialize in luxury weddings, birthdays, and anniversary celebrations, ensuring a stress-free and magical experience.</p>
    </section>
    
    <section id="services">
        <h2>Our Services</h2>
        <div class="services">
            <div class="service-card">
                <img src="wdy.jpeg" alt="Wedding Setup">
                <h3>Luxury Weddings</h3>
                <p>From royal palaces to beachside weddings, we bring your dream to life.</p>
            </div>
            <div class="service-card">
                <img src="bdy2.webp" alt="Birthday Party">
                <h3>Grand Birthday Parties</h3>
                <p>Themed birthday celebrations with fun and excitement.</p>
            </div>
            <div class="service-card">
                <img src="aniversry.jpeg" alt="Anniversary Event">
                <h3>Elegant Anniversaries</h3>
                <p>Celebrate your milestones with elegance and love.</p>
            </div>
        </div>
    </section>
    
    <section id="gallery">
        <h2>Our Work</h2>
        <div class="gallery">
            <div class="gallery-card">
                <img src="setup.jpeg" alt="Beautiful Indian Wedding">
                <p>Grand Royal Wedding Setup</p>
            </div>
            <div class="gallery-card">
                <img src="wedding decors.jpeg" alt="Lavish Wedding Decor">
                <p>Traditional Indian Wedding Decor</p>
            </div>
            <div class="gallery-card">
                <img src="mandap.jpg" alt="Luxury Mandap">
                <p>Luxurious Wedding Mandap</p>
            </div>
        </div>
    </section><h2>Bride Mehndi</h2>
    <p>
    <img width="600" src="mnd1.webp" alt="">
    <img width=600 src="mnd2.webp" alt="">
    <img width=600 src="mnd3.webp" alt="">
    <img width=600 src="mnd4.webp" alt="">
    </p>
    <section id="contact">
        <h2>Contact Us</h2>
        <p>Contact: 7454018549</p>
        <p>Email: nikhilpratap413@gmail.com</p>
        <p>Instagram: @carryonweddings</p>
        <p>Let’s plan your dream event! Get in touch today.</p>
        <a href="https://wa.me/917454018549" class="contact-btn" target="_blank">WhatsApp Us</a>

    </section>
    
    <footer>
        <p>© 2025 Carry On Wedding & Event Management. All Rights Reserved.</p>
    </footer>
</body>
</html>

