##Descriptions of Iterators

###Instructions
Below you will find a list of methods. In the space provided below each, please provide a brief description of what this method does based upon your review of the Docs. 

###Array methods:
May be helpful to look in [Enumerable](http://ruby-doc.org/core-2.2.0/Enumerable.html) as well...

####select: 
Returns an array with all elements that meet the condition of the block to be true.
if there is no block returns original array.

####reject:Returns an array with all elements that meet the condition of the block to be false.
if there is no block returns original array.

####map: Returns a new array with the results of running block once for every element in enum

####detect: runs the block for each entry and returns the 'first' for which the block is true or returns nil otherwise. doesnot return array.

####inject: inject is like reduce.. applies the block on two at a time

####partition: returns 2 arrays, the first array has contents that evaluates the block to be true and the 2nd array with rest

If no block is given, an enumerator is returned instead.

####sort: returns array

####one: returns true only if one element meets the block. returns true
returns false if more than one meets the block

####none:Passes each element of the collection to the given block. The method returns true if the block never returns true for all elements. If the block is not given, none? will return true only if none of the collection members is true.

####all:Passes each element of the collection to the given block. The method returns true if the block never returns false or nil. If the block is not given, Ruby adds an implicit block of { |obj| obj } which will cause all? to return true when none of the collection members are false or nil.

####empty?:

####eql?:Returns true if self and other are the same object, or are both arrays with the same content.

####include?: Returns true if any member of enum equals obj. Equality is tested using ==.

####nil?:

###Hash methods:

####key?:Returns true if the given key is present in hsh

####keys:Returns a new array populated with the keys from this hash. See also Hash#values.

####delete:Deletes the key-value pair and returns the value from hsh whose key is equal to key. If the key is not found, returns the default value. If the optional code block is given and the key is not found, pass in the key and return the result of block.

####delete_if:Deletes every key-value pair from hsh for which block evaluates to true.

If no block is given, an enumerator is returned instead.
returns the original array with whatever is left after deleting