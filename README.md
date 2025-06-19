<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Metis Crossing</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #ffffff;
            color: #333;
            min-height: 200vh; /* Ensure site is long enough */
        }
        header {
            background-color: rgba(0, 51, 102, 0.9); /* Dark blue, semi-transparent */
            color: white;
            text-align: center;
            padding: 2em;
        }
        h1 {
            color: #cc0000; /* Dark red */
        }
        main {
            padding: 20px;
            background-color: rgba(255, 255, 255, 0.8); /* White, semi-transparent */
            margin: 0 auto;
            max-width: 1200px;
            border-radius: 10px;
        }
        p {
            color: #333;
            font-size: 1.2em;
        }
        .columns {
            display: flex;
            justify-content: space-around;
            margin-top: 20px;
        }
        .column {
            width: 45%;
            padding: 20px;
            background-color: rgba(240, 248, 255, 0.9); /* Very light blue, semi-transparent */
            border: 1px solid #003366; /* Dark blue border */
            text-align: center;
            border-radius: 5px;
        }
        h2 {
            color: #003366; /* Dark blue */
        }
        a {
            color: #003366; /* Dark blue */
            text-decoration: none;
            font-size: 1.1em;
        }
        a:hover {
            text-decoration: underline;
        }
        .image-container {
            width: 100%; /* Full width within main */
            height: 500px; /* Fixed height to make site longer */
            margin: 20px 0;
            border: 3px solid #003366; /* Dark blue border */
            overflow: hidden;
        }
        .image-container img {
            width: 100%;
            height: 100%;
            object-fit: cover; /* Scale image to cover container */
            display: block;
        }
        .image-caption {
            background-color: rgba(240, 248, 255, 0.9); /* Very light blue, semi-transparent */
            padding: 10px;
            text-align: center;
            font-size: 1.2em;
            color: #003366; /* Dark blue */
            border: 1px solid #003366; /* Dark blue border */
            border-top: none; /* No top border to connect with image */
            margin-bottom: 20px;
        }
        @media (max-width: 600px) {
            .columns {
                flex-direction: column;
                align-items: center;
            }
            .column {
                width: 80%;
                margin-bottom: 20px;
            }
            .image-container {
                height: 300px; /* Smaller height on mobile */
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Metis Crossing</h1>
    </header>
    <main>
        <p>Please do the following:</p>
        <div class="columns">
            <div class="column">
                <h2>Drone Photos</h2>
                <a href="data/drone_photos.zip" download>Download Zip</a>
            </div>
            <div class="column">
                <h2>QGIS Files</h2>
                <a href="data/qgis_files.zip" download>Download Zip</a>
            </div>
        </div>
        <div class="image-container">
            <img src="images/background1.jpg" alt="Metis Crossing 1">
        </div>
        <div class="image-caption">Metis Crossing 1</div>
        <div class="image-container">
            <img src="images/background2.jpg" alt="Metis Crossing 2">
        </div>
        <div class="image-caption">Metis Crossing 2</div>
        <div class="image-container">
            <img src="images/background3.jpg" alt="Metis Crossing 3">
        </div>
        <div class="image-caption">Metis Crossing 3</div>
    </main>
</body>
</html>
