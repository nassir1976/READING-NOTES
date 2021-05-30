[*HOME*](https://nassir1976.github.io/reading-notes/)

## Readnote-30  Implementation: Hash Tables


### What is a Hashtable?
- Hashtables is a data structure that utilize key value pairs. This means every Node or Bucket has both a key, and a value.

### Hash

- A hash is the result of some algorithm taking an incoming string and converting it into a value that could be used for either security or some other purpose. In the case of a hashtable, it is used to determine the index of the array.

### buckets

- A bucket is what is contained in each index of the array of the hashtable. Each index is a bucket. An index could potentially contain multiple key/value pairs if a collision occurs.

### collisions

- A collision is what happens when more than one key gets hashed to the same location of the hashtable.

### How to hash?
- An element is converted into an integer by using a hash function. This element can be used as an index to store the original element, which falls into the hash table.

- The element is stored in the hash table where it can be quickly retrieved using hashed key.

              hash = 
              hashfunc(key)
              index = hash % 
              array_size

### Internal Methods
  - add() adding a new key value pair to the hashtable

   - find() find the index by taking the key

   - contains() taking the taking will return boolean if exists

  - getHash() taking a key will hash and return index to put key

