# Programming for Data Analysis Project

For this project students must create a dataset by simluating a real-world phenomenon of their choosing. They may pick any phenomeon they wish. Then, rather than collect the data related to the phenomenon, they should model and synthesise such data using Python using the numpy.random package for this purpose.

For this project I decided to create a random dataset based on a real world phenomenon that explains the factors that contribute to a higher level of salary in a company. In this case I used the variables: gender, education level, years of experience and salary to explain the behavior of the salary in relation with all the previous variables.

This repository contains the following:
* **PfDA-project.ipynb**: It contains the entire development of the project, the explanation of all the variables, the generation of the dataset and the study of the behavior of the salary.
* **Salary_Data.csv**: This has been the original database used as a reference for the development of the random database.
* **pairplot.png**: Image of the plots generated during the completion of the project.
* **README.md**: Explanatory document about the content of the repository and how to run the Jupyter notebook with the project.

## Instructions to clone the repository and run the Jupyter Notebook.

### Cloning the repository

This project was carried out with a Mac computer, so below I will explain the steps carried out on this computer to clone the repository:

1. The first step is to have Git installed on your computer.
2. Once we have Git installed, we need to open Terminal through the Applications -> Utilities folder.
3. We should navigate to the directory were we want to clone the repository using the command 'cd'.
4. The next step is to clone the repository using the 'git clone' command followed by the URL of the repository we want to clone, in this case: 
```python
git clone https://github.com/StefaniaVerduga/PfDA-project.git
```
This command will create a new directory with the same name as the repository in our current location and copy the repository files into it.

### Running Jupyter Notebook

Next, I am going to explain how I created and carried out this project in Jupyter Notebook through VSCode.

1. The first step is to install Visual Studio Code and all the needed extensions: Python and Jupyter extensions.
2. Open the folder or workshop where we want to create or open Jupyter Notebooks, in this case the folder where we have our repository. We should create a new Jupyter Notebook by clicking on the "Create a new file" button and saving it with a .ipynb extension.
3. Then, we should select a Kernel and choose the Python interpreter that we want to use for running the notebook.
4. Once all the previous steps are already done, we can run code cells by clicking the "Run Cell" button on the left side of each code cell or by using the keyboard shortcut Shift + Enter.