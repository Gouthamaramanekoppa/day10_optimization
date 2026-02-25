# day10_optimization
Optimized the model by increasing layers and adding dropout to improve accuracy and reduce overfitting.

The focus was on improving the performance of the neural network by refining its architecture and applying optimization techniques. After analyzing the training and validation results from previous days, it was observed that while training accuracy was high, validation accuracy showed signs of fluctuation. This indicated the possibility of overfitting, where the model performs well on training data but does not generalize effectively to unseen data.

To address this, the model architecture was enhanced by increasing the number of neurons and adding an additional hidden layer. Increasing layers and neurons improves the model’s capacity to learn complex patterns from data. However, higher model complexity can also increase the risk of overfitting.

To reduce overfitting, a Dropout layer was introduced. Dropout works by randomly disabling a percentage of neurons during each training step. This forces the model to learn more robust and generalized features instead of relying too heavily on specific neurons. As a result, the model becomes more stable and performs better on validation and test data.

Hyperparameters such as the number of epochs and learning rate were also adjusted to observe their impact on accuracy and loss. These refinements helped achieve improved validation accuracy and more consistent performance.

By the end of Day 10, the model demonstrated better generalization ability, reduced overfitting behavior, and improved overall accuracy. This phase provided practical understanding of how architectural modifications and regularization techniques enhance deep learning model performance.
