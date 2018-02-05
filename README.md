<!DOCTYPE html>
<html>
    <head>

        <meta charset="utf-8">
        <title>Portfolio</title>

        <style>
           .grid-container {
                display: grid;
                grid-template-columns: auto auto auto auto;
                grid-row-gap: 50px;
                grid-column-gap: 50px;
                background-color: #f6d3f2;
                padding: 100px;
            }
            .card {
                box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
                transition: 0.3s;
                width: 20%;
            }
            .card:hover {
                box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2);
            }
            a:link {
                text-decoration:  none;
                width: 90%
            }
            a:hover {
                opacity: 0.7;
                transition: .5s ease;
                background-color: #654D66;
            }
        </style>

    </head>
    <body>
        <body style="background-color:#f6d6ff;">
        <img src="images/banner4.png" width="100%">

        <div class="grid-container">
            <a href="https://gdpufrj.itch.io/stairs-to-the-top">
                <img src="images/stairs.png" width="100%">
            </a>
            <a href="https://vinizinho.itch.io/mind-the-gap">
                <img src="images/mtg.png" width="100%">
            </a>
            <a href="https://drive.google.com/open?id=1aKxAEyHqaraN_SqzLWWLiwRAEw4zqIaf">
                <img src="images/miagatos.png" width="100%">
            </a>
            <a href="https://gdpufrj.itch.io/cped">
                <img src="images/cped2.png" width="100%">
            </a>
        </div>

    </body>
</html>
