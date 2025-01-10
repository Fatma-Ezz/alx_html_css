<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Responsive Web Page</title>
    <style>
        /* General Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        /* Body Styles */
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            background-color: #f9f9f9;
            color: #333;
            margin: 0;
            padding: 0;
        }

        /* Container */
        .container {
            max-width: 1000px;
            margin: 0 auto;
            padding: 20px;
        }

        /* Header */
        header {
            text-align: center;
            margin-bottom: 20px;
        }

        header h1 {
            font-size: 2rem;
            color: #444;
        }

        /* Navigation */
        nav {
            margin-bottom: 20px;
        }

        .nav-links {
            list-style: none;
            display: flex;
            justify-content: center;
            gap: 15px;
            padding: 10px;
            background-color: #fff;
            border: 1px solid #ddd;
            border-radius: 5px;
        }

        .nav-links a {
            text-decoration: none;
            color: #333;
            transition: color 0.3s;
        }

        .nav-links a:hover,
        .nav-links a:active {
            color: #FF6565;
        }

        /* Main Content */
        main {
            text-align: center;
            margin-bottom: 20px;
        }

        main h2 {
            font-size: 1.8rem;
            margin-bottom: 10px;
        }

        main p {
            margin-bottom: 20px;
        }

        button {
            padding: 10px 20px;
            border: none;
            background-color: #FF6565;
            color: #fff;
            font-size: 1rem;
            cursor: pointer;
            transition: opacity 0.3s;
            border-radius: 5px;
        }

        button:hover,
        button:active {
            opacity: 0.9;
        }

        /* Footer */
        footer {
            text-align: center;
            margin-top: 20px;
            font-size: 0.9rem;
            color: #666;
        }

        /* Responsive Design */
        @media (max-width: 480px) {
            .nav-links {
                flex-direction: column;
            }

            header h1 {
                font-size: 1.5rem;
            }

            main h2 {
                font-size: 1.5rem;
            }

            button {
                width: 100%;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>My Responsive Page</h1>
        </header>
        <nav>
            <ul class="nav-links">
                <li><a href="#section1">Home</a></li>
                <li><a href="#section2">About</a></li>
                <li><a href="#section3">Services</a></li>
                <li><a href="#section4">Contact</a></li>
            </ul>
        </nav>
        <main>
            <section id="section1">
                <h2>Welcome to My Page</h2>
                <p>This is a demonstration of a responsive design that adapts to different screen sizes.</p>
                <button>Click Me</button>
            </section>
        </main>
        <footer>
            <p>&copy; 2025 Fatma.Ezz</p>
        </footer>
    </div>
</body>
</html>
