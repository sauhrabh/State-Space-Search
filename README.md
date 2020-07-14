# State Space Search

Project 1 for CPSC 481 summer 2020.

# Setup

+ Use python from a dedicated repository like `brew` or `apt`. Python 3 in macOS doesn't work with `tkinter` library.

    `brew install python`

+ Verify python3 installation:

    `which python3`     # should return path like /usr/local/bin/python3

+ Install project:

    `cd /path/to/directory`

    `git init`

    `git remote add origin https://github.com/saura8h/State-Space-Search.git`

    `git pull origin master`


+ Python virtual environment:

    `python3 -m venv sss`

    `source sss/bin/activate`


+ Run project:

    `python pacman.py`


# Test functions

+ Test search agent:

    `python pacman.py -l tinyMaze -p SearchAgent -a fn=tinyMazeSearch`


+ Depth First Search:

    `python pacman.py -l tinyMaze -p SearchAgent -a fn=dfs`

    `python pacman.py -l mediumMaze -p SearchAgent -a fn=dfs`

    `python pacman.py -l bigMaze -p SearchAgent -a fn=dfs`


+ Breadth First Search:

    `python pacman.py -l tinyMaze -p SearchAgent -a fn=bfs`

    `python pacman.py -l mediumMaze -p SearchAgent -a fn=bfs`

    `python pacman.py -l bigMaze -p SearchAgent -a fn=bfs`


+ Uniform Cost Search:

    `python pacman.py -l mediumMaze -p SearchAgent -a fn=ucs`

    `python pacman.py -l mediumDottedMaze -p StayEastSearchAgent` 
    
    `python pacman.py -l mediumScaryMaze -p StayWestSearchAgent`


# Team

| Members                | Email                     | CWID            |
| ---------------------- |:-------------------------:| ---------------:|
| Loai AlFarran          | loayei@gmail.com          |                 |
| Jacqueline I. Cardenas | jacisac@csu.fullerton.edu | 889397782       |
| Saurabh Mishra         | saurab.mish@gmail.com     | 887579779       |
| Wayne Lin              | waylin@csu.fullerton.edu  | 887280121       |
