<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Designer Portfolio</title>
    <link rel="stylesheet" href="C:\Users\jaanu\Desktop\portfolio.css">
</head>
<body>
    <header>
        <h1>VJ CLOTHING</h1>
    </header>
    <nav>
        <ul>
            <li><a href="branding.com">VJ</a></li>
            <li><a href="webdesign.com">Web Design</a></li>
            <li><a href="printdesign.com">Code More 
    </nav>
    <main>Design</a></li>
        </ul>
        <section id="branding" class="portfolio-category">
            <h2>Branding</h2>
            <div class="VJ" onclick="openModal('branding.com')">
                <img src="C:\Users\jaanu\Desktop\logo.jpg" alt="Vj brands">
                <p>VJ BRANDING CLOTH</p>
            </div>
            <!-- Add more items here -->
        </section>
        <section id="web-design" class="portfolio-category">
            <h2>Web Design</h2>
            <div class="" onclick="openModal('webdesign.com')">
                <img src="C:\Users\jaanu\Pictures\website.png" alt="Web Design">
                <p>Web Page</p>
            </div>
            <!-- Add more items here -->
        </section>
        <section id="print-design" class="portfolio-category">
            <h2>Code More</h2>
            <div class="CodeMore" onclick="openModal('printdesign.com')">
                <img src="C:\Users\jaanu\Pictures\PRINTDESIGN.png" alt="Code More Tshirts">
                <p>Code More T-shirts</p>
            </div>
            <!-- Add more items here -->
        </section>
    </main>

    <div id="modal" class="modal">
        <span class="close" onclick="closeModal()">&times;</span>
        <img class="modal-content" id="modal-image">
        <div id="caption"></div>
    </div>

    <script src="C:\Users\jaanu\Desktop\portfolio.js"></script>
</body>
</html>
