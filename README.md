<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="SVD - Social Video Downloader. Download videos from popular platforms in HD, Full HD, 2K, and 4K quality for free.">
    <meta name="keywords" content="video downloader, social media downloader, youtube downloader, instagram downloader, facebook downloader, tiktok downloader, 4K video download">
    <meta name="author" content="SVD Tools">
    <meta property="og:title" content="SVD - Social Video Downloader">
    <meta property="og:description" content="Download videos from social media in multiple resolutions including 480p, 720p, 1080p, 2K and 4K">
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://svd-downloader.com">
    <meta property="og:image" content="https://svd-downloader.com/images/svd-preview.jpg">
    <title>SVD - Social Video Downloader | Download HD Videos from Social Media</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-YOUR_ADSENSE_ID" crossorigin="anonymous"></script>
    <style>
        :root {
            --primary: #6c5ce7;
            --secondary: #a29bfe;
            --accent: #fd79a8;
            --dark: #2d3436;
            --light: #f5f6fa;
            --success: #00b894;
            --warning: #fdcb6e;
            --danger: #d63031;
            --gradient: linear-gradient(135deg, var(--primary), var(--accent));
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background-color: var(--light);
            color: var(--dark);
            line-height: 1.6;
            overflow-x: hidden;
        }
        
        .container {
            width: 100%;
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        header {
            background: var(--gradient);
            color: white;
            padding: 20px 0;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
            position: relative;
            overflow: hidden;
        }
        
        header::before {
            content: '';
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: radial-gradient(circle, rgba(255,255,255,0.1) 0%, rgba(255,255,255,0) 70%);
            animation: pulse 8s infinite linear;
            z-index: 0;
        }
        
        @keyframes pulse {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }
        
        .header-content {
            position: relative;
            z-index: 1;
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;
        }
        
        .logo {
            display: flex;
            align-items: center;
            gap: 10px;
            font-size: 1.8rem;
            font-weight: 700;
            text-decoration: none;
            color: white;
        }
        
        .logo i {
            font-size: 2.2rem;
            color: var(--accent);
        }
        
        nav ul {
            display: flex;
            list-style: none;
            gap: 20px;
        }
        
        nav a {
            color: white;
            text-decoration: none;
            font-weight: 500;
            transition: all 0.3s ease;
            padding: 5px 10px;
            border-radius: 5px;
        }
        
        nav a:hover {
            background-color: rgba(255, 255, 255, 0.2);
        }
        
        .hero {
            text-align: center;
            padding: 60px 0 40px;
            position: relative;
        }
        
        .hero h1 {
            font-size: 2.5rem;
            margin-bottom: 20px;
            background: var(--gradient);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            animation: fadeIn 1s ease;
        }
        
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        
        .hero p {
            font-size: 1.1rem;
            color: var(--dark);
            max-width: 700px;
            margin: 0 auto 30px;
            opacity: 0.9;
        }
        
        .download-box {
            background: white;
            border-radius: 12px;
            padding: 30px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
            margin-bottom: 40px;
            transform: translateY(0);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        
        .download-box:hover {
            transform: translateY(-5px);
            box-shadow: 0 15px 35px rgba(0, 0, 0, 0.15);
        }
        
        .input-group {
            display: flex;
            gap: 10px;
            margin-bottom: 20px;
        }
        
        .input-group input {
            flex: 1;
            padding: 15px;
            border: 2px solid #ddd;
            border-radius: 8px;
            font-size: 1rem;
            transition: all 0.3s ease;
        }
        
        .input-group input:focus {
            border-color: var(--primary);
            outline: none;
            box-shadow: 0 0 0 3px rgba(108, 92, 231, 0.2);
        }
        
        .btn {
            padding: 15px 25px;
            border: none;
            border-radius: 8px;
            font-size: 1rem;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.3s ease;
            display: inline-flex;
            align-items: center;
            gap: 8px;
        }
        
        .btn-primary {
            background: var(--gradient);
            color: white;
        }
        
        .btn-primary:hover {
            transform: translateY(-2px);
            box-shadow: 0 5px 15px rgba(108, 92, 231, 0.4);
        }
        
        .btn-secondary {
            background: var(--light);
            color: var(--dark);
            border: 1px solid #ddd;
        }
        
        .btn-secondary:hover {
            background: #f0f0f0;
        }
        
        .supported-platforms {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 15px;
            margin-bottom: 40px;
        }
        
        .platform {
            display: flex;
            align-items: center;
            gap: 8px;
            background: white;
            padding: 10px 15px;
            border-radius: 50px;
            box-shadow: 0 3px 10px rgba(0, 0, 0, 0.05);
            transition: all 0.3s ease;
        }
        
        .platform:hover {
            transform: translateY(-3px);
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
        }
        
        .platform i {
            font-size: 1.2rem;
        }
        
        .youtube { color: #FF0000; }
        .instagram { color: #E1306C; }
        .facebook { color: #1877F2; }
        .tiktok { color: #000000; }
        .twitter { color: #1DA1F2; }
        
        .ad-container {
            background: white;
            padding: 20px;
            border-radius: 8px;
            margin: 30px 0;
            text-align: center;
            box-shadow: 0 3px 10px rgba(0, 0, 0, 0.05);
        }
        
        .ad-label {
            font-size: 0.8rem;
            color: #999;
            margin-bottom: 10px;
            text-transform: uppercase;
            letter-spacing: 1px;
        }
        
        .results {
            display: none;
            background: white;
            border-radius: 12px;
            padding: 30px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
            margin-bottom: 40px;
            animation: fadeIn 0.5s ease;
        }
        
        .results-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 20px;
            padding-bottom: 15px;
            border-bottom: 1px solid #eee;
        }
        
        .results-title {
            font-size: 1.3rem;
            font-weight: 600;
            color: var(--dark);
        }
        
        .quality-options {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
            gap: 15px;
        }
        
        .quality-option {
            background: var(--light);
            border-radius: 8px;
            padding: 15px;
            display: flex;
            flex-direction: column;
            gap: 10px;
            transition: all 0.3s ease;
        }
        
        .quality-option:hover {
            background: #f0f0f0;
            transform: translateY(-3px);
        }
        
        .quality-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .quality-name {
            font-weight: 600;
            color: var(--dark);
        }
        
        .quality-size {
            font-size: 0.9rem;
            color: #777;
        }
        
        .download-btn {
            width: 100%;
            padding: 10px;
            background: var(--success);
            color: white;
            border: none;
            border-radius: 5px;
            font-weight: 500;
            cursor: pointer;
            transition: all 0.3s ease;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 8px;
        }
        
        .download-btn:hover {
            background: #00a884;
        }
        
        .features {
            padding: 60px 0;
            background: linear-gradient(to bottom, #f9f9f9, white);
        }
        
        .section-title {
            text-align: center;
            font-size: 2rem;
            margin-bottom: 40px;
            color: var(--dark);
        }
        
        .features-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
        }
        
        .feature-card {
            background: white;
            border-radius: 12px;
            padding: 30px;
            box-shadow: 0 5px 20px rgba(0, 0, 0, 0.05);
            transition: all 0.3s ease;
            text-align: center;
        }
        
        .feature-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.1);
        }
        
        .feature-icon {
            font-size: 2.5rem;
            margin-bottom: 20px;
            background: var(--gradient);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
        }
        
        .feature-title {
            font-size: 1.3rem;
            margin-bottom: 15px;
            color: var(--dark);
        }
        
        .feature-desc {
            color: #666;
            font-size: 0.95rem;
        }
        
        footer {
            background: var(--dark);
            color: white;
            padding: 50px 0 20px;
        }
        
        .footer-content {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 30px;
            margin-bottom: 40px;
        }
        
        .footer-column h3 {
            font-size: 1.2rem;
            margin-bottom: 20px;
            position: relative;
            padding-bottom: 10px;
        }
        
        .footer-column h3::after {
            content: '';
            position: absolute;
            left: 0;
            bottom: 0;
            width: 40px;
            height: 3px;
            background: var(--gradient);
            border-radius: 3px;
        }
        
        .footer-links {
            list-style: none;
        }
        
        .footer-links li {
            margin-bottom: 10px;
        }
        
        .footer-links a {
            color: #bbb;
            text-decoration: none;
            transition: all 0.3s ease;
        }
        
        .footer-links a:hover {
            color: white;
            padding-left: 5px;
        }
        
        .social-links {
            display: flex;
            gap: 15px;
            margin-top: 20px;
        }
        
        .social-links a {
            display: flex;
            align-items: center;
            justify-content: center;
            width: 40px;
            height: 40px;
            border-radius: 50%;
            background: rgba(255, 255, 255, 0.1);
            color: white;
            transition: all 0.3s ease;
        }
        
        .social-links a:hover {
            background: var(--primary);
            transform: translateY(-3px);
        }
        
        .copyright {
            text-align: center;
            padding-top: 20px;
            border-top: 1px solid rgba(255, 255, 255, 0.1);
            font-size: 0.9rem;
            color: #bbb;
        }
        
        .loading {
            display: none;
            text-align: center;
            padding: 20px;
        }
        
        .spinner {
            width: 40px;
            height: 40px;
            margin: 0 auto 15px;
            border: 4px solid rgba(108, 92, 231, 0.2);
            border-radius: 50%;
            border-top-color: var(--primary);
            animation: spin 1s linear infinite;
        }
        
        @keyframes spin {
            to { transform: rotate(360deg); }
        }
        
        /* Responsive styles */
        @media (max-width: 768px) {
            .header-content {
                flex-direction: column;
                gap: 20px;
            }
            
            nav ul {
                flex-wrap: wrap;
                justify-content: center;
            }
            
            .hero h1 {
                font-size: 2rem;
            }
            
            .input-group {
                flex-direction: column;
            }
            
            .btn {
                width: 100%;
                justify-content: center;
            }
            
            .quality-options {
                grid-template-columns: 1fr;
            }
            
            .features-grid {
                grid-template-columns: 1fr;
            }
        }
        
        /* Animation classes */
        .animate-bounce {
            animation: bounce 2s infinite;
        }
        
        @keyframes bounce {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-10px); }
        }
        
        .animate-pulse {
            animation: pulse 2s infinite;
        }
        
        /* Tooltip */
        .tooltip {
            position: relative;
            display: inline-block;
        }
        
        .tooltip .tooltiptext {
            visibility: hidden;
            width: 200px;
            background-color: var(--dark);
            color: #fff;
            text-align: center;
            border-radius: 6px;
            padding: 5px;
            position: absolute;
            z-index: 1;
            bottom: 125%;
            left: 50%;
            transform: translateX(-50%);
            opacity: 0;
            transition: opacity 0.3s;
            font-size: 0.8rem;
        }
        
        .tooltip:hover .tooltiptext {
            visibility: visible;
            opacity: 1;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <div class="header-content">
                <a href="#" class="logo">
                    <i class="fas fa-cloud-download-alt"></i>
                    <span>SVD</span>
                </a>
                <nav>
                    <ul>
                        <li><a href="#">Home</a></li>
                        <li><a href="#features">Features</a></li>
                        <li><a href="#how-it-works">How It Works</a></li>
                        <li><a href="#faq">FAQ</a></li>
                        <li><a href="#contact">Contact</a></li>
                    </ul>
                </nav>
            </div>
        </div>
    </header>

    <main class="container">
        <section class="hero">
            <h1>Download Videos from Social Media</h1>
            <p>Paste the URL of your favorite videos from YouTube, Instagram, Facebook, TikTok, and more. Download in multiple resolutions from 480p to 4K.</p>
            
            <div class="download-box">
                <div class="input-group">
                    <input type="text" id="video-url" placeholder="Paste video URL here..." autocomplete="off">
                    <button id="download-btn" class="btn btn-primary">
                        <i class="fas fa-download"></i> Download
                    </button>
                </div>
                <div class="supported-platforms">
                    <div class="platform">
                        <i class="fab fa-youtube youtube"></i>
                        <span>YouTube</span>
                    </div>
                    <div class="platform">
                        <i class="fab fa-instagram instagram"></i>
                        <span>Instagram</span>
                    </div>
                    <div class="platform">
                        <i class="fab fa-facebook facebook"></i>
                        <span>Facebook</span>
                    </div>
                    <div class="platform">
                        <i class="fab fa-tiktok tiktok"></i>
                        <span>TikTok</span>
                    </div>
                    <div class="platform">
                        <i class="fab fa-twitter twitter"></i>
                        <span>Twitter</span>
                    </div>
                </div>
            </div>
            
            <!-- Ad Space 1 -->
            <div class="ad-container">
                <div class="ad-label">Advertisement</div>
                <!-- Replace with your AdSense code -->
                <ins class="adsbygoogle"
                     style="display:block"
                     data-ad-client="ca-pub-YOUR_ADSENSE_ID"
                     data-ad-slot="YOUR_AD_SLOT_ID"
                     data-ad-format="auto"
                     data-full-width-responsive="true"></ins>
                <script>
                     (adsbygoogle = window.adsbygoogle || []).push({});
                </script>
            </div>
            
            <div class="loading" id="loading">
                <div class="spinner"></div>
                <p>Processing your video...</p>
            </div>
            
            <div class="results" id="results">
                <div class="results-header">
                    <h2 class="results-title">Available Download Options</h2>
                    <div class="tooltip">
                        <i class="fas fa-info-circle" style="color: var(--primary);"></i>
                        <span class="tooltiptext">Select your preferred quality. Higher resolutions may take longer to download.</span>
                    </div>
                </div>
                <div class="quality-options" id="quality-options">
                    <!-- Quality options will be dynamically inserted here -->
                </div>
            </div>
        </section>
        
        <!-- Ad Space 2 -->
        <div class="ad-container">
            <div class="ad-label">Advertisement</div>
            <!-- Replace with your AdSense code -->
            <ins class="adsbygoogle"
                 style="display:block"
                 data-ad-client="ca-pub-YOUR_ADSENSE_ID"
                 data-ad-slot="YOUR_AD_SLOT_ID"
                 data-ad-format="auto"
                 data-full-width-responsive="true"></ins>
            <script>
                 (adsbygoogle = window.adsbygoogle || []).push({});
            </script>
        </div>
        
        <section class="features" id="features">
            <h2 class="section-title">Why Choose SVD Downloader?</h2>
            <div class="features-grid">
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-tachometer-alt"></i>
                    </div>
                    <h3 class="feature-title">Fast Processing</h3>
                    <p class="feature-desc">Our servers process your video requests quickly, so you don't have to wait long for your downloads.</p>
                </div>
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-film"></i>
                    </div>
                    <h3 class="feature-title">Multiple Resolutions</h3>
                    <p class="feature-desc">Download videos in various qualities from 480p to stunning 4K resolution, depending on availability.</p>
                </div>
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-shield-alt"></i>
                    </div>
                    <h3 class="feature-title">Safe & Secure</h3>
                    <p class="feature-desc">We don't store your videos or personal data. Your privacy is our priority.</p>
                </div>
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-mobile-alt"></i>
                    </div>
                    <h3 class="feature-title">Mobile Friendly</h3>
                    <p class="feature-desc">Works perfectly on all devices including smartphones and tablets.</p>
                </div>
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-plug"></i>
                    </div>
                    <h3 class="feature-title">No Software Needed</h3>
                    <p class="feature-desc">Works directly in your browser. No need to install any apps or extensions.</p>
                </div>
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-globe"></i>
                    </div>
                    <h3 class="feature-title">Multiple Platforms</h3>
                    <p class="feature-desc">Supports videos from all major social media platforms and video sharing sites.</p>
                </div>
            </div>
        </section>
        
        <!-- How It Works Section -->
        <section class="features" id="how-it-works" style="background: white;">
            <h2 class="section-title">How It Works</h2>
            <div class="features-grid">
                <div class="feature-card">
                    <div class="feature-icon animate-bounce">
                        <i class="fas fa-link"></i>
                    </div>
                    <h3 class="feature-title">1. Paste URL</h3>
                    <p class="feature-desc">Copy and paste the link of the video you want to download into the input field above.</p>
                </div>
                <div class="feature-card">
                    <div class="feature-icon animate-bounce" style="animation-delay: 0.2s;">
                        <i class="fas fa-cogs"></i>
                    </div>
                    <h3 class="feature-title">2. Process Video</h3>
                    <p class="feature-desc">Our system will analyze the video and fetch all available download options.</p>
                </div>
                <div class="feature-card">
                    <div class="feature-icon animate-bounce" style="animation-delay: 0.4s;">
                        <i class="fas fa-download"></i>
                    </div>
                    <h3 class="feature-title">3. Download</h3>
                    <p class="feature-desc">Choose your preferred quality and format, then click download to save the video.</p>
                </div>
            </div>
        </section>
        
        <!-- FAQ Section -->
        <section class="features" id="faq" style="background: linear-gradient(to bottom, #f9f9f9, white);">
            <h2 class="section-title">Frequently Asked Questions</h2>
            <div class="features-grid" style="grid-template-columns: 1fr;">
                <div class="feature-card" style="text-align: left;">
                    <h3 class="feature-title">Is SVD Downloader free to use?</h3>
                    <p class="feature-desc">Yes, our service is completely free to use. We support our service through non-intrusive advertisements.</p>
                    
                    <h3 class="feature-title" style="margin-top: 20px;">What video platforms do you support?</h3>
                    <p class="feature-desc">We support YouTube, Instagram, Facebook, TikTok, Twitter, and many other popular video platforms.</p>
                    
                    <h3 class="feature-title" style="margin-top: 20px;">What video qualities are available?</h3>
                    <p class="feature-desc">Available qualities depend on the source video, but typically range from 144p to 4K resolution when available.</p>
                    
                    <h3 class="feature-title" style="margin-top: 20px;">Is it legal to download videos?</h3>
                    <p class="feature-desc">Downloading videos is generally allowed for personal use. However, distributing copyrighted content or using videos commercially may require permission from the copyright holder.</p>
                    
                    <h3 class="feature-title" style="margin-top: 20px;">Do you store my downloaded videos?</h3>
                    <p class="feature-desc">No, we don't store any videos on our servers. The videos are processed in real-time and served directly to you.</p>
                </div>
            </div>
        </section>
        
        <!-- Ad Space 3 -->
        <div class="ad-container">
            <div class="ad-label">Advertisement</div>
            <!-- Replace with your AdSense code -->
            <ins class="adsbygoogle"
                 style="display:block"
                 data-ad-client="ca-pub-YOUR_ADSENSE_ID"
                 data-ad-slot="YOUR_AD_SLOT_ID"
                 data-ad-format="auto"
                 data-full-width-responsive="true"></ins>
            <script>
                 (adsbygoogle = window.adsbygoogle || []).push({});
            </script>
        </div>
    </main>

    <footer id="contact">
        <div class="container">
            <div class="footer-content">
                <div class="footer-column">
                    <h3>SVD Downloader</h3>
                    <p>The fastest and most reliable social media video downloader. Download videos in HD quality with ease.</p>
                    <div class="social-links">
                        <a href="#"><i class="fab fa-facebook-f"></i></a>
                        <a href="#"><i class="fab fa-twitter"></i></a>
                        <a href="#"><i class="fab fa-instagram"></i></a>
                        <a href="#"><i class="fab fa-youtube"></i></a>
                    </div>
                </div>
                <div class="footer-column">
                    <h3>Quick Links</h3>
                    <ul class="footer-links">
                        <li><a href="#">Home</a></li>
                        <li><a href="#features">Features</a></li>
                        <li><a href="#how-it-works">How It Works</a></li>
                        <li><a href="#faq">FAQ</a></li>
                        <li><a href="#contact">Contact</a></li>
                    </ul>
                </div>
                <div class="footer-column">
                    <h3>Supported Sites</h3>
                    <ul class="footer-links">
                        <li><a href="#">YouTube</a></li>
                        <li><a href="#">Instagram</a></li>
                        <li><a href="#">Facebook</a></li>
                        <li><a href="#">TikTok</a></li>
                        <li><a href="#">Twitter</a></li>
                    </ul>
                </div>
                <div class="footer-column">
                    <h3>Contact Us</h3>
                    <ul class="footer-links">
                        <li><i class="fas fa-envelope"></i> support@svd-downloader.com</li>
                        <li><i class="fas fa-globe"></i> www.svd-downloader.com</li>
                    </ul>
                </div>
            </div>
            <div class="copyright">
                <p>&copy; 2025 SVD - Social Video Downloader. All rights reserved.</p>
            </div>
        </div>
    </footer>

    <script>
        document.addEventListener('DOMContentLoaded', function() {
            const downloadBtn = document.getElementById('download-btn');
            const videoUrlInput = document.getElementById('video-url');
            const resultsSection = document.getElementById('results');
            const loadingSection = document.getElementById('loading');
            const qualityOptions = document.getElementById('quality-options');
            
            // Sample quality options (in a real app, these would come from an API)
            const sampleQualities = [
                { name: '4K Ultra HD', resolution: '2160p', size: '120MB', type: 'MP4' },
                { name: '2K Quad HD', resolution: '1440p', size: '80MB', type: 'MP4' },
                { name: 'Full HD', resolution: '1080p', size: '50MB', type: 'MP4' },
                { name: 'HD', resolution: '720p', size: '30MB', type: 'MP4' },
                { name: 'Standard', resolution: '480p', size: '15MB', type: 'MP4' },
                { name: 'Audio Only', resolution: '128kbps', size: '5MB', type: 'MP3' }
            ];
            
            downloadBtn.addEventListener('click', function() {
                const videoUrl = videoUrlInput.value.trim();
                
                if (!videoUrl) {
                    alert('Please enter a valid video URL');
                    return;
                }
                
                // Show loading animation
                loadingSection.style.display = 'block';
                resultsSection.style.display = 'none';
                
                // Simulate API call with setTimeout
                setTimeout(function() {
                    // Hide loading animation
                    loadingSection.style.display = 'none';
                    
                    // Clear previous results
                    qualityOptions.innerHTML = '';
                    
                    // Generate quality options
                    sampleQualities.forEach(quality => {
                        const optionElement = document.createElement('div');
                        optionElement.className = 'quality-option';
                        optionElement.innerHTML = `
                            <div class="quality-header">
                                <span class="quality-name">${quality.name}</span>
                                <span class="quality-size">${quality.size}</span>
                            </div>
                            <div class="quality-details">
                                <span>Resolution: ${quality.resolution}</span>
                                <span>Format: ${quality.type}</span>
                            </div>
                            <button class="download-btn">
                                <i class="fas fa-download"></i> Download ${quality.type}
                            </button>
                        `;
                        
                        // Add click event to download buttons
                        const downloadBtn = optionElement.querySelector('.download-btn');
                        downloadBtn.addEventListener('click', function() {
                            alert(`Downloading ${quality.name} (${quality.resolution}) version...\n\nIn a real application, this would initiate the download.`);
                        });
                        
                        qualityOptions.appendChild(optionElement);
                    });
                    
                    // Show results section
                    resultsSection.style.display = 'block';
                    
                    // Smooth scroll to results
                    resultsSection.scrollIntoView({ behavior: 'smooth' });
                }, 2000);
            });
            
            // Handle paste event to automatically process if URL is detected
            videoUrlInput.addEventListener('paste', function(e) {
                setTimeout(function() {
                    const pastedText = videoUrlInput.value.trim();
                    if (pastedText.match(/^(http|https):\/\//)) {
                        downloadBtn.click();
                    }
                }, 100);
            });
            
            // Initialize AdSense ads
            (adsbygoogle = window.adsbygoogle || []).push({});
        });
    </script>
</body>
</html>
