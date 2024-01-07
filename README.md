# Fuzzy logic controller designed with SK-Fuzzy (Python)

## Description
This code shows the design of a fuzzy logic controller that I thought to be use for an air conditioner controller that can be built for a train. The input variables are the amount people and the wagon size (I'm assuming that the wagon size will be unidimensional and that will be the length of it). The output is the intensity of the air conditioner which I am assuming that it will be between 0 and 1. The main library that I'm using is SK-Fuzzy which is for python. Take also into account that I built this in collab from Google. The structures is as follows:
1) libraries installation, imports, etc.
2) Definition of the universe of discourse
3) Definition of membership function, assuming triangular ones
4) View of membership functions (you can also download them)
5) Option to build gaussian membership function if you want too
6) Option (it is commented) to check at the membership rules
7) Definition of if-then rules
8) Simulation creation and intensity output. There are also graphs to check here

## How to install this
1) Download the code
2) Open it in google colab. I didn't try with Jupyter but I guess that should be more or less the same. As far as I had just checked, this guy made it: https://www.youtube.com/watch?v=L80dn0PiN_U&ab_channel=TechTips

## How to tweak this code
There are several point to tweek. At least for me, the most important are the following ones:
1) Number of people inside
2) Train length
3) Membership functions shape
4) Base rules


## Found a bug?
Please let us know by writing it down and your thoughts about what caused that bug. Try to explain as much as you can. It will be very appreciate it

## Work in progress
I'm thinking about adding more features in the future like changing the defuzzification processs or even using evolutive algorithms to gather the membership functions perhaps.
