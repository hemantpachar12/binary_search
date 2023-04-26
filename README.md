# binary_search
A Binary Search is a sorting algorithm, that is used to search an element in a sorted array. A binary search technique works only on a sorted array, so an array must be sorted to apply binary search on the array. It is a searching technique that is better then the liner search technique as the number of iterations decreases in the binary search.

The logic behind the binary search is that there is a key. This key holds the value to be searched. The highest and the lowest value are added and divided by 2. Highest and lowest and the first and last element in the array. The mid value is then compared with the key. If mid is equal to the key, then we get the output directly. Else if the key is greater then mid then the mid+1 becomes the lowest value and the process is repeated on the shortened array. Else if the key value is less then mid, mid-1 becomes the highest value and the process is repeated on the shortened array. If it is not found anywhere, an error message is displayed.
# When to use Binary Search?
When searching a large dataset as it has a time complexity of O(log n), which means that it is much faster than linear search.

When the dataset is sorted.

When data is stored in contiguous memory.

Data does not have a complex structure or relationships.
# output
![image](https://user-images.githubusercontent.com/93450820/234482665-87d98d4c-75c7-4cb1-9958-3ae553dd3913.png)
