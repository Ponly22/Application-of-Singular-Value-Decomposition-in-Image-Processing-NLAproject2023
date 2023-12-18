# Application-of-Singular-Value-Decomposition-in-Image-Processing-NLAproject
This repository consist of the project at NLA2023 course at Skoltech.

## Table of Contents 

 - [Keys Features](#keys-features)
 - [Quickstart](#quickstart)
 - [Build & Test the program](#build--test-the-program)
 - [Reference](#reference) 
 - [Credit](#credit)

## Keys Features

-   Decimal to Binary and vice versa: Convert between decimal and binary numbers, ideal for programmers.
-   Decimal to Hexadecimal and vice versa: Convert between decimal and binary numbers, ideal for programmers.
-   Decimal to Roman Numerals and vice versa: Easily transform decimal numbers into Roman numerals and vice versa

## Quickstart

There are 3 main steps to build and test the program.

 1. Update and install necessary's packages 
    ``` bash 
    sudo apt-get update
    sudo apt-get install -y build-essential
    sudo apt-get install git
    ```
 2. Clone the repository
    ``` bash 
    git clone https://github.com/AxoyTO/FSE_2023_G4.git
    cd FSE_2023_G4
    ```
     
 3. [Build & Test the program](#build--test-the-program)

## Build & Test the program

 1. Using Makefile
    ``` bash 
    make -f Makefile 
    ```
    or just
    ``` bash 
    make
    ```
    Testing the program
    ``` bash 
    python3 test/test.py 
    ```
    or just
    ``` bash 
    make test
    ```
 3. Using Dockerfile
    ``` bash 
    docker build -t project:v1.0 -f Dockerfile .
    docker run -it --entrypoint bash project:v1.0 
    ```
    Testing the program
    ``` bash 
    ./test/test 
    ```

## Reference 

The source code is separated into three files:

> [main.cpp](https://github.com/AxoyTO/FSE_2023_G4/blob/dev/src/main.cpp)`
-   In the  `main.cpp`  file, it is the code for launching application and separately analyze command line arguments. In this file, you can change and add more features about the converting numbers.
> [converter.cpp](https://github.com/AxoyTO/FSE_2023_G4/blob/dev/src/converter.cpp)
-   In the  `converter.cpp`  file, it is the code for defining conditions of each feature to convert numbers in several types. In this file, you can change, add and delete conditions of each feature about the converting numbers to see new result and can modify to be a new converter.
> [converter.hpp](https://github.com/AxoyTO/FSE_2023_G4/blob/dev/src/converter.hpp)
- In the  `converter.hpp`  file, you can find source code for the library functions.



## Credit

Team members:

1. Addisu Zena
2. Anna Ermakova
3. Pattapon Tanankakorn
