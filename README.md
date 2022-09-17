# Income Prediction

This notebook aims to walk someone through the full Data Science pipeline from exploratory analysis all the way to model predictions. This notebook utilizes the [CIFAR-10](https://pytorch.org/vision/stable/generated/torchvision.datasets.CIFAR10.html#torchvision.datasets.CIFAR10) dataset within the [PyTorch](https://pytorch.org/) package. We go through and explain data transformations/augmentations for artifically increasing the size of our datasets and improving the performance of our model. We utilize PyTorch to create a [Convolutional Neural Network](https://en.wikipedia.org/wiki/Convolutional_neural_network) for image classification. We explain all the way from creating a custom module, to a custom training loop, and finally making predictions with our trained model. At the end, we analyze the models performance and save the model for later use. Further deatils of the actions that were taken and why they were taken is provided by the comments within each of the cells of the notebook. I also tried to make the code as user friendly as possible. If you have any questions feel free to open any issues, I will tend to them as soon as I see them. Thank you!!

## How to install and run the notebook
This project was made using [Pipenv](https://github.com/pypa/pipenv) for keeping track of dependencies. First you must have Pipenv installed:
```
pip install pipenv
```
After having Pipenv installed, you should create a virutalenv for the project. To do this, cd into the directory and run the command:
```
pipenv shell
```
Finally, to install the necessary dependencies run:
```
pipenv install
```
By calling ```pipenv install``` you install all of the necessary dependencies within the Pipfile.lock.

All that is needed to run the notebook now is just run the command below and check oyur browser instance for a new Jupyter Notebook tab:
```
jupyter notebook
```