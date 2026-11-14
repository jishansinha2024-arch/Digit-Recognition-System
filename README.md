Project One Handwritten Digit Recognition

This project uses a small neural network to recognize handwritten digits
It prepares the images trains the model and checks its predictions against
known labels



The program first checks the standard Kaggle data location
If the data is not there it looks for the training data file in the project
folder

How the project is organized

- Code brings the steps together and starts training
- Data reads and prepares the digit images
- Model contains the neural network calculations
- train.csv contains the dataset on which the model is trained.
- Training updates the network as it learns
- Visualization displays example images and predictions

The program prints its learning progress and validation accuracy
It also displays a few example predictions
