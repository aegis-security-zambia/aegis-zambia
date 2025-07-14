<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aegis Security Zambia - Premium Security Services</title>
    <style>
        /* Global Styles */
        :root {
            --primary-color: #003366;
            --secondary-color: #e8491d;
            --light-color: #f4f4f4;
            --dark-color: #333333;
            --max-width: 1100px;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            background: #ffffff;
            color: var(--dark-color);
        }
        
        a {
            text-decoration: none;
            color: var(--primary-color);
        }
        
        ul {
            list-style: none;
        }
        
        img {
            width: 100%;
        }
        
        /* Utility Classes */
        .container {
            max-width: var(--max-width);
            margin: auto;
            padding: 0 2rem;
            overflow: hidden;
        }
        
        .btn {
            display: inline-block;
            background: var(--primary-color);
            color: #fff;
            padding: 0.8rem 1.5rem;
            border: none;
            cursor: pointer;
            font-size: 1rem;
            border-radius: 5px;
            transition: all 0.3s ease;
        }
        
        .btn:hover {
            background: var(--secondary-color);
        }
        
        .text-primary {
            color: var(--primary-color);
        }
        
        .bg-primary {
            background: var(--primary-color);
            color: #fff;
        }
        
        .bg-secondary {
            background: var(--secondary-color);
            color: #fff;
        }
        
        .bg-light {
            background: var(--light-color);
            color: var(--dark-color);
        }
        
        .bg-dark {
            background: var(--dark-color);
            color: #fff;
        }
        
        .py-1 { padding: 1.5rem 0; }
        .py-2 { padding: 2rem 0; }
        .py-3 { padding: 3rem 0; }
        
        .p-1 { padding: 1.5rem; }
        .p-2 { padding: 2rem; }
        .p-3 { padding: 3rem; }
        
        .m-1 { margin: 1.5rem; }
        .m-2 { margin: 2rem; }
        .m-3 { margin: 3rem; }
        
        .text-center { text-align: center; }
        .text-left { text-align: left; }
        .text-right { text-align: right; }
        
        .lead {
            font-size: 1.3rem;
            margin-bottom: 1rem;
        }
        
        /* Navigation */
        .navbar {
            background: #fff;
            position: sticky;
            top: 0;
            z-index: 100;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }
        
        .navbar .container {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 1rem;
        }
        
        .navbar .logo {
            font-size: 1.5rem;
            font-weight: bold;
            color: var(--primary-color);
            <div class="logo">
  <img src="images/logo.png" alt="Aegis Security Logo" style="height: 50px;">
</div>        }
        
        .navbar .logo span {
            color: var(--secondary-color);
        }
        
        .navbar ul {
            display: flex;
        }
        
        .navbar ul li {
            margin-left: 2rem;
        }
        
        .navbar ul li a {
            color: var(--dark-color);
            font-weight: 500;
            transition: all 0.3s ease;
        }
        
        .navbar ul li a:hover {
            color: var(--secondary-color);
        }
        
        .navbar .mobile-menu {
            display: none;
            cursor: pointer;
        }
        
        /* Showcase */
        .showcase {
            background: url('https://images.unsplash.com/photo-1582732970800-4a1c5e946b8a?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80') no-repeat center center/cover;
            height: 60vh;
            display: flex;
            align-items: center;
            color: #fff;
            position: relative;
        }
        
        .showcase::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.6);
        }
        
        .showcase .showcase-content {
            position: relative;
            z-index: 1;
            width: 60%;
        }
        
        .showcase h1 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
        }
        
        /* About Section */
        .about {
            padding: 4rem 0;
        }
        
        .about h2 {
            text-align: center;
            margin-bottom: 2rem;
            font-size: 2rem;
            color: var(--primary-color);
        }
        
        .about-grid {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 2rem;
        }
        
        .about-card {
            background: #fff;
            padding: 2rem;
            border-radius: 5px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
        }
        
        .about-card h3 {
            margin-bottom: 1rem;
            color: var(--primary-color);
        }
        
        /* Services */
        .services {
            background: var(--light-color);
            padding: 4rem 0;
        }
        
        .services h2 {
            text-align: center;
            margin-bottom: 2rem;
            font-size: 2rem;
            color: var(--primary-color);
        }
        
        .services-grid {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 2rem;
        }
        
        .service-card {
            background: #fff;
            padding: 2rem;
            border-radius: 5px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
        
        .service-card i {
            font-size: 3rem;
            color: var(--secondary-color);
            margin-bottom: 1rem;
        }
        
        .service-card h3 {
            margin-bottom: 1rem;
            color: var(--primary-color);
        }
        
        /* Why Choose Us */
        .why-choose-us {
            padding: 4rem 0;
        }
        
        .why-choose-us h2 {
            text-align: center;
            margin-bottom: 2rem;
            font-size: 2rem;
            color: var(--primary-color);
        }
        
        .reasons {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 2rem;
        }
        
        .reason {
            display: flex;
            margin-bottom: 1.5rem;
        }
        
        .reason-number {
            background: var(--primary-color);
            color: #fff;
            width: 40px;
            height: 40px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            margin-right: 1rem;
            flex-shrink: 0;
        }
        
        .reason-content h3 {
            margin-bottom: 0.5rem;
            color: var(--primary-color);
        }
        
        /* Team */
        .team {
            background: var(--light-color);
            padding: 4rem 0;
        }
        
        .team h2 {
            text-align: center;
            margin-bottom: 2rem;
            font-size: 2rem;
            color: var(--primary-color);
        }
        
        .team-grid {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 2rem;
        }
        
        .team-member {
            background: #fff;
            padding: 1.5rem;
            border-radius: 5px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            text-align: center;

        }
        
        .team-member h3 {
            color: var(--primary-color);
            margin-bottom: 0.5rem;
        }
        
        .team-member p {
            color: var(--secondary-color);
            font-style: italic;
        }
        
        /* Contact */
        .contact {
            padding: 4rem 0;
        }
        
        .contact h2 {
            text-align: center;
            margin-bottom: 2rem;
            font-size: 2rem;
            color: var(--primary-color);
        }
        
        .contact-container {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 2rem;
        }
        
        .contact-info {
            background: var(--primary-color);
            color: #fff;
            padding: 2rem;
            border-radius: 5px;
        }
        
        .contact-info h3 {
            margin-bottom: 1.5rem;
        }
        
        .contact-info p {
            margin-bottom: 1rem;
            display: flex;
            align-items: center;
        }
        
        .contact-info p i {
            margin-right: 1rem;
        }
        
        .contact-form {
            background: #fff;
            padding: 2rem;
            border-radius: 5px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
        }
        
        .contact-form h3 {
            margin-bottom: 1.5rem;
            color: var(--primary-color);
        }
        
        .form-group {
            margin-bottom: 1.5rem;
        }
        
        .form-group label {
            display: block;
            margin-bottom: 0.5rem;
            color: var(--dark-color);
        }
        
        .form-group input,
        .form-group textarea {
            width: 100%;
            padding: 0.8rem;
            border: 1px solid #ddd;
            border-radius: 5px;
            font-family: inherit;
        }
        
        .form-group textarea {
            height: 150px;
        }
        
        /* Footer */
        .footer {
            background: var(--dark-color);
            color: #fff;
            padding: 2rem 0;
            text-align: center;
        }
        
        .footer p {
            margin-bottom: 1rem;
        }
        
        .social {
            margin-bottom: 1rem;
        }
        
        .social a {
            color: #fff;
            margin: 0 0.5rem;
            font-size: 1.5rem;
            transition: all 0.3s ease;
        }
        
        .social a:hover {
            color: var(--secondary-color);
        }
        
        /* Responsive */
        @media (max-width: 768px) {
            .navbar ul {
                display: none;
            }
            
            .navbar .mobile-menu {
                display: block;
            }
            
            .showcase .showcase-content {
                width: 100%;
            }
            
            .about-grid,
            .services-grid,
            .reasons,
            .team-grid,
            .contact-container {
                grid-template-columns: 1fr;
            }
            
            .team-member img {
                width: 100px;
                height: 100px;
            }
        }
    </style>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
</head>
<body>
    <!-- Navigation -->
    <nav class="navbar">
        <div class="container">
            <div class="logo">AEGIS <span>SECURITY</span></div>
            <div class="mobile-menu">
                <i class="fas fa-bars"></i>
            </div>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#why-choose-us">Why Choose Us</a></li>
                <li><a href="#team">Our Team</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </div>
    </nav>

    <!-- Showcase -->
    <section class="showcase" id="home">
        <div class="container">
            <div class="showcase-content">
                <h1>Premium Security Solutions for Zambia</h1>
                <p class="lead">Innovative security services tailored to your unique needs. Your safety is our mission.</p>
                <a href="#contact" class="btn">Get in Touch</a>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section class="about py-3" id="about">
        <div class="container">
            <h2>About Us</h2>
            <div class="about-grid">
                <div class="about-card">
                    <h3>Our Mission</h3>
                    <p>At Aegis Security Zambia, our mission is to provide exceptional security solutions tailored to the unique needs of our clients. We are committed to ensuring their safety and peace of mind through the highest standards of professionalism, innovation, and customer service.</p>
                </div>
                <div class="about-card">
                    <h3>Our Vision</h3>
                    <p>To be the most trusted and innovative security services provider in Zambia, recognized for our premium offerings and our dedication to excellence in service delivery.</p>
                </div>
            </div>
            
            <div class="about-card mt-2">
                <h3>Our Core Values</h3>
                <div class="values-grid">
                    <div class="value-item">
                        <h4><i class="fas fa-shield-alt"></i> Integrity</h4>
                        <p>We adhere to the highest ethical standards, ensuring transparency and trust in all our operations.</p>
                    </div>
                    <div class="value-item">
                        <h4><i class="fas fa-lightbulb"></i> Innovation</h4>
                        <p>We leverage cutting-edge technology and continuously seek new ways to enhance our services.</p>
                    </div>
                    <div class="value-item">
                        <h4><i class="fas fa-users"></i> Customer Focus</h4>
                        <p>Our clients are at the heart of our business; we listen, understand, and respond to their unique security needs.</p>
                    </div>
                    <div class="value-item">
                        <h4><i class="fas fa-star"></i> Excellence</h4>
                        <p>We strive for excellence in every aspect of our operations, from personnel training to service delivery.</p>
                    </div>
                    <div class="value-item">
                        <h4><i class="fas fa-hands-helping"></i> Teamwork</h4>
                        <p>Our collaborative approach ensures that we harness the collective expertise of our team to provide superior service.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Services -->
    <section class="services py-3" id="services">
        <div class="container">
            <h2>Our Services</h2>
            <div class="services-grid">
                <div class="service-card">
                    <i class="fas fa-user-shield"></i>
                    <h3>Manned Security Services</h3>
                    <p>Our highly trained security personnel provide a visible deterrent against crime, ensuring the safety of your premises and personnel.</p>
                </div>
                <div class="service-card">
                    <i class="fas fa-video"></i>
                    <h3>Electronic Security Solutions</h3>
                    <p>We integrate state-of-the-art technology, including CCTV surveillance, alarm systems, and access control systems.</p>
                </div>
                <div class="service-card">
                    <i class="fas fa-lock"></i>
                    <h3>Integrated Security Solutions</h3>
                    <p>We employ a holistic approach to security, integrating physical security measures with advanced surveillance systems.</p>
                </div>
                <div class="service-card">
                    <i class="fas fa-clipboard-check"></i>
                    <h3>Risk Assessment & Consulting</h3>
                    <p>Our expert consultants conduct thorough risk assessments to identify vulnerabilities and develop customized security strategies.</p>
                </div>
                <div class="service-card">
                    <i class="fas fa-building"></i>
                    <h3>Commercial Security</h3>
                    <p>Comprehensive security solutions tailored for commercial properties and businesses of all sizes.</p>
                </div>
                <div class="service-card">
                    <i class="fas fa-home"></i>
                    <h3>Residential Security</h3>
                    <p>Specialized security services designed to protect homes and residential communities.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Why Choose Us -->
    <section class="why-choose-us py-3" id="why-choose-us">
        <div class="container">
            <h2>Why Choose Aegis Security Zambia?</h2>
            <div class="reasons">
                <div>
                    <div class="reason">
                        <div class="reason-number">1</div>
                        <div class="reason-content">
                            <h3>Unmatched Expertise</h3>
                            <p>Our team comprises seasoned professionals with extensive experience in security management, risk assessment, and crisis response.</p>
                        </div>
                    </div>
                    <div class="reason">
                        <div class="reason-number">2</div>
                        <div class="reason-content">
                            <h3>Tailored Solutions</h3>
                            <p>We understand that every client has unique security needs. Our approach is consultative and client-centric.</p>
                        </div>
                    </div>
                    <div class="reason">
                        <div class="reason-number">3</div>
                        <div class="reason-content">
                            <h3>Cutting-Edge Technology</h3>
                            <p>We invest in advanced security technologies that enhance our service delivery and provide peace of mind.</p>
                        </div>
                    </div>
                </div>
                <div>
                    <div class="reason">
                        <div class="reason-number">4</div>
                        <div class="reason-content">
                            <h3>Commitment to Quality</h3>
                            <p>Our dedication to maintaining the highest quality standards is evident in our rigorous recruitment and training processes.</p>
                        </div>
                    </div>
                    <div class="reason">
                        <div class="reason-number">5</div>
                        <div class="reason-content">
                            <h3>Proven Track Record</h3>
                            <p>Aegis Security Zambia has built a solid reputation for excellence and reliability across various sectors.</p>
                        </div>
                    </div>
                    <div class="reason">
                        <div class="reason-number">6</div>
                        <div class="reason-content">
                            <h3>Client-Centric Approach</h3>
                            <p>We take the time to understand each client's unique needs and tailor our services accordingly.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Team -->
    <section class="team py-3" id="team">
        <div class="container">
            <h2>Our Team</h2>
            <p class="lead text-center">Experienced professionals dedicated to your security</p>
            <div class="team-grid">
                <div class="team-member">
                    <img src="https://randomuser.me/api/portraits/men/32.jpg" alt="Team Member">
                    <h3>John Banda</h3>
                    <p>Security Director</p>
                </div>
                <div class="team-member">
                    <img src="https://randomuser.me/api/portraits/women/44.jpg" alt="Team Member">
                    <h3>Sarah Mwale</h3>
                    <p>Operations Manager</p>
                </div>
                <div class="team-member">
                    <img src="https://randomuser.me/api/portraits/men/75.jpg" alt="Team Member">
                    <h3>David Phiri</h3>
                    <p>Technology Specialist</p>
                </div>
                <div class="team-member">
                    <img src="https://randomuser.me/api/portraits/women/68.jpg" alt="Team Member">
                    <h3>Grace Lungu</h3>
                    <p>Client Relations</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact -->
    <section class="contact py-3" id="contact">
        <div class="container">
            <h2>Contact Us</h2>
            <div class="contact-container">
                <div class="contact-info">
                    <h3>Get In Touch</h3>
                    <p><i class="fas fa-phone"></i> +260 769 673534</p>
                    <p><i class="fas fa-phone"></i> +260 777 944344</p>
                    <p><i class="fas fa-envelope"></i> info@aegiszambia.com</p>
                    <p><i class="fas fa-map-marker-alt"></i> 190 Luzi Road, Northmead, Lusaka - Zambia</p>
                    <p><i class="fas fa-globe"></i> www.aegiszambia.com</p>
                </div>
                <div class="contact-form">
                    <h3>Send Us a Message</h3>
                    <form>
                        <div class="form-group">
                            <label for="name">Name</label>
                            <input type="text" id="name" required>
                        </div>
                        <div class="form-group">
                            <label for="email">Email</label>
                            <input type="email" id="email" required>
                        </div>
                        <div class="form-group">
                            <label for="phone">Phone</label>
                            <input type="tel" id="phone">
                        </div>
                        <div class="form-group">
                            <label for="message">Message</label>
                            <textarea id="message" required></textarea>
                        </div>
                        <button type="submit" class="btn">Send Message</button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="footer">
        <div class="container">
            <div class="social">
                <a href="#"><i class="fab fa-facebook"></i></a>
                <a href="#"><i class="fab fa-twitter"></i></a>
                <a href="#"><i class="fab fa-linkedin"></i></a>
                <a href="#"><i class="fab fa-instagram"></i></a>
            </div>
            <p>Aegis Security Zambia Limited &copy; 2025. All Rights Reserved.</p>
            <p>Companies Registration No. 120241016079 | TPIN: 2003416546</p>
        </div>
    </footer>

    <script>
        // Simple mobile menu toggle
        document.querySelector('.mobile-menu').addEventListener('click', function() {
            const nav = document.querySelector('.navbar ul');
            nav.style.display = nav.style.display === 'flex' ? 'none' : 'flex';
        });
        
        // Smooth scrolling for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
                
                // Close mobile menu if open
                if (window.innerWidth <= 768) {
                    document.querySelector('.navbar ul').style.display = 'none';
                }
            });
        });
    </script>
</body>
</html>
