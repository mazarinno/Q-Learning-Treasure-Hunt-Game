# Q-Learning-Treasure-Hunt-Game

Here's a link to a shared Google Colab of the notebook to view it quicker. 

https://colab.research.google.com/drive/1flepQHroSHUMo2Kd0aJ8cHjDdjvkzSxT?usp=sharing

## Explanation
In this project, I created the qtrain() function and was provided with the Python files for the maze representation and state storage. 

The qtrain() function implements a deep-Q learning algorithm to have the agent learn to properly traverse the maze. The agent chooses actions in each state through exploration 10% of the time and exploitation for the other 90%. When choosing actions through exploitation, quality values of each action recorded through previous states determine the outcome. These Q values are based on a reward system which penalizes the agent for hitting walls or wandering to the same cell too many times. The algorithm also counts win rate and stops the learning once a 100% win rate is achieved. 


## Screenshots

![treasurepath](https://user-images.githubusercontent.com/15134446/216874648-d2a64d7c-e855-434c-8a1b-a8d714a40007.PNG)
![winratereached](https://user-images.githubusercontent.com/15134446/216874659-317a8afe-7065-4a65-ad07-27d9241cca37.PNG)
