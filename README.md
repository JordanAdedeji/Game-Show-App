# Game-Show-App
Created a browser version of “Wheel of Success”, a word guessing game where players click letters from an onscreen keyboard to try to guess a random phrase.
Using Javascript, I create an array of phrases and wrote functions in order to choose a random phrase from that array. I split the phrase into letters, and put those letters onto the game board.

Each time the player guesses a letter, it is compared with the random phrase. If the letter is in the phrase, the game board is updated with the chosen letters.

In this game, a player can keep choosing letters until they make five incorrect guesses. If the letter they chose isn’t in the phrase, one of the player’s 5 guesses is removed.

If the player completes the phrase before they run out of guesses, a winning screen will display. If the player guesses incorrectly 5 times, a losing screen will display.


