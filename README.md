# Aniketh's Sorting Algorithm

Aniketh's Sorting Algorithm is a comparison-based sorting algorithm where each element in the array is compared with every other element. If the current element is greater than the compared element, they are swapped. This process continues until all elements are sorted.

## Pseudocode
for i from 0 to n-1 do:
    for j from 0 to n-1 do:
        if arr[j] > arr[i] then:
            swap arr[j] and arr[i]
return arr

## Example
INPUT: 
Enter size of array: 4
Enter elements: 4 3 2 1

OUTPUT:
Sorted array: 1 2 3 4

## Characteristics of Aniketh's Sorting Algorithm:
- Correctness: It does sort the array correctly.
- Efficiency: The time complexity is O(n^2), making it inefficient for large arrays.
- Uniqueness: It follows a unique approach, not matching standard sorting algorithms like Bubble Sort, Selection Sort, or Insertion Sort.
