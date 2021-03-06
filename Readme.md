# Bank Management System
## Introduction
 * The main aim of this project is to develop software for bank management system. This project has been developed to carry out the process easily and quickly , which seems tedious with  manual systems .The system enables the user to create an account , display list of all account holders, deposit cash to his/her account,withdraw cash from his/her account also to check account balance, and it includes file operations also.
 #
![screen](https://github.com/priyankabb153/260150_python_miniproject/blob/master/Images/banner.png)

Codacy Analysis | Python Application/Pytest | Codacy 
|---------|------------|-----------|
|[![CI](https://github.com/priyankabb153/260150_python_miniproject/actions/workflows/codacy_analysis.yml/badge.svg)](https://github.com/priyankabb153/260150_python_miniproject/actions/workflows/codacy_analysis.yml) [![CI-Coverage](https://github.com/priyankabb153/260150_python_miniproject/actions/workflows/CI-coverage.yml/badge.svg)](https://github.com/priyankabb153/260150_python_miniproject/actions/workflows/CI-coverage.yml)|[![Python application](https://github.com/priyankabb153/260150_python_miniproject/actions/workflows/python-app.yml/badge.svg)](https://github.com/priyankabb153/260150_python_miniproject/actions/workflows/python-app.yml) |[![Codacy Badge](https://app.codacy.com/project/badge/Grade/0e30885e761248a994479d3e16d933fe)](https://www.codacy.com/gh/priyankabb153/260150_python_miniproject/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=priyankabb153/260150_python_miniproject&amp;utm_campaign=Badge_Grade)


   
## Bank Management System Features
![screen](https://github.com/priyankabb153/260150_python_miniproject/blob/master/Images/system.png)


###  Features of Bank Management system are:
  * Creating new accounts
  * Display all account holders details
  * Deposit amount
  * Withdraw amount
  * Get account balance

## Pre-requisites to run the files

1) Python version - 3.9.4
To download the latest version of python visit - https://www.python.org/downloads/

2) Downloading required packages
The packages used are:
* pip - 21.1.1
* pytest - 6.2.3

These packages can be downloaded easily in pycharm as : 
* Settings => Project:your_project_name => Project Interpreter => + sign => Search for the packages you want to install

## How to run the project in pycharm IDE

1) Download the zip folder of the code and extract it.
2) Install all the pre-requisites
3) The main file is bank.py -> run this file in the pycharm IDE

=> Press the run button to run the file OR 

=> Type python bank.py in the pycharm terminal

## Pytest

Make sure that pytest is installed in the pycharm IDE :
* Navigate to - Settings => Tools => Pycharm Integrated Tools => Default test runner => select pytest
* Make the required setting for pytest

1) The files - check_file_present.py and no_of_lines.py contains functions for pytest
2) check_file_present.py is used to test if the files exist or not
3) no_of_lines.py is used to check the no of lines present in the file
4) Run the functions in pytest_main.py separately in the pycharm IDE, by right-clicking on the test functions and run
   OR 

=> Enter command pytest pytest_main.py or pytest pytest_main.py -v




