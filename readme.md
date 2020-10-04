
## A GUI based Calculcator made In Python
_____________________________________________________

This is an assignment work given by professor, the task is to create calculator in Python langauge Using different GUI features, this is a basic model to understand GUI application in python.

For Creating this calculator we have to create 5 different python files which are following:<br>
1. test.py <br>
2. view.py <br>
3. main.py <br>
4. model.py <br>
5. controller.py <br>

### 1. test.py:

* Import sys packages, QApplication, Qlabels and Qwidgit into test.py from pyQt5.
* Now create an application using QApplication()
* Give dimensions of the window of output screen by using Qwidget()
* Now you can check output window by printing some message and then end the window using show().

### 2. view.py:

* Import following :Ot, QMainWindow, QLineEdit, QGridLayout, QPushButton, QVBoxLayout and Qwidget
* Construct class GUI which calls constructor of QMainWindow.
* Using different widget and layout functions, define the calculator's look and layout as needed.
* Create a display bar at top for showing the entered digits in a calculator.
* Construct the grid layout of buttons perfectly.

### 3. main.py:
* In this file we are going to import controller from controller.py file, model from evaluateExpression.
* first defining the main function.
* create the instance of Qapplication and then call it in function.
* show GUI using GUI() and Show() functions.

### 4. model.py:
* In this file we are creating model to handle the calculator's operation.
* Now create the evaluateExpression function in this file.
* Add the exception handling concept and test it by passing any expression.

### 5. controller.py:
* First we have to create a class named controller.
* Create a constructor which call model and view parameters in it.
* Create calculateResult function to evaluating result of expression.
* Create buildExpression function to validating and building the expression.
* Create connectSignals function to connect the expression through the buttons.






