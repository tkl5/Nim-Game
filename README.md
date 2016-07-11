# Nim Game

Simulates the game of Nim, in which two players alternate in removing the stones arranged in piles. On each turn, a player must remove one or more stones, provided all stones come from the same pile. The player that takes the last stone/s from the only remaining pile wins the game. First, go to the following site to play the game a few times to understand how it is played: http://www.dotsphinx.com/games/nim/
(the piles are arranged in columns and clicking on a specific dot indicates you want to remove the stones from that position up). 


Your Nim game should proceed as follows:

1.	Ask player 1 for his name

2.	Ask player 2 for his name

3.	Use random number generator to generate between 2 to 5 piles and to generate between 1 to 8 stones in each pile.

4.	Display the board in the following fashion:  (Note: O is the letter capital O)


  Pile 1:	O O O 

  Pile 2:	O

  Pile 3:	O O

  Pile 4:	O O O O O O O O


5.	Ask player 1 for the move – the pile number and the number of stones to remove. You need to make sure that if a user enters something invalid, whether the pile or stone number, you ask for input again until valid input is entered. Also, the program is to give a suggestion to player 1 as to the number of stones to remove and from which pile in order to win the game. The winning strategy that is to be proposed by the program is explained later on in this document.

6.	Repeat step 4

7.	Repeat step 5 for player 2.

8.	When the game terminates, you need to proclaim the winner.

9.	You should ask, if the players want to play the game again; if so, repeat steps 1-9



You are given a sample program run below – make sure your prompts look like the ones provided in the sample run.


# Sample Run

Playa 1, enter your name:  Superman


Playa 2, enter your name:  Batman

Let's look at the board now.

----------------------------

Pile 1:	O

Pile 2:	OOO

Pile 3:	OOO

----------------------------

Hint: nim sum is 1

Pick 1 stones from pile 1 

Superman, how many stones to remove? 2

Pick a pile to remove from:  a

Hmmm. You entered an invalid value. Try again, Superman.

Superman, how many stones to remove? 2

Pick a pile to remove from:  4

Hmmm. You entered an invalid value. Try again, Superman.

Superman, how many stones to remove? a

Pick a pile to remove from:  3

Hmmm. You entered an invalid value. Try again, Superman.

Superman, how many stones to remove? 4

Pick a pile to remove from:  3

Hmmm. You entered an invalid value. Try again, Superman.

Superman, how many stones to remove? 2

Pick a pile to remove from:  a

Hmmm. You entered an invalid value. Try again, Superman.

Superman, how many stones to remove? 3

Pick a pile to remove from: 2

Let's look at the board now.

----------------------------

Pile 1:	O

Pile 2:	

Pile 3:	OOO

----------------------------

Hint: nim sum is 2

Pick 2 stones from pile 3 

Batman, how many stones to remove? 2

Pick a pile to remove from: 3

Let's look at the board now.

----------------------------

Pile 1:	O

Pile 2:	

Pile 3:	O

----------------------------

Hint: nim sum is 0

Pick 1 stones from pile 3

Superman, how many stones to remove? 1

Pick a pile to remove from: 3

Let's look at the board now.

----------------------------

Pile 1:	O

Pile 2:	

Pile 3:	

----------------------------

Hint: nim sum is 1

Pick 1 stones from pile 1

Batman, how many stones to remove? 1

Pick a pile to remove from: 1

Let's look at the board now.

----------------------------

Pile 1:	

Pile 2:	

Pile 3:	

----------------------------

Batman is the winner of this round!

Do you want to play again? Enter y for yes, anything for no: 


