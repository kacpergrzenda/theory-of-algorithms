# Theory Of Algorithms

## Table of contents
* [About The Project](#about-the-project)
* [Technologies and Featrues Used](#technologies-and-features-used)
* [How to use the Project](#how-to-use-the-project)
* [Acknowledgements](#acknowledgements)


## About the Project
This project showcases the theory of algorithms, especially the areas of computation and computability.  Jupyter Labs is used to display the Post Correspondence problem (```post_correspondence_problem.ipynb```) and Countdown Numbers Game (```countdown.ipynb```). 

The complexity of the Countdown Number game solution is analysed and discussed, while following a functional programming style treating computation as the evaluation of mathematical functions (treating functions like variables and using them for processing. Receive Input, process input, return output) and avoiding using states. 

In the ```post_correspondence_problem.ipynb``` notebook the Post Correspondence Problem is explained and viewed as a decision problem using the Turing Machine as an example. And the explanation of why the PCP is an undecidable problem. A solvable variation of the PCP, the Bounded Post Correspondence Problem is solved and broken-down in the notebook. 

## Technologies and Features Used
* Python (programming language)
* Jupyter Lab (Jupyter notebooks)
* Itertools Libriary (itertools Product and permutation)
* Reverse Polish notation (Solve calculation in coundown.ipynb)

## How to use the Project
The two jupyter lab notebooks can be viewed by clicking on them or by can be viewed on nbviewer by clicking on the badges associated to each notebook:
<br>
[![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.org/github/kacpergrzenda/theory-of-algorithms/blob/main/countdown.ipynb) ```countdown.ipynb```
<br>
[![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.org/github/kacpergrzenda/theory-of-algorithms/blob/main/post_correspondence_problem.ipynb) ```post_correspondence_problem.ipynb```
<br>

To Edit and View the notebook use Google Volab, the two notebooks can be accessed throught the two links below:
https://colab.research.google.com/github/kacpergrzenda/theory-of-algorithms/blob/main/countdown.ipynb
<br>
https://colab.research.google.com/github/kacpergrzenda/theory-of-algorithms/blob/main/post_correspondence_problem.ipynb
<br>
You can also view and edit the files by cloning the repository to your desktop like so:

1. Open a directory on your machine and in the command line of this directory Git Clone this GitHub repository.
    ```bash
    $ git clone <repo>  (e.g. https://github.com/kacpergrzenda/theory-of-algorithms)
    ```

2. The first jupyter notebook is under "post_correspondence_problem.ipynbn", this contains the PCP part of the project. In this notebook you can change the List values for the Bounded Post Correspondence problem seeing which finite sequence of integers will return a true or false value.

3. The second jupyter notebook is "countdown.ipynb", this contains the countdown number game and explanation of functional programming. The game can be see working by running the ```countdown.ipynb``` notebook. The "solveCountdownNumbersGame()" function takes in the target number and game numbers as attributes and uses the game numbers to create an equation to get the target number. In the notebook you can un-comment print statements in some of the functions to see the different outputs that are printed during the process of solving the game.

## Acknowledgements

* Numbers Game https://wiki.apterous.org/Numbers_game
* Python Functional Programming https://docs.python.org/3/howto/functional.html
* Ian McLoughlin https://learnonline.gmit.ie/course/view.php?id=5197#section-6
* Undecidable Problems https://www.khanacademy.org/computing/ap-computer-science-principles/algorithms-101/solving-hard-problems/a/undecidable-problems
