# Buffer 2.0
### `Objective`

This is a react app which visualizes the various pathfinding algorithms and finds the shortest path between source and destination. It also shows execution time for each algorithm.
________________

### `Features`

- Dijkstra's , Depth first path, Breadth first path, A* are implemented using    javascript.
- Execution time of each algorithm is calculated.
- Source and destination are flexible and their positions can be changed.
- Obstacles can be created between source and destination.
- Clear walls and clear grids are also available as per our requirement.
________________

### `Algorithms implemented`

1. Dijkstra’s Algorithm
2. Depth First Search Algorithm
3. A* Algorithm
4. Breadth First Search Algorithm
________________
### `DataStructure Used`

Graph<br>
As this would be easy to visualize paths as graphs are meant to get shortest paths.</br>
________________

### `Team Members`

1. Pooja Dendage(TY IT, CCEW)<br>
She has implemented Dijkstra's algorithm.</br>

2. Seema Dhamgunde(TY IT, CCEW)<br>
She has implemented DFS.</br>

3. Yogita Bacchewar(TY IT, CCEW)<br>
She has implemented A*.</br>

4. Rutuja Chandegave(TY IT, CCEW)<br>
She has implemented BFS.</br>

Everyone has contributed to the frontend and syncing of algorithms in the react app.
________________

### `File Structure`

1. aStar.js, bfs.js, dfs.js, dijksra.js<br>
These files contains javascript code for respective algorithms</br>

2. Node.css<br>
This file contains the styling of the nodes and animation for searching and final paths.</br>

3. Node.jsx<br>
This contains mouse controls for the nodes.</br>

4. PathfindingVisualizer.css<br>
This includes styling of the grid, buttons and navigation bars.</br>

5. PathfindingVisualizer.jsx<br>
This is the main file which links all the algorithms, styling and mouse controls and provides us the final output.</br>
________________

### `Installation `

npm start<br>
Runs the app in the development mode.
Open http://localhost:3000 to view it in the browser.
The page will reload if you make edits.
You will also see any lint errors in the console.</br>

npm test<br>
Launches the test runner in the interactive watch mode.
See the section about running tests for more information.</br>

npm run build<br>
Builds the app for production to the build folder.
It correctly bundles React in production mode and optimizes the build for the best performance.
The build is minified and the filenames include the hashes.</br><br>
Your app is ready to be deployed!</br>
________________

### `Working`

We have a 25X35 grid with two nodes representing red as source and green as destination which are flexible to be moved. 

![WhatsApp Image 2021-06-05 at 6 10 06 PM (1)](https://user-images.githubusercontent.com/81221113/120913946-61ade300-c6b8-11eb-8cb4-76526c002900.jpeg)

By clicking and dragging the nodes we can create walls i.e. the obstacles are shown in purple colours.
  
![WhatsApp Image 2021-06-05 at 6 10 06 PM](https://user-images.githubusercontent.com/81221113/120913965-7ab69400-c6b8-11eb-9737-c4f04671131a.jpeg)

According to the algorithms four respective buttons are provided and we can click any of them to visualize the path.
Then the searching of nodes is shown in skyblue color in the grid.
Once the final path is detected it is shown in dark blue color.
Execution time for the chosen algorithm is shown.
  
![WhatsApp Image 2021-06-05 at 6 10 07 PM](https://user-images.githubusercontent.com/81221113/120913980-90c45480-c6b8-11eb-80b4-21d5feba852a.jpeg)
________________

### `Learnings`

We tried to work on a new technology that is React.js. Along with that we learned to implement animation using javascript.
________________

### `Next for the Project`

- We can implement many more pathfinding algorithms.
- Further on this project we'll try to adjust the grid according to device we are opening the project on i.e. the mobile view and desktop view.
- Also we can turn this into a game as well by adding bombs in the nodes.
________________

