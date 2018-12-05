# Udacity_Collaboration
Final Udacity project for deep reinforcement learning project
This learning application uses python and pytorch to solve a learning problem where there are multiple agents tying to keep a tenis ball up over mutlple interactions.
There are two tennis nets that can move left or right to hit the ball. Each agent has a 24 length vector to represent the state.
The tennis rakets get 0.1 point for time the ball is hit and loses -0.1 for time the ball hits the ground. The action space is considered solved if it averages a maxium score of 0.5 over an episode. 
This uses the unity Ml agents to for interactions with the action space.

# Getting Started 
Download the files and run ```pip requirements.txt``` to install the dependencies. In addition the Unity ml agents will need to be installed.

# Instructions 
The code to run the deep nueral net is found in the report.ipython code and can be modified there.
