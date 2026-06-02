# Food Ordering System

A simple command-line Food Ordering System written in Python. Users can select food items from a menu, add them to a cart, and view their total bill.

## Features

* Displays a menu with item prices.
* Allows users to add multiple items to their cart.
* Calculates the total cost automatically.
* Simple and interactive command-line interface.
* Supports quitting the ordering process at any time.

## Requirements

* Python 3.x

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/rohitdahiya04/food-ordering-system.git
```

2. Navigate to the project directory:

```bash
cd food-ordering-system
```

3. Run the program:

```bash
python main.py
```

## Menu

| Item     | Price ($) |
| -------- | --------- |
| Pizza    | 3.00      |
| Nachos   | 4.50      |
| Popcorn  | 6.00      |
| Fries    | 2.50      |
| Chips    | 1.00      |
| Pretzel  | 3.50      |
| Soda     | 3.00      |
| Lemonade | 4.25      |

## How to Use

1. View the menu displayed on the screen.
2. Enter the name of a food item to add it to your cart.
3. Continue adding items as desired.
4. Enter `q` to finish your order.
5. The program will display:

   * Items ordered
   * Total amount to pay

## Example

```text
-------------MENU-------------
pizza     : $3.00
nachos    : $4.50
popcorn   : $6.00
fries     : $2.50
chips     : $1.00
pretzel   : $3.50
soda      : $3.00
lemonade  : $4.25
------------------------------

Select an item (q to quit): pizza
Select an item (q to quit): soda
Select an item (q to quit): fries
Select an item (q to quit): q

--------------Your Order---------------
pizza soda fries

Total is $8.50
```

## Project Structure

```text
food-ordering-system/
│
├── main.py
└── README.md
```

## Future Improvements

* Add item quantities.
* Generate itemized bills.
* Save order history.
* Add discounts and coupons.
* Create a graphical user interface (GUI).

## Author

Rohit Dahiya

* GitHub: https://github.com/rohitdahiya04

## License

This project is open source and available under the MIT License.
