---
layout: post
title:  "Insertion Sort 插入排序"
date:   2019-09-06 13:35:08 +1000
categories: algorithms
---

Keyword: Sorting, Algorithm, Insertion sort
* * *
<h2 id="title">Insertion Sort</h2>
<h3 id="definition">Definition</h3>

Insertion Sort is similar to how we sorted cards in our hand when playing card games. Each card (element) is compared with the cards before it in the array/list and moved to left of the least card (element) that is larger than it. 

This graphical example clearly illustrates the sorting process:
![Oops, Image is missing](/assets/Insertion-sort-example-300px.gif)
Insertion Sort: go through every element from left to right and compare to its lefts

Coding in Java:

    // Java program for implementation of Insertion Sort 
    class InsertionSort { 
        /*Function to sort array using insertion sort*/
        void sort(int arr[]) 
        { 
            int n = arr.length; 
            for (int i = 1; i < n; ++i) { 
                int key = arr[i]; 
                int j = i - 1; 
    
                /* Move elements of arr[0..i-1], that are 
                greater than key, to one position ahead 
                of their current position */
                while (j >= 0 && arr[j] > key) { 
                    arr[j + 1] = arr[j]; 
                    j = j - 1; 
                } 
                arr[j + 1] = key; 
            } 
        } 