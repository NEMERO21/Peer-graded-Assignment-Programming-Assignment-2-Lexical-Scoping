# Peer-graded-Assignment-Programming-Assignment-2-Lexical-Scoping
# Programming Assignment 2

## Introduction

This repository contains the solution for the second programming assignment, which involves writing R functions to cache potentially time-consuming computations. The task is to create a pair of functions that can cache the inverse of a matrix.

## Example: Caching the Mean of a Vector

In the provided example, a special "vector" object is created that stores a numeric vector and caches its mean. The `makeVector` function is used to create this object, and the `cachemean` function calculates the mean while checking and utilizing the cache.

## Assignment: Caching the Inverse of a Matrix

The main focus of this assignment is to write two functions:
1. **makeCacheMatrix:** Creates a special "matrix" object that can cache its inverse.
2. **cacheSolve:** Computes the inverse of the special "matrix" returned by `makeCacheMatrix`. If the inverse has already been calculated and the matrix has not changed, `cacheSolve` retrieves the inverse from the cache.

## Instructions for Submission

To complete this assignment, follow these steps:

1. Fork the GitHub repository containing the stub R files at [ProgrammingAssignment2](https://github.com/rdpeng/ProgrammingAssignment2) to create a copy under your own account.
2. Clone your forked GitHub repository to your computer for local editing.
3. Edit the R file in the repository and place your solution in that file without renaming it.
4. Commit your completed R file into YOUR git repository and push your git branch to the GitHub repository under your account.
5. Submit the URL to your GitHub repository containing the completed R code for the assignment on Coursera.

## Grading

This assignment will be graded via peer assessment.
