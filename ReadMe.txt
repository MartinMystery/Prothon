Welcome to Prothon program version 1.2 !

1) Main feature :

Prothon is a primality proving program for specific classes of Proth numbers . Proth numbers are numbers of the form N=k*2^n+1 , with k odd and k<2^n . Prothon can test for primality following classes of Proth numbers :

Class 1 :

N=k*2^n+1 , with n>2 , k<2^n and

k= 1 (mod 42) with n= 2,4 (mod 6)

k= 5 (mod 42) with n= 3 (mod 6)

k= 11 (mod 42) with n= 3,5 (mod 6)

k= 13 (mod 42) with n= 4 (mod 6)

k= 17 (mod 42) with n= 5 (mod 6)

k= 19 (mod 42) with n= 0 (mod 6)

k= 23 (mod 42) with n= 1,3 (mod 6)

k= 25 (mod 42) with n= 0,2 (mod 6)

k= 29 (mod 42) with n= 1,5 (mod 6)

k= 31 (mod 42) with n= 2 (mod 6)

k= 37 (mod 42) with n= 0,4 (mod 6)

k= 41 (mod 42) with n= 1 (mod 6)

Class 2 :

N=k*2^n+1 , with n>2 , k<2^n and

k= 1 (mod 6) and k= 1,7 (mod 10) with n= 0 (mod 4)

k= 5 (mod 6) and k= 1,3 (mod 10) with n= 1 (mod 4)

k= 1 (mod 6) and k= 3,9 (mod 10) with n= 2 (mod 4)

k= 5 (mod 6) and k= 7,9 (mod 10) with n= 3 (mod 4)

2) Basic Algorithms :

Numbers are tested using Lucasian primality algorithms ,

see Theorem 3.3. and Theorem 3.4. in

http://arxiv.org/pdf/1506.03444v1.pdf
