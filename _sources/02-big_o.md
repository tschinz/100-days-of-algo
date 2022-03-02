# Big O notation

The Big O notation indicates how fast an algorithms is. It is the worst case evaluation of the given algorithms. In short, how many iterations are needed in the worst case.

```
  O(n)
  ^ ^
  | +-- Number of operations
  +---- Big O

```

A list of algorithms with theirs Big O notation can be found at https://big-o.io.


```{figure} img/big_o/big-o-graph.svg
---
width: 80%
name: Big O algorithms
---
Source: https://big-o.io
```

## Some common runtimes

* $O(log\;n)$ - also known as *log time*
  * [Binary Search](notebooks/006-binary-search.ipynb)
* $O(n)$ - also known as linear time
  * Simple search
* $O(n\;*\;log\;n)$ - fast sorting algorithms
  * quicksort
* $O(n^2)$ - slow sorting algorihtms
  * selection sort
* $O(n!)$ - very slow algorithms
  * traveling salesperson

```{figure} img/big_o/big-o-complexity.png
---
width: 80%
name: Big o complexity
---
Source: https://www.bigocheatsheet.com
```

```{figure} img/big_o/big-o-comparison_1.png
---
width: 80%
name: Big O comparison
---
Source: https://medium.com/@cparusso/what-the-hell-is-big-o-notation-9b90d9f9cd14
```
