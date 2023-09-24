# Digital-Pin-Status
The Program reads the Digital PINS of Arduino UNO with Python Tkinter and displays it on a GUI Screen.

# Serial Method
The program utilizes the Serial Method to retrieve data from the Digital PINS of Arduino. These values are then stored in an array called new data. After each utilization, the array is cleared to make way for the next set of data, which is subsequently read from the Arduino and displayed on the GUI screen. This iterative process continues...

# Python Tkinter
The execution begins with Python Tkinter, where the initial display showcases a heading. Subsequently, a row of labels appears below the heading, featuring the DIGITAL PINS as PIN0, PIN1, PIN2, etc. Following this, the program presents "ON" and "OFF" text in the next row, signifying the states of the Arduino Board. In the case of an ON state, the associated PIN transmits an output of "1", which is then stored in a new data array. Ultimately, the GUI screen exhibits "ON" if the array index contains "1" and "OFF" if it has "0".
