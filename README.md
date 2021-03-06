# DS_Binary_Search
A binary search technique works only on a sorted array, so an array must be sorted to apply binary search on the array.
It is a searching technique that is better than the linear search technique as the number of iterations decreases in the binary search.
The logic behind the binary search is that there is a key.
This key holds the value to be searched.
The highest and the lowest value are added and divided by 2,highest and lowest and the first and the last element in the array.
The mid value is then compared with the key.
If mid is equal to the key, then we get the output directly. 
Else if the key is greater then mid then the mid+1 becomes the lowest value and the process is repeated on the shortened array.
If it is not found anywhere, an error message is displayed. 
The time complexity is O(log n).
