<!DOCTYPE html>  
<html lang="en">  
<head>  
    <meta charset="UTF-8">  
    <meta name="viewport" content="width=device-width, initial-scale=1.0">  
    <title>NN Brothers Traders - Your Trusted Trading Partner in Pakistan</title>  
    <style>  
        * {  
            margin: 0;  
            padding: 0;  
            box-sizing: border-box;  
        }  
  
        body {  
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;  
            line-height: 1.6;  
            color: #333;  
        }  
  
        header {  
            background: linear-gradient(135deg, #1e3c72 0%, #2a5298 100%);  
            color: white;  
            padding: 1rem 0;  
            position: sticky;  
            top: 0;  
            z-index: 1000;  
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);  
        }  
  
        nav {  
            max-width: 1200px;  
            margin: 0 auto;  
            display: flex;  
            justify-content: space-between;  
            align-items: center;  
            padding: 0 2rem;  
        }  
  
        .logo {  
            font-size: 1.5rem;  
            font-weight: bold;  
            display: flex;  
            align-items: center;  
            gap: 0.5rem;  
        }  
  
        nav ul {  
            list-style: none;  
            display: flex;  
            gap: 2rem;  
        }  
  
        nav a {  
            color: white;  
            text-decoration: none;  
            transition: opacity 0.3s;  
            font-weight: 500;  
        }  
  
        nav a:hover {  
            opacity: 0.8;  
        }  
  
        .hero {  
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);  
            color: white;  
            padding: 6rem 2rem;  
            text-align: center;  
        }  
  
        .hero h1 {  
            font-size: 3rem;  
            margin-bottom: 1rem;  
            animation: fadeInUp 1s ease;  
        }  
  
        .hero p {  
            font-size: 1.3rem;  
            max-width: 700px;  
            margin: 0 auto 2rem;  
            opacity: 0.95;  
            animation: fadeInUp 1s ease 0.2s backwards;  
        }  
  
        .cta-button {  
            display: inline-block;  
            background: white;  
            color: #667eea;  
            padding: 1rem 2.5rem;  
            text-decoration: none;  
            border-radius: 50px;  
            font-weight: bold;  
            transition: transform 0.3s, box-shadow 0.3s;  
            animation: fadeInUp 1s ease 0.4s backwards;  
        }  
  
        .cta-button:hover {  
            transform: translateY(-3px);  
            box-shadow: 0 10px 25px rgba(0,0,0,0.2);  
        }  
  
        .container {  
            max-width: 1200px;  
            margin: 0 auto;  
            padding: 4rem 2rem;  
        }  
  
        .section-title {  
            text-align: center;  
            font-size: 2.5rem;  
            margin-bottom: 3rem;  
            color: #1e3c72;  
        }  
  
        .about-grid {  
            display: grid;  
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));  
            gap: 2rem;  
            margin-top: 2rem;  
        }  
  
        .about-card {  
            background: white;  
            padding: 2rem;  
            border-radius: 15px;  
            box-shadow: 0 5px 20px rgba(0,0,0,0.1);  
            transition: transform 0.3s;  
        }  
  
        .about-card:hover {  
            transform: translateY(-10px);  
        }  
  
        .about-card h3 {  
            color: #667eea;  
            font-size: 1.5rem;  
            margin-bottom: 1rem;  
            display: flex;  
            align-items: center;  
            gap: 0.5rem;  
        }  
  
        .services {  
            background: #f8f9fa;  
        }  
  
        .service-grid {  
            display: grid;  
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));  
            gap: 2rem;  
        }  
  
        .service-card {  
            background: white;  
            padding: 2rem;  
            border-radius: 15px;  
            text-align: center;  
            box-shadow: 0 5px 20px rgba(0,0,0,0.08);  
            transition: all 0.3s;  
        }  
  
        .service-card:hover {  
            transform: translateY(-10px);  
            box-shadow: 0 10px 30px rgba(102, 126, 234, 0.2);  
        }  
  
        .service-icon {  
            font-size: 3rem;  
            margin-bottom: 1rem;  
        }  
  
        .service-card h3 {  
            color: #1e3c72;  
            margin-bottom: 1rem;  
        }  
  
        .values {  
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);  
            color: white;  
        }  
  
        .values-grid {  
            display: grid;  
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));  
            gap: 2rem;  
            text-align: center;  
        }  
  
        .value-item {  
            padding: 2rem;  
        }  
  
        .value-item h3 {  
            font-size: 1.8rem;  
            margin-bottom: 1rem;  
        }  
  
        .contact {  
            background: white;  
        }  
  
        .contact-grid {  
            display: grid;  
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));  
            gap: 3rem;  
        }  
  
        .contact-info {  
            background: #f8f9fa;  
            padding: 2rem;  
            border-radius: 15px;  
            border-left: 5px solid #667eea;  
        }  
  
        .contact-info h3 {  
            color: #1e3c72;  
            margin-bottom: 1.5rem;  
            font-size: 1.5rem;  
        }  
  
        .contact-item {  
            display: flex;  
            align-items: start;  
            gap: 1rem;  
            margin-bottom: 1.5rem;  
        }  
  
        .contact-icon {  
            font-size: 1.5rem;  
            color: #667eea;  
        }  
  
        footer {  
            background: #1e3c72;  
            color: white;  
            text-align: center;  
            padding: 2rem;  
        }  
  
        @keyframes fadeInUp {  
            from {  
                opacity: 0;  
                transform: translateY(30px);  
            }  
            to {  
                opacity: 1;  
                transform: translateY(0);  
            }  
        }  
  
        @media (max-width: 768px) {  
            .hero h1 {  
                font-size: 2rem;  
            }  
  
            .hero p {  
                font-size: 1.1rem;  
            }  
  
            nav ul {  
                gap: 1rem;  
            }  
  
            .section-title {  
                font-size: 2rem;  
            }  
        }  
    </style>  
</head>  
<body>  
    <header>  
        <nav>  
            <div class="logo">  
                🏢 NN Brothers Traders  
            </div>  
            <ul>  
                <li><a href="#home">Home</a></li>  
                <li><a href="#about">About</a></li>  
                <li><a href="#services">Services</a></li>  
                <li><a href="#contact">Contact</a></li>  
            </ul>  
        </nav>  
    </header>  
  
    <section class="hero" id="home">  
        <h1>Your Trusted Trading Partner in Pakistan</h1>  
        <p>NN Brothers Traders delivers excellence in general trading and supply services with integrity, transparency, and unwavering commitment to customer satisfaction.</p>  
        <a href="#contact" class="cta-button">Get in Touch</a>  
    </section>  
  
    <section class="container" id="about">  
        <h2 class="section-title">Who We Are</h2>  
        <div class="about-grid">  
            <div class="about-card">  
                <h3>🎯 Our Mission</h3>  
                <p>NN Brothers Traders is a registered trading company committed to delivering exceptional value through reliable trading and supply services across Pakistan. We build lasting partnerships based on trust and quality.</p>  
            </div>  
            <div class="about-card">  
                <h3>✨ Our Vision</h3>  
                <p>To be the most trusted name in trading services, recognized for our integrity, reliability, and commitment to excellence in every transaction we undertake.</p>  
            </div>  
            <div class="about-card">  
                <h3>📋 Company Details</h3>  
                <p><strong>Business Name:</strong> NN Brothers Traders<br>  
                <strong>NTN:</strong> B-358577-8<br>  
                <strong>Location:</strong> Hub, Balochistan, Pakistan<br>  
                <strong>Status:</strong> Registered & Operational</p>  
            </div>  
        </div>  
    </section>  
  
    <section class="services" id="services">  
        <div class="container">  
            <h2 class="section-title">Our Services</h2>  
            <div class="service-grid">  
                <div class="service-card">  
                    <div class="service-icon">📦</div>  
                    <h3>General Trading</h3>  
                    <p>Comprehensive trading solutions for diverse product categories, ensuring quality and timely delivery for all your business needs.</p>  
                </div>  
                <div class="service-card">  
                    <div class="service-icon">🚚</div>  
                    <h3>Supply Services</h3>  
                    <p>Reliable supply chain management and distribution services to keep your operations running smoothly and efficiently.</p>  
                </div>  
                <div class="service-card">  
                    <div class="service-icon">🤝</div>  
                    <h3>Business Solutions</h3>  
                    <p>Tailored trading solutions designed to meet your specific business requirements with flexibility and professionalism.</p>  
                </div>  
                <div class="service-card">  
                    <div class="service-icon">🌟</div>  
                    <h3>Quality Assurance</h3>  
                    <p>Rigorous quality control processes to ensure every product and service meets the highest standards of excellence.</p>  
                </div>  
            </div>  
        </div>  
    </section>  
  
    <section class="values">  
        <div class="container">  
            <h2 class="section-title" style="color: white;">Our Core Values</h2>  
            <div class="values-grid">  
                <div class="value-item">  
                    <h3>🛡️ Integrity</h3>  
                    <p>We conduct business with honesty and strong moral principles, building trust through every interaction.</p>  
                </div>  
                <div class="value-item">  
                    <h3>💎 Transparency</h3>  
                    <p>Clear communication and open practices ensure our clients always know what to expect from our services.</p>  
                </div>  
                <div class="value-item">  
                    <h3>😊 Customer Satisfaction</h3>  
                    <p>Your success is our priority. We go above and beyond to exceed expectations and deliver exceptional value.</p>  
                </div>  
            </div>  
        </div>  
    </section>  
  
    <section class="contact" id="contact">  
        <div class="container">  
            <h2 class="section-title">Contact Us</h2>  
            <div class="contact-grid">  
                <div class="contact-info">  
                    <h3>Get in Touch</h3>  
                    <div class="contact-item">  
                        <div class="contact-icon">📍</div>  
                        <div>  
                            <strong>Address</strong><br>  
                            Main RCD Road, Near NBP<br>  
                            Hub, Balochistan<br>  
                            Pakistan  
                        </div>  
                    </div>  
                    <div class="contact-item">  
                        <div class="contact-icon">📞</div>  
                        <div>  
                            <strong>Phone</strong><br>  
                            <a href="tel:+923013352088" style="color: #667eea; text-decoration: none;">+92 301 3352088</a>  
                        </div>  
                    </div>  
                    <div class="contact-item">  
                        <div class="contact-icon">📧</div>  
                        <div>  
                            <strong>Email</strong><br>  
                            <a href="mailto:Info@nnbrotherstraders.com" style="color: #667eea; text-decoration: none;">Info@nnbrotherstraders.com</a><br>  
                            <a href="mailto:NNBrothersTraders@gmail.com" style="color: #667eea; text-decoration: none;">NNBrothersTraders@gmail.com</a>  
                        </div>  
                    </div>  
                    <div class="contact-item">  
                        <div class="contact-icon">🆔</div>  
                        <div>  
                            <strong>NTN</strong><br>  
                            B-358577-8  
                        </div>  
                    </div>  
                </div>  
                <div>  
                    <h3 style="margin-bottom: 1.5rem; color: #1e3c72;">Why Choose Us?</h3>  
                    <ul style="list-style: none; line-height: 2;">  
                        <li>✓ Registered and legally compliant business</li>  
                        <li>✓ Years of experience in trading sector</li>  
                        <li>✓ Competitive pricing and flexible terms</li>  
                        <li>✓ Reliable delivery and logistics</li>  
                        <li>✓ Dedicated customer support</li>  
                        <li>✓ Strong reputation in Balochistan region</li>  
                        <li>✓ Commitment to long-term partnerships</li>  
                    </ul>  
                </div>  
            </div>  
        </div>  
    </section>  
  
    <footer>  
        <p>&copy; 2024 NN Brothers Traders. All rights reserved. | NTN: B-358577-8</p>  
        <p style="margin-top: 0.5rem; opacity: 0.8;">Building Trust, Delivering Value</p>  
    </footer>  
</body>  
</html>  
