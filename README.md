# SculeJS

## What is SculeJS?

*SculeJS* (from Minuscule - pronounced **skyul**) is a JavaScript library emulating the functionality of [MongoDB](http://www.mongodb.org/). It's also
much more than that; *SculeJS* includes implementations of many general purpose data structures that can be used by developers in their day-to-day work.

I originally built [JSONDB](https://github.com/irlgaming/jsondb-public "JSONDB") for use in Titanium Appcelerator apps, but over time
it became apparent that a similar system could be really useful for other stuff as well. *SculeJS* can run in your web browser, in a NodeJS 
process, or even inside iOS and Android applications including a JavaScript runtime environment.

*SculeJS* provides a high-performance NoSQL database with the following features:

* Document-oriented storage
* Support for sparse B+tree and Hash indexes
* Fast in-place updates
* Rich document based queries
* Support for Map/Reduce operations
* Support for geo-locational queries using the $where and $near operators

Data structures currently included in *SculeJS* are:

* [Hash Map](http://en.wikipedia.org/wiki/Hash_Table  "Hash Map")
* [Hash Table](http://en.wikipedia.org/wiki/Hash_Table "Hash Table")
* [Binary Search Tree](http://en.wikipedia.org/wiki/Binary_Search_Tree "Binary Search Tree")
* [B+ Tree](http://en.wikipedia.org/wiki/B%2B_tree "B+ Tree")
* [Linked List](http://en.wikipedia.org/wiki/Linked_List "Linked List")
* [Doubly Linked List](http://en.wikipedia.org/wiki/Linked_List#Doubly_linked_list "Doubly Linked List")
* [Caching Linked List](http://en.wikipedia.org/wiki/Linked_List "Caching Linked List")
* [LRU Cache](http://en.wikipedia.org/wiki/LRU_cache#Least_Recently_Used "LRU Cache")
* [LIFO Stack](http://bit.ly/v0kKey "LIFO Stack")
* [FIFO Stack](http://bit.ly/v0kKey "FIFO Stack")
* [Queue](http://bit.ly/v0kKey "Queue")

## How does it work?

*SculeJS* stores collections of JavaScript objects in memory and uses a [Hybrid Virtual Machine](http://en.wikipedia.org/wiki/Virtual_machine "Virtual Machine") to process query expressions.
Using *SculeJS* to perform queries is actually pretty similar to using the MongoDB query shell - most operators are supported.

Collections can be persisted to disk (using LocalStorage in the browser), or other storage mediums using custom storage managers. At the time of writing I'm working on
support for [IndexDB](http://www.w3.org/TR/IndexedDB/ "IndexDB") and [WebSQL](http://en.wikipedia.org/wiki/Web_SQL_Database "WebSQL") storage engines.

## Can I contribute/donate/help in some way?

I'm still working on the process to enable users to contribute patches and features to the project, but sure, I'd be happy to have some
help. Donations aren't necessary - if you use *SculeJS* and love it then tell your friends, just getting the word out would be a huge help.

I have a full time job and maintain *SculeJS* in my spare time, so if I don't get to your tickets immediately please don't take it personally.