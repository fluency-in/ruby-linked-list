# Ruby: Linked List

Implement a doubly linked list

Like an array, a linked list is a simple linear data structure. Several 
common data types can be implemented using linked lists, like queues, 
stacks, and associative arrays.

A linked list is a collection of data elements called *nodes*. In a 
*singly linked list* each node holds a value and a link to the next node. 
In a *doubly linked list* each node also holds a link to the previous 
node.

You will write an implementation of a doubly linked list. Implement a 
Node to hold a value and pointers to the next and previous nodes. Then 
implement a List which holds references to the first and last node and 
offers an array-like interface for adding and removing items:

* `push` (*insert value at back*);
* `pop` (*remove value at back*);
* `shift` (*remove value at front*).
* `unshift` (*insert value at front*);

To keep your implementation simple, the tests will not cover error 
conditions. Specifically: `pop` or `shift` will never be called on an 
empty list.

If you want to know more about linked lists, check [Wikipedia](https://en.wikipedia.org/wiki/Linked_list).

The tests use the Minitest testing framework. To install it run the command:

    gem install minitest

Run the tests with the `ruby` command:

    ruby linked_list_test.rb

## Resources

If you have never used Minitest, check out [Intro to TDD][tdd] tutorial from Jumpstart Lab.

[tdd]: http://tutorials.jumpstartlab.com/topics/testing/intro-to-tdd.html

## Source

Classic computer science topic

This exercise is from the [Ruby][ruby] track on [Exercism][exercism]

[exercism]: http://exercism.io
[ruby]: http://exercism.io/languages/ruby



