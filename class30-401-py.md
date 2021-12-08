# Hashtables

## Terminology:
1. Hash - A hash is the result of some algorithm taking an incoming string and converting it into a value that could be used for either security or some other purpose. In the case of a hashtable, it is used to determine the index of the array.
2. Buckets - A bucket is what is contained in each index of the array of the hashtable. Each index is a bucket. An index could potentially contain multiple key/value pairs if a collision occurs.
3. Collisions - A collision is what happens when more than one key gets hashed to the same location of the hashtable.

## Why do we need hashtables?
1. Hold unique values
2. Dictionary
3. Library

## Benefit of Hashing
Arrays actually have fast access. If we know the index of the information we want we can access that information in O(1) time. The reason why searching for a piece of data in a collection is O(N) isn’t because the array is slow, it’s just that we have to look through all N things in the collection.
Hash maps take advantage of an array’s O(1) read access. Instead of adding elements to an array from beginning to end, a hash map uses a “hash function” to place each item at a precise index location, based off it’s key.

## Creating a Hash
1. Add or multiply all the ASCII values together.
2. Multiply it by a prime number such as 599.
3. Use modulo to get the remainder of the result, when divided by the total size of the array.
4. Insert into the array at that index.
  
  Example!
  
  Key = "Cat"

  67 + 97 + 116 = 280

  280 * 599 = 69648

  69648 % 1024 = 16

  Key gets placed in index of 16.
  

## Collisions
solved by Calculating hashes and indexes by multiplying the ascii values of each character.

## Internal Methods
1. Add()
When adding a new key/value pair to a hashtable:
2. Find()
The Find takes in a key, gets the Hash, and goes to the index location specified. Once at the index location is found in the array, it is then the responsibility of the algorithm the iterate through the bucket and see if the key exists and return the value.
3. Contains()
The Contains method will accept a key, and return a bool on if that key exists inside the hashtable. The best way to do this is to have the contains call the GetHash and check the hashtable if the key exists in the table given the index returned.
4. GetHash()
The GetHash will accept a key as a string, conduct the hash, and then return the index of the array where the key/value should be placed.

  
