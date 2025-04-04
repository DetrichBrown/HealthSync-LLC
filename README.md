# healthsync-website
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HealthSync LLC</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
            color: #333;
        }
        header {
            background-color: #2E7D32;
            color: white;
            padding: 20px;
            text-align: center;
            font-size: 24px;
            position: relative;
        }
        .profile-img {
            position: absolute;
            top: 10px;
            right: 10px;
            width: 80px;
            height: 80px;
            border-radius: 50%;
            border: 2px solid white;
        }
        .container {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background: white;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h2 {
            color: #2E7D32;
        }
        .contact-form {
            display: flex;
            flex-direction: column;
        }
        .contact-form input, .contact-form textarea {
            margin-bottom: 10px;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .contact-form button {
            background-color: #2E7D32;
            color: white;
            padding: 10px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .images {
            text-align: center;
            margin: 20px 0;
        }
        .images img {
            width: 45%;
            margin: 10px;
            border-radius: 8px;
        }
        footer {
            text-align: center;
            padding: 20px;
            background-color: #2E7D32;
            color: white;
        }
    </style>
</head>
<body>
    <header>
        HealthSync LLC - Telehealth Services
        <img src="professional/Headshot (1).jpg" alt="Your Photo" class="profile-img">
    </header>
    <div class="container">
        <h2>Our Services</h2>
        <p><strong>Acute Care:</strong> Common cold, viral infections, UTIs, sinus infections, and more.</p>
        <p><strong>Chronic Disease Management:</strong> Hypertension, hypothyroidism, anxiety, depression, type 2 diabetes, high cholesterol.</p>
        <p><strong>VA Nexus Letters</strong></p>
    </div>
    <div class="images">
        healthy-people1.jpg.jpg
        <img src=images/healthy-people2.jpg alt="Diverse Group Living Healthy Lives">
    </div>
    <div class="container">
        <h2>Health Promotion: Diet & Exercise</h2>
        <p><strong>Healthy Diet:</strong> A balanced diet rich in fruits, vegetables, lean proteins, and whole grains supports overall well-being. Avoid processed foods and excessive sugars.</p>
        <p><strong>Regular Exercise:</strong> Engage in at least 30 minutes of moderate physical activity most days of the week. Activities like walking, cycling, and yoga can improve cardiovascular health and reduce stress.</p>
    </div>
    <div class="container">
        <h2>Contact & Scheduling</h2>
        <p>Email: <a href="mailto:DetrichBrown@HealthSyncLLC.onmicrosoft.com">DetrichBrown@HealthSyncLLC.onmicrosoft.com</a></p>
        <form class="contact-form" action="mailto:DetrichBrown@HealthSyncLLC.onmicrosoft.com" method="post" enctype="text/plain">
            <input type="text" name="name" placeholder="Your Name" required>
            <input type="email" name="email" placeholder="Your Email" required>
            <textarea name="message" placeholder="Your Message" rows="5" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </div>
    <footer>
        <p>HealthSync LLC &copy; 2025</p>
        <p>Future Social Media Links Here</p>
    </footer>
</body>
</html>
