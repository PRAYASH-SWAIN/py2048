
***NOTE : The files for both programs are .txt extension since my PC does not have Python installed.***

**Two code files have been uploaded because I couldn't run a program with command line arguments on an online compiler. The second file, that is, *IvLabs ASSIGNMENT 1 (2048 GAME)* is working correctly where inputs have been taken during execution** 

# TASK : PYTHON PROGRAM TO IMPLEMENT 2048 GAME. 

COMPILER USED : [OnlineGDB](https://www.onlinegdb.com/online_python_compiler)

## GAMEPLAY DESCRIPTION

The game starts with the user entering the winning number(default value 5), size of the board(default value 2048). Once entered, a game board is displayed with a 2 on the board. The user has the option to move up('W'), move down('S'), move left('A') or move right('D') given that their move causes a change in the board orientation. If not, a message is displayed stating the same and the user is expected to play their move again. While moving in any direction, change(s) can be made in the following ways -  **1)** All non zero numbers are shifted to the farthest possible position in the direction of motion, in order of their position. Their original postions are replaced with zeroes. **2)** If 2 contiguous elements in direction of motion have the same value, the farther element in the direction of motion gets a value double of its original while the other value becomes zero. Step 1) is repeated after 2) once more to ensure all non-zero values are as shifted away in the direction of motion. For every succcessful move, a 2 is randomly placed at one position on the board which originally had a zero. The user is then asked to enter a direction of motion again following the same rules for play with a 2 being added after each successful move.

## WINNING A GAME

A user wins a game when they manage to have atleast one element on the board which is equal to the winning number. In a case where the user enters a value which is not an exponent of 2, the game would be won when the user manages to play through to have a value on the board greater than the winning number.

## LOSING A GAME

A user loses the game when they have no possible directions left for movement, that is, the board is full with no possible moves causing a change in the game board.

## ACTIONS
	W : Shift,merge elements up.
	S : Shift,merge elements down.
	A : Shift,merge elements left.
	D : Shift,merge elements right.	
    
## SAMPLE OUTPUT

<details><summary>Default input(5 and 2048)</summary>
<p>

![](/media2/default.png)

</p>
</details>

<details><summary>Moving Left</summary>
<p>

![](/media2/left.png)

</p>
</details>

<details><summary>Moving Right</summary>
<p>

![](/media2/right.png)

</p>
</details>

<details><summary>Moving Down</summary>
<p>

![](/media2/down.png)

</p>
</details>

<details><summary>Moving Up</summary>
<p>

![](/media2/up.png)

</p>
</details>

<details><summary>Winning game</summary>
<p>

![](/media2/win1.png)
![](/media2/win2.png)

![](/media2/win3.png)
![](/media2/win4.png)

</p>
</details>

<details><summary>Losing game</summary>
<p>

![](/media2/loss1.png)
![](/media2/loss2.png)

![](/media2/loss3.png)
![](/media2/loss4.png)

![](/media2/loss5.png)
![](/media2/loss6.png)

</p>
</details>

<details><summary>Unsuccessful move (Direction entered was left)</summary>
<p>

![](/media2/unsuccessful_move.png)

</p>
</details>
