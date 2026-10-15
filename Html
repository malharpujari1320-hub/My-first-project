<!DOCTYPE html>
<html lang="en">
<head>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Number Guessing Game</title>

<style>
body {
    font-family: Arial, sans-serif;
    background: linear-gradient(135deg, #141e30, #243b55);
    color: white;
    text-align: center;
    padding: 40px 10px;
}
.game {
    background: white;
    color: #222;
    max-width: 350px;
    margin: 40px auto;
    padding: 25px;
    border-radius: 15px;
}
input {
    padding: 12px;
    width: 80%;
    margin: 15px 0;
    font-size: 18px;
}
button {
    padding: 12px 20px;
    background: #243b55;
    color: white;
    border: none;
    border-radius: 8px;
    margin: 5px;
}
#message {
    font-weight: bold;
}
</style>
</head>

<body>

<div class="game">
    <h1>Guess the Number!</h1>
    <p>Guess a number between 1 and 100.</p>

    <input type="number" id="guess"
           min="1" max="100" placeholder="Your guess">

    <br>

    <button onclick="checkGuess()">Guess</button>
    <button onclick="restartGame()">Restart</button>

    <p id="message">Good luck!</p>
    <p>Attempts: <span id="attempts">0</span></p>
</div>

<script>
let secretNumber;
let attempts;
let gameOver;

function restartGame() {
    secretNumber = Math.floor(Math.random() * 100) + 1;
    attempts = 0;
    gameOver = false;

    document.getElementById("guess").value = "";
    document.getElementById("guess").disabled = false;
    document.getElementById("attempts").textContent = "0";
    document.getElementById("message").textContent = "Good luck!";
}

function checkGuess() {
    if (gameOver) return;

    const input = document.getElementById("guess");
    const guess = Number(input.value);
    const message = document.getElementById("message");

    if (input.value === "" ||
        !Number.isInteger(guess) ||
        guess < 1 || guess > 100) {
        message.textContent = "Enter a number from 1 to 100!";
        return;
    }

    attempts++;
    document.getElementById("attempts").textContent = attempts;

    if (guess < secretNumber) {
        message.textContent = "Too low! Try higher.";
    } else if (guess > secretNumber) {
        message.textContent = "Too high! Try lower.";
    } else {
        message.textContent =
            "You won in " + attempts + " attempts!";
        gameOver = true;
        input.disabled = true;
    }
}

document.getElementById("guess").addEventListener("keydown", function(event) {
    if (event.key === "Enter") checkGuess();
});

restartGame();
</script>

</body>
</html>
