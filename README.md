# 🚗 Rent а Car Project

# 🌟 Project goals:
  This project develops a system for viewing, renting and returning cars. Through a menu selection made by the Frond-end, the user selects a specific option, going through a check to see if the message entered is valid. With the help of the Back-end, the corresponding function is executed and the result is again returned to the Frond-end programmer, who provides it to the user.

# 🛠 System operation
  In the car rental system, it works like this:
 - At the beginning, the menu is visualized, with which the user can choose an option from 1 to 4, using the function def main_menu().
 - When the user's selection is made, the program initializes it using the def run_program() function, which starts the program.
 - If you choose option 1, the user has the option to view all available rental cars with their ID, make, model, rental price, and whether they are currently available for rental, with the function in the program responsible for this being def initialize_cars().
 - Choosing option 2 also triggers the function def rent_car(cars, car_id) and the user can rent the car, and if he tries to rent an already rented car, the program displays a message to that effect.
 - When choosing option 3, the user indicates that he wishes to return the car he has already rented, and again, if he enters the wrong car ID, the program sends a message to the user to correct his mistake. In software, the function def return_car(cars, car_id, days) performs this operation. Also here is the calculation of the price that the user has to pay.
 - By choosing option 4, the user can exit and finish working with the program.
   All the work of the project is based on the use of various functions, basic checks, proper structuring of the data and proper storage of it in various variables, lists and others.

# 🎯 Check by the project manager:
  The tests performed on the features in the project found that everything works as expected. There is coordination between the front and rear components. The UI in the project interacts correctly with the backend logic. Various plots in the program have been tested, as a result of which it can be seen that they are taken into account and the car rental program works perfectly.

# 📋 Sorce code:

https://pastebin.com/xgB4xNV3

# Screenshots:
 - The main menu:

![1 меню](https://github.com/user-attachments/assets/c3340b7a-56ea-4eef-afea-8c24d52745cf)

 - Option 1:

![опция 1](https://github.com/user-attachments/assets/2a3cbf10-0937-4d3b-bf8b-4fc05f672aa6)

 - Preview of the menu with already rented cars

![1](https://github.com/user-attachments/assets/9540a31e-534f-4f2f-a02e-d80050ed09a2)


 - Option 2: Rental

![опция 2 пак](https://github.com/user-attachments/assets/6306aa60-2d3e-4edb-a3df-c6a861c64415)

 - Option 3: Return

![3](https://github.com/user-attachments/assets/3a04321f-015b-411c-af18-e356c3553ac9)


 - Option 4: Exit

![опция 4](https://github.com/user-attachments/assets/37d3a5db-c191-4f4a-ac05-923681820280)
