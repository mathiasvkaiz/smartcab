# smartcab

## Machine Learning Engineer Nanodegree - Project 4
In this project you will apply reinforcement learning techniques for a self-driving agent in a simplified world to aid it in effectively reaching its destinations in the allotted time. You will first investigate the environment the agent operates in by constructing a very basic driving implementation. Once your agent is successful at operating within the environment, you will then identify each possible state the agent can be in when considering such things as traffic lights and oncoming traffic at each intersection. With states identified, you will then implement a Q-Learning algorithm for the self-driving agent to guide the agent towards its destination within the allotted time. Finally, you will improve upon the Q-Learning algorithm to find the best configuration of learning and exploration factors to ensure the self-driving agent is reaching its destinations with consistently positive results.

### Install
This project uses the following software and Python libraries:

- Python 2.7
- NumPy
- pandas
- matplotlib
- pygame

You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html).

#### Fixing Common PyGame Problems
The PyGame library can in some cases require a bit of troubleshooting to work correctly for this project. While the PyGame aspect of the project is not required for a successful submission (you can complete the project without a visual simulation, although it is more difficult), it is very helpful to have it working! If you encounter an issue with PyGame, first see these helpful links below that are developed by communities of users working with the library:

- [Getting Started](https://www.pygame.org/wiki/GettingStarted)
- [PyGame Information](http://www.pygame.org/wiki/info)
- [Google Group](https://groups.google.com/forum/#!forum/pygame-mirror-on-google-groups)
- [PyGame subreddit](https://www.reddit.com/r/pygame/)

### Code
This project contains three directories:

- /logs/:  
This folder will contain all log files that are given from the simulation when specific prerequisites are met.
- /images/:  
This folder contains various images of cars to be used in the graphical user interface. You will not need to modify or create any files in this directory.
- /smartcab/:  
This folder contains the Python scripts that create the environment, graphical user interface, the simulation, and the agents. You will not need to modify or create any files in this directory except for agent.py.

It also contains two files:
- smartcab.ipynb:  
This is the main file where you will answer questions and provide an analysis for your work. 
- visuals.py:  
This Python script provides supplementary visualizations for the analysis. Do not modify.

  
### Run
In the Terminal or Command Prompt, navigate to the folder containing the project files, and then use the command:  
```jupyter notebook smartcab.ipynb```
```python smartcab/agent.py
