# Coffee_Machine
# Hyperskill Python project Coffee Machine

Stage 1 - 
  Objective
  
    The first version of the program just makes you a coffee. It should print to the standard output what it is doing as it makes the drink.

Stage 2 - 
  Objectives
  
    Let's break the task into several steps:

    - First, read the numbers of coffee drinks from the input.
    - Figure out how much of each ingredient the machine will need. Note that one cup of coffee made on this coffee machine contains 200 ml of       water, 50 ml of milk, and 15 g of coffee beans.
    - Output the required ingredient amounts back to the user.

Stage 3 - 
  Objectives
  
    Write a program that does the following:

    - It requests the amounts of water, milk, and coffee beans available at the moment, and then asks for the number of cups a user needs.
    - If the coffee machine has enough supplies to make the specified amount of coffee, the program should print "Yes, I can make that amount       of coffee".
    - If the coffee machine can make more than that, the program should output "Yes, I can make that amount of coffee (and even N more than         that)", where N is the number of additional cups of coffee that the coffee machine can make.
    - If the amount of given resources is not enough to make the specified amount of coffee, the program should output "No, I can make only N     cups of coffee".

Stage 4 - 
  Objectives
  
    Write a program that offers to buy one cup of coffee or to fill the supplies or to take its money out. Note that the program is supposed       to do one of the mentioned actions at a time. It should also calculate the amounts of remaining ingredients and how much money is left.       Display the quantity of supplies before and after purchase.

    - First, your program reads one option from the standard input, which can be "buy", "fill", "take". If a user wants to buy some coffee,       the input is "buy". If a special worker thinks that it is time to fill out all the supplies for the coffee machine, the input line will be     "fill". If another special worker decides that it is time to take out the money from the coffee machine, you'll get the input "take".
    - If the user writes "buy" then they must choose one of three types of coffee that the coffee machine can make: espresso, latte, or           cappuccino.
    - For one espresso, the coffee machine needs 250 ml of water and 16 g of coffee beans. It costs $4.
    For a latte, the coffee machine needs 350 ml of water, 75 ml of milk, and 20 g of coffee beans. It costs $7.
    And for a cappuccino, the coffee machine needs 200 ml of water, 100 ml of milk, and 12 g of coffee beans. It costs $6.
    - If the user writes "fill", the program should ask them how much water, milk, coffee and how many disposable cups they want to add into       the coffee machine.
    - If the user writes "take" the program should give all the money that it earned from selling coffee.
    At the moment, the coffee machine has $550, 400 ml of water, 540 ml of milk, 120 g of coffee beans, and 9 disposable cups.

    To sum up, your program should print the coffee machine's state, process one query from the user, as well as print the coffee machine's       state after that. Try to use functions for implementing every action that the coffee machine can do.

Stage 5 - 
  Objectives
  
    - Write a program that will work endlessly to make coffee for all interested persons until the shutdown signal is given. Introduce two new       options: "remaining" and "exit".
    - Do not forget that you can be out of resources for making coffee. If the coffee machine doesn't have enough resources to make coffee,         the program should output a message that says it can't make a cup of coffee.
    - And the last improvement to the program at this step — if the user types "buy" to buy a cup of coffee and then changes his mind, they         should be able to type "back" to return into the main cycle.
