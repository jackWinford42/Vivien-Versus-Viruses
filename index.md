<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <title>Vivien Game</title>
        <link rel="icon" type="image/png" href="images/favicon.png">

        <link rel="stylesheet" href="styling/style.css">

        <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-beta.2/css/bootstrap.min.css" integrity="sha384-PsH8R72JQ3SOdhVi3uxftmaW6Vc51MKb0q5P2rRUpPvrszuE4W1povHYgTpBfshb" crossorigin="anonymous">
        <link href="https://fonts.googleapis.com/css?family=Bungee" rel="stylesheet">
        
    </head>
    <body>
        <div id="start">
            <div class="row">
                <div class="col-12">
                    <div id="title">
                        <p>Vivien</p>
                        <p>Versus</p>
                        <p>Viruses</p>
                    </div>
                </div>
            </div>
            <div id="space">

            </div>
            <div class="row text-center">
                <div class="col-4 offset-4">
                    <button id="start-button" class="btn btn-primary btn-block btn-lg pt-4 pb-4">Play Game</button>
                </div>
            </div>
        </div>

        <div id="container-body">
            <div id="container">
                <canvas id="gameBoard" height="600" width="1200"></canvas>
            </div>
        </div>
    </body>
    <script src="javascript/map.js"></script>
</html>