# Fast Drone Delivery System

This project was done in out Discrete Math class.

To run the program, you must first enter the name of the text file, which is 'entrepot'. Then, you may use the other features.
To find the shortest distance, we implemented Dijkstra's algorithm and calculated the shortest paths. 
You can see all the different areas of the Warehouse in PNG EntrepotGraphe provided in this repo. Each area, or 'node', has 3 types of objects: A, B, C.
The arcs represents the distance (in meters) between the areas. There are three types of Drones, X,Y,Z. Each has different Load Capacity and different flying speeds.
Also, the weight is changes dynamically on loading and unloading items. Which means that our program always selects the best Drone for your order!
It's a very user-friendly program! All computation is done behind the scenes and hidden from the User. 
So try it out!

Requirements to run the program:
    Python version 3.7.3

To run the program on a Terminal:\
    Windows:        $ python main.py
    MacOs or Linux: $ python3 main.py
