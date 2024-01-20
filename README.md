<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Zlearn</title>
    <link rel="stylesheet" type="text/css" href="styles.css">
</head>
<body>

    <nav>
        <ul>
            <li><a href="home.html">Home</a></li>
            <li><a href="about.html">About</a></li>
            <li><a href="features.html">Features</a></li>
            <li><a href="contact.html">Contact</a></li>
            <li class="logout"><a href="loginpage.html">Logout</a></li>
        </ul>
    </nav>

    <section id="about-zlearn">
        <h1>Zlearn: Revolutionizing Education and Technology</h1>

        <h2>Entry for Collabovate Innovation Challenge</h2>
        <p>
            <strong>Name of School:</strong> Aje Comprehensive Senior High School<br>
            <strong>Team Name:</strong> The ZLab<br>
            <strong>Innovation Theme:</strong> Education and Technology
        </p>

        <h2>The Big Idea: Zlearn</h2>
        <p>
            Zlearn is a flagship project of the Techbros of Aje Comprehensive Senior High School, aimed at creating an immersive educational platform that revolutionizes learning processes in our community. Led by Sanni Shazily, our team envisions a future where learning is not only interactive but also fun.
        </p>

        <h2>Zlearn Project Overview: A Glimpse into Zlearn</h2>
        <p>
            Born out of the commitment to solving local educational problems, Zlearn addresses the absence of quality and interactive education in our community. In Nigeria, traditional teaching methods rely heavily on textbooks and physical lectures, limiting learning to the confines of a classroom. Our research revealed that only about 60% of children in Lagos state have access to interactive learning.
        </p>
        <!-- Include additional project overview content here -->

        <h2>Why Zlearn? What Makes Zlearn a Game Changer?</h2>
        <p>
            Zlearn brings a new dimension to learning by offering an immersive educational platform that engages students through interactive content and virtual experiences. From virtual chemistry experiments to historical reenactments, Zlearn provides a wide range of educational opportunities.
        </p>
        <!-- Include additional content about why Zlearn is a game-changer -->

        <h2>Zlearn Unique Features: A Dive into Interactive Education!!</h2>
        <p>
            <strong>1. Immersive Learning Environment:</strong> Zlearn's immersive learning environment takes education beyond the ordinary by engaging students through multiple senses. Imagine learning about the solar system by virtually traveling through it, feeling the gravitational pull, seeing the planets up close, and hearing explanations that bring the subject to life.
        </p>
        <!-- Include details about other unique features -->

        <h2>Choosing Zlearn for Lagos State Future</h2>
        <p>
            We firmly believe that the innovation deserving of the Lagos State Government's investment is one that champions the development of its youth, a call echoed by the humble citizens we aim to empower. The resounding clamor comes not only from the students currently navigating the educational landscape of Lagos State but, more profoundly, from the heart of Generation Z. We are the voice of The ZLab, the heartbeat of Aje Comprehensive Senior High School, and the resonant echo of District IV students.
        </p>
        <!-- Include additional content about choosing Zlearn for Lagos State's future -->
    </section>

    <footer>
        <p>&copy; 2024 Zlearn. All rights reserved.</p>
    </footer>

</body>
</html>



/* Add your existing CSS styles here */

/* Additional styling for the chemistry page */
.experiment-container {
    text-align: center;
    padding: 20px;
}

h1 {
    color: #3498db; /* Experiment title color */
}

.virtual-lab {
    /* Add styling for the virtual lab environment */
    background-color: #f1f1f1; /* Background color for the virtual lab */
    padding: 20px;
    border-radius: 10px; /* Radius for the virtual lab container */
}

.experiment-controls {
    /* Add styling for experiment controls */
    margin-top: 20px;
}




/* Add your existing CSS styles here */

/* Additional styling for the acid-base reaction page */
.acid-container, .base-container, .result-container {
    /* Styling for the containers */
    display: inline-block;
    margin: 10px;
}

img {
    /* Add styling for the animation images */
    max-width: 100%;
    height: auto;
}

/* Add any other styling you need for the content within the acid-base reaction page */


/* Add any other styling you need for the content within the chemistry page */




<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ZLEARN - Chemistry Experiment</title>
    <!-- Link your existing CSS files -->
    <link rel="stylesheet" type="text/css" href="chemistry.css">
    <link href="https://fonts.googleapis.com/css2?family=jost:wght@500&display=swap" rel="stylesheet">
</head>
<body>
    <!-- Your existing HTML content for the chemistry page -->
    <div class="experiment-container">
        <h1>Virtual Chemistry Experiment</h1>
        <div class="virtual-lab">
            <!-- Add content for the virtual lab experiment -->
        </div>
        <div class="experiment-controls">
            <!-- Add controls for the experiment (buttons, sliders, etc.) -->
        </div>
    </div>
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>ZLEARN - Acid-Base Reaction</title>
        <link rel="stylesheet" type="text/css" href="chemistry.css">
        <link href="https://fonts.googleapis.com/css2?family=jost:wght@500&display=swap" rel="stylesheet">
    </head>
    <body>
        <div class="experiment-container">
            <h1>Acid-Base Reaction</h1>
            <div class="virtual-lab">
                <!-- Add content for the virtual lab -->
                <div class="acid-container">
                    <img src="acid.png" alt="Acid simulation">
                    <!-- Add animations for acid -->
                </div>
                <div class="base-container">
                    <img src="base.png" alt="Base simulation">
                    <!-- Add animations for base -->
                </div>
                <div class="result-container">
                    <img src="water.png" alt="Water animation">
                    <img src="salt.png" alt="Salt animation">
                    <!-- Add animations for water and salt -->
                </div>
            </div>
            <div class="experiment-controls">
                <!-- Add controls for the experiment -->
                <select id="chemical-list">
                    <option value="hydrochloric-acid">Hydrochloric Acid</option>
                    <option value="sodium-hydroxide">Sodium Hydroxide</option>
                    <!-- Add more virtual chemicals to the list -->
                </select>
                <button id="start-experiment">Start Experiment</button>
            </div>
        </div>
        <script src="chemistry.js"></script>
    </body>
    </html>
    

</body>
</html>






// Add your JavaScript code for interactive animations and controls here
document.getElementById('start-experiment').addEventListener('click', startExperiment);

function startExperiment() {
    // Implement interactive animations for the acid-base reaction
    // Adjust the visuals and animations based on the selected virtual chemical
    var selectedChemical = document.getElementById('chemical-list').value;
    // Example: Show animations for acid, base, and result based on the selectedChemical
    // You can use a library like GSAP for more advanced animations
    // Include logic for water and salt animations based on the reaction outcome
}


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Zlearn - Contact</title>
    <!-- Include your existing CSS link here -->
    <link rel="stylesheet" type="text/css" href="styles.css">
</head>
<body>

<!-- Navigation Bar -->
<nav>
    <ul>
        <li><a href="home.html">Home</a></li>
        <li><a href="about.html">About</a></li>
        <li><a href="features.html">Features</a></li>
        <li><a href="contact.html">Contact</a></li>
        <!-- Log Out Button -->
        <li class="logout-button"><button onclick="logout()">Log Out</button></li>
    </ul>
</nav>

<!-- Main Content - Contact Form -->
<div class="contact-container">
    <h1>Contact Us</h1>
    <p>Have questions or suggestions? Reach out to us!</p>

    <!-- Contact Form -->
    <form action="#" method="post">
        <label for="name">Your Name:</label>
        <input type="text" id="name" name="name" required>

        <label for="email">Your Email:</label>
        <input type="email" id="email" name="email" required>

        <label for="message">Your Message:</label>
        <textarea id="message" name="message" rows="4" required></textarea>

        <button type="submit">Send Message</button>
    </form>
</div>

<!-- Include your existing JavaScript code here -->
<script>
    function logout() {
        // Add any logout logic here if needed
        // For now, redirect to the login page
        window.location.href = "loginpage.html";
    }
</script>

</body>
</html>


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Zlearn - Features</title>
    <!-- Include your existing CSS link here -->
    <link rel="stylesheet" type="text/css" href="styles.css">
</head>
<body class="features-page">

<!-- Navigation Bar -->
<nav>
    <ul>
        <li><a href="home.html">Home</a></li>
        <li><a href="about.html">About</a></li>
        <li><a href="features.html">Features</a></li>
        <li><a href="contact.html">Contact</a></li>
        <!-- Log Out Button -->
        <li class="logout-button"><button onclick="logout()">Log Out</button></li>
    </ul>
</nav>

<!-- Main Content - Features Section -->
<div class="features-container">
    <h1>Zlearn Features</h1>


     <!-- Feature 4: Virtual Experiment -->
<fieldset><div class="feature" id="feature4">
    <h2><a href="virtualexperiment.html"><legend>Virtual Experiment</legend></a></h2>
    <p>Participate in chemistry experiments in a virtual environment. Safe and cost-effective, eliminating the need for physical chemicals and equipment.</p>
</div></fieldset>

    <!-- Feature 1: Immersive Learning Environment -->
    <fieldset><div class="feature" id="feature1">
        <h2><a href="#feature1">Immersive Learning Environment</a></h2>
        <p>Revolutionize learning by engaging students through multiple senses. Virtual exploration of subjects makes learning vibrant and memorable.</p>
    </div></fieldset>



    <!-- Feature 2: Personalized Learning Path -->
    <fieldset>
        <div class="feature" id="feature2">
        <h2><a href="#feature2"><legend>Personalized Learning Path</legend></a></h2>
        <p>Adapt to individual learning styles and paces. Users have a personalized dashboard tracking progress and suggesting content based on their needs.</p>

    </div></fieldset>

    <!-- Feature 3: Multi-media Content -->
<fieldset><div class="feature" id="feature3">
        <h2><a href="#feature3"><legend>Multi-media Content</legend></a></h2>
        <p>Visually stunning user interface designed by visual learning experts. Fusion of text, images, and 3D virtual environments for an engaging learning experience.</p>
    </div></fieldset>

   

    <!-- Feature 5: Student-Meet Feature -->
<fieldset><div class="feature" id="feature5">
        <h2><a href="#feature5"><legend> Student-meet Feature</legend> </a></h2>
        <p>Dynamic platform for students to connect, collaborate, and interact in real-time. Promotes teamwork, communication, and the exchange of diverse perspectives.</p>
    </div></fieldset>
</div>

<!-- Include your existing JavaScript code here -->
<script>
    function logout() {
        // Add any logout logic here if needed
        // For now, redirect to the login page
        window.location.href = "loginpage.html";
    }
</script>

</body>
</html>



<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Zlearn - Home</title>
    <!-- Include your existing CSS link here -->
    <link rel="stylesheet" type="text/css" href="styles.css">
</head>
<body>

<!-- Navigation Bar -->
<nav>
    <ul>
        <li><a href="home.html">Home</a></li>
        <li><a href="about.html">About</a></li>
        <li><a href="features.html">Features</a></li>
        <li><a href="contact.html">Contact</a></li>
        <!-- Log Out Button -->
        <li class="logout-button"><button onclick="logout()">Log Out</button></li>
    </ul>
</nav>

<!-- Main Content - Student Dashboard -->
<div class="dashboard-container">
    <div class="welcome-section">
        <h1>Welcome, [Zlab]!</h1>
        <img src="zlab-logo.png" alt="ZLab Logo">
    </div>

    <!-- Update Section -->
    <div class="update-section">
        <h2>Latest Updates</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam gravida, felis vel fermentum ultricies.</p>
        <button onclick="readMore()">Read More</button>
    </div>


    


    <!-- Main Content - Features Section -->
<div class="features-container">
    <h1>Zlearn Features</h1>

     <!-- Feature 4: Virtual Experiment -->
<fieldset><div class="feature" id="feature4">
    <h2><a href="virtualexperiment.html"><legend>Virtual Experiment</legend></a></h2>
    <p>Participate in chemistry experiments in a virtual environment. Safe and cost-effective, eliminating the need for physical chemicals and equipment.</p>
</div></fieldset>


    <!-- Feature 1: Immersive Learning Environment -->
    <fieldset><div class="feature" id="feature1">
        <h2><a href="#feature1">Immersive Learning Environment</a></h2>
        <p>Revolutionize learning by engaging students through multiple senses. Virtual exploration of subjects makes learning vibrant and memorable.</p>
    </div></fieldset>

    <!-- Feature 2: Personalized Learning Path -->
    <fieldset>
        <div class="feature" id="feature2">
        <h2><a href="#feature2"><legend>Personalized Learning Path</legend></a></h2>
        <p>Adapt to individual learning styles and paces. Users have a personalized dashboard tracking progress and suggesting content based on their needs.</p>

    </div></fieldset>

    <!-- Feature 3: Multi-media Content -->
<fieldset><div class="feature" id="feature3">
        <h2><a href="#feature3"><legend>Multi-media Content</legend></a></h2>
        <p>Visually stunning user interface designed by visual learning experts. Fusion of text, images, and 3D virtual environments for an engaging learning experience.</p>
    </div></fieldset>

   
    <!-- Feature 5: Student-Meet Feature -->
<fieldset><div class="feature" id="feature5">
        <h2><a href="#feature5"><legend> Student-meet Feature</legend> </a></h2>
        <p>Dynamic platform for students to connect, collaborate, and interact in real-time. Promotes teamwork, communication, and the exchange of diverse perspectives.</p>
    </div></fieldset>
</div>


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Zlearn - Login</title>
    <link rel="stylesheet" type="text/css" href="styles.css">
</head>
<body>

    <nav>
        <ul>
            <li><a href="home.html">Home</a></li>
            <li><a href="about.html">About</a></li>
            <li><a href="features.html">Features</a></li>
            <li><a href="contact.html">Contact</a></li>
            <li class="logout"><a href="loginpage.html">Logout</a></li>
        </ul>
    </nav>

    <section id="login">
        <h1>Login to Zlearn</h1>
        <form action="login_process.php" method="post">
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="password">Password:</label>
            <input type="password" id="password" name="password" required>

            <button><a href="home.html">Login</button>
        </form>

        <p>Not registered yet? <a href="registration.html">Register</a></p>
    </section>

    <footer>
        <p>&copy; 2024 Zlearn. All rights reserved.</p>
    </footer>

</body>
</html>

















