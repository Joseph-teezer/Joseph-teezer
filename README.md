<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Oladipo Joseph, popularly known as Joseph Teezer, is a magician from Nigeria. Follow him on Instagram, TikTok, and Twitter.">
    <meta name="author" content="Oladipo Joseph">
    <meta property="og:title" content="Oladipo Joseph - Joseph Teezer">
    <meta property="og:description" content="Oladipo Joseph, known as Joseph Teezer, is a magician from Nigeria. Follow his magic journey on social media.">
    <meta property="og:image" content="URL_TO_YOUR_IMAGE">
    <meta property="og:url" content="YOUR_WEBSITE_URL">
    <meta name="twitter:card" content="summary_large_image">
    <title>Oladipo Joseph - Joseph Teezer</title>
    <style>
        body, html {
            height: 100%;
            margin: 0;
            overflow: hidden;
            font-family: Arial, sans-serif;
            color: white;
            text-align: center;
            background: black;
        }

        .navbar {
            width: 100%;
            background: #333;
            overflow: auto;
            position: fixed;
            top: 0;
            z-index: 2;
        }

        .navbar a {
            float: left;
            padding: 14px 20px;
            color: white;
            text-decoration: none;
            text-align: center;
        }

        .navbar a:hover {
            background-color: #ddd;
            color: black;
        }

        .sparkles {
            position: absolute;
            width: 100%;
            height: 100%;
            overflow: hidden;
            z-index: 0;
        }

        .sparkle {
            position: absolute;
            width: 5px;
            height: 5px;
            background: white;
            opacity: 0.8;
            border-radius: 50%;
            box-shadow: 0 0 10px rgba(255, 255, 255, 0.5);
            animation: sparkle 3s linear infinite;
        }

        @keyframes sparkle {
            0% {
                opacity: 0;
                transform: translateY(0) scale(1);
            }
            50% {
                opacity: 1;
                transform: translateY(-100px) scale(1.5);
            }
            100% {
                opacity: 0;
                transform: translateY(0) scale(1);
            }
        }

        .content {
            position: relative;
            z-index: 1;
            padding: 80px 20px 50px;
        }

        h1 {
            margin-top: 0;
        }

        p {
            font-size: 1.2em;
        }

        .social-links a {
            color: #00acee; /* Twitter Blue */
            text-decoration: none;
            margin: 0 10px;
        }

        .social-links a:hover {
            text-decoration: underline;
        }

        footer {
            background: #333;
            color: white;
            padding: 10px 20px;
            position: fixed;
            bottom: 0;
            width: 100%;
            text-align: center;
            z-index: 2;
        }
    </style>
</head>
<body>
    <div class="navbar">
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#social">Social Links</a>
        <a href="#contact">Contact</a>
    </div>

    <div class="sparkles" id="sparkles"></div>
    
    <div class="content" id="home">
        <h1>Oladipo Joseph - Joseph Teezer</h1>
        <p>Born and raised in Nigeria, popularly known as Joseph Teezer, I'm a magician.</p>
    </div>

    <div class="content" id="about">
        <h2>About Me</h2>
        <p>Joseph Teezer, the magician, brings joy and wonder through his magical performances. With a passion for illusion and sleight of hand, he captivates audiences of all ages.</p>
    </div>

    <div class="content" id="social">
        <h2>Follow me on:</h2>
        <p class="social-links">
            <a href="https://www.instagram.com/josephteezer" target="_blank">Instagram</a> | 
            <a href="https://www.tiktok.com/@joseph.teezer?_r=1&_d=edae47ci843819&sec_uid=MS4wLjABAAAAWlvcRWjf0aGosiXcp0bDCnLB4cU4wJi_p4yfTLXbMqetRLVjqmnJIbMPHFagMFEg&share_author_id=7243007047074644997&sharer_language=en&source=h5_m&u_code=e8bgkfg58g8d01&ug_btm=b8727,b0&social_share_type=4&utm_source=copy&sec_user_id=MS4wLjABAAAAWlvcRWjf0aGosiXcp0bDCnLB4cU4wJi_p4yfTLXbMqetRLVjqmnJIbMPHFagMFEg&tt_from=copy&utm_medium=ios&utm_campaign=client_share&enable_checksum=1&user_id=7243007047074644997&share_link_id=1097B8DF-EC9E-403D-95ED-32D625C4674D&share_app_id=1233" target="_blank">TikTok</a> | 
            <a href="https://x.com/slimteezer" target="_blank">Twitter</a>
        </p>
    </div>

    <div class="content" id="contact">
        <h2>Contact</h2>
        <p>For bookings and inquiries, please reach out to me via social media.</p>
    </div>

    <footer>
        &copy; 2024 Oladipo Joseph. All rights reserved.
    </footer>

    <script>
        const numSparkles = 100;

        for (let i = 0; i < numSparkles; i++) {
            const sparkle = document.createElement('div');
            sparkle.classList.add('sparkle');
            sparkle.style.left = `${Math.random() * 100}%`;
            sparkle.style.top = `${Math.random() * 100}%`;
            sparkle.style.animationDelay = `${Math.random() * 3}s`;
            document.getElementById('sparkles').appendChild(sparkle);
        }
    </script>
</body>
</html>
