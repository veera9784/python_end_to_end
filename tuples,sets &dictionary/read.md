Tuples
In Python tuples are very similar to lists, however, unlike lists they are immutable meaning they can not be changed.

You would use tuples to present things that shouldn't be changed, such as days of the week, or dates on a calendar.

You'll have an intuition of how to use tuples based on what you've learned about lists. We can treat them very similarly with the major distinction being that tuples are immutable.

Constructing Tuples
The construction of a tuples use () with elements separated by commas.


Tuple Indexing
Indexing work just like in lists.

A tuple index refers to the location of an element in a tuple.

Remember the indexing begins from 0 in Python.

The first element is assigned an index 0, the second element is assigned an index of 1 and so on and so forth.


Tuple Slicing
We can use a : to perform slicing which grabs everything up to a designated point.

The starting index is specified on the left of the : and the ending index is specified on the right of the :.

Remember the element located at the right index is not included.




When to use Tuples
You may be wondering, "Why bother using tuples when they have fewer available methods?" To be honest, tuples are not used as often as lists in programming, but are used when immutability is necessary. If in your program you are passing around an object and need to make sure it does not get changed, then a tuple becomes your solution. It provides a convenient source of data integrity.

You will find them often in functions when you are returning some values

You should now be able to create and use tuples in your programming as well as have an understanding of their immutability.




Sets
Sets are an unordered collection of unique elements. We can construct them by using the set() function.

Sets cannot have duplicates.

Sets are mutable just like lists.

You can create a non-empty set with curly braces by specifying elements separated by a comma.
