<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Prateek Associates - Legal Advice and Representation">
    <title>Prateek Associates - Advocate Firm</title>
    <style>
        /* Reset some basic styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        /* Global styles */
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f4f4f4;
            color: #333;
        }

        /* Header styles */
        header {
            background-color: #2C3E50;
            color: #fff;
            padding: 20px 0;
        }

        header h1 {
            font-size: 2.5rem;
            margin-left: 20px;
        }

        header nav ul {
            list-style: none;
            display: flex;
            justify-content: flex-end;
            margin-right: 20px;
        }

        header nav ul li {
            margin-left: 20px;
        }

        header nav ul li a {
            color: #fff;
            text-decoration: none;
            font-size: 1.1rem;
            text-transform: uppercase;
        }

        header nav ul li a:hover {
            color: #E74C3C;
        }

        /* Hero section */
        .hero {
            background: url('legal-hero.jpg') no-repeat center center/cover;
            height: 60vh;
            display: flex;
            align-items: center;
            justify-content: center;
            color: #fff;
            text-align: center;
        }

        .hero h2 {
            font-size: 3rem;
            margin-bottom: 10px;
        }

        .hero p {
            font-size: 1.2rem;
            margin-bottom: 20px;
        }

        .hero .btn {
            padding: 12px 25px;
            background-color: #E74C3C;
            color: white;
            font-size: 1.1rem;
            border: none;
            cursor: pointer;
            text-decoration: none;
            border-radius: 5px;
            transition: background-color 0.3s;
        }

        .hero .btn:hover {
            background-color: #C0392B;
        }

        /* Services Section */
        .services {
            padding: 50px 0;
            background-color: #ECF0F1;
        }

        .services .container {
            text-align: center;
        }

        .services h2 {
            font-size: 2.5rem;
            margin-bottom: 30px;
        }

        .service-item {
            background-color: #fff;
            margin: 20px 0;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            text-align: center;
        }

        .service-item h3 {
            font-size: 1.8rem;
            color: #2C3E50;
            margin-bottom: 15px;
        }

        .service-item p {
            font-size: 1.1rem;
            color: #7F8C8D;
        }

        /* New Card for High Court Advocate */
        .highcourt-advocate {
            background-color: #fff;
            margin: 20px 0;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            display: inline-block;
            width: 300px;
            text-align: center;
        }

        .highcourt-advocate img {
            width: 100%;
            height: auto;
            border-radius: 50%;
            margin-bottom: 15px;
        }

        .highcourt-advocate h3 {
            font-size: 1.8rem;
            color: #2C3E50;
        }

        .highcourt-advocate p {
            font-size: 1.1rem;
            color: #7F8C8D;
        }

        /* About Us Section */
        .about {
            padding: 50px 0;
            background-color: #fff;
        }

        .about .container {
            max-width: 1200px;
            margin: 0 auto;
            text-align: center;
        }

        .about h2 {
            font-size: 2.5rem;
            margin-bottom: 20px;
        }

        .about p {
            font-size: 1.1rem;
            color: #7F8C8D;
            line-height: 1.6;
        }

        /* Contact Section */
        .contact {
            padding: 50px 0;
            background-color: #ECF0F1;
        }

        .contact .container {
            text-align: center;
        }

        .contact h2 {
            font-size: 2.5rem;
            margin-bottom: 20px;
        }

        .contact p {
            font-size: 1.1rem;
            margin-bottom: 30px;
            color: #7F8C8D;
        }

        .contact form {
            max-width: 600px;
            margin: 0 auto;
            text-align: left;
        }

        .contact input, .contact textarea {
            width: 100%;
            padding: 12px;
            margin: 10px 0;
            border: 1px solid #BDC3C7;
            border-radius: 5px;
            font-size: 1rem;
        }

        .contact button {
            background-color: #E74C3C;
            color: white;
            padding: 12px 25px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 1.1rem;
            transition: background-color 0.3s;
        }

        .contact button:hover {
            background-color: #C0392B;
        }

        /* Footer Section */
        footer {
            background-color: #2C3E50;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }

        footer p {
            font-size: 1rem;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            header h1 {
                font-size: 2rem;
            }

            .hero h2 {
                font-size: 2.5rem;
            }

            .services h2 {
                font-size: 2rem;
            }

            .service-item {
                margin: 15px 0;
            }

            .about h2, .contact h2 {
                font-size: 2rem;
            }

            .contact form {
                padding: 20px;
            }
        }
    </style>
</head>
<body>

    <!-- Header Section -->
    <header>
        <div class="container">
            <h1>Prateek Associates</h1>
            <nav>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#services">Services</a></li>
                    <li><a href="#about">About Us</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Home Section -->
    <section id="home" class="hero">
        <div class="hero-content">
            <h2>Your Trusted Legal Partner</h2>
            <p>Providing expert legal counsel and representation for over 10 years.</p>
            <a href="#contact" class="btn">Get in Touch</a>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="services">
        <div class="container">
            <h2>Our Services</h2>
            <div class="service-item">
                <h3>Legal Consultation</h3>
                <p>Our experienced advocates provide clear and actionable legal advice on various matters.</p>
            </div>
            <div class="service-item">
                <h3>Litigation</h3>
                <p>We represent clients in court cases with a proven track record of successful outcomes.</p>
            </div>
            <div class="service-item">
                <h3>Corporate Legal Services</h3>
                <p>Offering legal solutions for businesses, including contracts, mergers, and dispute resolution.</p>
            </div>

            <!-- New High Court Advocate Card -->
            <div class="highcourt-advocate">
                <img src="WhatsApp Image 2024-11-30 at 7.55.13 PM.jpeg" alt="High Court Advocate">
                <h3>High Court Advocate</h3>
                <p>Our High Court advocates specialize in representing clients in high-stakes legal matters. With years of experience, we ensure your case is in the right hands for effective representation.</p>
            </div>
        </div>
    </section>

    <!-- About Us Section -->
    <section id="about" class="about">
        <div class="container">
            <h2>About Us</h2>
            <p>Prateek Associates has been providing legal services for over 10 years, specializing in a wide range of practice areas. Our dedicated team of advocates is committed to ensuring the best outcomes for our clients through expert legal advice and representation.</p>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
        <div class="container">
            <h2>Contact Us</h2>
            <p>If you need expert legal advice or representation, feel free to reach out. Our team is here to help you with all your legal needs.</p>
            <form action="#">
                <input type="text" placeholder="Your Name" required>
                <input type="email" placeholder="Your Email" required>
                <textarea placeholder="Your Message" rows="4" required></textarea>
                <button type="submit">Send Message</button>
            </form>
        </div>
    </section>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2024 Prateek Associates. All rights reserved.</p>
    </footer>

</body>
</html>
