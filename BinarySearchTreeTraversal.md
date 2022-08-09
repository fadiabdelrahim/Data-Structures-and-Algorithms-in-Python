<h1>Binary Search Tree Traversal</h1>

<h2>What is a Binary Search Tree?</h2>

A binary search tree is a binary tree made up of nodes. Each node has a key signifying its value. The values of the node on the left subtree are smaller than the value of the root node. And the value of the the nodes on the right subtree are larger than the value of the root node. 

![image](https://user-images.githubusercontent.com/110497344/182504594-4762daf0-48e7-466a-8356-3b1b05eaf2f6.png)

<h2>Some important terms:</h2>

</p>

- Root - the top most node in the tree
- Parent - A node witha child or children
- Child - A node extended from another node (parent)
- Leaf - A node without a child

<h2>What is a Binary Search Tree Used for?</h2>

We can use the Binary Serach Tree for the addition and deletion of items in a tree. We can also represent data in a ranked order using a binary tree.

<h2>What is Tree Traversal?</h2>

Traversing a tree means visiting and outputting the value of each node in a particular order. The major importance of tree traversal is that there are multiple ways of carrying out traversal operations. 

<b>Each of these methosds of travesing a tree have a particular order they follow:</b>

- <b>Inorder</b> - you traverse from the left subtree to the root then to the right subtree.

      Inorder => Left, Root, Right

- <b>Preorder</b> - you traverse from the root to the left subtree then to the the right subtree

      Preorder => Root, Left, Right

- <b>Postorder</b> - you traverse freom the left subtree to the right subtree then to the root

      Postorder => Left, Right, Root

<h2>How to Traverse a Tree Using Inorder Traversal</h2>

Here is the diagram we will be working with for the follwoing traversals:

![image](https://user-images.githubusercontent.com/110497344/182506204-8ff8a0a5-ac5a-4332-b633-4a4cc427619d.png)

This is the result we get after using Inorder traversal:

![image](https://user-images.githubusercontent.com/110497344/182506317-52b33e7e-1834-4357-8c4c-877d45720c34.png)

<b>D, B, E, A, F, C, G</b>

<h2>How to Traverse a Tree Using Preorder Traversal</h2>

This is the result we get after using Preorder traversal:

![image](https://user-images.githubusercontent.com/110497344/182506502-c8b69484-e316-4233-942b-8baa7c5b7b17.png)

<b>A, B, D, E, C, F, G</b>

<h2>How to Traverse a Tree Using Postorder Traversal</h2>

This is the result we get after using Preorder traversal:

![image](https://user-images.githubusercontent.com/110497344/182506618-efe3059a-7802-4524-bc2a-dc287db6662e.png)

<b>D, E, B, F, G, C, A</b>

