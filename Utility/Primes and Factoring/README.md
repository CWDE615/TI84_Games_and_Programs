#Primes and Factoring
The files in this directory are a suite of programs and required lists for factoring and primality testing functionalities.
A list of the programs and dependencies is below

## Programs
|Program|Description|Required List(s)|
|:------|:----------|:---------------|
|FACTOR|Derives the prime factorization a given integer n by using primes to find a possible devisor. Uses PRIME to find all prime factors of n and outputs the factorization to FACTR|PRIME & FACTR|
|ISPRIME|Determines whether a given integer n is prime using the PRIME list to test whether there are any prime numbers less than or equal to sqrt(n) such that PRIME\|n|PRIME|
|PRIMES|Generates a list of prime numbers within a given range (max 999 primes) and stores it in the PRIME list|PRIME|
