# AllAboutArrays

The goal of this repo is to compile all kinds of exercies with arrays that represent some learning concept related to arrays and demo of how that concept is used.



##### FROM edX

The simplest linear data structure: arrays.

 Arrays are collections of elements of the same type, either primitive data types or objects of class types. 

Arrays have an attribute length, which helps us traverse arrays with for/while loops.

 Nevertheless, arrays have an important limitation: once the capacity is set it cannot be modified. 

Therefore, we cannot store in arrays more elements than the number defined in their capacity.

 While accessing any element in an array takes roughly the same amount of time, operations such as concatenating or splitting arrays are computationally expensive. 

Inserting an element in a given position of the array is also computationally expensive as it requires shifting to the right all the remaining elements from that position to the end of the array.

Recent Java versions allow working with generics, which serve to define the data types a class can handle. 

Generics are particularly relevant when working with data structures, as we can indicate what type of objects can be stored in the data structure, and check at compile time that everything is correct.

 Generics add stability to our code and act as a safety measure precluding from having errors at runtime due to incompatible types. It is important to note that errors at runtime are much more problematic than errors at compile time. We can use Java classes that make use of generics, but we can also define our own classes to make use of generics, as we saw with examples throughout this week...

Linked lists are linear data structures that overcome some of the limitations of arrays.

 They can be extended to store a non-predefined number of elements, and allow inserting elements, concatenating and splitting lists with much less effort than in the case of arrays. The access to certain elements of the linked list takes, however, more effort than in the case of arrays, due to the need of traversing the list until the desired position. Linked Lists can be traversed in one way (singly linked lists, where each node has a reference to the next node) or in two ways (doubly linked lists, where each node has a reference to the next and to the previous nodes).


Finally, this week also introduced some important Java interfaces and classes which helps us work with linear data structures. 

These were the interfaces Collection<E> and List<E>, and the classes LinkedList<E> and ArrayList<E>. Some of the main methods of these classes and interfaces have been explored in this week with specific exercises, although there are many more methods that could not be covered due to lack of time. We invite you to delve into the APIs for these classes and interfaces, and test the different methods to understand them better.
