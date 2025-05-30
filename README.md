Libft - 42 School

Libft is a project from 42 School that consists of creating a custom C library with useful functions that are commonly used in programming. The goal is to understand the fundamentals of C, memory management, and reimplement standard library functions.

Table of Contents

Introduction

Installation

Usage

Implemented Functions

Project Structure

Testing

License

Introduction

The Libft project requires students to implement a set of functions that replicate those found in the C standard library. These functions cover a variety of topics such as:

String manipulation

Memory management

Linked lists

Character classification and conversion

By completing this project, students gain a deeper understanding of how low-level operations work in C and how libraries are structured.

Installation

To compile the Libft library, simply clone the repository and run the make command:

# Clone the repository
git clone https://github.com/yourusername/libft.git
cd libft

# Compile the library
make

This will generate a libft.a file, which is a static library that can be used in other projects.

Usage

To use Libft in your own projects, include the library and header file in your compilation:

#include "libft.h"

Compile your project with libft.a:

gcc your_file.c -L. -lft -o your_program

Implemented Functions

Libft includes functions categorized into different groups:

1. Libc Functions

Reimplementations of standard C functions:

ft_strlen - Calculates the length of a string

ft_strcpy - Copies a string to another buffer

ft_strncmp - Compares two strings

ft_memcpy - Copies memory area

ft_memset - Fills memory with a constant byte

2. Additional Functions

Extra utility functions useful in many applications:

ft_strdup - Duplicates a string

ft_substr - Extracts a substring from a string

ft_strjoin - Concatenates two strings

ft_split - Splits a string into an array based on a delimiter

3. Linked List Functions

Basic linked list operations:

ft_lstnew - Creates a new linked list element

ft_lstadd_front - Adds an element at the beginning of a linked list

ft_lstadd_back - Adds an element at the end of a linked list

ft_lstmap - Applies a function to each element of a linked list

Project Structure

The project follows a simple directory structure:

libft/
├── src/           # Source files
├── include/       # Header files
├── Makefile       # Compilation rules
├── README.md      # Project documentation

Testing

To test the implementation, you can use external testers such as:

libft-unit-test

libft-war-machine

libftTester

To run tests, clone the tester repository, compile Libft, and execute the test script.

License

This project is open-source and follows the 42 School guidelines. You are free to use and modify it for learning purposes.

