<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Flip Chess - Official Rules</title>
    <style>
        body {
            font-family: Georgia, 'Times New Roman', Times, serif;
            line-height: 1.6;
            background-color: #f4f1ea;
            color: #333;
            margin: 0;
            padding: 20px;
            display: flex;
            justify-content: center;
        }
        .rulebook-container {
            max-width: 800px;
            width: 100%;
            background-color: #ffffff;
            padding: 30px 50px;
            border-radius: 8px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            border: 1px solid #ddd;
        }
        h1, h2, h3 {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            color: #2c3e50;
            border-bottom: 2px solid #e0e0e0;
            padding-bottom: 10px;
            margin-top: 30px;
        }
        h1 {
            text-align: center;
            font-size: 2.5em;
            margin-top: 0;
            border-bottom: 3px solid #34495e;
        }
        h2 {
            font-size: 2em;
        }
        h3 {
            font-size: 1.5em;
            border-bottom: 1px solid #eaeaea;
        }
        p, li {
            font-size: 1.1em;
        }
        ol, ul {
            padding-left: 20px;
        }
        li {
            margin-bottom: 10px;
        }
        strong {
            color: #2980b9;
        }
        .score-list {
            list-style-type: none;
            padding: 0;
        }
        .score-list li {
            display: flex;
            justify-content: space-between;
            border-bottom: 1px dotted #ccc;
            padding: 8px 0;
        }
        .score-list span {
            font-weight: bold;
        }
    </style>
</head>
<body>

<div class="rulebook-container">
    <h1>Happy Flip Chess</h1>

    <h2>Object of the Game</h2>
    <p>
        To outscore your opponent by capturing their pieces. The game ends when one player is eliminated or no legal moves can be made, at which point the player with the highest score from their remaining pieces on the board wins.
    </p>

    <h2>Game Setup</h2>
    <ol>
        <li><strong>The Board:</strong> The game is played on a half-sized chessboard, consisting of <strong>4 rows and 8 columns</strong> (32 squares).</li>
        <li><strong>The Pieces:</strong> The game uses a full, standard set of 32 chess pieces (16 white and 16 black).</li>
        <li><strong>Preparation:</strong> All 32 pieces are shuffled together and placed randomly on each of the 32 squares, <strong>face-down</strong>. At the start, neither player knows the location of any piece.</li>
    </ol>

    <h2>How to Play</h2>
    <h3>Starting the Game</h3>
    <p>
        The two players first decide who will go first. This can be done by any random method, such as flipping a coin or playing Rock-Paper-Scissors. This player is referred to as <strong>Player 1</strong>.
    </p>

    <h3>The First Turn (Color Selection)</h3>
    <ol>
        <li>Player 1 begins the game by choosing any single face-down piece on the board and flipping it face-up.</li>
        <li>The color of this revealed piece (White or Black) is assigned to <strong>Player 2</strong>.</li>
        <li>Player 1 is then assigned the opposite color for the rest of the game.</li>
        <li>Player 1's turn is now over. The turn passes to Player 2 to make the first move.</li>
    </ol>
    
    <h3>A Regular Turn</h3>
    <p>After the first turn, players take turns moving one of their revealed pieces on the board according to its movement rules.</p>
    
    <h2>Movement & Capture</h2>
    <p>
        <strong>The Golden Rule:</strong> You can only interact with face-up pieces. Face-down ("unflipped") pieces cannot be moved or captured and act as blockers on the board.
    </p>
    <ul>
        <li>Pieces move and capture exactly as they do in a normal chess game.</li>
        <li>You may only move your own colored pieces that are already face-up.</li>
        <li>You may only capture an opponent's piece that is also face-up by landing on its square.</li>
    </ul>

    <h3>Special Rules</h3>
    <ul>
        <li><strong>No Check or Checkmate:</strong> The King can be captured like any other piece. There is no concept of "check".</li>
        <li><strong>No Pawn Promotion:</strong> When a Pawn reaches the opposite side of the board, it is not promoted. It remains a Pawn.</li>
    </ul>

    <h2>Ending the Game</h2>
    <p>The game ends immediately when one of the following conditions is met:</p>
    <ul>
        <li><strong>Elimination:</strong> One player has no pieces left on the board.</li>
        <li><strong>No Legal Moves:</strong> The player whose turn it is has no legal moves they can make with any of their pieces.</li>
    </ul>

    <h2>Winning & Scoring</h2>
    <p>
        As soon as the game ends, both players count the scores of all their pieces <strong>remaining on the board</strong>. The player with the higher total score is the winner. If the scores are equal, the game is a draw.
    </p>
    <h3>Piece Scores</h3>
    <ul class="score-list">
        <li>Queen: <span>17 points</span></li>
        <li>Rook: <span>11 points</span></li>
        <li>King: <span>8 points</span></li>
        <li>Bishop: <span>6 points</span></li>
        <li>Knight: <span>5 points</span></li>
        <li>Pawn: <span>4 points</span></li>
    </ul>
</div>

</body>
</html>
