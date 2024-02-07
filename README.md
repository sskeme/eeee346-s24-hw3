# Introduction

In this homework assignment, you will implement a function that performs matrix multiplication. You will practice allocating and deallocating memory for 2D dynamic arrays and using the allocated arrays.


# Background: Matrix Multiplication

Please refer to [this](https://en.wikipedia.org/wiki/Matrix_multiplication#:~:text=In%20mathematics%2C%20particularly%20in%20linear,rows%20in%20the%20second%20matrix.).

# Task

* Implement the printMatrixMul() function in matrixMul.cpp.
  * You must 1) create a 2D dynamic array for the resulting matrix, 2) compute and store the resulting values in the matrix, 3) display the element values using a cout statement, and 4) deallocate the memory from the 2D dynamic array.
  * When displaying the element values, print all rows in the matrix on a single row, with each row separate by a semicolon ; (see the example below).
  * This function is already declared in matrixMul.h, and you can find information about its parameters in this header file.
  * Assume that input matrix dimensions are always compatible.

# Compile and Test

1. Type the following commands on Terminal.

```
g++ -o main *.cpp *.h
```
```
./main
```

2. Enter the number of rows of Matrix A, the number of columns of Matrix A, the element values of Matrix A, the number of rows of Matrix B, the number of columns of Matrix B, and the element values of Matrix B in order. Here is an example.

![example](https://github.com/sskeme/eeee346-s24-hw3-/assets/154963758/788bd7e2-211e-4036-b059-b6de7bc6d7cf)

 * Input
 ```
 2
 3 
 1 2 3
 4 5 6
 3
 2
 7 8
 9 10
 11 12
 ```

 * Expected Output (concatenated)
 ```
 58 64 ; 139 154 ;
 ```

# Submit

1. Type the following commands on Terminal.

```
git add .
```
```
git commit -m "your_message_or_note_for_this_submission"
```
```
git push
```

2. You can verify that your program is working properly with predetermined inputs on GitHub Actions.
