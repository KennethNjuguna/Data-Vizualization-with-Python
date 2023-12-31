# Data-Vizualization-with-Python
Offered by IBM this is DV0101EN.
This is one of the courses offered by IBM in my journey to a Data Scientist.

# Introduction to Matplotlib
There are three different layers in the architecture of the matplotlib which are the following:
1. Backend Layer
2. Artist layer
3. Scripting layer

# <h3>Backend layer</h3>

The backend layer is the bottom layer of the figure, which consists of the implementation of the various functions that are necessary for plotting. There are three essential classes from the backend layer FigureCanvas(The surface on which the figure will be drawn), Renderer(The class that takes care of the drawing on the surface), and Event(It handle the mouse and keyboard events).

# <h3>Artist Layer</h3>

The artist layer is the second layer in the architecture. It is responsible for the various plotting functions, like axis, which coordinates on how to use the renderer on the figure canvas.

# <h3>Scripting layer</h3>

The scripting layer is the topmost layer on which most of our code will run. The methods in the scripting layer, almost automatically take care of the other layers, and all we need to care about is the current state (figure & subplot).

![image](https://github.com/KennethNjuguna/Data-Vizualization-with-Python/assets/97665556/503c2632-2be1-4679-be17-ffcfac43f770)

