# Smartkids
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>StoryLand - Free E-Books for Kids | Children's Books PDF Download</title>
    
    <!-- SEO Meta Tags -->
    <meta name="description" content="Download free children's e-books in English. Adventure stories, fairy tales, educational books for kids. PDF format, instant download.">
    <meta name="keywords" content="free children books, kids ebooks, children stories PDF, free download, educational books kids, fairy tales, adventure stories">
    <meta name="author" content="StoryLand">
    <meta name="robots" content="index, follow">
    <meta name="language" content="English">
    
    <!-- Open Graph Meta Tags for Social Media -->
    <meta property="og:title" content="StoryLand - Free E-Books for Kids">
    <meta property="og:description" content="Download free children's e-books in English. Adventure stories, fairy tales, educational books for kids.">
    <meta property="og:image" content="https://yourwebsite.com/images/storyland-preview.jpg">
    <meta property="og:url" content="https://yourwebsite.com">
    <meta property="og:type" content="website">
    <meta property="og:site_name" content="StoryLand">
    
    <!-- Twitter Card Meta Tags -->
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="StoryLand - Free E-Books for Kids">
    <meta name="twitter:description" content="Download free children's e-books in English. Adventure stories, fairy tales, educational books.">
    <meta name="twitter:image" content="https://yourwebsite.com/images/storyland-preview.jpg">
    
    <!-- Schema.org Structured Data -->
    <script type="application/ld+json">
    {
        "@context": "https://schema.org",
        "@type": "WebSite",
        "name": "StoryLand",
        "description": "Free children's e-books and stories for kids",
        "url": "https://yourwebsite.com",
        "potentialAction": {
            "@type": "SearchAction",
            "target": "https://yourwebsite.com/search?q={search_term_string}",
            "query-input": "required name=search_term_string"
        }
    }
    </script>
    
    <!-- Google Analytics (Replace with your tracking ID) -->
    <script async src="https://www.googletagmanager.com/gtag/js?id=GA_TRACKING_ID"></script>
    <script>
        window.dataLayer = window.dataLayer || [];
        function gtag(){dataLayer.push(arguments);}
        gtag('js', new Date());
        gtag('config', 'GA_TRACKING_ID');
    </script>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            color: #333;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        /* Header */
        header {
            background: rgba(255, 255, 255, 0.95);
            backdrop-filter: blur(10px);
            box-shadow: 0 8px 32px rgba(31, 38, 135, 0.37);
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
            transition: all 0.3s ease;
        }

        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 1rem 0;
        }

        .logo {
            font-size: 2rem;
            font-weight: bold;
            background: linear-gradient(45deg, #ff6b6b, #4ecdc4);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }

        .nav-links {
            display: flex;
            list-style: none;
            gap: 2rem;
        }

        .nav-links a {
            text-decoration: none;
            color: #333;
            font-weight: 500;
            transition: all 0.3s ease;
            position: relative;
        }

        .nav-links a:hover {
            color: #ff6b6b;
            transform: translateY(-2px);
        }

        .nav-links a::after {
            content: '';
            position: absolute;
            width: 0;
            height: 2px;
            bottom: -5px;
            left: 0;
            background: linear-gradient(45deg, #ff6b6b, #4ecdc4);
            transition: width 0.3s ease;
        }

        .nav-links a:hover::after {
            width: 100%;
        }

        /* Hero Section */
        .hero {
            margin-top: 80px;
            padding: 4rem 0;
            text-align: center;
            color: white;
        }

        .hero h1 {
            font-size: 3.5rem;
            margin-bottom: 1rem;
            animation: fadeInUp 1s ease;
        }

        .hero p {
            font-size: 1.3rem;
            margin-bottom: 2rem;
            opacity: 0.9;
            animation: fadeInUp 1s ease 0.2s both;
        }

        .cta-button {
            display: inline-block;
            background: linear-gradient(45deg, #ff6b6b, #ff8e53);
            color: white;
            padding: 1rem 2rem;
            text-decoration: none;
            border-radius: 50px;
            font-weight: bold;
            transition: all 0.3s ease;
            box-shadow: 0 10px 30px rgba(255, 107, 107, 0.4);
            animation: fadeInUp 1s ease 0.4s both;
        }

        .cta-button:hover {
            transform: translateY(-3px);
            box-shadow: 0 15px 40px rgba(255, 107, 107, 0.6);
        }

        /* Main Content */
        main {
            background: white;
            margin: 2rem 0;
            border-radius: 20px;
            overflow: hidden;
            box-shadow: 0 20px 60px rgba(0, 0, 0, 0.1);
        }

        /* Featured Books */
        .featured-section {
            padding: 4rem 0;
            background: linear-gradient(135deg, #f093fb 0%, #f5576c 100%);
            color: white;
        }

        .section-title {
            text-align: center;
            font-size: 2.5rem;
            margin-bottom: 3rem;
            position: relative;
        }

        .section-title::after {
            content: '';
            width: 100px;
            height: 4px;
            background: white;
            position: absolute;
            bottom: -10px;
            left: 50%;
            transform: translateX(-50%);
            border-radius: 2px;
        }

        .books-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            margin-top: 2rem;
        }

        .book-card {
            background: rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(10px);
            border-radius: 15px;
            padding: 2rem;
            text-align: center;
            transition: all 0.3s ease;
            border: 1px solid rgba(255, 255, 255, 0.2);
        }

        .book-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.2);
        }

        .book-cover {
            width: 150px;
            height: 200px;
            background: linear-gradient(45deg, #ff9a9e, #fecfef);
            border-radius: 10px;
            margin: 0 auto 1rem;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 3rem;
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.2);
        }

        .book-title {
            font-size: 1.3rem;
            font-weight: bold;
            margin-bottom: 0.5rem;
        }

        .book-description {
            opacity: 0.9;
            margin-bottom: 1rem;
        }

        .download-btn {
            background: rgba(255, 255, 255, 0.2);
            color: white;
            border: 2px solid white;
            padding: 0.8rem 1.5rem;
            border-radius: 25px;
            text-decoration: none;
            font-weight: bold;
            transition: all 0.3s ease;
            display: inline-block;
        }

        .download-btn:hover {
            background: white;
            color: #f5576c;
            transform: scale(1.05);
        }

        /* Categories Section */
        .categories-section {
            padding: 4rem 0;
            background: #f8f9ff;
        }

        .categories-section .section-title {
            color: #333;
        }

        .categories-section .section-title::after {
            background: linear-gradient(45deg, #ff6b6b, #4ecdc4);
        }

        .categories-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
            margin-top: 2rem;
        }

        .category-card {
            background: white;
            border-radius: 15px;
            padding: 2rem;
            text-align: center;
            transition: all 0.3s ease;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
            cursor: pointer;
        }

        .category-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 15px 40px rgba(0, 0, 0, 0.15);
        }

        .category-icon {
            font-size: 3rem;
            margin-bottom: 1rem;
            display: block;
        }

        .category-title {
            font-size: 1.3rem;
            font-weight: bold;
            color: #333;
            margin-bottom: 0.5rem;
        }

        .category-count {
            color: #666;
            font-size: 0.9rem;
        }

        /* Newsletter Section */
        .newsletter-section {
            padding: 4rem 0;
            background: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%);
            color: white;
            text-align: center;
        }

        .newsletter-form {
            max-width: 500px;
            margin: 2rem auto 0;
            display: flex;
            gap: 1rem;
        }

        .newsletter-input {
            flex: 1;
            padding: 1rem;
            border: none;
            border-radius: 25px;
            font-size: 1rem;
            outline: none;
        }

        .newsletter-btn {
            background: rgba(255, 255, 255, 0.2);
            color: white;
            border: 2px solid white;
            padding: 1rem 2rem;
            border-radius: 25px;
            font-weight: bold;
            cursor: pointer;
            transition: all 0.3s ease;
        }

        .newsletter-btn:hover {
            background: white;
            color: #4facfe;
        }

        /* Footer */
        footer {
            background: #2c3e50;
            color: white;
            padding: 3rem 0 1rem;
        }

        .footer-content {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
            margin-bottom: 2rem;
        }

        .footer-section h3 {
            margin-bottom: 1rem;
            color: #4ecdc4;
        }

        .footer-section a {
            color: #bdc3c7;
            text-decoration: none;
            transition: color 0.3s ease;
        }

        .footer-section a:hover {
            color: #4ecdc4;
        }

        .footer-bottom {
            text-align: center;
            padding-top: 2rem;
            border-top: 1px solid #34495e;
            color: #bdc3c7;
        }

        /* Animations */
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

        /* Responsive Design */
        @media (max-width: 768px) {
            .nav-links {
                display: none;
            }
            
            .hero h1 {
                font-size: 2.5rem;
            }
            
            .newsletter-form {
                flex-direction: column;
            }
            
            .newsletter-input,
            .newsletter-btn {
                width: 100%;
            }
        }

        /* Floating Animation */
        .floating {
            animation: floating 3s ease-in-out infinite;
        }

        @keyframes floating {
            0%, 100% { transform: translateY(0px); }
            50% { transform: translateY(-10px); }
        }
    </style>
</head>
<body>
    <header>
        <nav class="container">
            <div class="logo">📚 StoryLand</div>
            <ul class="nav-links">
                <li><a href="#home">Home</a></li>
                <li><a href="#books">Free Books</a></li>
                <li><a href="#categories">Categories</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero" id="home">
        <div class="container">
            <h1 class="floating">Free E-Books for Kids</h1>
            <p>Discover magical stories that spark imagination and learning</p>
            <a href="#books" class="cta-button">Start Reading Now</a>
        </div>
    </section>

    <main>
        <section class="featured-section" id="books">
            <div class="container">
                <h2 class="section-title">Featured Free Children's E-Books</h2>
                <div class="books-grid">
                    <article class="book-card" itemscope itemtype="https://schema.org/Book">
                        <div class="book-cover">🦁</div>
                        <h3 class="book-title" itemprop="name">The Brave Little Lion</h3>
                        <p class="book-description" itemprop="description">A heartwarming tale about courage and friendship in the African savanna. Perfect for children ages 4-8.</p>
                        <meta itemprop="author" content="StoryLand Authors">
                        <meta itemprop="genre" content="Children's Adventure">
                        <meta itemprop="bookFormat" content="EBook/PDF">
                        <meta itemprop="price" content="0">
                        <a href="#" class="download-btn" onclick="downloadBook('brave-lion')" itemprop="url">Download Free PDF</a>
                    </article>
                    <article class="book-card" itemscope itemtype="https://schema.org/Book">
                        <div class="book-cover">🌟</div>
                        <h3 class="book-title" itemprop="name">Magic Stars Adventure</h3>
                        <p class="book-description" itemprop="description">Join Luna on her magical journey through the constellation kingdom. Educational and entertaining for kids 5-10.</p>
                        <meta itemprop="author" content="StoryLand Authors">
                        <meta itemprop="genre" content="Children's Fantasy">
                        <meta itemprop="bookFormat" content="EBook/PDF">
                        <meta itemprop="price" content="0">
                        <a href="#" class="download-btn" onclick="downloadBook('magic-stars')" itemprop="url">Download Free PDF</a>
                    </article>
                    <article class="book-card" itemscope itemtype="https://schema.org/Book">
                        <div class="book-cover">🐸</div>
                        <h3 class="book-title" itemprop="name">Freddy the Friendly Frog</h3>
                        <p class="book-description" itemprop="description">Learn about friendship and kindness with Freddy and his pond friends. Great for bedtime reading ages 3-7.</p>
                        <meta itemprop="author" content="StoryLand Authors">
                        <meta itemprop="genre" content="Children's Educational">
                        <meta itemprop="bookFormat" content="EBook/PDF">
                        <meta itemprop="price" content="0">
                        <a href="#" class="download-btn" onclick="downloadBook('freddy-frog')" itemprop="url">Download Free PDF</a>
                    </article>
                </div>
            </div>
        </section>

        <section class="categories-section" id="categories">
            <div class="container">
                <h2 class="section-title">Book Categories</h2>
                <div class="categories-grid">
                    <div class="category-card" onclick="showCategory('adventure')">
                        <span class="category-icon">🏴‍☠️</span>
                        <h3 class="category-title">Adventure</h3>
                        <p class="category-count">25 Books Available</p>
                    </div>
                    <div class="category-card" onclick="showCategory('fairy-tales')">
                        <span class="category-icon">🧚</span>
                        <h3 class="category-title">Fairy Tales</h3>
                        <p class="category-count">18 Books Available</p>
                    </div>
                    <div class="category-card" onclick="showCategory('educational')">
                        <span class="category-icon">🎓</span>
                        <h3 class="category-title">Educational</h3>
                        <p class="category-count">32 Books Available</p>
                    </div>
                    <div class="category-card" onclick="showCategory('animals')">
                        <span class="category-icon">🐾</span>
                        <h3 class="category-title">Animals</h3>
                        <p class="category-count">22 Books Available</p>
                    </div>
                </div>
            </div>
        </section>

        <section class="newsletter-section">
            <div class="container">
                <h2 class="section-title">Get New Books First!</h2>
                <p>Subscribe to our newsletter and be the first to know about new free e-books</p>
                <form class="newsletter-form" onsubmit="subscribeNewsletter(event)">
                    <input type="email" class="newsletter-input" placeholder="Enter your email address" required>
                    <button type="submit" class="newsletter-btn">Subscribe</button>
                </form>
            </div>
        </section>
    </main>

    <footer>
        <div class="container">
            <div class="footer-content">
                <div class="footer-section">
                    <h3>About StoryLand</h3>
                    <p>We believe every child deserves access to quality books. Our mission is to provide free, engaging e-books that inspire young minds and foster a love for reading.</p>
                </div>
                <div class="footer-section">
                    <h3>Quick Links</h3>
                    <ul style="list-style: none;">
                        <li><a href="#books">Free Books</a></li>
                        <li><a href="#categories">Categories</a></li>
                        <li><a href="#about">About Us</a></li>
                        <li><a href="#contact">Contact</a></li>
                    </ul>
                </div>
                <div class="footer-section">
                    <h3>Categories</h3>
                    <ul style="list-style: none;">
                        <li><a href="#">Adventure Stories</a></li>
                        <li><a href="#">Fairy Tales</a></li>
                        <li><a href="#">Educational Books</a></li>
                        <li><a href="#">Animal Stories</a></li>
                    </ul>
                </div>
                <div class="footer-section">
                    <h3>Contact Info</h3>
                    <p>📧 hello@storyland.com</p>
                    <p>📱 +1 (555) 123-4567</p>
                    <p>🌐 www.storyland.com</p>
                </div>
            </div>
            <div class="footer-bottom">
                <p>&copy; 2025 StoryLand. All rights reserved.
