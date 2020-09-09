# introduction
In this project I wanted to train a navigator agent in a simulation environment that can gather blue cubes and can get away from colliding with red cubes.
I have used Deep Q-network algorithm to train my agent.
each episode consists of 500-time steps that takes about 10 seconds to run. each blue cube gives +5 points and each red cube gives -5 points. falling from the square surface ends the episode, takes away all of positive scores that had been gathered during this episode and also gives -10 points to the agent. there are 6 red and 6 blue cubes on the surface of our simulation at each time step. The agent gets -0.015 points at each time step so that it can learn to move faster in the environment.

![alt text](https://github.com/AlirezaTalakoobi/DQN-navigator-agent/blob/master/readme%20pictures/1.PNG?raw=true)

this project consists of 4 different files:
1. Simulation
2. Neural Network code
3. DQN code
4. main code

*important: you can find project description in presentation.pptx*

 the agent that I have trained is version 4.1.6 in the "presentation" file that can gather about 50 points in each episode which is equal to gathering about 11.5 blue cubes in each episode and you can see that it is a fantastic result.
 
 ![alt text](https://github.com/AlirezaTalakoobi/DQN-navigator-agent/blob/master/readme%20pictures/learning%20process.PNG?raw=true)
 ![alt text](https://github.com/AlirezaTalakoobi/DQN-navigator-agent/blob/master/readme%20pictures/map.PNG?raw=true)
