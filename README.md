# Subsequence_PI

It demostrates how to find no. of subsequences of '123' of first 100,000 digits of PI in JAVASCRIPT with O(N) complexity.

Approach: 
	Build a tree. Consider results[0] as root node. Iterate along the string if the character is '1', add a node to the the root of the tree. If the character is '2', 
	add a child to each first level node. If the character is '3', add a child to each second level node.
	Return the number of third layer nodes.
