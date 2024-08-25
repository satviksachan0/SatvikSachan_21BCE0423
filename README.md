<!-- Embed Google Fonts -->
<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&family=Montserrat:wght@400;700&display=swap" rel="stylesheet">

<!-- Title -->
<h1 style="font-family: 'Montserrat', sans-serif; color: #2c3e50; text-align: center; font-weight: 700;">
    Chess-like Game
</h1>

<!-- Introduction -->
<p style="font-family: 'Roboto', sans-serif; font-size: 18px; color: #34495e; line-height: 1.6;">
    Welcome to the <b>Chess-like Game</b>, a web-based, turn-based strategy game inspired by chess. The game is designed to be played by two players on a 5x5 grid. Each player commands a set of pieces with unique movement abilities. The objective is to outmaneuver and capture your opponent's pieces until one player remains victorious.
</p>

<!-- Game Features -->
<h2 style="font-family: 'Montserrat', sans-serif; color: #2980b9; font-weight: 700; margin-top: 30px;">
    Game Features
</h2>
<ul style="font-family: 'Roboto', sans-serif; color: #2c3e50; font-size: 16px; line-height: 1.6;">
    <li><b>Real-Time Multiplayer:</b> Play with another player in real-time through a WebSocket server.</li>
    <li><b>Unique Grid Layout:</b> A compact 5x5 grid that demands strategic thinking and quick decision-making.</li>
    <li><b>Dynamic Piece Movement:</b> Pieces have distinct movement patterns, creating complex tactical scenarios.</li>
    <li><b>Victory Conditions:</b> The game ends when one player captures all of the opponent's pieces or achieves the set win condition.</li>
</ul>

<!-- Installation Instructions -->
<h2 style="font-family: 'Montserrat', sans-serif; color: #2980b9; font-weight: 700; margin-top: 30px;">
    Installation and Setup
</h2>
<p style="font-family: 'Roboto', sans-serif; font-size: 16px; color: #34495e; line-height: 1.6;">
    To get the game up and running locally, follow these steps:
</p>
<ol style="font-family: 'Roboto', sans-serif; color: #2c3e50; font-size: 16px; line-height: 1.6;">
    <li>Clone the repository to your local machine:
        <pre style="background-color: #f4f4f4; padding: 10px; border-radius: 5px; font-family: 'Courier New', monospace;">
git clone https://github.com/satviksachan0/chess-game.git
        </pre>
    </li>
    <li>Navigate to the project directory:
        <pre style="background-color: #f4f4f4; padding: 10px; border-radius: 5px; font-family: 'Courier New', monospace;">
cd chess-game
        </pre>
    </li>
    <li>Install the required dependencies:
        <pre style="background-color: #f4f4f4; padding: 10px; border-radius: 5px; font-family: 'Courier New', monospace;">
npm install
        </pre>
    </li>
    <li>Start the server:
        <pre style="background-color: #f4f4f4; padding: 10px; border-radius: 5px; font-family: 'Courier New', monospace;">
npm start
        </pre>
    </li>
    <li>Open your web browser and navigate to <a href="http://localhost:8080" style="color: #2980b9;">http://localhost:8080</a> to start playing!</li>
</ol>

<!-- Game Rules -->
<h2 style="font-family: 'Montserrat', sans-serif; color: #2980b9; font-weight: 700; margin-top: 30px;">
    Game Rules
</h2>
<ul style="font-family: 'Roboto', sans-serif; color: #2c3e50; font-size: 16px; line-height: 1.6;">
    <li><b>Grid:</b> The game board consists of a 5x5 grid.</li>
    <li><b>Pieces:</b> Each player has several pieces, including "Pawn," "Hero1," and "Hero2," each with distinct movement abilities.</li>
    <li><b>Turns:</b> Players take turns moving one piece at a time. The current player is indicated at the top of the game screen.</li>
    <li><b>Winning the Game:</b> Capture all of your opponent's pieces or achieve the specified win condition to win the game.</li>
    <li><b>Movement:</b> Click on a piece to view its possible moves, highlighted on the grid. Click on a highlighted cell to move the piece.</li>
</ul>

<!-- Technologies Used -->
<h2 style="font-family: 'Montserrat', sans-serif; color: #2980b9; font-weight: 700; margin-top: 30px;">
    Technologies Used
</h2>
<ul style="font-family: 'Roboto', sans-serif; color: #2c3e50; font-size: 16px; line-height: 1.6;">
    <li><b>Frontend:</b> HTML, CSS, JavaScript</li>
    <li><b>Backend:</b> Node.js, Express, WebSocket</li>
    <li><b>Version Control:</b> Git, GitHub</li>
</ul>

<!-- Screenshot -->
<h2 style="font-family: 'Montserrat', sans-serif; color: #2980b9; font-weight: 700; margin-top: 30px;">
    Screenshot
</h2>
<p style="text-align: center;">
    <img src="screenshot.png" alt="Game Screenshot" width="600" style="border-radius: 10px; border: 2px solid #2980b9;">
</p>

<!-- License -->
<h2 style="font-family: 'Montserrat', sans-serif; color: #2980b9; font-weight: 700; margin-top: 30px;">
    License
</h2>
<p style="font-family: 'Roboto', sans-serif; font-size: 16px; color: #34495e; line-height: 1.6;">
    This project is licensed under the MIT License. See the <a href="LICENSE" style="color: #2980b9;">LICENSE</a> file for more details.
</p>
