<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rahat Travel</title>
    <meta http-equiv="Content-Security-Policy" content="default-src 'self'; script-src 'self'; object-src 'none';">
    <meta http-equiv="X-Frame-Options" content="DENY">
    <meta http-equiv="X-XSS-Protection" content="1; mode=block">
    <meta http-equiv="X-Content-Type-Options" content="nosniff">
    <style>
        body { 
            font-family: Arial, sans-serif; 
            padding: 20px; 
            background: linear-gradient(to bottom, #ffffff, #87CEEB);
            display: flex;
        }
        .sidebar {
            width: 250px;
            background: rgba(255, 255, 255, 0.9);
            padding: 20px;
            position: fixed;
            left: 0;
            top: 0;
            height: 100%;
            box-shadow: 2px 0px 10px rgba(0, 0, 0, 0.1);
            display: none;
        }
        .sidebar h2 {
            text-align: center;
        }
        .sidebar ul {
            list-style: none;
            padding: 0;
        }
        .sidebar ul li {
            padding: 10px;
            border-bottom: 1px solid #ddd;
        }
        .sidebar ul li a {
            text-decoration: none;
            color: black;
        }
        .content {
            margin-left: 270px;
            width: 100%;
            text-align: center;
        }
        img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
        }
        .contact-number {
            margin-top: 20px;
            font-size: 20px;
            font-weight: bold;
        }
        .login-container, .signup-container {
            margin-top: 30px;
            padding: 20px;
            background: white;
            display: inline-block;
            border-radius: 10px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }
        input, button {
            display: block;
            width: 100%;
            margin: 10px 0;
            padding: 10px;
            font-size: 16px;
        }
        .error-message {
            color: red;
            font-weight: bold;
        }
        .reviews {
            margin-top: 30px;
            padding: 20px;
            background: white;
            border-radius: 10px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }
        .commands {
            margin-top: 30px;
            padding: 20px;
            background: white;
            border-radius: 10px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }
    </style>
    <script>
        window.onbeforeunload = function() {
            return 'Would you like to leave a review before you go?';
        };
    </script>
</head>
<body>
    <div class="content">
        <div class="commands">
            <h2>Deployment Commands (GitHub Pages)</h2>
            <pre>
                git init
                git add .
                git commit -m "Initial commit"
                git branch -M main
                git remote add origin https://github.com/YOUR_GITHUB_USERNAME/rahat-tours.git
                git push -u origin main
            </pre>
        </div>
    </div>
</body>
</html>
