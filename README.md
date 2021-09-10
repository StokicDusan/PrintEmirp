# Print Emirp

An emirp is a prime number that results in a different prime when its decimal digits are reversed.

## What does the script do?
The script prints emirp prime numbers on the command line.

## `printEmirp.py` :
This script is ready to use script which uses one argument to run. The argument is the integer passed for the upper bound of numbers to be 
checked if they are emirp numbers.

### print_emirp function:
Function prints numbers divided by a space character.  
Invoking the script runs this function.  

### print_emirp_count function:
Function prints numbers divided by a space character and a count of how 
many numbers it printed in the new line.

## Installing the dependencies

### Used packages
This script require the math, sys and doctest package.

## How to use it
#### 1. Clone this repository:
```bash
$> git clone https://github.com/StokicDusan/PrintEmirp.git
$> cd PrintEmirp/
```
#### 2. Launch
In the command line simply invoke the script with one argument:
```zsh
$> python printEmirp.py argv1
```
* argv1:  
Any positive integer  

:warning: *Note:* Other input will result in an error


Invoking the script with no arguments will run testmod().
