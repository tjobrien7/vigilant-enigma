# X-Team 66 FoodFinder1000

See https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#code for tips on using *Markdown* tags to format __.md__ files

## Goal

Work as a team to create a project proposal for your X-team to complete together.
The project does not have to be extremely difficult,
but there must be work to do for each member of your team.
You may reference figures using "See figure 1".  
Be sure to submit corresponding image files, i.e. figure1.png (or figure1.jpg) for each figure.

## Grading: To earn full credit, your team's proposal must include:

* (md) documentation: [this file] describing purpose and use of your program

* Description of a program that has:

  ** a main Java program class in a file named Main.java
  
  ** a custom data structure designed and built by your team
  
  ** comprehensive testing of individual units
  
 Caution: You are not being asked to implement this program, at least not yet. 
 We just want your group to make a proposal or pitch for your program.
 
 Tip: Your custom data structure can be composed of or extensions of data structures that you have learned and used in previous programming assignments.  We're looking for decisions about how to build a high-level data structure that will likely have lower-level components.

## Problem Description

Briefly describe a problem that your team would like to solve.  

When users are hungry for a certain food, they sometimes have trouble locating a source for that food and they starve. Our program will prevent users in Madison from going hungry and make the world a better place.

Describe at a high level a program that could solve that problem.

We are designing a program that will take input (ie the food that a user is hungry for) and output a list of places in Madison where that item may be sourced and the price of the item at that location.

## Questions to answer for Exercise #2

1. Name: Give your project proposal a name (and edit the top line of this file)

FoodFinder 1000


2. Output: Describe the output your program will produce.  Include and example format of the output produced.

List of places that sell the desired food item and price in madison.

Ex:

McDonalds     McDouble       $1.69

McDonalds     Big Mac        $4.99

Badger Pub    Bucky Burger   $2.99

Burger King   Whopper        $3.69

Culver's      ButterBurger   $4.79



3. Input: Describe the data that is needed to solve your problem. Include an example format of the input data.

The input data would be a food item/type the customer wants to find a restauarant and price for in Madison. 

Ex:  
 
burger 

pizza 

The data required to build this program would be a list consisting of places in Madison selling food items along with their prices.
The example includes the data format for "pizza" foodtype.

Ex:

Ian's Pizza   MacnCheese Pizza     $3.00

Papa Johns    Gluten Free Pizza    $10.99

Strada        Pesto Pie Pizza      $8.00

Rocky Rococo  Pepperoni Slice      $3.50

Toppers       Two Topping Pizza    $9.99
 
 
4. User Interface: Describe a user interface for your program.  Use text menus or a simple graphic user interface.

The program will prompt the user to enter the food item that they would like to find. It will return a text menu with a list of resturants, food name, and price.

5. Types List: Break your solution idea down into units that you think can be implemented with a single class.


Name each interface or class and briefly describe its function or purpose.

FoodNode: contains food name, restaurant, and price

FoodTable: hash table holding arraylists hashed by type of food contained in the array

Main: main controller to use/interpret input data and also generate required output for the user

## Edit and Submit this file and any figures referenced by this document.

