# Discrete Mathematics
## Q1. Identify and explain the workings of two sorting algorithms and discuss and compare their perforance/efficiency.  
### Bogo sort:  
Bogo sort is arguably the worst possible way to sort anything. In it's worst case, it runs at a performance of O((n+1)!).  
Bogo sort is a method that tries to sort it's input by randomly generating permutations of itself until it finds one that is in a sorted order.  
### Bubble sort:  
Bubble sort is one of the most simple sorting algorithms, with an efficiency of O(n^2), as it is simply comparing 2 items at a time and swapping them if they aren't in order, and this is done until there are no swaps that occur in a loop.  

Comparing these 2 sorting algorithms is very simple, although both are generally very inefficient, bubble sort will almost always be better and faster than bogo sort, as there is actually some logic behind the sorting, rather than working on what's essentially luck.  
References:  
[link to reference for bogo sort](https://en.wikipedia.org/wiki/Bogosort)  
[link to reference for bubble sort](https://www.geeksforgeeks.org/bubble-sort/)