# birthday-message

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dynamic Birthday Wishes</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
    <style>
        /* Basic Body Styling */
        body {
            margin: 0;
            padding: 0;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
            font-family: 'Poppins', sans-serif;
            background: linear-gradient(45deg, #ff6f61, #d85c6b, #ffce45);
            background-size: 400% 400%;
            animation: gradientAnimation 10s ease infinite;
            color: white;
            overflow: hidden;
        }

        /* Header and Text Styling */
        h1 {
            font-size: 3rem;
            font-weight: 600;
            text-align: center;
            margin: 10px;
            animation: fadeInUp 2s ease-out infinite;
            animation-delay: 1s;
            opacity: 0;
        }

        /* Message Text */
        p {
            font-size: 1.4rem;
            text-align: center;
            animation: fadeInUp 2s ease-out infinite;
            animation-delay: 2s;
            opacity: 0;
            max-width: 600px;
            line-height: 1.6;
            margin: 10px;
        }

        /* Special Message */
        .special-message {
            font-size: 1.8rem;
            color: #ffec61;
            text-align: center;
            font-weight: 600;
            margin-top: 20px;
            animation: bounceIn 2s ease-out infinite;
            opacity: 0;
        }

        /* Emojis floating effect */
        .emoji {
            font-size: 2rem;
            display: inline-block;
            animation: float 3s ease-in-out infinite;
        }

        /* Animation Definitions */
        @keyframes gradientAnimation {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }

        @keyframes fadeInUp {
            0% { opacity: 0; transform: translateY(20px); }
            100% { opacity: 1; transform: translateY(0); }
        }

        @keyframes bounceIn {
            0% { transform: scale(0); opacity: 0; }
            50% { transform: scale(1.1); opacity: 1; }
            100% { transform: scale(1); }
        }

        @keyframes float {
            0% { transform: translateY(0); }
            50% { transform: translateY(-10px); }
            100% { transform: translateY(0); }
        }

        /* Media Queries for Responsiveness */
        @media (max-width: 768px) {
            h1 {
                font-size: 2.5rem;
            }

            p, .special-message {
                font-size: 1.2rem;
            }
        }
    </style>
</head>
<body>

    <!-- Header -->
    <h1>Happy Birthday, My Dear Friend! <span class="emoji">🎉🎉</span></h1>

    <!-- Birthday Message -->
    <p>You are so special and cute! <span class="emoji">🥰🥰</span></p>
    <p>Wishing you all the joy, love, and success in the world. May this year bring you everything you've been dreaming of! <span class="emoji">🌟</span></p>
    <p>You're such a wonderful person, and I hope you always stay happy in life. Never let anything bring you down! Be healthy, and I will pray for your well-being! <span class="emoji">🙏</span></p>

    <!-- Special Message with Floating Emojis -->
    <div class="special-message">
        Allah kare aapko har wo jayyaz cheez se nawazay jo aap chahtay ho. <span class="emoji">🌙</span><br>
        Allah aapki umar lambe kare. <span class="emoji">🕊️🕊️😇😇</span><br>
        And one last thing, Mashallah, you are too cute! <span class="emoji">🥰🥰</span>
    </div>

    <!-- Final Message -->
    <p> To My dear friend.... <span class="emoji">😒😒</span></p>

</body>
</html>

