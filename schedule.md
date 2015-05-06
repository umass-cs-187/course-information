# Course Schedule

You should consult the [UMass academic calendar][umasscal] to make
sure you are aware of important dates and events. The following are
the weekly topics that will be covered during this course. Be aware
that the schedule is subject to change during the semester at the
instructor's discretion.

In order to cover the same amount of material required by the regular
semester course in a shorter period of time we will be following a
fairly strict and intensive schedule. Course material will be provided
on the Sunday of each week during the course. This will include any
reading, presentation material/video that you will be required to
view, possible activities that you will complete, and discussion
questions that you will be required to contribute toward. The
assignments and exercises for the next week will also be made
available on Sunday and be due by midnight of the following Sunday.

[umasscal]: https://www.umass.edu/gradschool/current-students/academic-calendar/academic-year-2014-2015

## Course Schedule

### Part 1: Overview and Abstract Data Types

**Week 01: Getting Organized and Abstract Data Types**

This week we will be covering Chapter's 1 and 2 from the book
Object-Oriented Data Structures Using Java, Third Edition. In
particular, we will be studying the basic structuring mechanisms
provided by Java, what data structures are, how to organize classes, a
little about software engineering, an overview of abstraction and why
it is important, Java interfaces, the `StringLog` abstract data type
(ADT), and how the `StringLog` interface can be implemented using
arrays and linked lists.

### Part 2: Stacks, Recursion, and Queues

**Week 02: The Stack ADT**

This week we will be focusing on the Stack ADT.  We will explore the
fundamentals of stacks and Java collections in general.  We will look
at Java parameterized classes also known as “Java Generics”.  We will
study the formal specification of the Stack ADT using Java interfaces.
We will investigate an implementation of a bounded stack using arrays
and an unbounded stack using linked lists.  We will look at an
application of stacks by learning about well formed expressions and
using a stack to test them.

**Week 03: Recursion**

This week we will be focusing on the idea of Recursion.  We will look
at why recursion is important and how it can be used to solve problems
that could be more difficult to solve iteratively. Recursion is an
elegant way of expressing algorithms to certain types of problems. It
is not suited to all problems and it can often lead to poor
performance - yet provide a deep understanding to the problem at hand.
So, why study recursion at all? The reason why we look at recursion is
because it provides a window into looking at how to solve problems
from a different perspective. In particular, it focuses on solving
problems through a common technique known as divide and conquer. That
is, we solve a problem by trying to solve smaller sub-problems. In the
case of recursion, it happens to be trying to solve the same problem
in smaller parts.

**Week 04: The Queue ADT**

This week we will be focusing on the Queue ADT. We will look at the
formal specification of queues using three different interfaces - a
generic queue and bounded and unbounded forms that extend the generic
queue.  We will explore two different implementations using arrays and
linked lists for both bounded and unbounded versions. You will study
two different applications using queues (and stacks): palindromes and
the card game of war. We will discuss concurrent programming in Java
using threads and the synchronization of variables. You will
investigate a program using queues to determine average waiting times.

### Part 3: Lists and Binary Search Trees

**Week 05: The List ADT**

This week we will be focusing on the List ADT. We will look at the
formal specification of lists and as we have done before investigate
two implementations of a list ADT: an array-based and reference-based
implementation. As part of our exploration of lists we will cover how
to compare objects using the `equals()` method and the `Comparable`
interface - this will be useful for object comparisons for ordering.
We will learn how to store object data into external files using text
and binary serialization using the `Serializable` interface.  Lastly, we
will cover the binary search algorithm using lists.

**Week 06: More Lists**

This week will extend your knowledge on variants of linked lists.  We
will look at circular linked lists, doubly linked lists, list with
headers and trailers, and array-based linked lists.

**Week 07: Binary Search Trees**

This week we will combine binary search with linked lists to create
binary search trees. We learned in past weeks that linear search of a
linked list is an O(N) operation.  We also learned that binary search
could find an element in a sorted list stored sequentially in an
array. The binary search operation is an O(log2N) operation. It would
be nice if we could use binary search with linked lists, however, how
do we find the midpoint of a linked list of nodes?  It turns out that
there is no practical way of doing this, however, we can reorganize
the list elements into a linked structure that is perfect for binary
search: the binary search tree.

### Part 4: Priority Queues, Heaps, Sorting, and Search

**Week 08: Priority Queues, Heaps, and Graphs**

This week we will consider how additional branching structures are
defined and implemented to support a variety of applications.  In
particular, we will investigate priority queues that allow access to
elements that have the highest priority, heaps which are an
implementation of priority queues that use a binary tree to enforce
shape and order, and graphs which allow us to represent useful
relationships that are not hierarchical.

**Week 09: Sorting and Searching Algorithms**

For much of this course we have focused on keeping lists in sorted
order. One important reason for doing this is to facilitate
searching - given an appropriate ADT implementation an element in a
list can be found faster if the list is sorted.  This week we examine
directly strategies for both sorting and searching. In particular, we
will investigate three simple sorting algorithms: selection sort,
bubble sort, and insertion.  We will then explore three additional
sorting algorithms that are more efficient: merge sort, quick sort,
and heap sort.  We will also cover general issues related to sorting
objects. Lastly, we will discuss some details related to hashing, an
approach allowing the quick storage and retrieval of information
quickly under certain conditions.


