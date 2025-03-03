<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Evergreen Landscaping</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(to bottom, #4CAF50, #2E8B57), url('background-pattern.png');
            background-size: cover, 100px 100px;
            color: white;
        }
        header {
            background-color: rgba(0, 100, 0, 0.8);
            color: white;
            padding: 20px;
            text-align: center;
            font-size: 24px;
            position: relative;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        header img {
            max-width: 250px;
            display: block;
            margin: 0 auto;
        }
        .call-now {
            position: absolute;
            top: 20px;
            right: 20px;
            background-color: #FFD700;
            color: black;
            padding: 10px 15px;
            border-radius: 5px;
            text-decoration: none;
            font-weight: bold;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
        }
        .call-now:hover {
            background-color: #FFC107;
        }
        nav {
            background-color: #333;
            padding: 10px;
            text-align: center;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 14px 20px;
            display: inline-block;
        }
        nav a:hover {
            background-color: #575757;
        }
        .hero {
            background: url('hero-landscaping.jpg') no-repeat center center/cover;
            height: 300px;
            color: white;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            font-size: 28px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
        }
        .container {
            padding: 20px;
            text-align: center;
            background: rgba(255, 255, 255, 0.2);
            border-radius: 10px;
            margin: 20px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        .service {
            background: rgba(255, 255, 255, 0.3);
            margin: 10px;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.3);
            color: white;
            text-align: left;
        }
        .slideshow-container {
            position: relative;
            max-width: 400px;
            margin: auto;
        }
        .slide {
            display: none;
        }
        .slide img {
            width: 100%;
            border-radius: 8px;
        }
    </style>
</head>
<body>
    <header>
        <img src="IMG_6054.jpg" alt="Evergreen Landscaping Logo">
        Evergreen Landscaping
        <a href="tel:3175169452" class="call-now">📞 Call Now</a>
    </header>
    <nav>
        <a href="#lawn-care">Lawn Care</a>
        <a href="#mulching">Mulch Installation</a>
        <a href="#tree-removal">Tree Removal</a>
    </nav>
    <div class="hero">Professional Landscaping Services</div>
    <div class="container" id="lawn-care">
        <h2>Lawn Care</h2>
        <p>Our comprehensive lawn care services include regular mowing, edging, aeration, and dethatching. We also provide fertilization programs tailored to your lawn’s specific needs and seasonal requirements, ensuring it remains green and healthy all year long.</p>
        <div class="slideshow-container" id="lawn-care-slideshow">
            <div class="slide"><img src="IMG_3532.HEIC" alt="Lawn Care Image 1"></div>
            <div class="slide"><img src="IMG_3574.HEIC" alt="Lawn Care Image 2"></div>
            <div class="slide"><img src="IMG_6140.DNG" alt="Lawn Care Image 3"></div>
        </div>
    </div>
    <div class="container" id="mulching">
        <h2>Mulch Installation</h2>
        <p>Our professional mulch installation service helps conserve moisture, suppress weeds, and enhance the appearance of your landscape. We use high-quality mulch materials to improve soil health and protect plant roots.</p>
        <div class="slideshow-container" id="mulching-slideshow">
            <div class="slide"><img src="IMG_3665.HEIC" alt="Mulching Image 1"></div>
            <div class="slide"><img src="IMG_3666.HEIC" alt="Mulching Image 2"></div>
            <div class="slide"><img src="IMG_3667.HEIC" alt="Mulching Image 3"></div>
        </div>
    </div>
    <div class="container" id="tree-removal">
        <h2>Tree Removal and Land Clearance</h2>
        <p>We specialize in tree removal and land clearance services, ensuring your property is safe and cleared efficiently. Whether it's hazardous trees, overgrown areas, or preparing a site for new development, our professional team handles it with precision and care.</p>
        <div class="slideshow-container" id="tree-removal-slideshow">
            <div class="slide"><img src="IMG_3866.HEIC" alt="Tree Removal Image 1"></div>
            <div class="slide"><img src="IMG_3880.HEIC" alt="Tree Removal Image 2"></div>
            <div class="slide"><img src="IMG_3883.HEIC" alt="Tree Removal Image 3"></div>
        </div>
    </div>
    <footer>&copy; 2025 Evergreen Landscaping. All rights reserved.</footer>
</body>
</html>

