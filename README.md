# Swift 4 Generic Doubly Linked List
My generic doubly linked list in an Xcode 9 playground and written in Swift 4.

In the [tutorial on my blog](http://iosbrain.com/blog/2018/10/04/building-a-generic-doubly-linked-list-using-protocol-oriented-swift-4/), I'll show you how to develop a list on steroids, i.e., a generic doubly linked list in Swift. For our purposes here, a _list_ is a software receptacle that contains related data that we're interested in inspecting, organizing, manipulating, etc. A doubly linked list stores a list of "nodes." Each node contains data, knows about the preceding node in the list, and knows about the following node in the list. We'll talk about adding nodes to the list, removing nodes from the list, displaying information stored in nodes in the list, and traversing the list. I've used the term _generic_ because you'll see that I can store store every built-in or custom Swift type in my linked list.

Here's a diagram that conceptualizes the doubly linked list _data structure_:

![alt text][logo1]

[logo1]: http://iosbrain.com/wp-content/uploads/2018/10/Doubly_Linked_List.png "Doubly Linked List"

-------
Copyright (c) 2018 Andrew L. Jaffee, microIT Infrastructure, LLC, and iosbrain.com.
