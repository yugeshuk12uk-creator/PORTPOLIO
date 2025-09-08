<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Hockey Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
        }
        header {
            background-color: #003366;
            color: white;
            text-align: center;
            padding: 20px;
        }
        .container {
            width: 80%;
            margin: 0 auto;
            padding: 20px;
        }
        .section-title {
            font-size: 24px;
            color: #003366;
            margin-bottom: 15px;
        }
        .profile, .achievements, .contact {
            background-color: #ffffff;
            padding: 15px;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            margin-bottom: 30px;
        }
        .profile img {
            width: 150px;
            border-radius: 50%;
            margin-bottom: 15px;
        }
        .achievements ul {
            list-style-type: square;
            margin-left: 20px;
        }
        footer {
            background-color: #003366;
            color: white;
            text-align: center;
            padding: 10px;
            position: absolute;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Hockey Portfolio</h1>
        <p>Showcasing my journey in hockey and my achievements on and off the ice</p>
    </header>

  <div class="container">
        <!-- Profile Section -->
        <section class="profile">
            <h2 class="section-title">Player Profile</h2>
            <img src="player-photo.jpg" alt="Player Photo"> <!-- Replace with your photo -->
            <p><strong>Name:</strong> John Doe</p>
            <p><strong>Position:</strong> Forward</p>
            <p><strong>Team:</strong> City Tigers</p>
            <p><strong>Years of Experience:</strong> 8 years</p>
            <p><strong>Strengths:</strong> Speed, Agility, Playmaking</p>
        </section>
    <!-- Achievements Section -->
        <section class="achievements">
            <h2 class="section-title">Achievements</h2>
            <ul>
                <li>Won State Championship (2023)</li>
                <li>Most Valuable Player - City Tigers (2022)</li>
                <li>Top Scorer in League (2021)</li>
                <li>Captain of School Hockey Team (2019-2021)</li>
            </ul>
        </section>
<!-- Contact Section -->
        <section class="contact">
            <h2 class="section-title">Contact</h2>
            <p><strong>Email:</strong> johndoe@email.com</p>
            <p><strong>Phone:</strong> (123) 456-7890</p>
            <p><strong>Social Media:</strong></p>
            <ul>
                <li><a href="https://twitter.com/johndoe" target="_blank">Twitter</a></li>
                <li><a href="https://linkedin.com/in/johndoe" target="_blank">LinkedIn</a></li>
                <li><a href="https://instagram.com/johndoe" target="_blank">Instagram</a></li>
            </ul>
        </section>
    </div>

  <footer>
        <p>&copy; 2025 John Doe - All Rights Reserved</p>
    </footer>
</body>
</html>
