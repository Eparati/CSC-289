Dice Roller User Manual
Overview
The Dice Roller is a web application that allows users to roll dice and view the results. It supports rolling multiple dice with a customizable number of sides per die. This program was created with the assistance of an AI system, with only minor manual editing. The specific AI used were mostly via poe.com: 
PythonAIChat By Anas Katwa @anaskatwa
Claude-3-Haiku via @Poe, official host.
This program was built under the assumption that Large Language Models could be stress tested to make a functional webpage capable of processing information.
Features
Roll Dice: The main feature of the Dice Roller is the ability to roll dice. Users can enter a dice format (e.g., "2d6") and click the "Roll Dice" button to generate a random roll.
View Roll Results: After rolling the dice, the application will display the individual dice rolls and the total sum.
Roll History: The Dice Roller keeps track of the last 5 dice rolls. Users can toggle the roll history to view the previous rolls.
How to Use
Open the Application: Access the Dice Roller application by navigating to the appropriate URL or running the application locally.
Enter Dice Format: In the "Enter dice format" input field, enter the dice format you want to roll. The format should be in the form of "xdy", where "x" is the number of dice and "y" is the number of sides per die. For example, "2d6" would roll two 6-sided dice.
Roll the Dice: Click the "Roll Dice" button to generate a random dice roll.
View the Results: The application will display the individual dice rolls and the total sum.
View Roll History: If you want to see the history of previous dice rolls, click the "View Roll History" button. To hide the roll history, click the "Hide Roll History" button.
Error Handling
If you enter an invalid dice format, the application will display an error message explaining the correct format.

Technical Details
The Dice Roller is built using the Flask web framework for Python. It uses the random module to generate random dice rolls. The application stores the last 5 dice rolls in a list, which is displayed in the roll history.

This program was created with the assistance of an AI system, with only minor manual editing. The AI was responsible for the majority of the code development, while the human user provided guidance and made minor adjustments as needed.

Conclusion
The Dice Roller is a simple and easy-to-use web application for rolling dice. It allows users to customize the number of dice and the number of sides per die, and provides a history of previous rolls. Enjoy using the Dice Roller for your gaming needs!
