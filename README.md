# RSA Factoring Challenge
## Case description
We have sniffed an unsecured network and found numbers that are used to encrypt very important documents. It seems that those numbers are not always generated using large enough prime numbers. Your mission should you choose to accept it, is to factorize these numbers as fast as possible before the target fixes this bug on their server - so that we can decode the encrypted documents.

### Task 0
Factorize as many numbers as possible into a product of two smaller numbers.
- Usage: factors "file"
	- where "file" is a file containing natural numbers to factor.
	- One number per line
	- You can assume that all lines will be valid natural numbers greater than 1
	- You can assume that there will be no empy line, and no space before and after the valid number
	- The file will always end with a new line

### Task 1
RSA Laboratories states that: for each RSA number n, there exist prime numbers p and q such that

	n = p × q. 

The problem is to find these two primes, given only n.

This task is the same as task 0, except:
- p and q are always prime numbers
- There is only one number in the files
How far can you go in less than 5 seconds?
