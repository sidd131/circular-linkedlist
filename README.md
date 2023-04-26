# circular-linkedlist
Introduction
A circular linked list is a list in which the nodes are connected in a sequence, where the last node always points to the head (first) node of the linked list. Generally, the last node in a singly or doubly linked list contains NULL, which means the end of the list. However, the circular linked lists do not have any end as the last node always points to the first node of the linked list which makes it circular.

We must be cautious when navigating circular linked lists to avoid endlessly exploring the list. It should be noted that, unlike normally linked lists, circularly linked lists do not have any nodes with a NULL pointer, every node has a next node in a linear sequence.
Advantages of circular linked list in C
Any node of the list can act as the head as the list does not end.
Access to the first node from the last node is easy and time-saving.
Queues can be easily implemented with a circular linked list.
We can traverse the whole list from any node.

 ![image](https://user-images.githubusercontent.com/125429673/234379689-6be7d5b9-610b-4afb-8dc0-e5646dce44cf.png)
