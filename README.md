<!DOCTYPE html>

  <head>
    <title>Movie Hangman</title>
    <link rel = "stylesheet" href = "style.css">
    
  </head>

  <body>

    <main>

      <h1>M o v i e  H a n g m a n</h1>

      <div id = "gallows" class = "image">
        <img style = "padding-right: 70px " id = "hangmanImage" src = "img/hangman0.png">
      </div>

      <div id = "word"></div>

      <br>

      <div id = "controls">
        <input type = "text" id = "guessBox">
        <button id = "guessWordButton" class = "button" onclick = "guessWord( game )">Guess Word</button>
        <button id = "newGameButton" class = "button" onclick = "newGame();">New Game</button>
        <br>
        <br>
      </div>

      <br>

      <div id = "guesses"></div>

    </main>   

   <script src = "java.js"></script>

  </body>
  
</html>
