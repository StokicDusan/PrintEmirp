[![Contributors][contributors-shield]][contributors-url]
[![Commit-activity][commit-activity-shield]][commit-activity-url]
[![Issues][issues-shield]][issues-url]
[![Repo-size][repo-size-shield]][repo-size-url]
[![License][license-shield]][license-url]  
[![Forks][forks-shield]][forks-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

# Welcome to PrintEmirp

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
$ git clone https://github.com/StokicDusan/PrintEmirp.git
$ cd PrintEmirp/
```
#### 2. Launch
In the command line simply invoke the script with one argument:
```bash
$ python printEmirp.py argv1
```
* argv1:  
Any positive integer  

:warning: *Note:* Other input will result in an error


Invoking the script with no arguments will run testmod().

## Examples

The following code block shows examples of calling the printEmirp script from terminal.

```bash
$ python3 printEmirp.py 7

$ python3 printEmirp.py 100
13 17 31 37 71 73 79 97 
$ python3 printEmirp.py 1000
13 17 31 37 71 73 79 97 107 113 149 157 167 179 199 311 337 347 359 389 701 709 733 739 743 751 761 769 907 937 941 953 967 971 983 991 
```
## Provide Feedback 👍

If you encounter any bugs or have suggestions, please file an issue in the
[Issues][issues-url]
section of the project.

[contributors-shield]: https://img.shields.io/github/contributors/StokicDusan/PrintEmirp
[contributors-url]: https://github.com/StokicDusan/PrintEmirp/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/StokicDusan/PrintEmirp?style=social
[forks-url]: https://github.com/StokicDusan/PrintEmirp/network/members
[issues-shield]: https://img.shields.io/github/issues/StokicDusan/PrintEmirp
[issues-url]: https://github.com/StokicDusan/PrintEmirp/issues
[commit-activity-shield]: https://img.shields.io/github/last-commit/StokicDusan/PrintEmirp
[commit-activity-url]: https://github.com/StokicDusan/PrintEmirp/graphs/commit-activity
[license-url]: https://github.com/StokicDusan/PrintEmirp/blob/main/LICENSE
[license-shield]: https://img.shields.io/github/license/StokicDusan/PrintEmirp
[repo-size-shield]: https://img.shields.io/github/repo-size/StokicDusan/PrintEmirp
[repo-size-url]: https://img.shields.io/github/repo-size/StokicDusan/PrintEmirp
[linkedin-shield]: https://img.shields.io/badge/LinkedIn-0077B5?style=plastice&logo=linkedin&logoColor=white
[linkedin-url]: https://linkedin.com/in/stokicdusan
