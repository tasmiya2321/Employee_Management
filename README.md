<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Fantastic Side Navigation Bar</title>
    <script src="https://kit.fontawesome.com/bc0ac06df1.js" crossorigin="anonymous"></script>
</head>
<style>
    body {
        margin: 0;
        padding: 0;
        font-family: Arial, sans-serif;
        background-color: #fffcfc;
        overflow: hidden;
    }
    
    header {
        
      
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 10px 20px;
       
    }
    
    .logo img {
        height: 40px;
    }
    
    .menu-toggle {
        display: flex;
        flex-direction: column;
        cursor: pointer;
        transition: transform 0.3s;
    }
    
    .menu-toggle:hover {
        transform: scale(1.1);
    }
    
    .bar {
        width: 25px;
        height: 3px;
        background-color: #1e1c1c;
        margin: 3px 0;
        transition: background-color 0.3s, transform 0.3s;
    }
    
    .bar:hover {
        background-color: orange;
    }
    
    nav#sidebar {
        position: fixed;
        left: -250px;
        top: 0;
        width: 250px;
        height: 100%;
        background-color:white;
        overflow-y: auto;
        transition: left 0.5s, transform 0.5s;
        transform: scaleX(0);
    }
    
    nav#sidebar.active {
        left: 0;
        transform: scaleX(1);
    }
    
    nav#sidebar ul {
        padding: 0;
        list-style: none;
    }
    
    nav#sidebar ul li {
        padding: 15px;
        text-align: center;
        opacity: 0;
        transform: translateY(20px);
        transition: opacity 0.5s, transform 0.5s;
    }
    
    nav#sidebar.active ul li {
        opacity: 1;
        transform: translateY(0);
    }
    
    nav#sidebar ul li a {
        text-decoration: none;
        color: #100d0d;
        transition: color 0.3s;
    }
    
    nav#sidebar ul li a:hover {
        color: orange;
    }
    
</style>
<body>
    <header>
       
        <div class="menu-toggle" id="menuToggle">
            <div class="bar"></div>
            <div class="bar"></div>
            <div class="bar"></div>
        </div>
    </header>
    <nav id="sidebar">
        <ul>
            <li>
                <img src="./Copy of Creating Futures Desktop Prototype (1).jpg" width="110%">
            </li>
            <li><a href="#"><i class="fa-solid fa-house" style="color: #d66e29;"></i>Home</a></li>
            <li><a href="#"><i class="fa-solid fa-business-time" style="color: #c58326;"></i>Sessions</a></li>
            <li><a href="#"><i class="fa-solid fa-chart-simple" style="color: #dd7c22;"></i>Details</a></li>
           
        </ul>
    </nav>
    <main>
        <!-- Your content goes here -->
    </main>
    <script>
        const menuToggle = document.getElementById("menuToggle");
const sidebar = document.getElementById("sidebar");

menuToggle.addEventListener("click", () => {
    sidebar.classList.toggle("active");
});

// Close the sidebar if the user clicks outside of it
window.addEventListener("click", (event) => {
    if (sidebar.classList.contains("active") && event.target !== menuToggle && event.target !== sidebar) {
        sidebar.classList.remove("active");
    }
});

    </script>
</body>
</html>
