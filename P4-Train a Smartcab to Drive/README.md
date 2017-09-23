## Project: Train a Smartcab How to Drive
Reinforcement learning project : Q-learning 


### Code

This project contains three directories:

- `/logs/`: This folder will contain all log files that are given from the simulation when specific prerequisites are met.
- `/images/`: This folder contains various images of cars to be used in the graphical user interface. 
- `/smartcab/`: This folder contains the Python scripts that create the environment, graphical user interface, the simulation, and the agents. 

It also contains two files:
- `smartcab.ipynb`: This is the main file of my coding work.
-`visuals.py`: This Python script provides supplementary visualizations for the analysis.

Finally, in `/smartcab/` are the following four files:
- **Modify:**
  - `agent.py`: This is the main Python file 
- **Do not modify:**
  - `environment.py`: This Python file will create the *smartcab* environment.
  - `planner.py`: This Python file creates a high-level planner for the agent to follow towards a set goal.
  - `simulation.py`: This Python file creates the simulation and graphical user interface. 
  
### Run

In a terminal or command window, navigate to the top-level project directory `smartcab/`  and run one of the following commands:

```python smartcab/agent.py```  
```python -m smartcab.agent```


### Requirement

This project requires **Python 2.7** with the [pygame](https://www.pygame.org/wiki/GettingStarted
) library installed