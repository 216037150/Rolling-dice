# Rolling-dice

## HTML:

    The HTML structure includes a <div> with the class main-content.
    Inside it, there's a <div> with the class container, containing an <h1> heading and two <div> elements with the class dice.
    Each .dice div contains a paragraph with either "Player 1" or "Player 2" text, and an <img> element with classes img1 and img2.
    After the container, there's a <div> with the class btn-replay, containing a <button> element with the ID replayButton.

## JavaScript:

    The JavaScript function rollDice() is defined.
    It generates random numbers between 1 and 6 using Math.random() and Math.floor() to simulate dice rolls.
    It constructs the file path for the corresponding dice images based on the random numbers.
    It sets the src attribute of the <img> elements with classes img1 and img2 to the randomly selected dice images.
    It compares the random numbers to determine the winner (or if it's a draw) and updates the text of the <h1> element accordingly.
    An event listener is added to the replayButton that triggers the rollDice() function whenever the button is clicked.
    Finally, rollDice() is called once to display the initial dice roll result when the page loads.


## DOM
    When the page loads, rollDice() is called, which generates random dice rolls, updates the images, and displays the result.
    Clicking the "Replay" button triggers the rollDice() function again, simulating a new round of dice rolls and updating the result.
    The function also dynamically changes the content of the h1 element to display the outcome of the dice rolls, whether it's a win for 
    Player 1, Player 2, or a draw.
