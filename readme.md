<!DOCTYPE html>
<html>
<head>
    <title>Shadman Khan Khattak - Game Developer</title>
    <!-- Include Bootstrap from the official CDN -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.5.0/dist/css/bootstrap.min.css">
    <!-- Add custom CSS for animations, styles, and background color -->
    <style>
        body {
            background-color: #f0f0f0;
            font-family: 'Arial', sans-serif;
        }
        header {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 60px 0;
            animation: fadeIn 1s ease-in-out;
        }
        h1 {
            font-size: 36px;
            margin: 0;
        }
        h2 {
            font-size: 24px;
            margin-bottom: 20px;
        }
        .container {
            background-color: #fff;
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
            border-radius: 10px;
            animation: fadeInUp 1s ease-in-out;
        }
        .contact {
            text-align: center;
            margin-top: 20px;
            animation: fadeIn 1s ease-in-out;
        }
        .contact p {
            font-size: 18px;
            margin-bottom: 10px;
        }
        a {
            color: #007BFF;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
        @keyframes fadeIn {
            0% {
                opacity: 0;
                transform: translateY(20px);
            }
            100% {
                opacity: 1;
                transform: translateY(0);
            }
        }
        @keyframes fadeInUp {
            0% {
                opacity: 0;
                transform: translateY(20px);
            }
            100% {
                opacity: 1;
                transform: translateY(0);
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Shadman Khan Khattak</h1>
        <h2>Professional Game Developer</h2>
    </header>
    <div class="container mt-4">
        <h2 class="text-center">About Me</h2>
        <p class="lead text-center">
            I am a professional Game Developer with 2 years of experience. I specialize in Gameplay Programming, ANRs, and Optimization, along with core modules implementations.
        </p>
    </div>

    <!-- Contact Information -->
    <div class="container contact">
        <h2 class="text-center">Contact Information</h2>
        <p class="text-center">Feel free to get in touch:</p>
        <p class="text-center"><strong>Email:</strong> <a href="mailto:shadman@example.com">shadman@example.com</a></p>
        <p class="text-center"><strong>LinkedIn:</strong> <a href="https://www.linkedin.com/in/shadman" target="_blank">linkedin.com/in/shadman</a></p>
        <p class="text-center"><strong>GitHub:</strong> <a href="https://github.com/shadman" target="_blank">github.com/shadman</a></p>
    </div>

    <!-- Include Bootstrap JS and jQuery from the official CDN -->
    <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.5.0/dist/js/bootstrap.min.js"></script>
</body>
</html>