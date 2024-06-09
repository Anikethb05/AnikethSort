# Aniketh's Sorting Algorithm

Aniketh's Sorting Algorithm is a comparison-based sorting algorithm where each element in the array is compared with every other element. If the current element is greater than the compared element, they are swapped. This process continues until all elements are sorted.

## Pseudocode
for i from 0 to n-1 do:
    for j from 0 to n-1 do:
        if arr[j] > arr[i] then:
            swap arr[j] and arr[i]
return arr
