# Novel
Legoo
<br>
author-ari
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cute Novel Store</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <h1>Midori</h1>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#featured">Featured</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
   
            <button id="logoutButton" onclick="window.location.href='first.html';">Logout</button>
        <div class="alert">
  <span class="logoutButton" onclick="this.parentElement.style.display='none';">&times;</span>
  This is an alert box.
</div>

            </ul>
<input type="text" id="searchBox" placeholder="Search novels..." onkeyup="searchNovels()">

        </nav>
    </header>
    
    <main>
        <section id="home">
            <h2>Welcome to the Cute Novel Store!</h2>
            <p>Discover the best novels to read and fall in love with.</p>
        </section>
        
        <section id="featured">
            <h2>Featured Novels</h2>
            <div class="novel-list">
                <div class="novel">
                    <img src="greena.jpg" alt="MENDAK">
                    <h3>MENDAK</h3>
                    <p>Author: Author Name</p>
                    <button onclick="addToCart('MENDAK')">Add to Cart</button>
                </div>
                <div class="novel">
                    <img src="green2.jpg" alt="Novel 2" height="150">
                    <h3>MAGARMACH</h3>
                    <p>Author: Author Name</p>
                    <button onclick="addToCart('Novel Title 2')">Add to Cart</button>
                </div>
                <!-- Add more novels as needed -->
            </div>
        </section>
    </main>
    
    <footer>
        <p>Follow us on:</p>
        <ul>
            <li><a href="#">Facebook</a></li>
            <li><a href="#">Twitter</a></li>
            <li><a href="#">Instagram</a></li>
        </ul>
    </footer>

    <script src="script.js"></script>
</body>
</html>
