# Project Title

A smart contract that implements the require(), assert(), and revert() statements

## Description

The above project demonstrates the usage of the require(), assert(), and revert() statements in a Solidity smart contract. These statements are used to handle exceptions, validate inputs, and enforce constraints within the contract.

The ExceptionExample contract includes three functions:

-> requireStatement: This function takes an input num and checks if it is greater than zero using the require() statement. If the condition fails, it throws an exception with the specified error message. If the condition passes, it returns the value of num.

-> assertStatement: This function takes two inputs a and b and uses the assert() statement to check if they are not equal. If the condition fails, it throws an exception. If the condition passes, it returns the value of a.

-> revertStatement: This function does not take any inputs. It uses the revert() statement to immediately abort the execution and revert any changes. It always throws an exception with the specified error message.

The purpose of this project is to showcase how these exception handling statements can be used in Solidity to ensure the contract behaves as expected, handle invalid inputs or exceptional conditions, and maintain the integrity of the contract's state.

## Getting Started

### Executing program

Make sure you have Solidity ^0.8.17 installed and use remix ide.
Compile and deploy the  contract to a supported Ethereum network.
Interact with the deployed contract by calling the available functions and entering the required parameters.



## Authors

Arshdeep Kaur




## License

This project is licensed under the MIT license.
