# Sorting-Algorithms

This repository holds the code for the Sorting Alogrithms website that gives you the option to visualize BubbleSort, MergeSort, QuickSort, HeapSort and RadixSort(using buckets). You can select between tow themes: the standard theme with blue staples or the rainbow theme.

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
**BubbleSort** (Optimized)  : - Placeholder text -

**MergeSort**               : - Placeholder text -

**QuickSort**               : - Placeholder text -

**HeapSort**                : - Placeholder text -

**RadixSort** (With buckets): - Placeholder text -

## Fun facts
Whilst in rainbow mode two staples in an sorted array that have the same height could be in wrong color order if the chosen sorting algorithm is unstable. This can only occur if two staples have the same height. The probabillity of atleast one of these pair existing can be calculated by the formula, where n = length of array:
<img src="https://render.githubusercontent.com/render/math?math={\begin{equation*}\prod_{k=1}^{n} \frac{399 - k}{400}\end{equation*}}">
