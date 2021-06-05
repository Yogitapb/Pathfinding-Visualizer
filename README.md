# BUFFER 2.0
    
### `Objective`
 
This is a react app which visualizes the various pathfinding algorithms and finds the shortest path between source and destination. It also shows execution time for each algorithm.
____

### `Features`

1. Dijkstra's , Depth first path, Breadth first path, A* are implemented using    javascript.
2. Execution time of each algorithm is calculated.
3. Source and destination are flexible and their positions can be changed.
4. Obstacles can be created between source and destination.
5. Clear walls and clear grids are also available as per our requirement.
____

### `Algorithms Implemented`

1. Dijkstra’s Algorithm
2. Depth First Search Algorithm
3. A* Algorithm
4. Breadth First Search Algorithm
____

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
____

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
____

### `Installation` 

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
The build is minified and the filenames include the hashes.
Your app is ready to be deployed!</br>
____

### `Working`

We have a 25X35 grid with two nodes representing red as source and green as destination which are flexible to be moved. 

![WhatsApp Image 2021-06-05 at 6 10 06 PM (1)](https://user-images.githubusercontent.com/81221113/120892347-7a23ec00-c62b-11eb-88c4-1ffb838020a0.jpeg)

By clicking and dragging the nodes we can create walls i.e. the obstacles are shown in purple colours.

![WhatsApp 2021-06-05 at 6 10 06 PM](https://user-images.githubusercontent.com/81221113/120892222-d89c9a80-c62a-11eb-8d79-fbe9d3720c92.jpeg)

According to the algorithms four respective buttons are provided and we can click any of them to visualize the path.
Then the searching of nodes is shown in skyblue color in the grid.
Once the final path is detected it is shown in dark blue color.
Execution time for the chosen algorithm is shown.

![WhatsApp Image 2021-06-05 at 6 10 07 PM](https://user-images.githubusercontent.com/81221113/120892312-4c3ea780-c62b-11eb-90be-9099d322f29a.jpeg)

____

The link for the video is in this repository only along with the code files.
Name of the video is pathfindingvisualizer.mp4.






