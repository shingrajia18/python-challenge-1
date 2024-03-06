# Printing a Menu

## Introduction

In this activity, you'll navigate a food truck menu stored in a Python dictionary to print out different sections based on user selection.

## Instructions

1. Examine the starter code and the `menu` dictionary. Observe that there is a continuous loop that can only be exited when a user types "q" during an input prompt.

2. Inside the `while` loop, print out the first level of menu items in the dictionary, along with a number to indicate the user input. The printed output should be similar to the following text:

    ```text
    Which menu would you like to view?
    1: Snacks
    2: Meals
    3: Drinks
    4: Dessert
    ```

 *  This menu should be saved as a new dictionary, `menu_items`, with the numbers as the dictionary's keys and the menu category as the values.

3. Navigate to the `elif` conditional that checks if the `menu_category` selected by the user is a number.

4. Use the following pseudocode to navigate through printing the sub-menus.

    ```text
    # Check if the user selection is in the menu_items dictionary
    If yes
        # Save the name of the menu category as a variable
        # Tell the user the menu category they selected
        # Display a heading for the sub-menu
        # Initialize a counter for the menu items
        # Check if the 'value' of the sub-menu item is a dictionary
        If yes
            # Iterate through the dictionary items
            For each item in the dictionary
                # Print the menu item formatted as follows:
                # Item counter | Menu item - Menu sub-item | price
                # Pipe lines should match the heading format
                # Add 1 to the item counter
        Else
            # Print the menu item formatted as follows:
            # Item counter | Menu item | price
            # Pipe lines should match the heading format
            # Add 1 to the item counter
    Else
        # Print an error
    ```

    An example of the Dessert menu output follows.

    ```text
    You selected Dessert
    ------------------------------------------
    This is the Dessert menu.
    ------------------------------------------
    Item # | Item name                | Price
    -------|--------------------------|-------
    1      | Chocolate lava cake      | $10.99
    2      | Cheesecake - New York    | $4.99
    3      | Cheesecake - Strawberry  | $6.49
    4      | Australian Pavlova       | $9.99
    5      | Rice pudding             | $4.99
    6      | Fried banana             | $4.49
    ------------------------------------------
    ```

# README.md

## Code Source and Attribution

The code for the interactive ordering system was adapted from an assignment prompt provided in the Module 2 Challenge of the Python course. 

- Original code source: [Module 2 Challenge Instructions](https://bootcampspot.instructure.com/courses/5430/assignments/73203?module_item_id=1200258)
- Location within repository: [menu.py](https://github.com/shingrajia18/python-challenge-1)

Note: The code provided in the `menu.py` file has been modified and expanded upon to meet the requirements of the assignment.
