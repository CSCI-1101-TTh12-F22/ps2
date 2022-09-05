# Problem Set 2
### Due Friday, September 9, 2022, at 11:59pm EDT

For this problem set, you will submit to Canvas **a single .zip file**. Detailed instructions for what the .zip file should contain are at the end of this problem set. Note that if you do not submit the files as specified here, there will be a major deduction in your grade for this assignment. Following directions to the letter is a crucial skill for computer programming.

## Getting started

1. If you haven't already, create a folder called `CS1` on your Desktop, in your Documents, or in some place that is easy to find on your computer.

2. In that folder, create a folder called `ps2`. You will put all of the components required for this problem set in the `ps2` folder.

3. Launch IDLE.

## Part 1: Strings

1. In the IDLE Shell, create a variable `mystring` and set its value to `"assiduously"`. 

2. Write a command to print out the string's length, which is 11.

3. Write a command to print out the first letter of the string, which is "a".

4. Write a command to print out the last letter of the string, which is "y".

5. Create a variable called `middle` and use a **mathematical operation** to identify the location of the middle character of the string. The middle character of "assiduously" is "u". It is the 6th letter in the string, but remember that Python starts counting from 0, so it will be the character at "index 5". Then, write a command to print out the value of `middle`.

6. Write a command to print out that middle character using the variable `middle` that you created in step 5.

7. Write a command to print out `"assiduouslyassiduously"` using the `mystring` variable. 

8. Write a *different* command to print out `"assiduouslyassiduously"` using the `mystring` variable. 

9. Open a new file in IDLE (`File -> New File`). Save the file in your `ps2` directory, and call it `part1.py`.

10. Paste each of the above commands, in the order specified, into your `part1.py` file.

11. At the top of the file, write four comments:

* The name of the file.
* Your name.
* The date.
* A statement saying "This code is my own work. I did not share my code or look at the code of another student."

12. Save the file, select `Run -> Run Module`. The output should look like this

```
=================== RESTART: /Users/emilypx/Desktop/part1.py ===================
11
a
y
5
u
assiduouslyassiduously
assiduouslyassiduously
```


## Part 2: Numbers

1. Create a new file called `part2.py`. This program will estimate a user's body surface area, i.e., a measure of the area of a person's skin.

2. At the top, add these four comments: 

* The name of the file.
* Your name.
* The date.
* A statement saying "This code is my own work. I did not share my code or look at the code of another student."

3. The first line of the program  should use `input()` to ask the user for his height in inches and save it as a variable `H`. *(If you don't know how to do this, please see Lab 1! Don't forget that `input` will make a string, but you will need an integer or float to do calculations.)*

4. The second line of the program should use `input()` to ask the user for his weight in pounds and save it as a variable `W`.

5. Next write a line of code that calculates BSA according to the following forumula. Do this using only the mathematical operators and parentheses, as needed. Do not import any libraries.

<img src="formula.png" width=200>

6. Using `print()`, report to the user their BSA and tell them they look great.

7. Run your program.

Here's some examples of what the output of your script should look like. (Remember that you have to enter something when it asks a question!)

```
========= RESTART: /Users/emilypx/Desktop/CS1-F22/ProblemSets/part2.py =========
What is your height in inches? 69
What is your weight in pounds? 155
Your BSA is 1.8520156914054808 and you look great!

========= RESTART: /Users/emilypx/Desktop/CS1-F22/ProblemSets/part2.py =========
What is your height in inches? 62
What is your weight in pounds? 110
Your BSA is 1.4789260367652675 and you look great!

========= RESTART: /Users/emilypx/Desktop/CS1-F22/ProblemSets/part2.py =========
What is your height in inches? 73
What is your weight in pounds? 190
Your BSA is 2.109077303160572 and you look great!
```
---

## What to turn in
In your `ps2` folder you should have two python scripts: `part1.py` and `part2.py`. Remove any other things you might have accidentally put in the folder, then zip the folder up using whatever means you normally use to zip things up (e.g., on a Mac, you can control-click and select `Compress`).

Upload the `.zip` file you created to Canvas. 

Note that if you do not submit the files exactly as specified here (i.e., named correctly and zipped up in a folder called `ps2.zip`), there will be a major deduction in your grade for this assignment. Following directions to the letter is a crucial skill for computer programming.

### This problem set is due Friday, September 9, 2022, at 11:59pm EDT


