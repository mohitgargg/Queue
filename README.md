# Queue-using-array<br>
<b><ins>How to implement Queue using Array?</b></ins><br>
To implement a queue using an array, <br>

1.create an array arr of size n<br>
2.take two variables front and rear both of which will be initialized to 0 which means the queue is currently empty. <br>
3.Element rear is the index up to which the elements are stored in the array<br>
4.Element front is the index of the first element of the array. <br>
<br>
# Some of the implementations of queue operations are as follows: <br>
1.<b>Enqueue:</b> Addition of an element to the queue. Adding an element will be performed after checking whether the queue is full or not. If rear < n which indicates that the array is not full then store the element at arr[rear] and increment rear by 1 but if rear == n then it is said to be an Overflow condition as the array is full.<br>
2.<b>Dequeue:</b> Removal of an element from the queue. An element can only be deleted when there is at least an element to delete i.e. rear > 0. Now, the element at arr[front] can be deleted but all the remaining elements have to shift to the left by one position in order for the dequeue operation to delete the second element from the left on another dequeue operation.<br>
3.<b>Front:</b> Get the front element from the queue i.e. arr[front] if the queue is not empty.<br>
4.<b>Display:</b> Print all elements of the queue. If the queue is non-empty, traverse and print all the elements from the index front to rear.<br>
<br>
<br>
![image](https://user-images.githubusercontent.com/125802204/234173572-3073a47e-e125-43cc-b3cb-96961f75499b.png)
<br>
