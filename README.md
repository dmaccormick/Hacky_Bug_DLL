# Hacky Bug C++ Neural Network DLL

## Introduction
Hacky Bug was a game my team made for a final project for an artificial intelligence course in 4th year (2019). It is a Flappy Bird clone made in Unity but the 'birds' are instead programming bugs trying to avoid detection by slipping past breakpoints in the code.  

While the game does have player controls, the bugs are actually controlled by artificial neural networks. A genetic evolution algorithm slowly breeds the best bugs from each generation so they learn to fly further and further over time. This logic is written in C++ and integrated with Unity through a DLL.

A video demonstration of Hacky Bug can be found here: https://www.youtube.com/watch?v=VXDwaPZgYto

## Code Overview
This repository only contains the source code for the C++ neural network DLL, not the Unity project. 
The neural networks were built from scratch but relied on Eigen (https://eigen.tuxfamily.org/index.php?title=Main_Page) for efficient matrix multiplication.
