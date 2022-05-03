# w1-
w1 算法

(1). On my machine, a certain O(n2) sorting algorithm takes one second to sort 1000 random items.  Sorting 100,000 random items can be expected to take:

(1000)^2 =1000 000,  

(100,000)^2 = 10,000,000,000      
 
10,000,000,000/1,000,000=10,000s=166.67min =2 -3 hours

(2). If f(n) is O(g(n)) then f(n) grows asymptotically no faster than g(n).

     True 
     A function f(n) is O(g(n)) if g(n) defines an upper bound on the growth of f(n) as n becomes large

(3).Consider the following statement: n(n+1)∈ O(n2)
   
     False， c=1，n0=0，n≥n0， f（n）=n(n+1) ≥ n2,  n(n+1)∈ Ω(n2)
  
(4).Consider the function t(n) =57n4 + 10n2 + 75 .
t(n) ∈ O( g(n) ) where g(n) is:

    n^7 and n^4
   
(5). Which of the following claims about growth rate are correct: 

     3n^3 + n√n ∈ n^3
     lets assume c= 4
     3n^3 + n√n ≤ 4（n^3）
              n ≤ n^4
     For all n≥1 ,n0=1,C=4 ,  3n^3 + n√n ∈ n^3
    
(6). Which of the following claims about growth rate are correct:  

    2^(n+1) ∈ Ө 2^n
    for c2 ≥ 2, 2^(n+1) ≤ c2*(2^n)
    for c1 ≤ 2, 2^(n+1) ≥ c1*(2^n)
    so  2^(n+1) ∈ Ө 2^n

(7). Which of the following claims are correct:


(8). 2^2n is O(2n)

    False .2^2n is equivalent to 2n*2n. Consequently, 2n is not an upper bound on 2^2n!
    
(9). Given an array of n items, A, what is the Big-Ө complexity of retrieving the element at index k in the array (A[k])?

    Ө(1). Accessing the element at index k in an array is a constant time operation -- it does not depend on the number of items in the array.
    
(10). n^2 + 5n is Ө(g(n)) where g(n) is
      
      n^2







