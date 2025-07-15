
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aegis Security Zambia - Premium Security Services</title>
    <style>
        /* Global Styles */
        :root {
            --primary-color: #153462; /* Dark blue */
            --secondary-color: #feb139; /* Yellow accent */
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
            color: var(--primary-color);
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
        
        .navbar .logo img {
            height: 100px;
            width: auto;
        }
        
        .navbar ul {
            display: flex;
            align-items: center; /* Added for vertical alignment */
        }
        
        .navbar ul li {
            margin-left: 2rem;
        }
        
        .navbar ul li a {
            color: var(--dark-color);
            font-weight: 500;
            transition: all 0.3s ease;
            padding: 0.5rem 0; /* Added for better click area */
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
            background: var(--secondary-color);
            height: 60vh;
            display: flex;
            align-items: center;
            color: var(--primary-color);
            position: relative;
        }
        
        .showcase .container {
            width: 100%;
        }
        
        .showcase .showcase-content {
            max-width: 600px;
        }
        
        .showcase h1 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
            color: var(--primary-color);
        }
        
        /* Rest of your CSS remains the same */
        /* ... (keep all other CSS sections the same as before) ... */
    </style>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
</head>
<body>
    <!-- Navigation -->
    <nav class="navbar">
        <div class="container">
            <div class="logo">
                <img src="images/logo.png" alt="Aegis Security Zambia Logo">
            </div>
            <div class="mobile-menu">
                <i class="fas fa-bars"></i>
            </div>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#why-choose-us">Why Choose Us</a></li>
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

    <!-- Rest of your HTML remains the same -->
    <!-- ... (keep all other HTML sections the same as before) ... -->

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
