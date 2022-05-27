# Sorting-Algorithms

This repository holds the code for the Sorting Alogrithms website that gives you the option to visualize BubbleSort, MergeSort, QuickSort, HeapSort and RadixSort(using buckets). You can select between two themes: the standard theme with blue staples or the rainbow theme.

Sorting Algorithm webpage URL:
(Use FireFox or Chrome for the best experience) https://qodemaster.github.io/Sorting-Algorithms/


## Quick Guide
This websites visually displays the five sorting algortihms listed beneath the header below.
A guest can generate a new unsorted array by pressing the "Generate New Array"-button. It will generate a roster of unsorted staples which will be the subjects of a selected algorithm. The highlighted name of the sorting algorithm means that it's currently selected.

### Size/Speed
The size of the unsorted array and the speed of sorting can be altered by moving each slider respectively.
___
![sliders](https://user-images.githubusercontent.com/59826211/162976032-95dfe926-eac8-43bd-955f-8e67be811802.PNG)

### Default mode
The color of the staples are contingent upon the state of the staple. The following table describes the meaning of each color and state.
| Color/State     | Description |
| ------------- |:-------------:|
| Blue      | Unsorted |
| Red     | Compared/Evaluated |
| Purple | Position Swapped |
| Green | In sorted position  |

### Rainbow mode
The rainbow mode is accessed by pressing the rainbow button that is to the left of the play button.
___
![toggleRainbowMode](https://user-images.githubusercontent.com/59826211/163394658-d639dbbd-61e2-4473-bfd6-0d38d7a1ed58.PNG)
<br />
This will sort the staples in respect to height and color order according to the colors of the rainbow.

## Algorithm Descriptions
**BubbleSort** (Optimized)  : This sorting algorithm works by comparing two adjacent array elements and switches their position if the first one is greater than the second one. Iterating through the array in this fashion will result in the greatest element becoming placed in the last index of the array. Applying the same algoithm on every element will result in the array being sorted.

**MergeSort**               : The merge sort algorithm uses the "divide and conquer" strategy to sort an array. Merge Sort splits the array into smaller data sets, sorts those smaller sets, and then merges the resulting sorted lists together. The algorithm utilizes recursion to break the array into smaller sets and this overall strategy makes merge sort faster than bubble sort.

**QuickSort**               : Similarly to MergeSort, QuickSort is a *Divide and Conquer* algorithm. It uses pivots to partition the unsorted list into smaller data sets and sorts those sets of data. This particular implementation of the quick sort algorithm chooses the pivot index to be equal to the index of the last element in the partition.

**HeapSort**                : The Heap sort algorithm is as well as the previously four mentioned algorithm a comparison based sorter. It rearranges the contents of the array so that it resembles a priority queue. This action results in the greatest element being the first element. Switching the first with the element and the last element will cause the list to be sorted for that one element.  Turning the array(excluding the last element) into priority queue and repeating the process with result in the array being sorted.

**RadixSort** (With buckets): The radix sort algorithm is a non-comparative sorting algorithm which means that it doesn't compare two elements to see whether they should switch or not. This implementation of the radix sort algorithm uses lists to store the radix of the elements. The elements that are stored are later put back in the array and this is repeated for every digit of every element until the most significant digit has been reached which results in the array being sorted.

## Fun facts
Whilst in rainbow mode two staples in an sorted array that have the same height could be in wrong color order if the chosen sorting algorithm is unstable. This can only occur if two staples have the same height. The probabillity of atleast one of these pair existing can be calculated by the formula, where n = length of array:
<br/>
![eq](https://user-images.githubusercontent.com/59826211/163401784-a5b8fdae-ce5a-4ba0-8f6f-e912b90cd11c.PNG)
