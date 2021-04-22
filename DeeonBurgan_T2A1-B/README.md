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

## Q2. Identify and explain the workings of two search algorithms and discuss and compare their performance/efficiency.  
### Linear search algorithm  
The linear search algorithm is a very simple algorithm that can work on a set whether it's sorted or not. The algorithm works by going through the set by it's values one by one until the search query is found, or nothing is found. Due to the way the search looks through all values one after the other, the complexity is O(n)

### Binary search algorithm  
The binary search algorithm is used on sorted sets, and is performed by repeatedly dividing the search set in half.  
The search starts by having an interval which covers the whole set, then if the value of the search is less than the item in the middle of the set, the interval is narrowed to the lower half of the full set, and so on, until the value is found or the interval is empty. Complexity of this algorithm is O(log n).

Comparing these 2 is a little more complicated than the sorting algorithms, as they differ in use. If a set is ordered, in most cases the binary search algorithm will be a better choice, though if the set is small in size, a linear algorithm may work just as efficiently.

[link to reference for bubble sort](https://geeksforgeeks.org/binary-search/)