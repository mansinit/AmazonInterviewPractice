# AmazonInterviewPractice
What is AVL tree? Same as Binary tree just the height difference between left subtree and right subtree should not be more than 1
Why AVL is required when BST is there? So the worst case condition for insertion,deletion and searching in BST is O(n) for a skewed BST. For n elements  in a left skewed binary, the worst case complexity is O(n).
Whereas for AVL it will never be more than O(log n). Only required to traverse half of the elements always.
And complexity is log n when :
8 -- 3
16 -- 4
2 -- 1
this complies that, if we have 8 elements and we divide the array to search for an element into first 4 and then first 2 and one more search that
