# Path estimation using machine learning techniques project

The solution relies on a path prediciton idea, where path consists of an arranged set of datapoints from X0Y0 to XfYf. 

| N (number of vehicles) | X0  | Y0 | W0 (weight of cell, 0 for start) | ...| Xf | Yf |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | 
| ... | ... | ...| ...| ... | ... | ...|

The idea is following: 
We receive start, finish coordinates and then ask api for square that fits these coordinates. Api returns square of some predefined size, along with coordinates of enemy. On model side we prepare data, reducing dimensionality (convolution, etc.) and marking deadly points (applying weight). The idea is illustrated on an image below. The task is in finding optimal path between start and finish points.

Since we defined we want to predict optimal path, the task can be solved with **Path prediction model**. Following solutions suggested:

- Random forest
- Particle filter (Monte-Carlo)
- Reinforcement learning
- Recurrent Neural Network


![image](https://github.com/ucu-intro-to-ds-23-group4/project/assets/50377678/062a2968-ea92-4125-8c97-1e1181017039)

