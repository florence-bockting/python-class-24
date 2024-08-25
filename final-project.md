# Final project

## General ideal & Content

The goal of the project work is to use your learned programming skills for solving a "small-scale" problem. Furthermore, you should be able to organise your code in a Python package, which can be installed locally. Finally, the solution to your problem should be described in a Jupyternotebook in which you import your package and write a tutorial about it.
-   The specific function that the Python package will fulfill is left to each group (for example, the package could implement and visualize an algorithm, or it could involve post-processing, analysis, and visualization of a specific dataset).
-   It is not necessary for the package to generalize across multiple datasets or algorithms. It is sufficient if the functions work for a specific dataset/ algorithm.

## Organisation of the project work:
+ project is done in groups of 1-3 people (please indicate the groups also in Moodle)
+ you pick a topic that is of your interest (e.g., implementing an algorithm, analyzing and visualizing a data set, etc.)
+ submission deadline of the project is September 30, 2024
+ project can be written in German or English
  
**Some ideas about possible projects:**
+ you can analyse a data set as part of your project incl. data wrangling, data cleaning, data analysis, data visualization, …
+ data sets can be found in [Kaggle](https://www.kaggle.com/), furthermore some python libraries come already with data sets (e.g., [scikit-learn](https://scikit-learn.org/stable/datasets.html), [seaborn](https://github.com/mwaskom/seaborn-data))
+ if you like problems apart from data analysis the website [Project Euler](https://projecteuler.net/archives) has a whole archive with small problems.
+ another possibility is the selection of a particular algorithm in which you are interested in and implementing it, together with some visualizations (e.g., [EM-algorithm](https://github.com/Ransaka/GMM-from-scratch), Mixture Models, etc.)

The project should include the following aspects:

|\# | Content                                                                                                      | Comment                                                                                                                                      |
|--|------------------------------|------------------------------------------|
|1| Create a `Git repository` hosted on `GitHub`.                                                                | I will fork your GitHub repo and use the forked repo for grading.                                                                            |
|2| Create a `Readme.md`                                                                                           | Create a readme for your repo including information about at least: (1) Introduction/Description of repo (2) Installation of your package (3) Usage of your package with 1-2 example functions (4) License  |                                                                                                                                            |                                                                  |
|3| Installing your own `Python package` (which should consist of at least 2 classes with at least two functions). | At this point, I rely on common sense, expecting more than just basic functions (e.g., addition and subtraction). Utilize various: |
||                                                                                                              | \- Python packages introduced in the seminar (such as numpy, pandas, matplotlib, seaborn, math, etc.).                                       |
||                                                                                                              | \- Control flows (for, while, if, comprehensions).                                                                                           |
||                                                                                                              | \- Data types/structures (lists, dictionaries, vectors, strings, etc.).                                                                      |
||                                                                                                              | \- Define 2-3 classes with several functions | 
||                                                                                                              | \- At least one function should visualize your data (e.g., using pyplot, seaborn)
|4| `Docstring` for your functions, classes                                                                     | at least description of the goal of each function                      |
|5| `Comments` in your Code                                                                                     | each "concept" (equivalent to one or more lines of code) should be accompanied by a comment                                                  |
|6| Create a `tutorial` with Jupyter Notebook                                                                   | describe your package in detail and showcase each function. Your tutorial should incl. at least:                         |
||                                                                                                              | \- Markdown blocks in which you explain the problem and each function in words                         |
||                                                                                                              | \- Code blocks in which you import your package and call its functions                                                                 |

## Example folder structure of final project

**Note:**
I only include the minimal folder structure here. You may have additional folder/files. Furthermore, some files/folders will be automatically generated through various installations (e.g., when creating a git repo the (hidden) folder .git will be created)

```{raw}
root_directory  
├── .gitignore             # Defines which files/folders should (not) be pushed to GitHub (optional)
├── name_of_your_package   # Your Python package directory   
│  ├── __init__.py         # Indicates that this directory should be treated as a Python package
│  ├── module1.py          # Your Python class 1 with multiple functions (incl. docstring + comments)
│  └── module2.py          # Your Python class 2 with multiple functions (incl. docstring + comments)
├── LICENSE.txt            # Select a licence 
├── pyproject.toml         # Specify version of the build tool you need to correctly build your pip package in your virtual environment
├── README.md              # Create a ReadME including information about your project and at least: Installation, license, and usage
└── TUTORIAL.md            # Create a Tutorial in which your describe and showcase/call your package and each function 			 

```

## Grading

+ Please refrain from copying entire code blocks from online resources, as I will be checking for original work.
+ If your project incorporates all the aspects mentioned above, and they function without error messages, you will receive a grade of 1.0, which is the highest grade in the German grading system.
+ I will deduct points if for example: essential content is missing or not functional (e.g., absence of license, Readme, Jupyter notebook, etc.), errors when importing your own package in the Jupyter notebook, if the GitHub page fails to build, etc. (note: errors are not the same as warnings. Warnings won't affect grading.)
+ the overall project is considered as failed when no GitHub repository is provided. 

## How to hand-in the project?

+ The submission deadline of the project is *September 30, 2024*
+ Send me the link to your GitHub repo via slack or mail
+ if you don't want to make your repo public, you can invite me as collaborator in GitHub
+ if you make your repo public, you can simply send me the link to your GitHub repo via slack/mail and I will fork your repo
+ Grading will be based on the version of your project after the submission deadline
+ Please let me know if you need a grade before the submission deadline 

