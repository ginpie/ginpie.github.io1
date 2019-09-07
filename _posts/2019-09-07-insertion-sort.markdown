---
layout: post
title:  "Insertion Sort 插入排序"
date:   2019-08-16 13:35:08 +1000
categories: algorithms
---

Keyword: Comparative Sorting, Algorithm

<h2 id="sorting">Sorting Algorithm</h2>
<h3 id="definition">Definition</h3>
Sorting is an algorithm that puts elements of a list in a certain order. The most frequently used orders are numerical order and lexicographical order. Efficient sorting is important for optimizing the efficiency of other algorithms (such as search and merge algorithms) which require input data to be in sorted lists. Sorting is also often useful for canonicalizing data and for producing human-readable output.
<h3 id="classification">Classification</h3>
Sorting algorithms are often classified by:
* Computational complexity （worst, average and best) 

Insertion Sort is similar to how we sorted cards in our hand when playing card games. Each card (element) is compared with the cards before it in the array/list and moved to left of the least card (element) that is larger than it. 

This graphical example clearly illustrates the sorting process:
![Oops, Image is missing](/assets/Insertion-sort-example-300px.gif)Insertion Sort: go through every element from left to right and compare to its lefts

