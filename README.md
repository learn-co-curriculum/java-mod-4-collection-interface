# Collection Interface

## Learning Goals

- Explain the various methods provided by the `Collection` interface.

## Collection Methods

Here’s the `Collection` interface hierarchy diagram from earlier for reference.
All of the concrete classes indirectly implements the `Collection` interface.
This interface provides a set of general methods that can be used with any of
the implementations.

![Collection Framework Diagram](https://curriculum-content.s3.amazonaws.com/java-mod-4/Collection-Framework-Diagram.png)

Let’s take a look at the most common methods provided by this interface:

- `int size()`: Returns the total number of elements the collection.
- `boolean isEmpty()`: Returns `true` if the collection contains no elements.
- `boolean contains(Object o)`: Returns `true` if the collection contains the
  object specified as the argument.
- `boolean add(E e)`: Adds an element to the collection. It returns `true` if
  the element was added successfully, else it returns `false`.
- `boolean remove(Object o)`: Removes one instance of the specified element.
- `boolean removeAll(Collection<?> collection)`: Removes all elements from the
  current collection that are also present in the the collection provided as the
  argument.
- `void clear()`: Removes all elements from the collection.

We’ll look at several more methods that are provided by the concrete classes in
addition to these base methods explained here.
