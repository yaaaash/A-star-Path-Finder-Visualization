# A-star-Path-Finder-Visualization

**Overview**

This project demonstrates my implementation of the A* algorithm in Python, which is widely used for efficient pathfinding in grid-based environments. With the help of pygame graphics, I have created a visually interactive application that allows users to define a start and end point and visually observe the algorithm finding the shortest path.

![5](https://github.com/yaaaash/A-star-Path-Finder-Visualization/assets/87315730/f6871cc0-4824-4c9c-a07d-121f5ebb795e)


The A* algorithm is a widely used pathfinding algorithm that finds the shortest path between two points on a graph. It is especially useful in grid-based environments, such as maps or mazes.

**Features:**
- Graphical visualization: The program provides a graphical user interface to visualize the pathfinding process in real time.
- User interaction: Users can set the start and end points on the grid and add barriers or obstacles that the algorithm must navigate around.
- Heuristic function: The A* algorithm uses a heuristic function to estimate the distance between two points, allowing it to prioritize paths that are more likely to be shorter.
- Optimized search: The algorithm intelligently explores the graph, considering both the actual cost to reach a specific point and the estimated cost to reach the goal, leading to more efficient pathfinding.

This project serves as a practical demonstration of the A* algorithm and its applications in solving pathfinding problems.

**Demonstration:**

1. Initially, the grid is displayed in its default state when the script is executed.
   
![0](https://github.com/yaaaash/A-star-Path-Finder-Visualization/assets/87315730/46242e36-7a62-4fef-a848-67bd8b71b285)


2. The user can interactively select a starting and ending point on the grid using their mouse.
   
![1](https://github.com/yaaaash/A-star-Path-Finder-Visualization/assets/87315730/ed1419ef-85b8-439c-a818-1d9e738f0f6d)

3. Upon initiating the pathfinding process by pressing the space bar, the script visually demonstrates the step-by-step pathfinding from the chosen start point to the end point.
   
![2](https://github.com/yaaaash/A-star-Path-Finder-Visualization/assets/87315730/1601689e-1320-4255-8551-e19c13ac1e78)

4. In addition, it calculates and displays the total distance between the selected starting and ending points.
   
![3](https://github.com/yaaaash/A-star-Path-Finder-Visualization/assets/87315730/c19a64c2-8c78-403a-94f1-74b29c8893af)

   
5. Additionally, the user has the ability to obstruct the path by placing obstacles on the grid using their mouse.
    
![4](https://github.com/yaaaash/A-star-Path-Finder-Visualization/assets/87315730/9d5e3f16-8d9b-480d-84a0-77026ad2f7b7)


6. To reset the grid and remove all markings, the user can simply press the 'c' key on their keyboard.

**Real-Life Applications:**

1. Efficient Path Finding: This project showcases a robust implementation of path finding algorithms, enabling users to find optimal routes between locations in diverse scenarios, from GPS navigation to robotics and game development.
   
2. Real-World Applications: Explore the practical applications of path finding in fields like logistics, urban planning, network routing, and more, demonstrating the versatility and significance of this code in solving complex spatial problems.
