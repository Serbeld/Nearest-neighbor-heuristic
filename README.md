# Nearest-neighbor-heuristic-as-a-solution-for-Robot-Tour-Optimization

This repository shows how to use the nearest neighbor heuristic as a solution for Robot Tour Optimization (RTO).

Robot Tour Optimisation

This repository shows how to use the nearest neighbor heuristic as a solution for Robot Tour Optimization (RTO).

This algorithm was created by:

    Author: sergio Beleño
    Date: 2020-11-11
    
Some references present for the development of this algorithm were taken from:

    Jason Brownlee (February 24, 2020). Develop k-Nearest Neighbors in Python From Scratch
    https://machinelearningmastery.com/tutorial-to-implement-k-nearest-neighbors-in-python-from-scratch/
    
    Bryn Mawr(2015).The Traveling Salesperson Problem
    https://jupyter.brynmawr.edu/services/public/dblank/jupyter.cs/FLAIRS-2015/TSPv3.ipynb

## Algorithm

To make use of the algorithm, go to the folder found in the repository under the name of src.

This implementation was created with the following specifications:

        Operating system: Windows 10
        Programming language: Python 3.8
        Compiler name: Spyder 4.1.5

## Libraries

For the correct functioning of the code it is necessary to install the "pandas" file reading library, to install this library it is necessary to enter the "System Symbol" in case of having windows or the "Terminal" in case of Linux operating systems and write the following line:

        pip install pandas

## How does it work

When the algorithm is executed, the code asks the user to enter the name of an excel file containing the coordinates of each of the points where the cities are located to find the path of travel given by the nearest neighbor heuristic as a solution for Robot Tour Optimization (RTO):

        Please, put the name of the input file: test1
        Instance:
        1  1.4  6.2
        2  5.1  6.2
        3  6.2  9.8
        4  7.4  6.2
        5  8.1  4.1
        6  11.2  6.2
        7  9.3  0.6
        8  6.2  2.7
        9  3.3  0.6
        10  4.4  4.1
        Solution: [10, 2, 4, 5, 8, 9, 1, 3, 6, 7, 10]
        Distance: 42.67766018727815
        
        Best solution: [7, 5, 4, 2, 10, 8, 9, 1, 3, 6, 7]
        Best distance: 40.276298606305396

### Note: 
You can use the names of the excel files like test1, test2 and test3.
