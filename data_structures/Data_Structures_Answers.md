For each of the methods associated with each data structure, classify it based on its runtime, using Big O notation.

## Linked List

1.  What is the runtime complexity of `addToTail`?

    a. What if our list implementation didn't have a reference to the tail of the list in its constructor? What would be the runtime of the `addToTail` method?

2.  What is the runtime complexity of `removeHead`?

3.  What is the runtime complexity of `contains`?

4.  What is the runtime complexity of `getMax`?

## Queue

1.  What is the runtime complexity of `enqueue`?

2.  What is the runtime complexity of `dequeue`?

3.  What is the runtime complexity of `isEmpty`?

4.  What is the runtime complexity of `length`?

## Doubly Linked List

1.  What is the runtime complexity of `ListNode.insertAfter`?

2.  What is the runtime complexity of `ListNode.insertBefore`?

3.  What is the runtime complexity of `ListNode.delete`?

4.  What is the runtime complexity of `DoublyLinkedList.addToHead`?

5.  What is the runtime complexity of `DoublyLinkedList.removeFromHead`?

6.  What is the runtime complexity of `DoublyLinkedList.addToTail`?

7.  What is the runtime complexity of `DoublyLinkedList.removeFromTail`?

8.  What is the runtime complexity of `DoublyLinkedList.moveToFront`?

9.  What is the runtime complexity of `DoublyLinkedList.moveToBack`?

10. What is the runtime complexity of `DoublyLinkedList.delete`?

    a. Compare the runtime of the doubly linked list's `delete` method with the worst-case runtime of the `Array.splice` method. Which method generally performs better?

## Binary Search Tree

1.  What is the runtime complexity of `insert`?

2.  What is the runtime complexity of `contains`?

3.  What is the runtime complexity of `getMax`?

4.  What is the runtime complexity of `depthFirstForEach`?

5.  What is the runtime complexity of `breadthFirstForEach`?

6.  [Stretch Question] What is the runtime complexity of your `checkBalanced` function?

## Heap

1.  What is the runtime complexity of your `heapsort` function?
    worst case: O(n log n)
    best case: O(n log n)
    avg: O(n log n)

2.  What is the space complexity of the `heapsort` function? Recall that your implementation should return a new array with the sorted data. What would be the space complexity if your function instead altered the input array?
    unaltered array: O(1)
    altered array: O(2)

3.  What is the runtime complexity of `bubbleUp`? O(n)

4.  What is the runtime complexity of `siftDown`? O(n)

5.  What is the runtime complexity of `insert`? O(n)

6.  What is the runtime complexity of `delete`? O(1)

7.  What is the runtime complexity of `getMax`? O(1)
