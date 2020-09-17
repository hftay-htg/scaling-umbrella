# code-challenge

Instructions:

Given an n x n array, write a function that returns the array elements arranged from outermost elements to the middle element, traveling clockwise.

```
array = [[1,2,3],
	 [4,5,6],
	 [7,8,9]]

arrange(array) #=> [1,2,3,6,9,8,7,4,5]
```

For better understanding, please follow the numbers of the next array consecutively:

```
array = [[1,2,3],
	 [8,9,4],
	 [7,6,5]]

arrange(array) #=> [1,2,3,4,5,6,7,8,9]
```
This image will illustrate things more clearly:
  
![img-snl](https://user-images.githubusercontent.com/71165417/93446840-428ddc00-f904-11ea-8605-112792dc61f6.png)


Note: The idea is not sort the elements from the lowest value to the highest; the idea is to traverse the 2-d array in a clockwise pattern.
