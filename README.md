## COEN 79 Lab 9
<b>The Assignment:</b>
Implement the bag template class using a binary search tree to store the items.

<ul>Binary Search Tree (BST) storage rules:
<li>The entry in node n is never less than an entry in its left subtree (though it may be
equal to one of these entries)</li>
<li>The entry in node n is less than every entry in its right subtree</li>
</ul>

BSTs also can store a collection of strings, or real numbers, or anything that can be compared using some sort of less-than comparison. This provides higher search efficiency compared to the implementations using array or linked-list. The higher efficiency of searching in a BST motivates us to implement the bag class with a BST.


<ul>Invariants:
  <li>The items in the bag are stored in a binary search tree</li>
<li>The root pointer of the binary search tree is stored in the member variable root_ptr (which may be NULL for an empty tree)>/li>
</ul>

<ol><b>Files that you must complete:</b>
  <li>bag_bst.h</li>
  <li>bintree.h</li>
</ol>

<ol><b>Other files that you may find helpful:</b>
  <li>bagtest.cpp: A simple interactive test program.</li>
  <li>bagexam.cpp: A test program that will be used to grade the correctness of your bag
class.</li>
  </ol>
