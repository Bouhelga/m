<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #f2f2f2;
            text-align: center;
            padding: 20px;
        }

        nav {
            background-color: #333;
            overflow: hidden;
        }

        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
        }

        nav ul li {
            float: left;
        }

        nav a {
            display: block;
            color: white;
            text-align: center;
            padding: 14px 16px;
            text-decoration: none;
        }

        nav a:hover {
            background-color: #ddd;
            color: black;
        }

        section {
            padding: 20px;
            position: relative;
        }

        button {
            background-color: #4CAF50;
            color: white;
            padding: 10px 20px;
            font-size: 16px;
            cursor: pointer;
        }

        #noButton {
            position: fixed;
            bottom: 20px;
            right: 20px;
            opacity: 0;
        }

        footer {
            background-color: #7e5e5e;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
    <title>Nhebek</title>
</head>

<body>
    <header>
        <h1>Nhebek</h1>
    </header>

    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#story">Our Story</a></li>
            <li><a href="#proposal">The Proposal</a></li>
        </ul>
    </nav>

    <section id="home">
        <h2>Welcome to Our Love Story</h2>
        <p>Nhebek</p>
    </section>

    <section id="story">
        <h2>Our Story</h2>
        <p>
            we've met the 6th of November 2023
            I told you I love you the 20th of November
            and now we're officially dating for 73 days 
            2 months and 13 days 
            1752 Hour , 105120 minute , 6307200 Second </p>
    </section>

    <section id="proposal">
        <h2>The Proposal</h2>
        <p>Will you Marry Me ? </p>
        <button onclick="playSong()">Yes</button>
        <button id="noButton" onclick="alert('You found the elusive button!')">No</button>
    </section>

    <footer>
        <p>&copy; 2024 Abdou</p>
    </footer>

    <script>
        function playname() {
            // Get the girlfriend's name from the input Field 
            var Haifa = document.getElementById("Hayfa هيافي").value;

            // Display the Name
            var Hayfa = document.getElementById("Hayfa");
            Hayfa.innerHTML = "Her name is :"+ Haifa ;

            // reveal the elusive "No" button by changing it's opacity 
            document.getElementById("noButton").style.opacity = 1;
        }
    </script>
</body>

</html>
