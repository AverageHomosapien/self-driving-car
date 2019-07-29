# Self Driving Car

## Brief:
A deep-learning self-driving car.

To Play: Type "python map.py" to call the game

The car will learn over time, and attempt to reach its goal in the TOP LEFT and the BOTTOM RIGHT of the map.

Once the car has reached one goal, the next goal will become active.

### Actions:
Click on the map to draw sand. The car will attempt to avoid the sand to reach its goals.

Click on the save button to save the AI. Then click the load button to re-load a previous AI. This works even after the game is played.

### Requirements:
- PyTorch
- Numpy
- Kivy
- Matplotlib

## Implementation:

The car is written in the PyTorch framework.

It has 2 hidden layers with a ReLU cost function and an output layer with a Sigmoid function.
The action choice is based on a Softmax function.
