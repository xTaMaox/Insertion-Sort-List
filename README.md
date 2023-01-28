# Insertion-Sort-List

Given the head of a singly linked list, sort the list using insertion sort, and return the sorted list's head.

The steps of the insertion sort algorithm:

Insertion sort iterates, consuming one input element each repetition and growing a sorted output list.
At each iteration, insertion sort removes one element from the input data, finds the location it belongs within the sorted list and inserts it there.
It repeats until no input elements remain.
The following is a graphical example of the insertion sort algorithm. The partially sorted list (black) initially contains only the first element in the list. One element (red) is removed from the input data and inserted in-place into the sorted list with each iteration.

![Insertion-sort-example-300px](https://user-images.githubusercontent.com/88260025/215275459-2bccb17a-a447-4bbe-91c4-b59eb303b549.gif)

Example 1:

![sort1linked-list](https://user-images.githubusercontent.com/88260025/215275490-7caf52b6-9c1c-4e60-9a44-94ac75a4dd71.jpg)

Input: head = [4,2,1,3]
Output: [1,2,3,4]

Example 2:

![sort2linked-list](https://user-images.githubusercontent.com/88260025/215275516-415283f3-6037-429f-b609-6f609f59efec.jpg)

Input: head = [-1,5,3,4,0]
Output: [-1,0,3,4,5]
 

Constraints:

The number of nodes in the list is in the range [1, 5000].
-5000 <= Node.val <= 5000
