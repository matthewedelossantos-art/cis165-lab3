CIS-165-W198

Matthew Delos Santos

Program 1: Diamond Pattern

My plan is to write a separate cout statement for each of the seven lines. I will include the correct number of spaces before each group of asterisks so that the pattern forms a diamond. I will use endl to move to the next line and compare the program output with the assignment example.

Program 2: Video Game Level Times

My plan is to store the Level 1 time of 78 minutes and the Level 2 time of 144 minutes in separate integer variables. I will use integer division by 60 to calculate the hours and the remainder operator to calculate the remaining minutes. I will subtract the two original times to find the difference, then convert that difference into hours and minutes. I will store the calculations in variables before displaying the labeled results.


3. Testing and Results

Test 1: Diamond Pattern

Expected result before running: Seven lines with the following spacing and asterisk counts:

   *
  ***
 *****
*******
 *****
  ***
   *

Actual output: 
   *
  ***
 *****
*******
 *****
  ***
   *

Match or correction: Initially, i created a triangle and then realized my mistake and needed to add symmetrical stars to make a diamond. I also initially created a all the lines without spaces.

Test 2: Assigned Video Game Times

Values used:

Level 1: 78 minutes

Level 2: 144 minutes

Expected results before running:

Calculation

Expected result

Level 1 hours

78 / 60 = 1

Level 1 remaining minutes

78 % 60 = 18

Level 2 hours

144 / 60 = 2

Level 2 remaining minutes

144 % 60 = 24

Difference in minutes

144 - 78 = 66

Difference in hours

66 / 60 = 1

Difference in remaining minutes

66 % 60 = 6

Expected output:

Level 1 time: 1 hours and 18 minutes
Level 2 time: 2 hours and 24 minutes
Difference: 1 hours and 6 minutes

Actual output: 
Level 1 time: 1 hours and 18 minutes
Level 2 time: 2 hours and 24 minutes
Difference: 1 hours and 6 minutes


Match or correction: I needed to adjust spaces so that is will show all the values properly by line

Test 3: Changed Video Game Times

For an additional test, temporarily change the values in game_time.cpp to:

Level 1: 95 minutes

Level 2: 157 minutes

Expected results before running:

Calculation

Expected result

Level 1 time

1 hour and 35 minutes

Level 2 time

2 hours and 37 minutes

Difference in minutes

157 - 95 = 62

Difference

1 hour and 2 minutes

Expected output:

Level 1 time: 1 hours and 35 minutes
Level 2 time: 2 hours and 37 minutes
Difference: 1 hours and 2 minutes

Actual output:
Level 1 time: 1 hours and 35 minutes
Level 2 time: 2 hours and 37 minutes
Difference: 1 hours and 2 minutes


Match or correction: Match 

Code Explanations

Diamond Program

The diamond program uses seven cout statements, one for each line of the pattern. Spaces inside the quotation marks position the asterisks. The number of asterisks increases toward the middle line and decreases afterward. The program does not need loops or user input because every line is written explicitly.

To check the spacing, I will compare each line against the assignment example and count its leading spaces and asterisks.

Game Time Program

Integer division (/) divides two integers and keeps the whole-number result. The remainder operator (%) gives the amount left over after division.

For example, dividing 78 by 60 gives 1 whole hour, while 78 % 60 gives 18 remaining minutes. Together, these results represent 1 hour and 18 minutes.

The Level 1 variable starts at 78 minutes. Dividing by 60 produces 1 hour, and taking the remainder produces 18 minutes.

The Level 2 variable starts at 144 minutes. Dividing by 60 produces 2 hours, and taking the remainder produces 24 minutes.

Subtracting the Level 1 time from the Level 2 time gives 66 minutes. Dividing 66 by 60 produces 1 hour, and the remainder is 6 minutes. Therefore, Level 2 took 1 hour and 6 minutes longer.


Storing calculations in variables separates the calculation from the output. This makes the program easier to read, test, debug, and explain. It also follows the assignment's requirement to calculate the results before displaying them with cout.



   
