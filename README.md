<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Ansh Tiwari | Profile</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background: linear-gradient(135deg, #1d2671, #c33764);
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .profile-card {
            background: #ffffff;
            width: 90%;
            max-width: 900px;
            border-radius: 15px;
            box-shadow: 0 15px 30px rgba(0,0,0,0.2);
            overflow: hidden;
        }

        .profile-header {
            background: linear-gradient(135deg, #667eea, #764ba2);
            color: white;
            padding: 30px;
            text-align: center;
        }

        .profile-header h1 {
            font-size: 32px;
            margin-bottom: 8px;
        }

        .profile-header p {
            font-size: 16px;
            opacity: 0.9;
        }

        .profile-content {
            padding: 30px;
        }

        .section {
            margin-bottom: 25px;
        }

        .section h2 {
            font-size: 22px;
            margin-bottom: 10px;
            color: #5a3ec8;
            border-left: 5px solid #5a3ec8;
            padding-left: 10px;
        }

        .section p {
            font-size: 16px;
            line-height: 1.7;
            color: #555;
        }

        .skills {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }

        .skill {
            background: #f1f1f1;
            padding: 10px 15px;
            border-radius: 20px;
            font-size: 14px;
            transition: 0.3s;
        }

        .skill:hover {
            background: #5a3ec8;
            color: white;
            transform: scale(1.05);
        }

        /* ===== Social Links ===== */
        .social-links {
            display: flex;
            flex-wrap: wrap;
            gap: 15px;
            margin-top: 10px;
        }

        .social-links a {
            text-decoration: none;
            color: white;
            padding: 12px 20px;
            border-radius: 30px;
            font-size: 15px;
            font-weight: 500;
            display: flex;
            align-items: center;
            gap: 8px;
            transition: 0.3s;
        }

        .youtube {
            background: #ff0000;
        }

        .instagram {
            background: linear-gradient(45deg, #f58529, #dd2a7b, #8134af);
        }

        .social-links a:hover {
            transform: translateY(-3px);
            box-shadow: 0 8px 15px rgba(0,0,0,0.2);
        }

        .profile-footer {
            text-align: center;
            padding: 15px;
            background: #f7f7f7;
            font-size: 14px;
            color: #777;
        }

        @media (max-width: 600px) {
            .profile-header h1 {
                font-size: 26px;
            }
        }
    </style>
</head>

<body>

<div class="profile-card">

    <div class="profile-header">
        <h1>Ansh Krishnakant Tiwari</h1>
        <p>Student | Coding Learner | Gamer</p>
    </div>

    <div class="profile-content">

        <div class="section">
            <h2>Introduction</h2>
            <p>
                Hello! My name is <strong>Ansh Krishnakant Tiwari</strong>.
                I am studying in <strong>11th Standard</strong> at
                <strong>RKT College, Ulhasnagar</strong>.
            </p>
        </div>

        <div class="section">
            <h2>Education</h2>
            <p>
                I am focusing on <strong>IT</strong> with practical knowledge
                along with learning modern technical skills.
            </p>
        </div>

        <div class="section">
            <h2>Interests</h2>
            <p>
                I love playing games and learning <strong>coding</strong>.
                I am currently a beginner in web development.
            </p>
        </div>

        <div class="section">
            <h2>Skills & Learning</h2>
            <div class="skills">
                <div class="skill">HTML</div>
                <div class="skill">JavaScript</div>
                <div class="skill">Web Development</div>
                

        <!-- Social Media Section -->
        <div class="section">
            <h2>Social Media</h2>
            <div class="social-links">
                <a href="___---" target="_blank" class="youtube">
                    ▶ YouTube Channel
                </a>

                <a href="https://www.instagram.com/isolatedx.soul?igsh=MXRlbnc2MGY5dnFmbg==" target="_blank" class="instagram">
                    📷 Instagram Profile
                </a>
            </div>
        </div>

    </div>

    <div class="profile-footer">
        © 2026 | Created by Ansh Tiwari
    </div>

</div>

</body>
</html>
