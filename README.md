# String Verification using Regular Expressions 🌠

This repository contains an implementation for verifying a string against a given regular expression. The goal of this project is to provide a reliable and efficient solution for pattern matching and validation using regular expressions in Python.

## Overview ✨

Regular expressions are powerful tools for matching and manipulating strings based on specific patterns. They are widely used in various applications, including text processing, data validation, and pattern recognition. This project aims to demonstrate how regular expressions can be utilized to verify whether a given string matches a specified pattern.

## Implementation ⌨️👩‍💻

The implementation utilizes the regular expression module provided by Python's standard library. It allows users to define custom regular expressions using a set of predefined rules and syntax. The program takes a user-input string and checks if it matches the provided regular expression.
1. **String processing :** Insert '.' which are multiplications in expressions that are written without it
2. **Regex to postfix :** We change the regular expression to a postfix to be able to effectively make the machine understand the priorities
3. **postfix to ast :** We change the Postfix to an AST, a tree structure that represents what part of the expression to start processing first
4. **Pasrse Tree to NFA :** Change the AST to be represented as NFA [Thompson's Construction]
5. **Change NFA to DFA :** Change the NFA to DFA [Subset Construction Theorem]
6. **Checking**: Checking by tracing the DFA and finding if we reach an end state or acceptance state

