# CPlusPlus
C++ Programming Assignments


8-1 Journal: README

Nicholas Shaner
SNHU
CS-210-R4727 Programming Languages
Professor Cory Thoma
April 28, 2024


Project Summary:
The program I decided to share was completed in module 5. As a new junior developer of Chada Tech, a theoretical software development firm, I was tasked with working with a local bank in creating a program that would be usable for high school students to aid in teaching them about fiscal responsibilities. The program’s aim was to be an interactive tool used to help understand investment and compound interest. The program was to accept an initial investment amount, a monthly recurring deposit, the investment APR, as well as a designated number of years to invest. The program would then display two ROI tables. The first would show the yearly interest and account balance for each year of investment without any recurring monthly deposits. The second table would supply the same information with the calculated recurring monthly deposits.

Program Highlights:
What I feel I was able to do particularly well in this project was the code structure. I was able to successfully utilize a class with member elements and functions, as well as global functions for printing all the tables and menus as required. My program utilizes a header file to declare the class and global variables and declare any necessary C-files that would be needed. I then create a file for initializing the class and handling the class functions, another page for handling the global print functions, as well as a main file to run the program.

Make It Better:
	After completing my program and verifying its operation, I received one piece of feedback that could have really improved my program; in particular, input handling. With my current program, though it functions correctly and displays all the correct values needed, there is not input validation to restrict the end user from inputting negative numbers or non-number characters. By modifying the user input loops of the class functions to limit these inappropriate values, my program would have worked flawlessly.

The Challenge:
	While designing this program, there was one aspect that proved to be a real challenge. Within the print file, a nested loop iteration was used to calculate monthly interest returned based off of the user defined yearly percentage rate. After what seemed to be an endless number of attempts, I was able to solve the error with help and guidance after posting my issue on the StackOverflow forum page. Since taking multiple different coding courses, StackOverflow has been an essential tool through multiple tasks and projects. The question-and-answer forums allow users to get answers and examples from other members of the coding community of all different skill levels.

Transferrable Skill:
	The primary concept behind this project has already proven to be beneficial in additional projects and will be particularly transferrable to other projects and languages in the future. This is the concept of classes. As C++ is the basis for a number of later languages, the function and construct of classes learned in this class will be usable in others. 

Maintenance:
	In addition to the benefits class concepts provide, they also make programs very maintainable and easily modified. When using a class, objects are created in the terms of the class. Each variable and function is then called in reference to the class against the object created. Additionally, to create consistent and readable code, appropriate naming conventions, and syntax structure were used. This includes easily readable variable and functions titles, as well as well documented inline and multiline comments to direct and explain code decisions and function expectations.
