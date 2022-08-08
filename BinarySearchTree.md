<h1>Binary Search Tree</h1>




<h2>Description</h2>
<b>A Binary Search Tree is a node-based binary tree data structure which has the following properties:
</b>
<br />
<br />

- The left subtree of a node contains only nodes with keys lesser than the node's key
- The right subtree of a node contains only nodes with keys greater than the node's key
- The left and right subtree each must also be a binary search tree
- There must be no duplicate nodes

<p align="center">
<img src="https://media.geeksforgeeks.org/wp-content/uploads/BSTSearch.png" height="85%" width="85%" alt=""/>
</p>

The above properties of Binary Serach Tree provides an ordering among keys so that 
the operations like search, minmum, and maximum can be done fast. If there is no 
ordering, then we may have to compare every key to serach for a given key
<br />
<br />

<h2>How to serach a key in given Binary Tree</h2>

</p>

For searching a value, if we had a sorted array we could have performed a binary 
serach. Lets say we want to search a number in the array, in binary search, we first 
define the complete list as our search space, the number can exist only within the 
search space. 

Now we compare the number to be searched or the element to be searched with the 
middle element (median) of the serach space and if the record being serached is 
less than the middle element, we go seaching in the left half, else we go seraching
in the right half, in case of equality we have found the element.

In binary search, we start with 'n' elements in search space and if the mid element 
is not the element that we are looking for, we reduce the search space to 'n/2'. We 
keep reducing the search space until we either find the record that we are looking for
or we get to only element in serach space and be done with this whole reduction.

Search operations in binary serach trees will be very similar. Lets say we want to 
serach for the number, we start at the root, and then we compare the vlaue to be searched
eith the value of the root, if it's equal we are done with the serach, if its smaller
we know that we need to go to the left subtree becaue in a binary serach tree all the
elements in the left subtree are smaller, and all the elements in the right subtee are
larger.

Searching an element in the binary serach tree is basically this traversal, at each step
we go either left or right and at each step we discard one of the sub-trees. If the tree
is balanced (we call a tree balanced if for all nodes the difference between the heights
of left and right subtrees is not greater than one) we start with a search space of 'n' 
nodes and as we discard one of the sub-trees, we discard 'n/2' nodes so our search space
gets reduced to 'n/2'. 

In the next step, we reduce the search space to 'n/4' and we repeat unitl we find the 
element or our search space is reduced to only one node. The serach here is also a binary
search hence the name Binary Search Tree.

<b> Illustration to serach 6 in below tree:</b>
  
  1. Start from the root
  2. Compare the seraching element with root, if less than root, then recursively call
  left subtee, else recursively call right subtree
  3. If the element to serach is found anywhere, return true, else return false
 
<p align="center">
<img src="https://media.geeksforgeeks.org/wp-content/uploads/BSTSearch.png" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>

<b> Illustration to insert 2 in below tree:</b>
  
  1. Start from the root
  2. Compare the inserting element with root, if less than root, then recursively call
  left subtee, else recursively call right subtree
  3. After reaching the end, just insert that node at left (if less than current) or else right
 
<p align="center">
<img src="https://media.geeksforgeeks.org/wp-content/uploads/BSTSearch.png" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>

<h2>Utilities Used</h2>

- <b>ipgeolocation.io:</b> IP Address to Geolocation API

<h2>Attacks from China coming in; Custom logs being output with geodata</h2>

<p align="center">
<img src="https://i.imgur.com/LhDCRz4.jpeg" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>

<h2>World map of incoming attacks after 24 hours (built custom logs including geodata)</h2>

<p align="center">
<img src="https://i.imgur.com/krRFrK5.png" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
