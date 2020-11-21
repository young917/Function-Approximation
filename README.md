# PROBLEM
To look at the possibility of general function approximation in the neural network, I solved the sine function approximation problem.

Although it is known that any function can be expressed through the neural network by the Universal Function Approximation Theorem, how to determine the hyper-parameter is unknown. Therefore, I tried to find the most accurate neural network by adjusting the width and depth of the neural network layer, and examined the relationship between hyper-parameter and accuracy.

# MODEL
What was difficult about the problem was that a model was needed to predict the y-value for x defined in infinite range. Since data cannot be made to cover the infinite range, solutions had to be found in the model design.

![model outline](./img/model.png =200x)

### LSTM

![architecture](./img/lstm_1.png =200x)
![parameter](./img/lstm_2.png =200x)
