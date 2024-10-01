# The-Incredibles

# Team members

Srihari Dasari<br />

Akanksha Gottumukkala<br />

# Description 
our application is " THE SCRUM GAME".<br />

Basically this application will allow students to play the game so that they can learn about WIP limits in a sportive and exciting way.<br />

# Installations
Python<br />

Flask<br />

Random<br />

matplotlib<br />

These 3 are required to be installed on system to run this project.<br />

The required files are provided in the requirement.txt file as well.<br />

# Running
Python can be installed in the system using the following link
```
https://www.python.org/downloads/macos/
```
First install the requirements mentioned in the requirement.txt file using the following commands
```
pip3 install -r requirements.txt
```
First we need to run the application.py file. using the command
```
python3 application.py
```
Now copy and paste the local host link in to your local browser and click "enter".
Example of the URL may be 
```
http://127.0.0.1:5000
```

Now the welcome page appears click on "stat here" to stat the game.<br />
That directs you to the main page of SCRUM GAME.<br />
Home page contains severals buttons like - Roll Dice, Reset, Roll Dice for a Day, and day count, and the score of the day will appear after every single day.<br />
There is a button to change the configuration in the config button. Which allows user with 3 different options.<br />
These options will change the way the game runs.<br />

# usage
  1. Click on the "Roll  Dice" button to roll the dice and move the tokens from one bucket to next bucket 
  and it will also show from which bucket the tokens will move.<br />
  2. The first step continues till 10 days are completed.After every 5 rolls of a dice is considered as 1 day.<br />
  3. You can reset the game by clicking on the "reset" button.<br />
  4. "Roll Dice for a Day" is a special feature which rolls the dice 5 times and displays day resut,<br />
  5. By clicking on “show/hide graph here” button the cumulative graph will be displayed on the side of the screen
   where as “show graph in new page” will display cumulative graph in a new page.<br />
  6. Clicking on "result" button will navigate you to a result page and result table will be displayed.<br />
  7. clicking on  "c" button at top right corner will display the configuration selections.<br />
  8. clicking on config button will navigate to new page.<br />
  9. This page has three buttons "select game type" and "modify game parameters" and "modify any game config" and "back to normal" button.<br />
  10. clinking on "select game type" button will navigate to new page .<br />
     a)” Work In Progress (WIP) Limit to the Refinement bowl”. 
     If you select this option, you can be able to select a value below Enter the value for above option. 
     Here you can set the WIP limit of your choice to the game and click on the submit button to start the game.<br />
     b) “System WIP (aka Con WIP) Limit to your Middle 4 Bowls”. 
     If you select this option, you can select a value below as similar to (a) option, but it applicable for middle 4 bowls and click on submit button to    start the game.<br />
     c) “Positive Modifier (like +2)”. 
     If you select this option, you can be able to select either positive or negative value and click on the submit button to start the game.<br />
  11. clicking on "modify game parameters" will navigate to new page.<br />
     a) Click on Select Dice Max Value button to select the custom maximum value on the dice. You can have the maximum value on the dice as 4 or 6 or 8.<br />
     b) Click on Select Number of Buckets button to select the number of buckets on the game rather than having fixed number of buckets. You can have 5 to 7 buckets on the game as you wish.<br />
     c) Click on Select Number of Days for Game to have the customized count of days to complete a round of game. You can select the number of days as 5 or 10 or 15.<br />
  12. clicking on "modify any game config" will navigate you to new page. here you can select both game mode  as well as you can modify the parameters simultaneously.<br />   
  13. Clicking on instruction botton will display the instructions.<br /> 
  
