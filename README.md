# Shopping-Cart

A Python business application that automates the checkout process for a local grocery store.

## Prerequisites

  + Anaconda 3.7+
  + Python 3.7+
  + Pip

## Installation

Fork this [remote repository](https://github.com/abansal22/Shopping_cart) under your own control, then "clone" or download your remote copy onto your local computer.

Then navigate there from the command line (subsequent commands assume you are running them from the local repository's root directory):

```sh
cd ~/Desktop/shopping_cart
```
Use Anaconda to create and activate a new virtual environment, perhaps called "shopping-env":

```sh
conda create -n shopping-env python=3.8
conda activate shopping-env
```

After activating the virtual environment, install package dependencies:

```sh
pip install -r requirements.txt
```

## Setup

### Usage

Run the program:

```py
python shopping_cart.py
```

### Inputs

At Good Foods Grocery, we keep in stock 20 items. See below:
```
 "Chocolate Sandwich Cookies"	 price:	 3.50
 "All-Seasons Salt"	 price:	 4.99
 "Robust Golden Unsweetened Oolong Tea"	 price:	 2.49
 "Smart Ones Classic Favorites Mini Rigatoni With Vodka Cream Sauce"	 price:	 6.99
 "Green Chile Anytime Sauce"	 price:	 7.99
 "Dry Nose Oil"	 price:	 21.99
 "Pure Coconut Water With Orange"	 price:	 3.50
 "Cut Russet Potatoes Steam N' Mash"	 price:	 4.25
 "Light Strawberry Blueberry Yogurt"	 price:	 6.50
 "Sparkling Orange Juice & Prickly Pear Beverage"	 price:	 2.99
 "Peach Mango Juice"	 price:	 1.99
 "Chocolate Fudge Layer Cake"	 price:	 18.50
 "Saline Nasal Mist"	 price:	 16.00
 "Fresh Scent Dishwasher Cleaner"	 price:	 4.99
 "Overnight Diapers Size 6"	 price:	 25.50
 "Mint Chocolate Flavored Syrup"	 price:	 4.50
 "Rendered Duck Fat"	 price:	 9.99
 "Pizza for One Suprema Frozen Pizza"	 price:	 12.50
 "Gluten Free Quinoa Three Cheese & Mushroom Blend"	 price:	 3.99
 "Pomegranate Cranberry & Aloe Vera Enrich Drink"	 price:	 4.25
```


The program will ask you to input product #'s. Select product #'s from 1-20. These numbers represent the 20 items above.

Once you finish selecting all the items you like, type:

```
    DONE
```

This will prompt a receipt to be printed along with the final price.

Thank you for shopping at Good Foods Grocery!
