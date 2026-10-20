AI Reflection — CIS-165 Lab 3

Tools Used

I used ChatGPT to help me understand the requirements for the two C++ programs, write an initial version of the code, and troubleshoot a compiler error. I also used it to understand how cout, #include <iostream>, integer division, and the remainder operator work.

One Decision

One prompt I used was asking for help fixing the error saying that cout was not declared. ChatGPT explained that I needed #include <iostream> to use cout and endl. I used this suggestion because my program used C++ output statements, but I had included stdio.h instead. I also used separate variables for the time calculations in game_time.cpp because the assignment required me to calculate the results before displaying them.

Verification

I checked the expected output for the diamond pattern and calculated the expected results for the game-time program. For the assigned values, 78 minutes should equal 1 hour and 18 minutes, while 144 minutes should equal 2 hours and 24 minutes. Their difference is 66 minutes, or 1 hour and 6 minutes. I still need to compare these expectations with my actual program output and record the results from my own runs.

Learning

I learned why C++ programs need the correct header for cout and how integer division and the remainder operator convert minutes into hours and remaining minutes. I still need more practice compiling programs, checking output carefully, and explaining each line of code without relying on AI.
