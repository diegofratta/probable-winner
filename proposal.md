# X-Team 58 Project Proposal: College Library People Sorter

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

College Library is one of the most popular libraries on campus, and at busy times it is very hard to find a seat. 
A College Library People Sorter can sort through open seats in the library and place groups and people throughout the library to maximize the filling of the library.

## Questions to answer for Exercise #2

1. Name: Give your project proposal a name (and edit the top line of this file)

College Library People Sorter


2. Output: Describe the output your program will produce.  Include and example format of the output produced.

The program will output a list of available tables and tables that with wait lines.

Example output format:

Table1 is open with 4 spots

Table2 is open with 1 spot

WindowSeat1 has 4 people in line.

3. Input: Describe the data that is needed to solve your problem. Include an example format of the input data.

The administrator will input the amount of tables  and seats available at those tables. Then the students will input where they would like to sit and if they are apart of a group.

4. User Interface: Describe a user interface for your program.  Use text menus or a simple graphic user interface.

We will use graphic user interface that display the layout of each floor in College Library (including details about tables near windows and and size of of table). For example, use circle and squares to represent the desks and seats that already get occupied. And people can pick out the blank spots where there are seats available. 

5. Types List: Break your solution idea down into units that you think can be implemented with a single class.

Group class: Will contain general user information, such as group size, table preferences, willingness to share a table. Table preferences will be options for a windowseat, outlet availability, and location preferences.

Floorplan class: Will contain the number of tables and seats in the library, as well as the number of window seats and outlet seats.

Test class: Will contain tests that test the general functionality of the solution to our problem.

Queue class: Will contain the data structure to decide where groups are placed in the library, as well as wait times for specialty seats.



Name each interface or class and briefly describe its function or purpose.


## Edit and Submit this file and any figures referenced by this document.

