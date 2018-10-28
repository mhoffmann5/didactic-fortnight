# X-Team NN Project Proposal

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

In restaraunts online orders are typically filled before in person order. We would like to create a program that determines which order to prepare next. Our program will use two data structures to store the information. A priority queue will contain the order number, with the next order at the top. A hashtable will contain the information about the order.


## Questions to answer for Exercise #2

1. Name: Give your project proposal a name (and edit the top line of this file)

Restaraunt order queue

2. Output: Describe the output your program will produce.  Include an example format of the output produced.

The next order to prepare for the cooks. Output will contain the next couple orders to prepare. When the current order is filled the list will shift accordingly.

Order Number -- Order -- Delivery/Online Order or In Restaraunt  -- Outstanding Time on Order (On screen infront of cook)
 
1             Cheeseburger     Online Order                       1:00
2             Shake            Online Order                       1:30
3             Chicken Sandwich  In Restaraunt                     0:30

3. Input: Describe the data that is needed to solve your problem. Include an example format of the input data.

Order type(online or in restaraunt) -- Order Contents -- Order Number


4. User Interface: Describe a user interface for your program.  Use text menus or a simple graphic user interface.

The gui will display the next five order for the staff that is dynamically changing. There will also be options for specific order lookup, manually be able to search, delete or add an order. 


5. Types List: Break your solution idea down into units that you think can be implemented with a single class.
The individual methods that our program will contain-

Print Queue(See all orders currently active)
Add Order
Delete Order
Search Order 


Name each interface or class and briefly describe its function or purpose.

The class we create will prioritize incoming orders based on if they are in person or if they are online orders. This class will show the staff which order to prepare next. We will use a priority queue for managing orders and a hash table for fast lookup. 

## Edit and Submit this file and any figures referenced by this document.

