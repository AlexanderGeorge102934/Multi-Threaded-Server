The contents of this repository creates a server that plays a word guessing game with each client that connects
to that server (similar to Wheel of Fortune or Hangman). Each client that logs into the
server must guess 3 different words in 3 different categories to win. First, the client picks
a category. The server will send the client the number of letters in a word from that
category to guess. The client gets to guess a total of six letters, one at a time. Correct
guesses do not count towards the six guess total.
The client will guess a letter and send it to the server. The server will respond with
either: the letter is in the word and where that letter is located or the letter is not in the
word and how many guesses are left.
If the client guesses the word within 6 letter guesses, they can not guess at another
word in the same category but must chose from the two remaining. If they do not guess
the word correctly, they are free to choose from any of the three categories for another
word. Clients may guess at a maximum of three words per category. If they do not make
a correct guess within three attempts, the game is over. The game is won when the
client successfully guesses one word in each category. When the game is over, the
client can either play again or quit. 
