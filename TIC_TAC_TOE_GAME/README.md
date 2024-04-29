# TIC_TAC_TOE_GAME
This Repository contains Source Code Python file of Tic Tac Toe Game

## REQUIREMENTS:

To Run the Source Code of Tic Tac Toe Game you would need Python3 Installed onto your Computer.

## INSTALLATION OF PYTHON 3:

STEP 1 : Visit the link [Python Link] (https://www.python.org/downloads) and Select the Version above 
         Python 3.0 and above

STEP 2 :  Download Python Executable Installer 

STEP 3 : Run Executable Installer

STEP 4 :  Verify Python Was Installed On Windows

***Note: if above steps are not clear please visit below link for more information***
(https://phoenixnap.com/kb/how-to-install-python-3-windows)


## GENERAL INSTRUCTION ABOUT GAME:

**INSTRUCTIONS**:

  1: YOU CAN MAKE YOUR MOVE BY ENTERING A NUMBER IN BETWEEN **0-8** 
  
  2: THE NUMBER WILL CORRESPOND TO THE BOARD POSITION AS ILLUSTRATED. 
  

                    0 | 1 | 2
                    ---------
                    3 | 4 | 5
                    ---------
                    6 | 7 | 8
                    
  3: **CONDITION OF WINNING** 
  
  WINNER WILL BE DECIDED ON THE BASIS OF WHOEVER SO FIRST FILL THEIR RESPECTIVE SIGN ON THE BOARD'S     POSITION THREE CONSECUTIVE IN ROW OR COLUMN OR EITHER IN DIAGONAL 
  
  4: PLAY YOUR WITH YOUR BEST MOVES.
  
## FUNCTIONS IN SOURCE CODE : 

The Source Code Contains many functions such as 
```
1) def main_tic_tac_toe()
2) def instructions()
3) def display_board()
4) def choose_player()
5) def choose_computer()
6) def win_vertical()
7) def win_horizontal()
8) def win_diagonal()
9) def win_direction()
10) def get_char()
```
## Function Description ##

***1) def main_tic_tac_toe():***
This Function is the main function of the game, This function will consist of many other functions under the block of def main_tic_tac_toe() Basically, this is a Driver Function for the Tic Tac Toe Game.

***2) def instructions():*** 
This Function consists of a print statement, which will print General instructions to play the game whenever the game gets started.

***3) def display_board():***
This Function will Display the board after every turn of the User as well as the Computer, This function Consists of Print Function to Display the Updated Entry while playing the game.

***4)  def choose_player():***
This Function contains Functionality of User's Gameplay, Initially it will Check for the user Character i.e X or O, and then it will check for the Choice of User that is the index ranging from 0 to 8 then, According to that it will update the Tic Tac Toe Board after every move which User played.

***5) def choose_computer():***
This Function contains Functionality of Computer's Gameplay, This Function will automatically choose the Character opposite to the User Choice, i.e If User Chooses X then Computer will Choose Character as O and Play the Game and vice versa, This Function consists of inbuild Python Function that is ***Random()*** So, The Computer will Choose the index of Tic Tac Toe Board randomly within the specified range of 0-8

***6) def win_vertical():***
This Function will Check the Vertical Column of Tic Tac Toe i.e Index [0,3,6] or [1,4,7] or [2,5,8] whether this Column index contains the identical character. And it will check whether the winning Condition is achieved by the User or Computer.

***7) def win_horizontal():***
This Function will Check the Horizontal Rows of Tic Tac Toe i.e Index [0,1,2] or [3,4,5] or [6,7,8] 
whether this Rows index contains identical character. And it will check whether the winning Condition is achieved by the User or Computer.  

***8) def win_diagonal():***
This Function will Check the Diagonal Index of Tic Tac Toe i.e Index [0,4,8] or [2,4,6] whether this Diagonal index contains the identical character. And will check whether the winning Condition is achieved by the User or Computer.  

***9) def win_direction():***
This Function will Check the Direction of Winning Condition i.e whether Won by Vertical, Horizontal or Diagonal

***10) def get_char():***
This function will give the User a choice to choose the Character X or O to play the game.

## OTHER FUNCTIONALITY AND VALIDATION ##

The game will restart once the winner or tie situation comes in which user will be asked "DO YOU WANT TO RESTART THE GAME (Y/N) if they want to play or not if a user enters Y then the game will restart else if N, then there will be a prompt message "THANK YOU FOR PLAYING THE GAME"

This Program has Validation such that it will check for the user's input index number if the number entered is valid then it will let the user proceed with the game further, if not Then it will prompt -"PLEASE ENTER NUMBER WITHIN THE RANGE OF 0-8 " to User to enter valid index number.

This has Validation, To check the Input character which will be accepted by User X or O. If the character entered by the user is other than these two characters it will prompt user such that "INVALID CHARACTER, CHOOSE VALID CHARACTER X or O "

## RESOURCE ## 
* Python (https://www.python.org/doc)
* Python Tutorial (https://www.tutorialspoint.com/python/index.html)

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
**CREATED BY RISHI PATEL**

**SOFTWARE ENGINEER** 
