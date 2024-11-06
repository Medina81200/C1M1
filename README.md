
# ARRAY DATA ANALYZER

@author Edgar Medina
@date Nov 5, 2024

# Statistical analysis of an array of unsigned char data

This project provides functions to analyze an array of unsigned char data by calculating its minimum, maximum, mean, and median. 
It also includes functionality to sort the array in descending order and print it in a structured format.

## Overview

The purpose of this project is to perform basic statistical analysis on an array of unsigned `char` values. The project includes a set of functions that:
- Find the minimum and maximum values
- Calculate the mean and median
- Sort the array from largest to smallest
- Print the array and statistics in a nicely formatted manner

## Project Structure

- `main.c`: Contains the `main()` function, which initializes a sample array and calls the statistical functions to analyze and print results.
- `stats.h`: Header file with function declarations for all statistical operations.
- `stats.c`: Implementation of the functions declared in `stats.h`.

## Functions

The following functions are implemented in `stats.c`:

- `find_minimum(unsigned char *array, unsigned int size)`: Returns the minimum value in the array.
- `find_maximum(unsigned char *array, unsigned int size)`: Returns the maximum value in the array.
- `find_mean(unsigned char *array, unsigned int size)`: Calculates and returns the mean value, rounded down.
- `find_median(unsigned char *array, unsigned int size)`: Finds and returns the median value, rounded down if necessary.
- `sort_array(unsigned char *array, unsigned int size)`: Sorts the array in descending order.
- `print_statistics(unsigned char *array, unsigned int size)`: Prints the calculated statistics for the array.
- `print_array(unsigned char *array, unsigned int size)`: Prints the array in a 5x8 grid format for readability.

## Usage

To use these functions in your project, include the `stats.h` header file and link `stats.c` when compiling. You can modify the array in `main.c` to test the functions with different datasets.


## Compilation

To compile the code, use the following command:


```bash
gcc -o stats.out main.c stats.c


