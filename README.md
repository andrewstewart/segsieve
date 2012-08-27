segsieve
========

Segmented sieve of Eratosthenes in Python

Usage is as simple as:

from primes import sieveSegm
primeList = sieveSegm(10**8)

Using Python 2.7.3, it takes about 40 seconds to generate all primes less than 10**8.
Using Pypy 1.8.0 with Python 2.7.3 it takes 1.2 seconds for all primes less than 10**8, and 11.65 seconds for all primes less than 10**9.
