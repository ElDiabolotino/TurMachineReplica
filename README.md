# TuringMachineReplica
I am trying to replicate a tabletop game called Turing Machine for my friends and personnal enjoyment


This game focuses on finding a code of three numbers from 1 to 5.

How to find them? Choose a combination of these three numbers, each number has a corresponding "mask" and the combination makes it so that only one small square goes through every mask 

This combination is then presented to different "condition cards" that, through the small square, confirm or deny a whether the combination fulfills the condition associated with the card. 

Only one combination fulfills every condition and this combination is the winning code ! 
How to win against multiple people ? verify less conditions than your opponent before deducing the code. 

48 conditions (4 to 6 per game)
95 cards associated with the conditions (1 per condition in the game)

The cards and the "masks" are matrices of 12x12 squares, each card has some identification numbers 



Parts not solved : 
- How to proceduraly create a code
- How to link functions verifying the conditions to the specific card 
- Which engine ? 

Can do :
- increase the possible numbers in the combinations (from 1 to 9, use 4 or 5 digits,...)

Solved : 
- Use Bitwise AND for the combinations in order to simulate the final mask (and verify the validity of the code -> the sum of the array is 1)


Not implemented but possible use 
- Arrays of 0x1 to 0xF to code the ID of the combination

