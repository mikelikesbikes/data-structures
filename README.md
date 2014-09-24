# The Data Structures Challenge

I'm setting myself a challenge: implement 42 data structures in 42 days.

## The reason

The real killer insights of CS are in data structures and algorithms. I've done project-specific implementations of various simple structures, and I know a bit in abstract about more complex structures like bloom filters from reading source code. But I know my work would benefit greatly from a thorough grounding in data structures. I'm fed up with not knowing enough, so I'm fixing it. Abstract learning is not sufficient - I want to cement the knowledge by _doing_.

## The structures

Enough talk: here's the unordered list (cobbled together from Stack Overflow posts) with wiki links.

### Array-like structures

*   [Queue](http://en.wikipedia.org/wiki/Queue_%28abstract_data_type%29)
*   [Priority queue](http://en.wikipedia.org/wiki/Priority_queue)
*   [Deque](http://en.wikipedia.org/wiki/Deque)
*   [Double-ended priority queue](http://en.wikipedia.org/wiki/Double-ended_priority_queue)
*   [Stack](http://en.wikipedia.org/wiki/Stack_(data_structure%29)
*   [Linked list](http://en.wikipedia.org/wiki/Linked_list)
*   [Work-stealing queue](http://supertech.csail.mit.edu/papers/steal.pdf)
*   [Suffix array](http://en.wikipedia.org/wiki/Suffix_array%E2%80%8E)
*   [Disjoint set](http://en.wikipedia.org/wiki/Disjoint-set_data_structure)
*   [Sparse array](http://en.wikipedia.org/wiki/Sparse_array)
*   [Sparse matrix](http://en.wikipedia.org/wiki/Sparse_matrix)

### Graphical structures

#### Basic

*   [Graph](http://en.wikipedia.org/wiki/Graph_(abstract_data_type%29)
*   [Directed graph](http://en.wikipedia.org/wiki/Directed_graph)
*   [Directed acyclic graph](http://en.wikipedia.org/wiki/Directed_acyclic_graph)

#### Heaps

*   [Heap](https://en.wikipedia.org/wiki/Heap_(data_structure%29)
*   [Binary heap](http://en.wikipedia.org/wiki/Binary_heap)
*   [Fibonacci heap](http://en.wikipedia.org/wiki/Fibonacci_heap)

#### Trees

*   [Tree](http://en.wikipedia.org/wiki/Tree_(data_structure%29)
*   [Trie (radix tree)](http://en.wikipedia.org/wiki/Trie)
*   [Binary tree](http://en.wikipedia.org/wiki/Binary_tree)
*   [Binary search tree](http://en.wikipedia.org/wiki/Binary_search_tree)
*   [Weight balanced tree](http://en.wikipedia.org/wiki/Weight-balanced_tree)
*   [Self-balancing binary search tree](http://en.wikipedia.org/wiki/Self-balancing_binary_search_tree)
*   [B-tree](http://en.wikipedia.org/wiki/B-tree)
*   [B+tree](http://en.wikipedia.org/wiki/B%2B_tree)
*   [Rope](http://en.wikipedia.org/wiki/Rope_(data_structure%29)
*   [Decision tree](http://en.wikipedia.org/wiki/Decision_tree)
*   [Treap](http://en.wikipedia.org/wiki/Treap)
*   [R-tree](http://en.wikipedia.org/wiki/R-tree)
*   [Huffman tree](http://en.wikipedia.org/wiki/Huffman_coding)
*   [Merkle tree](http://en.wikipedia.org/wiki/Merkle_tree)
*   [Min-max heap](http://en.wikipedia.org/wiki/Min-max_heap)
*   [Fenwick tree](http://en.wikipedia.org/wiki/Fenwick_tree)
*   [Suffix tree](http://en.wikipedia.org/wiki/Suffix_tree)
*   [Suffix trie](http://www.cs.cmu.edu/%7Eckingsf/bioinfo-lectures/suffixtrees.pdf) (note: PDF link, no wiki article)
*   [Splay tree](http://en.wikipedia.org/wiki/Splay_tree)
*   [Ternary tree](http://en.wikipedia.org/wiki/Ternary_tree)

### Probabilistic and streaming structures

*   [Bloom filter](http://en.wikipedia.org/wiki/Bloom_filter)
*   [Quotient filter](http://en.wikipedia.org/wiki/Quotient_filter)
*   [Skip list](http://en.wikipedia.org/wiki/Skip_list)
*   [Counting bloom filter](http://en.wikipedia.org/wiki/Bloom_filter#Counting_filters)
*   [Count-Min sketch](http://en.wikipedia.org/wiki/Count%E2%80%93min_sketch)

Whew! A pretty long list. But many of these build on one another, so that many will inherit from their parent structures. The challenge is less daunting than it might appear at first.

Of course, some of these structures might be prohibitively slow in pure Ruby. I'm thinking in particular of bloom-filters and count-min sketches. But I'm going to go ahread an implement them in Ruby so that I understand them. Then, if performance is weak, I can rewrite in C and use Ruby bindings.

I'm also interested in implementing [lock-free](http://en.wikipedia.org/wiki/Non-blocking_algorithm) versions of as many of the above as possible. I couldn't find a nice list of structures with lock-free implementations, so I'll expand this point as I learn more..

### The end

This is a living document - I will update with links to explanatory posts and code as I complete them. I will also structure and annotate the list as I learn more about the structures.

Have I missed an important structure? Is one of these redundant? Suggestions/corrections to this list are welcome.

See you on the other side!