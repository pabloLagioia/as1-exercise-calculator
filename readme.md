Introduction
============
In this document you will find the information required to develop a very small web app with some business logic that we use at AutoServe1.
Please review the document and ask all questions you may have.
The app is not difficult to develop but it may take some time. You may have to investigate some libraries to get it working.
Please note that you will have 1 week to finish it but we can provide you with additional time in case you feel it's not enough.   

Summary
=======
Create an HTML5 calculator and call a REST API to perform the calculation

What needs to be done
=====================

UI
--
*Designs are provided*

Create an HTML document and include a calculator that looks as similar as possible as the image called calculator-design.png.

* Clicking on the numbers will populate the display of the calculator
* Clicking on the operations will add them to the display of the calculator
* Del will set the display to 0
* Equal will make a request to the server to do the math and then display the result in the calculator
* Pressing the up key will fill in the display with the previous calculation in the history and so on
* Pressing the down will fill in the display with the next calculation in the history and so on

REST API
--------

The API should at least accomplish the following:
  * perform an operation given a string like (5 + 3) / 4
  * get a list of the operations performed (history)
  * add an operation to the history
  * remove an operation from the history

Notes
=====
  * NodeJS is mandatory
  * Please use Express, Restify or HapiJS to build the REST API
  * There is no need to use a database. You can do it if you want but you could also use an in-memory array or a file for the sake of this exercise
  * Try to use descriptive HTTP response codes to inform the user about the result of the operations
  * You could use SASS for styling the app
  * You could use RiotJS to code the UI
  * Try not to use jQuery to modify the DOM. You can use it freely to make ajax calls
  * Feel free to use flux, redux or RiotControl
  * If you choose to use a build system please choose between gulp or webpack
  * Questions are always welcome

What will be evaluated
======================
  * Readability and robustness of the code
  * The level of completion