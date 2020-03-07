# project-optim

Homework for the course [*Optimization theory with applications*](https://www.eurecom.fr/~spyropou/optim2019_files/lectures.htm)

:date: Date: Dec 2019

:school: Master in *Data Science and Engineering* at [*EURECOM*](https://www.eurecom.fr/en)

## Description

#### Homework 1
Convex sets and functions   

Assignment: [here](https://www.eurecom.fr/~spyropou/optim2019_files/hw1.pdf)   
My solution: done on paper

#### Homework 2
Implementation of gradient descent and dual ascent   

Assignment: [here](https://www.eurecom.fr/~spyropou/optim2019_files/hw2.pdf)   
My solution: exercise 1: [`hmw2_1.ipynb`](hmw2_1.ipynb), exercise 2: [`hmw2_2.ipynb`](hmw2_2.ipynb)


## Run the code

To run the code, you need Python 3, Jupyter Notebook (or JupyterLab) and the Python packages listed in [`requirements.txt`](requirements.txt).

### Using virtual environment

Create a virtual environment, install the package dependencies and add a custom kernel to Jupyter:

```
$ python -m venv venv
$ source venv/bin/activate
(venv) $ pip install -r requirements.txt ipykernel
(venv) $ ipython kernel install --user --name=project-optim
(venv) $ deactivate
```
Now you can simply run:
```
$ jupyter-lab
```
and open the two notebook files.

## License

The source code is licensed under the [GNU GPLv3](LICENSE). The content of the report is licensed under the [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)