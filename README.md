<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple HTML and CSS Program</title>
    <style>
        /* CSS Styles */
        /* Reset some basic styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        /* Body styles */
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            color: #333;
            text-align: center;
            padding: 20px;
        }

        /* Header styling */
        header {
            background-color: #4CAF50;
            padding: 10px;
            color: white;
        }

        h1 {
            font-size: 2.5em;
        }

        /* Main content styles */
        main {
            margin-top: 20px;
        }

        p {
            font-size: 1.2em;
            margin-bottom: 20px;
        }

        /* Button styling */
        .cta-button {
            padding: 10px 20px;
            background-color: #008CBA;
            color: white;
            border: none;
            border-radius: 5px;
            font-size: 1.1em;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }

        .cta-button:hover {
            background-color: #005f73;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Website</h1>
    </header>
    <main>
        <p>This is a simple webpage with HTML and CSS styling.</p>
        <button class="cta-button">Click Me!</button>
    </main>
</body>
</html>
