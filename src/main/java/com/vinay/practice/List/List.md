#List Interface
The List interface is an ordered collection that allows us to add and remove elements like an array.
 
 
###Properties
1. Elements can be inserted or accessed by their position in the list, using a zero-based index.
2. A list may contain duplicate elements.
3. In addition to the methods defined by Collection, List defines some of its own, which are summarized in the following table.
4. Several of the list methods will throw an UnsupportedOperationException if the collection cannot be modified, and a ClassCastException is generated when one object is incompatible with another.



###Classes that implement List
* ArrayList
* LinkedList
* Vector
* Stack


###Methods of List
The List interface includes all the methods of the Collection interface. Its because Collection is a super interface of List.

Some of the commonly used methods of the Collection interface that's also available in the List interface are:

1. add() - adds an element to a list
2. addAll() - adds all elements of one list to another
3. get() - helps to randomly access elements from lists
4. iterator() - returns iterator object that can be used to sequentially access elements of lists
5. set() - changes elements of lists
6. remove() - removes an element from the list
7. removeAll() - removes all the elements from the list
8. clear() - removes all the elements from the list (more efficient than removeAll())
9. size() - returns the length of lists
10. toArray() - converts a list into an array
11. contains() - returns true if a list contains specified element