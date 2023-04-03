# Activities

## Task 1

> Refer to the following links while discussing the answer.

- What is the difference between `array` and `std::array`
std::array-It has friendly value semantics, so that it can be passed to or returned from functions by value. Its interface makes it more convenient to find the size, and use with STL-style iterator-based algorithms.
A std::array is a very thin wrapper around a C-style array
  https://stackoverflow.com/questions/30263303/stdarray-vs-array-performance
- What is the difference between `std::array` and `std::vector`
  https://www.softwaretestinghelp.com/arrays-in-stl/
- What is the difference between `std::list` and `std::vector`
Lists-The list is a container that overcomes this drawback of the array and vector containers. It allows us to insert elements anywhere in the list without causing much of an overhead. But lists are slower than vectors as far as traversal is concerned.
  https://www.softwaretestinghelp.com/lists-in-stl/

## Task 2

- Run the Stack and Queue examples in the following link
  https://www.softwaretestinghelp.com/stacks-and-queues-in-stl/

> make sure you correct the syntax e.g `&lt;int&gt; becomes  <int>`

## Task 3

- Discuss the different types of iterators present in C++. You can refer to the following link
 Types of iterators: Based upon the functionality of the iterators, they can be classified into five major categories:

    Input Iterators: They are the weakest of all the iterators and have very limited functionality. They can only be used in a single-pass algorithms, i.e., those algorithms which process the container sequentially, such that no element is accessed more than once.
    Output Iterators: Just like input iterators, they are also very limited in their functionality and can only be used in single-pass algorithm, but not for accessing elements, but for being assigned elements.
    Forward Iterator: They are higher in the hierarchy than input and output iterators, and contain all the features present in these two iterators. But, as the name suggests, they also can only move in a forward direction and that too one step at a time.
    Bidirectional Iterators: They have all the features of forward iterators along with the fact that they overcome the drawback of forward iterators, as they can move in both the directions, that is why their name is bidirectional.
    Random-Access Iterators: They are the most powerful iterators. They are not limited to moving sequentially, as their name suggests, they can randomly access any element inside the container. They are the ones whose functionality are same as pointers.
  https://www.geeksforgeeks.org/introduction-iterators-c/
- What are the Benefits of Iterators
An iterator is an object (like a pointer) that points to an element inside the container. We can use iterators to move through the contents of the container. They can be visualized as something similar to a pointer pointing to some location and we can access the content at that particular location using them. Iterators play a critical role in connecting algorithm with containers along with the manipulation of data stored inside the containers. The most obvious form of an iterator is a pointer. A pointer can point to elements in an array and can iterate through them using the increment operator (++). But, all iterators do not have similar functionality as that of pointers. Depending upon the functionality of iterators they can be classified into five categories, as shown in the diagram below with the outer one being the most powerful one and consequently the inner one is the least powerful in terms of functionality.

benefits-
Ease in programming: It is convenient to use iterators rather than using a subscript operator[] to access the elements of a container. If we use subscript operator[] to access the elements, then we need to keep the track of the number of elements added at the runtime, but this would not happen in the case of an iterator.

Code Reusability: A code can be reused if we use iterators. In the above example, if we replace vector with the list, and then the subscript operator[] would not work to access the elements as the list does not support the random access. However, we use iterators to access the elements, then we can also access the list elements.
Dynamic Processing: C++ iterators provide the facility to add or delete the data dynamically.

## Links

- https://cpp.sh/
