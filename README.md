# BudgetBuddy

BudgetBuddy is an app designed to help you track daily spending. It is based on the "envelope budgeting" system.


## Prerequisites

BudgetBuddy requires a TI-89 running AMS version 2.07 or higher. It makes heavy use of the getDate() command, which was introduced in that AMS. The getDate() command also works on any TI-89 Titanium or Voyage 200 calculator, so BudgetBuddy should work on those systems as well. However, I have not tested it on those systems.

## Getting Started

I recommend storing all BudgetBuddy files in their own special folder on your calculator, named something like "budget".

Before using BudgetBuddy, set up your envelopes. Unarchive the matrix "envs" and open it from the Data/Matrix Editor.

Each row in the matrix represents an envelope. In theory BudgetBuddy supports arbitrarily many envelopes, though it will run slower if the number of envelopes gets too large. By default, the matrix contains four envelopes (rows).

The first column stores the envelope names. By default, there are four envelopes: "Disc.," "Food", "Transit", and "Gifts". Change these to whatever envelopes suit your needs. Feel free to add rows or delete rows if desired. You should have at least two envelopes.

The second column stores the monthly budget for each envelope, i.e. the amount you intend to spend from each envelope in a given month. For example, by default, the "Food" envelope has a monthly budget of $400, because I tend to spend about $400 on food each month.

You do not need to update the third column. It stores the amount you should spend each day, given the monthly budget. The program will automatically update this column on startup.

The fourth column stores the amount currently in your envelope, ie the amount that you have available to spend for the rest of the month. Update that column as needed.

You do not need to update the fifth column. It stores the ideal balance you would have available to be on track by the end of today. The program will automatically update this column on startup.



## Running the Program

Once you have set up your envelopes, you can run the program by typing "budget()" (no quotes) at the command line, and pressing ENTER.

### Main Screen
After booting up, the program will display the first two envelopes, the remaining balance in each for the month, and the remaining balance you can use today and still remain on track. You can scroll to see more envelopes by using the left and right arrow keys, select an envelope by typing its number, or press ESC to quit the program.

### Envelope View

If you select an envelope, a new screen appears showing the most recent transaction (if there is one). You can scroll to see previous transactions by using the left and right arrow keys. To create a new transaction, press the (+) key. You can also edit the transaction that is in focus by pressing (E/÷), or change the current balance of the envelope by pressing (B/left parenthesis).

To remove a transaction, edit it and change the transaction amount to 0. 

### Quitting the program
To exit the program, press "ESC" from the main screen. The program will perform some maintenance before quitting such as deleting unnecessary variables.


## Version History

Version 1.2: removed defragmenting feature to increase program speed.

## Authors

BudgetBuddy was written by Matthew Dirks.


## Acknowledgements
This program was loosely inspired by the "Goodbudget" smartphone app from Dayspring Technologies, Inc.

