
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TicTacToeGame</title>
    <link rel="stylesheet" href="style1.css"></linksheet>
</head>
<body>
    <div class="msg-container hide">
        <p id="msg">Winner</p>
        <button id="newgame-btn">New Game</button>
    </div>

    <main>
        <h1>TIC-TAC-TOE GAME</h1>
        <div class="choice">
            <span class="choice_heading">Enter your choice</span>
            <button class="choice_button cross" onclick="cross()">X</button>
            <button class="choice_button circle" onclick="circle()">O</button>
            <div class="Choose-choice"></div>
        </div>
        <div class="container">
           <div class="game">
               <button class="box box1"></button>
               <button class="box box1"></button>
               <button class="box box1"></button>
               <button class="box box1"></button>
               <button class="box box1"></button>
               <button class="box box1"></button>
               <button class="box box1"></button>
               <button class="box box1"></button>
               <button class="box box1"></button>
           </div>
        </div>
        <button id="reset-btn">Reset Game</button>
    </main>
    <script src="Second.js"></script>
</body>
</html>
