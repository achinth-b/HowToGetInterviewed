# ⭕ Big O (my god this is exciting)

## Things to remember and notes:



### Complexity 
* space should be the memory USED to solve the given problem 
* in-place means O(1)
* if f(n) is in o(g(n)) -> f(n) is in O(g(n))
* 


### Runtimes you need to memorize
* Insertion Sort, Selection Sort and Quicksort: O(n<sup>2</sup>)
* Mergesort, Heapsort: O(n log n)
*

### Spaces we need to memorize 
* Insertion, selection, heapsort, bubble sort: O(1) 
* Mergesort, Quicksort: O(n) 
* When in doubt, O(n) space complexity 




## Questions: 
1)
~~~
int product(int a, int b){
    int sum = 0; 
    for(int i = 0; i < b; i++){
        sum +=a;
    }
    return sum; 
}
~~~

2)
~~~
int power(int a, int b) { 
    if (b < 0) {
        return 0;
    }
        
    else if (b == 0) {
        return 1;
    }
    
    else {
        return a * pow(a, b - 1);
    }
~~~

3)
~~~
int sqrt(int x){
    for (int i = 0; i < x; i++){
        if (pow(i, 2) == x){
            return i; 
        }
    }
}
~~~
4) 
~~~
int intersect(int[] a, int[] b){
    mergesort(b);
    int intersect = 0; 
    
    for (int x : a) {
        if (binarySearch(b, x) >= 0) {
            intersect++;
        }
    }
    return intersect; 
}
~~~

5) 
~~~

~~~


