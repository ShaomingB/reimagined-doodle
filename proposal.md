# X-Team InventoryTracker Project Proposal

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
The problem we are solving is inventory managment for a medium sized store. Using our program employees can view how much inventory is in stock and search for items.

Describe at a high level a program that could solve that problem.
To solve this problem 

## Questions to answer for Exercise #2

1. Name: Give your project proposal a name (and edit the top line of this file)
InventoryTracker



2. Output: Describe the output your program will produce.  Include and example format of the output produced.

Output would include how much of the item the store has on hand.

The output would be a list of information for the item based of the serial number. Outputs would include name, description of item, amount in storage, amount in front of store, price per item, and brand of item.

3. Input: Describe the data that is needed to solve your problem. Include an example format of the input data.
Input would require the serial number of the item.


4. User Interface: Describe a user interface for your program.  Use text menus or a simple graphic user interface.

There would include a login menu, then separate menus for managers and employees. Managers would be able to search and update items, employees would be able to just search items.



5. Types List: Break your solution idea down into units that you think can be implemented with a single class.

ItemNode: Will include serial number as key and other values such as inventory, price, and source company.
InventoryDB: Will implement a hash table that looks up items based on serial numbers.

Name each interface or class and briefly describe its function or purpose.


## Edit and Submit this file and any figures referenced by this document.

