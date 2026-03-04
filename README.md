<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FluentRise - English Learning & Soft Skills App</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body { font-family: 'Poppins', sans-serif; background: #f4f7fb; color: #333; }
        header {
            background: linear-gradient(135deg, #4e73df, #1cc88a);
            color: white;
            padding: 60px 20px;
            text-align: center;
        }
        header h1 { font-size: 42px; margin-bottom: 15px; }
        header p { font-size: 18px; max-width: 700px; margin: auto; }
        .btn {
            display: inline-block;
            margin-top: 20px;
            padding: 12px 25px;
            background: white;
            color: #4e73df;
            border-radius: 30px;
            text-decoration: none;
            font-weight: 600;
            transition: 0.3s ease;
        }
        .btn:hover { background: #e2e6f5; }
        section { padding: 60px 20px; text-align: center; }
        .section-title { font-size: 32px; margin-bottom: 40px; }
        .features {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 25px;
            max-width: 1100px;
            margin: auto;
        }
        .card {
            background: white;
            padding: 25px;
            border-radius: 15px;
            box-shadow: 0 8px 20px rgba(0,0,0,0.08);
            transition: 0.3s;
        }
        .card:hover { transform: translateY(-5px); }
        .card h3 { margin-bottom: 15px; color: #4e73df; }
        .progress-section {
            background: #ffffff;
        }
        .testimonial {
            max-width: 800px;
            margin: auto;
            font-style: italic;
        }
        footer {
            background: #2c3e50;
            color: white;
            padding: 20px;
            text-align: center;
        }
        .cta {
            background: linear-gradient(135deg, #1cc88a, #4e73df);
            color: white;
            padding: 50px 20px;
        }
        .cta h2 { margin-bottom: 20px; }
        input[type="email"] {
            padding: 12px;
            width: 250px;
            border-radius: 25px;
            border: none;
            margin-right: 10px;
        }
        button {
            padding: 12px 20px;
            border-radius: 25px;
            border: none;
            background: white;
            color: #4e73df;
            font-weight: 600;
            cursor: pointer;
        }
        button:hover { background: #e2e6f5; }
    </style>
</head>
<body>

<header>
    <h1>FluentRise</h1>
    <p>Master English Communication & Soft Skills to Boost Your Career Confidence.</p>
    <a href="#features" class="btn">Explore Features</a>
</header>

<section id="features">
    <h2 class="section-title">App Features</h2>
    <div class="features">
        <div class="card">
            <h3>Daily Speaking Practice</h3>
            <p>Interactive speaking exercises to improve fluency and pronunciation.</p>
        </div>
        <div class="card">
            <h3>Soft Skills Training</h3>
            <p>Learn communication, leadership, teamwork, and interview skills.</p>
        </div>
        <div class="card">
            <h3>Vocabulary Builder</h3>
            <p>Expand your vocabulary with daily words and real-life examples.</p>
        </div>
        <div class="card">
            <h3>Mock Interviews</h3>
            <p>Practice job interviews with AI-based real-world questions.</p>
        </div>
    </div>
</section>

<section class="progress-section">
    <h2 class="section-title">Track Your Progress</h2>
    <p>Monitor streaks, completed lessons, speaking score, and overall improvement.</p>
</section>

<section>
    <h2 class="section-title">What Our Learners Say</h2>
    <div class="testimonial">
        "This app improved my confidence in English speaking and helped me clear my job interview!"
    </div>
</section>

<section class="cta">
    <h2>Start Your Learning Journey Today</h2>
    <p>Join thousands of learners improving their English & soft skills.</p>
    <br>
    <input type="email" placeholder="Enter your email">
    <button>Get Started</button>
</section>

<footer>
    <p>© 2026 FluentRise | English Learning & Soft Skills App</p>
</footer>

</body>
</html>
