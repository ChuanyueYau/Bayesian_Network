# Artificial Intelligence
## Baysian Network

Write a python code can generate full joint probabilities of a Baysian Network and compute the compatness.

### Install

This project requires **Python 2.7** 

### Code

The code is provided in the `BN.py` python file.

### Data

The data are stored in five text files, namely bayesnets1.txt, bayesnets2.txt, bayesnets3.txt, bayesnets4.txt, examplebayes.txt. Each file represents a baysian network. Each line in text file represents a node in baysian network except last line **END**, the first element is the Name of current Node and the string element(s) behind that is the parent(s) of the node, the rest is the Conditional Probability Table.

### Run

In a terminal or command window, navigate to the top-level project directory `Bayesian_Network/` and run one of the following commands:

```python Bayesian_Network/BN.py```  

This will run the `BN.py` file and execute code and generate 5 text files of full joint probability distribution of 5 different baysian networks.
