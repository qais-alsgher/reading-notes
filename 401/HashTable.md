# Hash Table
A hash table is an implementation of an associative array, a list of key-value pairs that allow you to retrieve a value via a key

###  ways to implement a hash table/associative array in JavaScript.

1. Using the Object Data Type
  There are some downsides to this approach:

    The Object comes with its own properties which could collide with potential key names.
    There no easy way to get the size of a Hash Table stored in an Object, so it must be tracked manually.
    Since they are also property names, the keys used are limited to String or Symbol types.
    Object isn’t optimized for frequent additions and removals of key-value pairs
    
 1. Using a Map Object
    The Map object was created to implement this type of associative array without some of the downsides of using a basic Object:

    There are no pre-existing keys that could result in a collision
      A Map object has a size property to track its contents.
      A Map object can have keys that are any data type.
      A Map has been optimized for repeated addition and insertion of key-value pairs.
      
    A Map object also comes with the following methods:

        .clear() Removes all key-value pairs from the Map object.
        .delete(key) Deletes the key-value pair and returns true if the key exists. Returns false otherwise.
        .get(key) Returns the value associated with key, or undefined if key doesn’t exist.
        .has(key) Returns true if key exists, false otherwise.
        .set(key,value) Sets the value for the key in the Map object and returns the Map object.
