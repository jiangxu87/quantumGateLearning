# quantumGateLearning

## Description 

This repository contains a simplified, yet operative, version of the programs that have been used in [this paper] (http://arxiv.org/pdf/1509.04298.pdf) . The code is written in Python. Priority has been given to comprehension rather then optimization. The current version is divided in two parts: a functions file, and a file for launching. 

With this code one can stochastically optimaze the Hamiltonian of a four qubit network such that its time evolution implements either a Toffoli or a Fredkin gate in the first three qubits (0,1,2) at time equal to one. 
In priciple one can simulate any other three or two body gate as long as the network has four qubits. Note that, if you want to simlate a two body gate, you need to use the proper likelihood which is defined in the functions file. In order to simulate the gate that you like you need to define it in the [qutip language] (http://qutip.org/).

## Dependencies 

In order to run this code you only need:

-Python 
-Numpy
-Scipy (not really, but it doesn't hurt)
-Qutip

## Running 

Once you have all the libraries you can just clone the repository and run the command 

