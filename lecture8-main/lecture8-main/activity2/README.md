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
  https://www.geeksforgeeks.org/introduction-iterators-c/
- What are the Benefits of Iterators
An iterator is an object (like a pointer) that points to an element inside the container. We can use iterators to move through the contents of the container. They can be visualized as something similar to a pointer pointing to some location and we can access the content at that particular location using them. Iterators play a critical role in connecting algorithm with containers along with the manipulation of data stored inside the containers. The most obvious form of an iterator is a pointer. A pointer can point to elements in an array and can iterate through them using the increment operator (++). But, all iterators do not have similar functionality as that of pointers. Depending upon the functionality of iterators they can be classified into five categories, as shown in the diagram below with the outer one being the most powerful one and consequently the inner one is the least powerful in terms of functionality.
## Links

- https://cpp.sh/
