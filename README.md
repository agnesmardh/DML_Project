# Final project for Group 35 in SSY340 SP1 2020/2021

## Setup

### Environment
To run this code it is advised that you first setup the `dml`-environment as described in the git-repo linked on the course page.

### Data
The code expects the data to be stored in the following structure:
```
/DML_Project
|-- train
|   |-- cats
|   |-- dogs
|-- test
|   |--cats
|   |--dogs
```
Where each subfolder `cats` only contains images of cats and each subfolder `dogs` only contains images of dogs.
We used images from the [cats and dogs dataset](https://www.kaggle.com/c/dogs-vs-cats/data) used for HA1.

## The code
The code in `Project_unconditional.ipynb` is from [PyTorch's DCGAN tutorial](https://pytorch.org/tutorials/beginner/dcgan_faces_tutorial.html) which has been altered to create a cGAN in `Project_conditional.ipynb`.
