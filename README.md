# Mia
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mission I Am | Spiritual Reader</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: 'Helvetica Neue', Arial, sans-serif;
            /* Darker midnight purple sky */
            background: radial-gradient(circle at top, #2e004f 0%, #1a002e 100%);
            color: #ffffff;
            display: flex;
            flex-direction: column;
            align-items: center;
            min-height: 100vh;
            overflow-x: hidden;
        }

        /* Subtle gold star effect in background */
        body::before {
            content: "";
            position: fixed;
            top: 0; left: 0; width: 100%; height: 100%;
            background-image: 
                radial-gradient(white, rgba(255,255,255,.2) 2px, transparent 40px),
                radial-gradient(white, rgba(255,255,255,.1) 1px, transparent 30px);
            background-size: 550px 550px, 350px 350px;
            background-position: 0 0, 40px 60px;
            opacity: 0.3;
            z-index: -1;
        }

        .container {
            max-width: 500px;
            text-align: center;
            padding: 40px 20px;
        }

        .profile-img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            border: 3px solid #FFD700;
            object-fit: cover;
            margin-bottom: 15px;
            box-shadow: 0 0 20px rgba(255, 215, 0, 0.4);
        }

        h1 {
            font-size: 2.8rem;
            margin: 0;
            letter-spacing: 3px;
            text-transform: uppercase;
            color: #FFD700; /* Sunflower Gold */
            text-shadow: 0 0 10px rgba(255, 215, 0, 0.3);
        }

        .tagline {
            font-size: 1rem;
            letter-spacing: 2px;
            margin-bottom: 30px;
            opacity: 0.8;
            color: #e0b0ff; /* Soft lavender */
        }

        .bio-card {
            background: rgba(0, 0, 0, 0.5);
            padding: 30px;
            border-radius: 20px;
            border: 1px solid rgba(255, 215, 0, 0.5);
            margin-bottom: 35px;
            line-height: 1.6;
            backdrop-filter: blur(10px);
        }

        .offer-price {
            font-size: 1.6rem;
            font-weight: bold;
            display: block;
            margin-top: 20px;
            color: #FFD700;
        }

        .button-stack {
            display: flex;
            flex-direction: column;
            gap: 15px;
        }

        .btn {
            text-decoration: none;
            padding: 18px;
            border-radius: 50px; /* Pill shape */
            font-weight: bold;
            font-size: 1.1rem;
            transition: all 0.3s ease;
            display: block;
            text-align: center;
            border: 1px solid rgba(255,255,255,0.1);
        }

        .book-btn { background-color: #FFD700; color: #1a002e; }
        .fb-btn { background-color: #1877F2; color: white; }
        .cash-btn { background-color: #00D632; color: white; }
        .venmo-btn { background-color: #008CFF; color: white; }

        .btn:hover {
            transform: translateY(-3px);
            filter: brightness(1.1);
            box-shadow: 0 10px 20px rgba(0,0,0,0.4);
        }

        footer {
            margin-top: 50px;
            font-size: 0.8rem;
            opacity: 0.5;
            padding-bottom: 30px;
        }
    </style>
</head>
<body>

    <div class="container">
        <img src="profile.jpg" alt="Mission I Am" class="profile-img">
        
        <h1>Mission I Am</h1>
        <p class="tagline">SPIRITUAL GUIDANCE & CLARITY</p>

        <div class="bio-card">
            Spirituality isn't just about looking upward—it’s about looking inward. I created <strong>Mission I Am</strong> to help you reclaim your power and walk your path with absolute confidence. My readings are designed to be practical, transformative, and deeply personal. Let’s identify the blocks holding you back and turn your "I want" into <strong>"I AM."</strong>
            
            <span class="offer-price">🌻 Intro Reading: $25 🌻</span>
        </div>

        <div class="button-stack">
            <a href="mailto:yourname@email.com?subject=Reading Request" class="btn book-btn">📅 Book Your Reading</a>
            <a href="https://facebook.com/YourPageLink" target="_blank" class="btn fb-btn">📱 Connect on Facebook</a>
            <a href="https://cash.app/$YourTag" target="_blank" class="btn cash-btn">💸 Pay via Cash App</a>
            <a href="https://venmo.com/YourUsername" target="_blank" class="btn venmo-btn">💙 Pay via Venmo</a>
        </div>

        <footer>
            &copy; 2026 Mission I Am • ✨ • Stay Grounded
        </footer>
    </div>

</body>
</html>
