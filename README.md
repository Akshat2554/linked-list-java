# Linked List — Java

A singly linked list implementation built from scratch in Java.
No built-in Java libraries used. Every method written manually
as part of building up my data structures foundation.

## Methods

- **insert** — adds a new node to the end of the list
- **delete** — removes a node by value, handles head and middle/end cases
- **search** — returns true if a value exists in the list, false if not
- **print** — traverses the list and prints every node's value

## What I learned

Deleting a node isn't just removing it, you have to make the previous 
node skip over it by pointing to the one after. Getting that pointer 
manipulation right took a few tries.

## How to run

javac LinkedList.java
java LinkedList

## Language
Java