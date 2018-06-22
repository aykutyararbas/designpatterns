# designpatterns
GOF Design Patterns in Java

Thanks to 
https://en.wikipedia.org/wiki/Design_Patterns

Erich Gamma, 
Richard Helm, 
Ralph Johnson and John Vlissides


## Solution and Pattern

A recursive composition is a hierarchical structure of elements, that builds "increasingly complex elements out of simpler ones" (pp36). Each node in the structure knows of its own children and its parent. If an operation is to be performed on the whole structure, each node calls the operation on its children (recursively).

This is an implementation of the composite pattern, which is a collection of nodes. The node is an abstract base class, and derivatives can either be leaves (singular), or collections of other nodes (which in turn can contain leaves or collection-nodes). When an operation is performed on the parent, that operation is recursively passed down the hierarchy.


