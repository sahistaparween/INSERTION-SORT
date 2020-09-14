# INSERTION-SORT

Insertion sort is a simple sorting algorithm that works similar to the way you sort playing cards in your hands. The array is virtually split into a sorted and an unsorted part. Values from the unsorted part are picked and placed at the correct position in the sorted part.

# Approach for insertion sort

The first element in the array is assumed to be sorted. Take the second element and store it separately in key.

Compare key with the first element. If the first element is greater than key, then key is placed in front of the first element.





Now, the first two elements are sorted.

Take the third element and compare it with the elements on the left of it. Placed it just behind the element smaller than it. If there is no element smaller than it, then place it at the beginning of the array.



Similarly, place every unsorted element at its correct position.



# Time Complexities
#  Worst Case Complexity: O(n2)

Suppose, an array is in ascending order, and you want to sort it in descending order. In this case, worst case complexity occurs.

Each element has to be compared with each of the other elements so, for every nth element, (n-1) number of comparisons are made.

Thus, the total number of comparisons = n*(n-1) ~ n2


#  Best Case Complexity: O(n)


When the array is already sorted, the outer loop runs for n number of times whereas the inner loop does not run at all. So, there are only n number of comparisons. Thus, complexity is linear.


#  Average Case Complexity: O(n2)


It occurs when the elements of an array are in jumbled order (neither ascending nor descending).



# Space Complexity

Space complexity is O(1) because an extra variable key is used.


# Insertion Sort Applications
The insertion sort is used when:
The array is has a small number of elements
There are only a few elements left to be sorted



# LINKS FOR REFERENCE
1.JENNY'S LECTURE
https://www.youtube.com/watch?v=yCxV0kBpA6M

