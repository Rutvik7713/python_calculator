
## A GUI based Calculcator made In Python
_____________________________________________________

This assignemt was completed using various basic GUI features of Python. This model is perfect for understanding how the basic GUI features work in Python.

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

* import Ot, QMainWindow, QLineEdit, QGridLayout, QPushButton, QVBoxLayout and Qwidget into view.py from PyQt5.QtWidgets.
* Now, construct class GUI which calls constructor of QMainWindow.
* Using different widget and layout functions, define the calculator's look and layout as needed.
* Create a display bar at top for showing the entered digits in a calculator.
* Now using tuples, define position of each and every button in the calculator layout.
* Construct the grid layout of buttons perfectly.

### 3. main.py
* In this file we are going to import controller from controller.py file, model from evaluateExpression.
* first defining the main function.
* create the instance of Qapplication and then call it in function.
* show GUI using GUI() and Show() functions.






