---
layout: post
title:  "Sorting Algorithm 排序算法"
date:   2019-09-05 15:21:43 +1000
categories: algorithms
---

Keyword: Sorting, Algorithm, Insertion sort
* * *
<h2 id="sorting">Sorting Algorithm</h2>
<h3 id="definition">Definition</h3>
Sorting is an algorithm that puts elements of a list in a certain order. The most frequently used orders are numerical order and lexicographical order. Efficient sorting is important for optimizing the efficiency of other algorithms (such as search and merge algorithms) which require input data to be in sorted lists. Sorting is also often useful for canonicalizing data and for producing human-readable output.
<h3 id="classification">Classification</h3>
Sorting algorithms are often classified by the following aspects:
* <b>Computational complexity</b> （worst, average and best) wrt the size of the array/list. For comparison-based sorting algorithms, the least times of comparison is Ω(n log n).
* <b>Memory usage</b>. For in-place algorithm ("原地算法", whose input is overwritten by the outputs so no additional data structure is used.) always takes O(1) memory.
* <b>Recursion</b>. Recursive, non-recursive or partial recursive.
* <b>Stability</b>. A stable sort maintains the order of equal value elements.
* <b>Comparison</b> or non-comparison.
* <b>Serial or Parallel</b>. Parallel sorting is to break the array into sub-arrays that are themselves sorted and then merged. It runs its process in multiple threads. 
* <b>Adaptability</b>. If the presortedness affects the running time.
* <b>Sorting method</b>. Insertion sort, merge sort, quick sort, heap sort, etc.

<h3 id="list">List of popular comparison sortings</h3>
<table style="width:100%">
  <caption>Comparison sortings</caption>
  <tr>
    <th>Name</th><th>Worst</th><th>Average</th><th>Best</th><th>Memory</th><th>Stable</th><th>Method</th>
  </tr>
  <tr>
    <td>Insertion sort</td><td>![n^2](/assets/n^2.png)</td><td>$n^2$</td><td>n</td><td>1</td><td>Y</td><td>Insertion</td>
  </tr>
  <tr>
    <td>Bubble sort</td><td>$n^2$</td><td>$n^2$</td><td>n</td><td>1</td><td>Y</td><td>Exchanging</td>
  </tr>
  <tr>
    <td>Merge sort</td><td>nlog(n)</td><td>nlog(n)</td><td>nlog(n)</td><td>n</td><td>Y</td><td>Merging</td>
  </tr>
  <tr>
    <td>Quicksort</td><td>n2</td><td>nlog(n)</td><td>nlog(n)</td><td>log(n) (average) <br> n (worst) </td><td>N</td><td>Partitioning</td>
  </tr>
  <tr>
    <td>Selection sort</td><td>$n^2$</td><td>$n^2$</td><td>$n^2$</td><td>1</td><td>N</td><td>Selection</td>
  </tr>
  <tr>
    <td>Heapsort</td><td>nlog(n)</td><td>nlog(n)</td><td>nlog(n)</td><td>1</td><td>N</td><td>Selection</td>
  </tr>
</table>
