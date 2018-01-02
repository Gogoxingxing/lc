## MATH RELATED
- [168. Excel Sheet Column Title](#168) | [Leetcode](https://leetcode.com/problems/excel-sheet-column-title/description/) | [Discussion](https://leetcode.com/problems/excel-sheet-column-title/discuss/51399)
```
Given a positive integer, return its corresponding column title as appear in an Excel sheet.

For example:

    1 -> A
    2 -> B
    3 -> C
    ...
    26 -> Z
    27 -> AA
    28 -> AB 
```
## DESIGN
- [348. Design Tic-Tac-Toe](#348) | [Leetcode](https://leetcode.com/problems/design-tic-tac-toe/description/) | [Discussion](https://leetcode.com/problems/design-tic-tac-toe/discuss/81898)
```
Design a Tic-tac-toe game that is played between two players on a n x n grid.

You may assume the following rules:

A move is guaranteed to be valid and is placed on an empty block.
Once a winning condition is reached, no more moves is allowed.
A player who succeeds in placing n of their marks in a horizontal, vertical, or diagonal row wins the game.
Example:
Given n = 3, assume that player 1 is "X" and player 2 is "O" in the board.

TicTacToe toe = new TicTacToe(3);

toe.move(0, 0, 1); -> Returns 0 (no one wins)
|X| | |
| | | |    // Player 1 makes a move at (0, 0).
| | | |

toe.move(0, 2, 2); -> Returns 0 (no one wins)
|X| |O|
| | | |    // Player 2 makes a move at (0, 2).
| | | |

toe.move(2, 2, 1); -> Returns 0 (no one wins)
|X| |O|
| | | |    // Player 1 makes a move at (2, 2).
| | |X|

toe.move(1, 1, 2); -> Returns 0 (no one wins)
|X| |O|
| |O| |    // Player 2 makes a move at (1, 1).
| | |X|

toe.move(2, 0, 1); -> Returns 0 (no one wins)
|X| |O|
| |O| |    // Player 1 makes a move at (2, 0).
|X| |X|

toe.move(1, 0, 2); -> Returns 0 (no one wins)
|X| |O|
|O|O| |    // Player 2 makes a move at (1, 0).
|X| |X|

toe.move(2, 1, 1); -> Returns 1 (player 1 wins)
|X| |O|
|O|O| |    // Player 1 makes a move at (2, 1).
|X|X|X|
```

## BIT MANIPULATION
- [477. Total Hamming Distance](#477) | [Leetcode](https://leetcode.com/problems/total-hamming-distance/description/) | [Discussion](https://discuss.leetcode.com/topic/72092/java-o-n-time-o-1-space)
```
The Hamming distance between two integers is the number of positions at which the corresponding bits are different.

Now your job is to find the total Hamming distance between all pairs of the given numbers.

Example:
Input: 4, 14, 2

Output: 6

Explanation: In binary representation, the 4 is 0100, 14 is 1110, and 2 is 0010 (just
showing the four bits relevant in this case). So the answer will be:
HammingDistance(4, 14) + HammingDistance(4, 2) + HammingDistance(14, 2) = 2 + 2 + 2 = 6.
```

- [371. Sum of Two Integers](#371) | [Leetcode](https://leetcode.com/problems/sum-of-two-integers/description/) | [Discussion](https://discuss.leetcode.com/topic/49771/java-simple-easy-understand-solution-with-explanation) | [Discussion](https://discuss.leetcode.com/topic/50315/a-summary-how-to-use-bit-manipulation-to-solve-problems-easily-and-efficiently)
```
Calculate the sum of two integers a and b, but you are not allowed to use the operator + and -.

Example:
Given a = 1 and b = 2, return 3.

```

- [318. Maximum Product of Word Lengths](#318) | [Leetcode](https://leetcode.com/problems/maximum-product-of-word-lengths/description/) | [Discussion](https://discuss.leetcode.com/topic/35539/java-easy-version-to-understand/4)
```
Given a string array words, find the maximum value of length(word[i]) * length(word[j]) where the two words do not share common letters. You may assume that each word will contain only lower case letters. If no such two words exist, return 0.

Example 1:
Given ["abcw", "baz", "foo", "bar", "xtfn", "abcdef"]
Return 16
The two words can be "abcw", "xtfn".

Example 2:
Given ["a", "ab", "abc", "d", "cd", "bcd", "abcd"]
Return 4
The two words can be "ab", "cd".

Example 3:
Given ["a", "aa", "aaa", "aaaa"]
Return 0
No such pair of words.

```

## STACK

- [232. Implement Queue using Stacks](#232) | [Leetcode](https://leetcode.com/problems/implement-queue-using-stacks/description/)
```
Implement the following operations of a queue using stacks.

push(x) -- Push element x to the back of queue.
pop() -- Removes the element from in front of queue.
peek() -- Get the front element.
empty() -- Return whether the queue is empty.
```

- [155. Min Stack](#155) | [Leetcode](https://leetcode.com/problems/min-stack/description/)
```
Design a stack that supports push, pop, top, and retrieving the minimum element in constant time.

push(x) -- Push element x onto stack.
pop() -- Removes the element on top of the stack.
top() -- Get the top element.
getMin() -- Retrieve the minimum element in the stack.
Example:
MinStack minStack = new MinStack();
minStack.push(-2);
minStack.push(0);
minStack.push(-3);
minStack.getMin();   --> Returns -3.
minStack.pop();
minStack.top();      --> Returns 0.
minStack.getMin();   --> Returns -2.
```

- [341. Flatten Nested List Iterator](#341) | [Leetcode](https://leetcode.com/problems/flatten-nested-list-iterator/description/)
```
Given a nested list of integers, implement an iterator to flatten it.

Each element is either an integer, or a list -- whose elements may also be integers or other lists.

Example 1:
Given the list [[1,1],2,[1,1]],

By calling next repeatedly until hasNext returns false, the order of elements returned by next should be: [1,1,2,1,1].

Example 2:
Given the list [1,[4,[6]]],

By calling next repeatedly until hasNext returns false, the order of elements returned by next should be: [1,4,6].
```

- [71. Simplify Path](#71) | [Leetcode](https://leetcode.com/problems/simplify-path/description/)
```
Given an absolute path for a file (Unix-style), simplify it.

For example,
path = "/home/", => "/home"
path = "/a/./b/../../c/", => "/c"
click to show corner cases.

Corner Cases:
Did you consider the case where path = "/../"?
In this case, you should return "/".
Another corner case is the path might contain multiple slashes '/' together, such as "/home//foo/".
In this case, you should ignore redundant slashes and return "/home/foo".
```


## TREE

- [572. Subtree of Another Tree](#572) | [Leetcode](https://leetcode.com/problems/subtree-of-another-tree/discuss/)

- [Check complete binary tree](#complete-binary-tree) | [Solution](http://www.geeksforgeeks.org/check-whether-binary-tree-complete-not-set-2-recursive-solution/)

- [222. Count Complete Tree Nodes](#222) | [Leetcode](https://leetcode.com/problems/count-complete-tree-nodes/description/) | [Tree Type](https://en.wikipedia.org/wiki/Binary_tree#Types_of_binary_trees)

- [199. Binary Tree Right Side View](#199) | [Leetcode](https://leetcode.com/problems/binary-tree-right-side-view/description/)
```
Given a binary tree, imagine yourself standing on the right side of it, return the values of the nodes you can see ordered from top to bottom.

For example:
Given the following binary tree,
   1            <---
 /   \
2     3         <---
 \     \
  5     4       <---
You should return [1, 3, 4].
```

- [117. Populating Next Right Pointers in Each Node II](#117) | [Leetcode](https://leetcode.com/problems/populating-next-right-pointers-in-each-node-ii/description/)

- [116. Populating Next Right Pointers in Each Node](#116) | [Leetcode](https://leetcode.com/problems/populating-next-right-pointers-in-each-node/description/)

- [236. Lowest Common Ancestor of a Binary Tree](#236) | [Leetcode](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-tree/description/)
```
Given a binary tree, find the lowest common ancestor (LCA) of two given nodes in the tree.

According to the definition of LCA on Wikipedia: “The lowest common ancestor is defined between two nodes v and w as the lowest node in T that has both v and w as descendants (where we allow a node to be a descendant of itself).”

        _______3______
       /              \
    ___5__          ___1__
   /      \        /      \
   6      _2       0       8
         /  \
         7   4
For example, the lowest common ancestor (LCA) of nodes 5 and 1 is 3. Another example is LCA of nodes 5 and 4 is 5, since a node can be a descendant of itself according to the LCA definition.
```

- [235. Lowest Common Ancestor of a Binary Search Tree](#235) | [Leetcode](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-search-tree/description/)
```
Given a binary search tree (BST), find the lowest common ancestor (LCA) of two given nodes in the BST.

According to the definition of LCA on Wikipedia: “The lowest common ancestor is defined between two nodes v and w as the lowest node in T that has both v and w as descendants (where we allow a node to be a descendant of itself).”

        _______6______
       /              \
    ___2__          ___8__
   /      \        /      \
   0      _4       7       9
         /  \
         3   5
For example, the lowest common ancestor (LCA) of nodes 2 and 8 is 6. Another example is LCA of nodes 2 and 4 is 2, since a node can be a descendant of itself according to the LCA definition.
```

- [543. Diameter of Binary Tree](#543) | [Leetcode](https://leetcode.com/problems/diameter-of-binary-tree/description/)
```
Given a binary tree, you need to compute the length of the diameter of the tree. The diameter of a binary tree is the length of the longest path between any two nodes in a tree. This path may or may not pass through the root.

Example:
Given a binary tree 
          1
         / \
        2   3
       / \     
      4   5    
Return 3, which is the length of the path [4,2,1,3] or [5,2,1,3].
```

- [653. Two Sum IV - Input is a BST](#653) | [Leetcode](https://discuss.leetcode.com/topic/98440/java-c-three-simple-methods-choose-one-you-like)

- [285. Inorder Successor in BST](#285) | [Leetcode](https://leetcode.com/problems/inorder-successor-in-bst/description/)

- [173. Binary Search Tree Iterator](#173) | [Leetcode](https://leetcode.com/problems/binary-search-tree-iterator/description/)
```
Implement an iterator over a binary search tree (BST). Your iterator will be initialized with the root node of a BST.

Calling next() will return the next smallest number in the BST.

Note: next() and hasNext() should run in average O(1) time and uses O(h) memory, where h is the height of the tree.
```

- [144. Binary Tree Preorder Traversal](#144) | [Leetcode](https://leetcode.com/problems/binary-tree-preorder-traversal/description/)

- [94. Binary Tree Inorder Traversal](#94) | [Leetcode](https://leetcode.com/problems/binary-tree-inorder-traversal/discuss/)

- [98. Validate Binary Search Tree](#98) | [Leetcode](https://leetcode.com/problems/validate-binary-search-tree/description/)
```
Given a binary tree, determine if it is a valid binary search tree (BST).

Assume a BST is defined as follows:

The left subtree of a node contains only nodes with keys less than the node's key.
The right subtree of a node contains only nodes with keys greater than the node's key.
Both the left and right subtrees must also be binary search trees.
```

- [230. Kth Smallest Element in a BST](#230) | [Leetcode](https://discuss.leetcode.com/topic/17810/3-ways-implemented-in-java-python-binary-search-in-order-iterative-recursive)
```
Given a binary search tree, write a function kthSmallest to find the kth smallest element in it.

Note: 
You may assume k is always valid, 1 ≤ k ≤ BST's total elements.

Follow up:
What if the BST is modified (insert/delete operations) often and you need to find the kth smallest frequently? How would you optimize the kthSmallest routine?
```

- [105. Construct Binary Tree from Preorder and Inorder Traversal](#105) | [Leetcode](https://leetcode.com/problems/construct-binary-tree-from-preorder-and-inorder-traversal/description/)
```
Given preorder and inorder traversal of a tree, construct the binary tree.
```

## STRING

- [28. Implement strStr()](#28) | [Leetcode](https://leetcode.com/problems/implement-strstr/description/)
```
Implement strStr().

Returns the index of the first occurrence of needle in haystack, or -1 if needle is not part of haystack.
```

- [38. Count and Say](#38) | [Leetcode](https://leetcode.com/problems/count-and-say/description/)
```
The count-and-say sequence is the sequence of integers with the first five terms as following:

1.     1
2.     11
3.     21
4.     1211
5.     111221
1 is read off as "one 1" or 11.
11 is read off as "two 1s" or 21.
21 is read off as "one 2, then one 1" or 1211.
Given an integer n, generate the nth term of the count-and-say sequence.

Note: Each term of the sequence of integers will be represented as a string.

Example 1:

Input: 1
Output: "1"
Example 2:

Input: 4
Output: "1211"
```

- [273. Integer to English Words](#273) | [Leetcode](https://discuss.leetcode.com/topic/23054/my-clean-java-solution-very-easy-to-understand)
```
123 -> "One Hundred Twenty Three" 
12345 -> "Twelve Thousand Three Hundred Forty Five" 
1234567 -> "One Million Two Hundred Thirty Four Thousand Five Hundred Sixty Seven"
```

- [20. Valid Parentheses](#20) | [Leetcode](https://leetcode.com/problems/valid-parentheses/description/)
```
Given a string containing just the characters '(', ')', '{', '}', '[' and ']', determine if the input string is valid.

The brackets must close in the correct order, "()" and "()[]{}" are all valid but "(]" and "([)]" are not.
```

- [5. Longest Palindromic Substring](#5) | [Leetcode](https://leetcode.com/problems/longest-palindromic-substring/description/)
```
Given a string s, find the longest palindromic substring in s. You may assume that the maximum length of s is 1000.

Example:

Input: "babad"

Output: "bab"

Note: "aba" is also a valid answer.
Example:

Input: "cbbd"

Output: "bb"
```

- [67. Add Binary](#67) | [Leetcode](https://leetcode.com/problems/add-binary/description/)
```
Given two binary strings, return their sum (also a binary string).

For example,
a = "11"
b = "1"
Return "100".
```

- [161. One Edit Distance](#161) | [Leetcode](https://leetcode.com/problems/one-edit-distance/description/)
```
Given two strings S and T, determine if they are both one edit distance apart.
```

- [125. Valid Palindrome](#125) | [Leetcode](https://leetcode.com/problems/valid-palindrome/description/)
```
Given a string, determine if it is a palindrome, considering only alphanumeric characters and ignoring cases.

For example,
"A man, a plan, a canal: Panama" is a palindrome.
"race a car" is not a palindrome.
```

- [680. Valid Palindrome II](#680) | [Leetcode](https://leetcode.com/problems/valid-palindrome-ii/description/)
```
Given a non-empty string s, you may delete at most one character. Judge whether you can make it a palindrome.

Example 1:
Input: "aba"
Output: True
Example 2:
Input: "abca"
Output: True
Explanation: You could delete the character 'c'.
Note:
The string will only contain lowercase characters a-z. The maximum length of the string is 50000.
```

- [151. Reverse Words in a String](#151) | [Leetcode](https://leetcode.com/problems/reverse-words-in-a-string/discuss/)
```
Given an input string, reverse the string word by word.

For example,
Given s = "the sky is blue",
return "blue is sky the".
```

- [186. Reverse Words in a String II](#186) | [Leetcode](https://leetcode.com/problems/reverse-words-in-a-string-ii/description/)
```
Given an input string, reverse the string word by word. A word is defined as a sequence of non-space characters.

The input string does not contain leading or trailing spaces and the words are always separated by a single space.

For example,
Given s = "the sky is blue",
return "blue is sky the".

Could you do it in-place without allocating extra space?
```

- [189. Rotate Array](#189) | [Leetcode](https://leetcode.com/problems/rotate-array/description/)
```
Rotate an array of n elements to the right by k steps.

For example, with n = 7 and k = 3, the array [1,2,3,4,5,6,7] is rotated to [5,6,7,1,2,3,4].
```

- [157. Read N Characters Given Read4](#157) | [Leetcode](https://leetcode.com/problems/read-n-characters-given-read4/description/)
```
The API: int read4(char buf) reads 4 characters at a time from a file.

The return value is the actual number of characters read. For example, it returns 3 if there is only 3 characters left in the file.

By using the read4 API, implement the function int read(char buf, int n) that reads n characters from the file.
```

- [158. Read N Characters Given Read4 II - Call multiple times](#158) | [Leetcode](https://leetcode.com/problems/read-n-characters-given-read4-ii-call-multiple-times/description/)
```
The API: int read4(char buf) reads 4 characters at a time from a file.

The return value is the actual number of characters read. For example, it returns 3 if there is only 3 characters left in the file.

By using the read4 API, implement the function int read(char buf, int n) that reads n characters from the file.
```

- [139. Word Break](#139) | [Leetcode](https://leetcode.com/problems/word-break/description/) | [Discussion](https://discuss.leetcode.com/topic/6156/java-implementation-using-dp-in-two-ways)
```
Given a non-empty string s and a dictionary wordDict containing a list of non-empty words, determine if s can be segmented into a space-separated sequence of one or more dictionary words. You may assume the dictionary does not contain duplicate words.

For example, given
s = "leetcode",
dict = ["leet", "code"].

Return true because "leetcode" can be segmented as "leet code".
```

- [14. Longest Common Prefix](#14) | [Leetcode](https://leetcode.com/problems/longest-common-prefix/description/)
```
Write a function to find the longest common prefix string amongst an array of strings.
```

- [344. Reverse String](#344) | [Leetcode](https://leetcode.com/problems/reverse-string/description/) | [Summary](http://www.geeksforgeeks.org/reverse-a-string-in-java-5-different-ways/)
```
Write a function that takes a string as input and returns the string reversed.

Example:
Given s = "hello", return "olleh".
```

- [383. Ransom Note](#383) | [Leetcode](https://leetcode.com/problems/ransom-note/description/)
```
Given an arbitrary ransom note string and another string containing letters from all the magazines, write a function that will return true if the ransom note can be constructed from the magazines ; otherwise, it will return false.

Each letter in the magazine string can only be used once in your ransom note.

Note:
You may assume that both strings contain only lowercase letters.

canConstruct("a", "b") -> false
canConstruct("aa", "ab") -> false
canConstruct("aa", "aab") -> true
```

## HASHTABLE

- [1. Two Sum](#1) | [Leetcode](https://leetcode.com/problems/two-sum/description/)
```
Given an array of integers, return indices of the two numbers such that they add up to a specific target.

You may assume that each input would have exactly one solution, and you may not use the same element twice.

Example:
Given nums = [2, 7, 11, 15], target = 9,

Because nums[0] + nums[1] = 2 + 7 = 9,
return [0, 1].
```

- [554. Brick Wall](#554) | [Leetcode](https://leetcode.com/problems/brick-wall/description/)
```
There is a brick wall in front of you. The wall is rectangular and has several rows of bricks. The bricks have the same height but different width. You want to draw a vertical line from the top to the bottom and cross the least bricks.

The brick wall is represented by a list of rows. Each row is a list of integers representing the width of each brick in this row from left to right.

If your line go through the edge of a brick, then the brick is not considered as crossed. You need to find out how to draw the line to cross the least bricks and return the number of crossed bricks.

You cannot draw a line just along one of the two vertical edges of the wall, in which case the line will obviously cross no bricks.

Example:
Input: 
[[1,2,2,1],
 [3,1,2],
 [1,3,2],
 [2,4],
 [3,1,2],
 [1,3,1,1]]
Output: 2

Note:
The width sum of bricks in different rows are the same and won't exceed INT_MAX.
The number of bricks in each row is in range [1,10,000]. The height of wall is in range [1,10,000]. Total number of bricks of the wall won't exceed 20,000.
```

- [49. Group Anagrams](#49) | [Leetcode](https://leetcode.com/problems/group-anagrams/description/) | [Discussion](https://discuss.leetcode.com/topic/24494/share-my-short-java-solution/17)
```
Given an array of strings, group anagrams together.

For example, given: ["eat", "tea", "tan", "ate", "nat", "bat"], 
Return:

[
  ["ate", "eat","tea"],
  ["nat","tan"],
  ["bat"]
]
Note: All inputs will be in lower-case.
```

- [325. Maximum Size Subarray Sum Equals k](#325) | [Leetcode](https://leetcode.com/problems/maximum-size-subarray-sum-equals-k/description/)
```
Given an array nums and a target value k, find the maximum length of a subarray that sums to k. If there isn't one, return 0 instead.

Note:
The sum of the entire nums array is guaranteed to fit within the 32-bit signed integer range.

Example 1:
Given nums = [1, -1, 5, -2, 3], k = 3,
return 4. (because the subarray [1, -1, 5, -2] sums to 3 and is the longest)

Example 2:
Given nums = [-2, -1, 2, 1], k = 1,
return 2. (because the subarray [-1, 2] sums to 1 and is the longest)

Follow Up:
Can you do it in O(n) time?
```

- [523. Continuous Subarray Sum](#523) | [Leetcode](https://leetcode.com/problems/continuous-subarray-sum/description/)
```
Given a list of non-negative numbers and a target integer k, write a function to check if the array has a continuous subarray of size at least 2 that sums up to the multiple of k, that is, sums up to n*k where n is also an integer.

Example 1:
Input: [23, 2, 4, 6, 7],  k=6
Output: True
Explanation: Because [2, 4] is a continuous subarray of size 2 and sums up to 6.
Example 2:
Input: [23, 2, 6, 4, 7],  k=6
Output: True
Explanation: Because [23, 2, 6, 4, 7] is an continuous subarray of size 5 and sums up to 42.
Note:
The length of the array won't exceed 10,000.
You may assume the sum of all the numbers is in the range of a signed 32-bit integer.
```

- [311. Sparse Matrix Multiplication](#311) | [Leetcode](https://leetcode.com/problems/sparse-matrix-multiplication/description/) | [Discussion](https://discuss.leetcode.com/topic/30625/easiest-java-solution)
```
Given two sparse matrices A and B, return the result of AB.

You may assume that A's column number is equal to B's row number.

Example:

A = [
  [ 1, 0, 0],
  [-1, 0, 3]
]

B = [
  [ 7, 0, 0 ],
  [ 0, 0, 0 ],
  [ 0, 0, 1 ]
]


     |  1 0 0 |   | 7 0 0 |   |  7 0 0 |
AB = | -1 0 3 | x | 0 0 0 | = | -7 0 3 |
                  | 0 0 1 |

```

- [314. Binary Tree Vertical Order Traversal](#314) | [Leetcode](https://leetcode.com/problems/binary-tree-vertical-order-traversal/description/)
```
Given a binary tree, return the vertical order traversal of its nodes' values. (ie, from top to bottom, column by column).

If two nodes are in the same row and column, the order should be from left to right.

Examples:

Given binary tree [3,9,20,null,null,15,7],
   3
  /\
 /  \
 9  20
    /\
   /  \
  15   7
return its vertical order traversal as:
[
  [9],
  [3,15],
  [20],
  [7]
]
```

- [347. Top K Frequent Elements](#347) | [Leetcode](https://leetcode.com/problems/top-k-frequent-elements/description/)
```
Given a non-empty array of integers, return the k most frequent elements.

For example,
Given [1,1,1,2,2,3] and k = 2, return [1,2].
```

- [692. Top K Frequent Words](#692) | [Leetcode](https://leetcode.com/problems/top-k-frequent-words/description/)
```
Given a non-empty list of words, return the k most frequent elements.

Your answer should be sorted by frequency from highest to lowest. If two words have the same frequency, then the word with the lower alphabetical order comes first.

Example 1:
Input: ["i", "love", "leetcode", "i", "love", "coding"], k = 2
Output: ["i", "love"]
Explanation: "i" and "love" are the two most frequent words.
    Note that "i" comes before "love" due to a lower alphabetical order.
Example 2:
Input: ["the", "day", "is", "sunny", "the", "the", "the", "sunny", "is", "is"], k = 4
Output: ["the", "is", "sunny", "day"]
Explanation: "the", "is", "sunny" and "day" are the four most frequent words,
    with the number of occurrence being 4, 3, 2 and 1 respectively.
```

- [349. Intersection of Two Arrays](#349) | [Leetcode](https://discuss.leetcode.com/topic/45685/three-java-solutions)
```
Given two arrays, write a function to compute their intersection.

Example:
Given nums1 = [1, 2, 2, 1], nums2 = [2, 2], return [2].

Note:
Each element in the result must be unique.
The result can be in any order.
```

- [127. Word Ladder](#127) | [Leetcode](https://leetcode.com/problems/word-ladder/description/)
```
Given two words (beginWord and endWord), and a dictionary's word list, find the length of shortest transformation sequence from beginWord to endWord, such that:

Only one letter can be changed at a time.
Each transformed word must exist in the word list. Note that beginWord is not a transformed word.
For example,

Given:
beginWord = "hit"
endWord = "cog"
wordList = ["hot","dot","dog","lot","log","cog"]
As one shortest transformation is "hit" -> "hot" -> "dot" -> "dog" -> "cog",
return its length 5.
```

- [126. Word Ladder II](#126) | [Leetcode](https://leetcode.com/problems/word-ladder-ii/description/) | [Discussion](https://discuss.leetcode.com/topic/27504/my-concise-java-solution-based-on-bfs-and-dfs) 
```
Given two words (beginWord and endWord), and a dictionary's word list, find all shortest transformation sequence(s) from beginWord to endWord, such that:

Only one letter can be changed at a time
Each transformed word must exist in the word list. Note that beginWord is not a transformed word.
For example,

Given:
beginWord = "hit"
endWord = "cog"
wordList = ["hot","dot","dog","lot","log","cog"]
Return
  [
    ["hit","hot","dot","dog","cog"],
    ["hit","hot","lot","log","cog"]
  ]
```

- [380. Insert Delete GetRandom O(1)](#380) | [Leetcode](https://leetcode.com/problems/insert-delete-getrandom-o1/description/)
```
Design a data structure that supports all following operations in average O(1) time.

insert(val): Inserts an item val to the set if not already present.
remove(val): Removes an item val from the set if present.
getRandom: Returns a random element from current set of elements. Each element must have the same probability of being returned.
```

- [381. Insert Delete GetRandom O(1) - Duplicates allowed](#381) | [Leetcode](https://leetcode.com/problems/insert-delete-getrandom-o1-duplicates-allowed/description/)
```
Design a data structure that supports all following operations in average O(1) time.

Note: Duplicate elements are allowed.
insert(val): Inserts an item val to the collection.
remove(val): Removes an item val from the collection if present.
getRandom: Returns a random element from current collection of elements. The probability of each element being returned is linearly related to the number of same value the collection contains.
```

- [205. Isomorphic Strings](#205) | [Leetcode](https://leetcode.com/problems/isomorphic-strings/description/)
```
Given two strings s and t, determine if they are isomorphic.

Two strings are isomorphic if the characters in s can be replaced to get t.

All occurrences of a character must be replaced with another character while preserving the order of characters. No two characters may map to the same character but a character may map to itself.

For example,
Given "egg", "add", return true.

Given "foo", "bar", return false.

Given "paper", "title", return true.
```


- [249. Group Shifted Strings](#249) | [Leetcode](https://leetcode.com/problems/group-shifted-strings/description/)
```
Given a string, we can "shift" each of its letter to its successive letter, for example: "abc" -> "bcd". We can keep "shifting" which forms the sequence:

"abc" -> "bcd" -> ... -> "xyz"
Given a list of strings which contains only lowercase alphabets, group all strings that belong to the same shifting sequence.

For example, given: ["abc", "bcd", "acef", "xyz", "az", "ba", "a", "z"], 
A solution is:

[
  ["abc","bcd","xyz"],
  ["az","ba"],
  ["acef"],
  ["a","z"]
]
```

- [First Unique Number In Stream](#funis) | [Answer](https://www.jiuzhang.com/solution/first-unique-number-in-stream/)
```
Given a continuous stream of numbers, write a function that returns the first unique number whenever terminating number is reached(include terminating number). If there no unique number before terminating number or you can't find this terminating number, return -1.
```

## TWO POINTERS

- [15. 3Sum](#15) | [Leetcode](https://leetcode.com/problems/3sum/description/)
```
Given an array S of n integers, are there elements a, b, c in S such that a + b + c = 0? Find all unique triplets in the array which gives the sum of zero.

Note: The solution set must not contain duplicate triplets.

For example, given array S = [-1, 0, 1, 2, -1, -4],

A solution set is:
[
  [-1, 0, 1],
  [-1, -1, 2]
]
```

- [283. Move Zeroes](#283) | [Leetcode](https://leetcode.com/problems/move-zeroes/description/)
```
Given an array nums, write a function to move all 0's to the end of it while maintaining the relative order of the non-zero elements.

For example, given nums = [0, 1, 0, 3, 12], after calling your function, nums should be [1, 3, 12, 0, 0].

Note:
You must do this in-place without making a copy of the array.
Minimize the total number of operations.
```

- [167. Two Sum II - Input array is sorted](#167) | [Leetcode](https://leetcode.com/problems/two-sum-ii-input-array-is-sorted/description/)

- [75. Sort Colors](#75) | [Leetcode](https://leetcode.com/problems/sort-colors/description/)
```
Given an array with n objects colored red, white or blue, sort them so that objects of the same color are adjacent, with the colors in the order red, white and blue.

Here, we will use the integers 0, 1, and 2 to represent the color red, white, and blue respectively.
```

- [209. Minimum Size Subarray Sum](#209) | [Leetcode](https://leetcode.com/problems/minimum-size-subarray-sum/description/) | [Discussion] (https://discuss.leetcode.com/topic/13749/two-ac-solutions-in-java-with-time-complexity-of-n-and-nlogn-with-explanation)
```
Given an array of n positive integers and a positive integer s, find the minimal length of a contiguous subarray of which the sum ≥ s. If there isn't one, return 0 instead.

For example, given the array [2,3,1,2,4,3] and s = 7,
the subarray [4,3] has the minimal length under the problem constraint.
```

- [76. Minimum Window Substring](#76) | [Leetcode](https://leetcode.com/problems/minimum-window-substring/description/) | [Discussion](https://discuss.leetcode.com/topic/30941/here-is-a-10-line-template-that-can-solve-most-substring-problems)
```
Given a string S and a string T, find the minimum window in S which will contain all the characters in T in complexity O(n).

For example,
S = "ADOBECODEBANC"
T = "ABC"
Minimum window is "BANC".

Note:
If there is no such window in S that covers all characters in T, return the empty string "".

If there are multiple such windows, you are guaranteed that there will always be only one unique minimum window in S.
```

- [3. Longest Substring Without Repeating Characters](#3) | [Leetcode](https://leetcode.com/problems/longest-substring-without-repeating-characters/description/)
```
Given a string, find the length of the longest substring without repeating characters.

Examples:

Given "abcabcbb", the answer is "abc", which the length is 3.

Given "bbbbb", the answer is "b", with the length of 1.

Given "pwwkew", the answer is "wke", with the length of 3. Note that the answer must be a substring, "pwke" is a subsequence and not a substring.
```

- [159. Longest Substring with At Most Two Distinct Characters](#159) | [Leetcode](https://leetcode.com/problems/longest-substring-with-at-most-two-distinct-characters/description/)
```
Given a string, find the length of the longest substring T that contains at most 2 distinct characters.

For example, Given s = “eceba”,

T is "ece" which its length is 3.
```

- [443. String Compression](#443) | [Leetcode](https://leetcode.com/problems/string-compression/description/)
```
Given an array of characters, compress it in-place.

The length after compression must always be smaller than or equal to the original array.

Every element of the array should be a character (not int) of length 1.

After you are done modifying the input array in-place, return the new length of the array.


Follow up:
Could you solve it using only O(1) extra space?


Example 1:
Input:
["a","a","b","b","c","c","c"]

Output:
Return 6, and the first 6 characters of the input array should be: ["a","2","b","2","c","3"]

Explanation:
"aa" is replaced by "a2". "bb" is replaced by "b2". "ccc" is replaced by "c3".
Example 2:
Input:
["a"]

Output:
Return 1, and the first 1 characters of the input array should be: ["a"]

Explanation:
Nothing is replaced.
Example 3:
Input:
["a","b","b","b","b","b","b","b","b","b","b","b","b"]

Output:
Return 4, and the first 4 characters of the input array should be: ["a","b","1","2"].

Explanation:
Since the character "a" does not repeat, it is not compressed. "bbbbbbbbbbbb" is replaced by "b12".
Notice each digit has it's own entry in the array.
```


## PRIORITY QUEUE

- [621. Task Scheduler](#621) | [Leetcode](https://leetcode.com/problems/task-scheduler/description/)
```
Given a char array representing tasks CPU need to do. It contains capital letters A to Z where different letters represent different tasks.Tasks could be done without original order. Each task could be done in one interval. For each interval, CPU could finish one task or just be idle.

However, there is a non-negative cooling interval n that means between two same tasks, there must be at least n intervals that CPU are doing different tasks or just be idle.

You need to return the least number of intervals the CPU will take to finish all the given tasks.

Example 1:
Input: tasks = ["A","A","A","B","B","B"], n = 2
Output: 8
Explanation: A -> B -> idle -> A -> B -> idle -> A -> B.
```

- [253. Meeting Rooms II](#253) | [Leetcode](https://leetcode.com/problems/meeting-rooms-ii/description/)
```
Given an array of meeting time intervals consisting of start and end times [[s1,e1],[s2,e2],...] (si < ei), find the minimum number of conference rooms required.

For example,
Given [[0, 30],[5, 10],[15, 20]],
return 2.
```

## GRAPH

- [133. Clone Graph](#133) | [Leetcode](https://discuss.leetcode.com/topic/4690/simple-java-iterative-bfs-solution-with-hashmap-and-queue)
```
Clone an undirected graph. Each node in the graph contains a label and a list of its neighbors.
OJ's undirected graph serialization:
Nodes are labeled uniquely.

We use # as a separator for each node, and , as a separator for node label and each neighbor of the node.
As an example, consider the serialized graph {0,1,2#1,2#2,2}.

The graph has a total of three nodes, and therefore contains three parts as separated by #.

First node is labeled as 0. Connect node 0 to both nodes 1 and 2.
Second node is labeled as 1. Connect node 1 to node 2.
Third node is labeled as 2. Connect node 2 to node 2 (itself), thus forming a self-cycle.
Visually, the graph looks like the following:

       1
      / \
     /   \
    0 --- 2
         / \
         \_/
```

- [207. Course Schedule](#207) | [Leetcode](https://leetcode.com/problems/course-schedule/description/) | [Wiki](https://en.wikipedia.org/wiki/Topological_sorting#Algorithms)
```
There are a total of n courses you have to take, labeled from 0 to n - 1.

Some courses may have prerequisites, for example to take course 0 you have to first take course 1, which is expressed as a pair: [0,1]

Given the total number of courses and a list of prerequisite pairs, is it possible for you to finish all courses?

For example:

2, [[1,0]]
There are a total of 2 courses to take. To take course 1 you should have finished course 0. So it is possible.

2, [[1,0],[0,1]]
There are a total of 2 courses to take. To take course 1 you should have finished course 0, and to take course 0 you should also have finished course 1. So it is impossible.

Hints:
This problem is equivalent to finding if a cycle exists in a directed graph. If a cycle exists, no topological ordering exists and therefore it will be impossible to take all courses.
Topological Sort via DFS - A great video tutorial (21 minutes) on Coursera explaining the basic concepts of Topological Sort.
Topological sort could also be done via BFS.
```

- [210. Course Schedule II](#210) | [Leetcode](https://leetcode.com/problems/course-schedule-ii/description/) | [Wiki](https://discuss.leetcode.com/topic/27940/concise-java-solution-based-on-bfs-with-comments)


- [261. Graph Valid Tree](#261) | [Leetcode](https://leetcode.com/problems/graph-valid-tree/description/) | [Discussion - Union Find](https://discuss.leetcode.com/topic/21712/ac-java-union-find-solution) | [Discussion - DFS](https://discuss.leetcode.com/topic/21714/ac-java-graph-dfs-solution-with-adjacency-list)
```
Given n nodes labeled from 0 to n - 1 and a list of undirected edges (each edge is a pair of nodes), write a function to check whether these edges make up a valid tree.

For example:

Given n = 5 and edges = [[0, 1], [0, 2], [0, 3], [1, 4]], return true.

Given n = 5 and edges = [[0, 1], [1, 2], [2, 3], [1, 3], [1, 4]], return false.

Note: you can assume that no duplicate edges will appear in edges. Since all edges are undirected, [0, 1] is the same as [1, 0] and thus will not appear together in edges.
```


## ARRAY

- [26. Remove Duplicates from Sorted Array](#26) | [Leetcode](https://leetcode.com/problems/remove-duplicates-from-sorted-array/description/)
```
Given a sorted array, remove the duplicates in place such that each element appear only once and return the new length.

Do not allocate extra space for another array, you must do this in place with constant memory.

For example,
Given input array nums = [1,1,2],

Your function should return length = 2, with the first two elements of nums being 1 and 2 respectively. It doesn't matter what you leave beyond the new length.
```

- [34. Search for a Range](#34) | [Leetcode](https://leetcode.com/problems/search-for-a-range/description/)
```
Given an array of integers sorted in ascending order, find the starting and ending position of a given target value.

Your algorithm's runtime complexity must be in the order of O(log n).

If the target is not found in the array, return [-1, -1].

For example,
Given [5, 7, 7, 8, 8, 10] and target value 8,
return [3, 4].
```

- [10. Regular Expression Matching](#10) | [Leetcode](https://discuss.leetcode.com/topic/40371/easy-dp-java-solution-with-detailed-explanation)
```
Implement regular expression matching with support for '.' and '*'.

'.' Matches any single character.
'*' Matches zero or more of the preceding element.

The matching should cover the entire input string (not partial).

The function prototype should be:
bool isMatch(const char *s, const char *p)

Some examples:
isMatch("aa","a") → false
isMatch("aa","aa") → true
isMatch("aaa","aa") → false
isMatch("aa", "a*") → true
isMatch("aa", ".*") → true
isMatch("ab", ".*") → true
isMatch("aab", "c*a*b") → true
```

- [56. Merge Intervals](#56) | [Leetcode](https://leetcode.com/problems/merge-intervals/description/)
```
Given a collection of intervals, merge all overlapping intervals.

For example,
Given [1,3],[2,6],[8,10],[15,18],
return [1,6],[8,10],[15,18].
```

- [252. Meeting Rooms](#252) | [Leetcode](https://leetcode.com/problems/meeting-rooms/description/)
```
Given an array of meeting time intervals consisting of start and end times [[s1,e1],[s2,e2],...] (si < ei), determine if a person could attend all meetings.

For example,
Given [[0, 30],[5, 10],[15, 20]],
return false.
```

- [435. Non-overlapping Intervals](#435) | [Leetcode](https://leetcode.com/problems/non-overlapping-intervals/description/)
```
Given a collection of intervals, find the minimum number of intervals you need to remove to make the rest of the intervals non-overlapping.

Note:
You may assume the interval's end point is always bigger than its start point.
Intervals like [1,2] and [2,3] have borders "touching" but they don't overlap each other.
Example 1:
Input: [ [1,2], [2,3], [3,4], [1,3] ]

Output: 1

Explanation: [1,3] can be removed and the rest of intervals are non-overlapping.
Example 2:
Input: [ [1,2], [1,2], [1,2] ]

Output: 2

Explanation: You need to remove two [1,2] to make the rest of intervals non-overlapping.
Example 3:
Input: [ [1,2], [2,3] ]

Output: 0

Explanation: You don't need to remove any of the intervals since they're already non-overlapping.
```

- [670. Maximum Swap](#670) | [Leetcode](https://leetcode.com/problems/maximum-swap/description/)
```
Given a non-negative integer, you could swap two digits at most once to get the maximum valued number. Return the maximum valued number you could get.

Example 1:
Input: 2736
Output: 7236
Explanation: Swap the number 2 and the number 7.
Example 2:
Input: 9973
Output: 9973
Explanation: No swap.
```

- [277. Find the Celebrity](#277) | [Leetcode](https://leetcode.com/problems/find-the-celebrity/description/)
```
Suppose you are at a party with n people (labeled from 0 to n - 1) and among them, there may exist one celebrity. The definition of a celebrity is that all the other n - 1 people know him/her but he/she does not know any of them.

Now you want to find out who the celebrity is or verify that there is not one. The only thing you are allowed to do is to ask questions like: "Hi, A. Do you know B?" to get information of whether A knows B. You need to find out the celebrity (or verify there is not one) by asking as few questions as possible (in the asymptotic sense).

You are given a helper function bool knows(a, b) which tells you whether A knows B. Implement a function int findCelebrity(n), your function should minimize the number of calls to knows.

Note: There will be exactly one celebrity if he/she is in the party. Return the celebrity's label if there is a celebrity in the party. If there is no celebrity, return -1.
```

- [33. Search in Rotated Sorted Array](#33) | [Leetcode](https://leetcode.com/problems/search-in-rotated-sorted-array/description/)
```
Suppose an array sorted in ascending order is rotated at some pivot unknown to you beforehand.

(i.e., 0 1 2 4 5 6 7 might become 4 5 6 7 0 1 2).

You are given a target value to search. If found in the array return its index, otherwise return -1.

You may assume no duplicate exists in the array.
```

- [215. Kth Largest Element in an Array](#215) | [Leetcode](https://leetcode.com/problems/kth-largest-element-in-an-array/description/) | [Discussion](https://discuss.leetcode.com/topic/14597/solution-explained)
```
Find the kth largest element in an unsorted array. Note that it is the kth largest element in the sorted order, not the kth distinct element.

For example,
Given [3,2,1,5,6,4] and k = 2, return 5.

Note: 
You may assume k is always valid, 1 ≤ k ≤ array's length.
```

- [31. Next Permutation](#31) | [Leetcode](https://leetcode.com/problems/next-permutation/description/)
```
Implement next permutation, which rearranges numbers into the lexicographically next greater permutation of numbers.

If such arrangement is not possible, it must rearrange it as the lowest possible order (ie, sorted in ascending order).

The replacement must be in-place, do not allocate extra memory.

Here are some examples. Inputs are in the left-hand column and its corresponding outputs are in the right-hand column.
1,2,3 → 1,3,2
3,2,1 → 1,2,3
1,1,5 → 1,5,1
```

- [118. Pascal's Triangle](#118) | [Leetcode](https://leetcode.com/problems/pascals-triangle/description/)
```
Given numRows, generate the first numRows of Pascal's triangle.

For example, given numRows = 5,
Return

[
     [1],
    [1,1],
   [1,2,1],
  [1,3,3,1],
 [1,4,6,4,1]
]
```

- [41. First Missing Positive](#41) | [Leetcode](https://leetcode.com/problems/first-missing-positive/description/)
```
Given an unsorted integer array, find the first missing positive integer.

For example,
Given [1,2,0] return 3,
and [3,4,-1,1] return 2.

Your algorithm should run in O(n) time and uses constant space.
```

## Dynamic Programming

- [560. Subarray Sum Equals K](#560) | [Leetcode](https://leetcode.com/problems/subarray-sum-equals-k/description/)
```
Given an array of integers and an integer k, you need to find the total number of continuous subarrays whose sum equals to k.

Example 1:
Input:nums = [1,1,1], k = 2
Output: 2
Note:
The length of the array is in range [1, 20,000].
The range of numbers in the array is [-1000, 1000] and the range of the integer k is [-1e7, 1e7].
```

- [121. Best Time to Buy and Sell Stock](#121) | [Leetcode](https://leetcode.com/problems/best-time-to-buy-and-sell-stock/description/) | [Discussion](https://discuss.leetcode.com/topic/19853/kadane-s-algorithm-since-no-one-has-mentioned-about-this-so-far-in-case-if-interviewer-twists-the-input)
```
Say you have an array for which the ith element is the price of a given stock on day i.

If you were only permitted to complete at most one transaction (ie, buy one and sell one share of the stock), design an algorithm to find the maximum profit.

Example 1:
Input: [7, 1, 5, 3, 6, 4]
Output: 5

max. difference = 6-1 = 5 (not 7-1 = 6, as selling price needs to be larger than buying price)
Example 2:
Input: [7, 6, 4, 3, 1]
Output: 0

In this case, no transaction is done, i.e. max profit = 0.
```

- [122. Best Time to Buy and Sell Stock II](#122) | [Leetcode](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-ii/description/)
```
Say you have an array for which the ith element is the price of a given stock on day i.

Design an algorithm to find the maximum profit. You may complete as many transactions as you like (ie, buy one and sell one share of the stock multiple times). However, you may not engage in multiple transactions at the same time (ie, you must sell the stock before you buy again).
```

- [120. Triangle](#120) | [Leetcode](https://leetcode.com/problems/triangle/description/) | [Discussion](https://discuss.leetcode.com/topic/1669/dp-solution-for-triangle)
```
Given a triangle, find the minimum path sum from top to bottom. Each step you may move to adjacent numbers on the row below.

For example, given the following triangle
[
     [2],
    [3,4],
   [6,5,7],
  [4,1,8,3]
]
The minimum path sum from top to bottom is 11 (i.e., 2 + 3 + 5 + 1 = 11).
```

- [64. Minimum Path Sum](#64) | [Leetcode](https://leetcode.com/problems/minimum-path-sum/description/)
```
Given a m x n grid filled with non-negative numbers, find a path from top left to bottom right which minimizes the sum of all numbers along its path.

Note: You can only move either down or right at any point in time.

Example 1:
[[1,3,1],
 [1,5,1],
 [4,2,1]]
Given the above grid map, return 7. Because the path 1→3→1→1→1 minimizes the sum.
```

- [647. Palindromic Substrings](#647) | [Leetcode](https://leetcode.com/problems/palindromic-substrings/description/)
```
Given a string, your task is to count how many palindromic substrings in this string.

The substrings with different start indexes or end indexes are counted as different substrings even they consist of same characters.

Example 1:
Input: "abc"
Output: 3
Explanation: Three palindromic strings: "a", "b", "c".
Example 2:
Input: "aaa"
Output: 6
Explanation: Six palindromic strings: "a", "a", "a", "aa", "aa", "aaa".

```

- [494. Target Sum](#494) | [Leetcode](https://leetcode.com/problems/target-sum/description/)
```
You are given a list of non-negative integers, a1, a2, ..., an, and a target, S. Now you have 2 symbols + and -. For each integer, you should choose one from + and - as its new symbol.

Find out how many ways to assign symbols to make sum of integers equal to target S.

Example 1:
Input: nums is [1, 1, 1, 1, 1], S is 3. 
Output: 5
Explanation: 

-1+1+1+1+1 = 3
+1-1+1+1+1 = 3
+1+1-1+1+1 = 3
+1+1+1-1+1 = 3
+1+1+1+1-1 = 3

There are 5 ways to assign symbols to make the sum of nums be target 3.
```

- [91. Decode Ways](#91) | [Leetcode](https://leetcode.com/problems/decode-ways/description/)
```
A message containing letters from A-Z is being encoded to numbers using the following mapping:

'A' -> 1
'B' -> 2
...
'Z' -> 26
Given an encoded message containing digits, determine the total number of ways to decode it.

For example,
Given encoded message "12", it could be decoded as "AB" (1 2) or "L" (12).

The number of ways decoding "12" is 2.

```

- [357. Count Numbers with Unique Digits](#357) | [Leetcode](https://leetcode.com/problems/count-numbers-with-unique-digits/description/)
```
Given a non-negative integer n, count all numbers with unique digits, x, where 0 ≤ x < 10n.

Example:
Given n = 2, return 91. (The answer should be the total numbers in the range of 0 ≤ x < 100, excluding [11,22,33,44,55,66,77,88,99])
```

- [17. Letter Combinations of a Phone Number](#17) | [Leetcode](https://leetcode.com/problems/letter-combinations-of-a-phone-number/description/)
```
Given a digit string, return all possible letter combinations that the number could represent.
Input:Digit string "23"
Output: ["ad", "ae", "af", "bd", "be", "bf", "cd", "ce", "cf"].
```

- [322. Coin Change](322#) | [Leetcode](https://leetcode.com/problems/coin-change/description/)
```
You are given coins of different denominations and a total amount of money amount. Write a function to compute the fewest number of coins that you need to make up that amount. If that amount of money cannot be made up by any combination of the coins, return -1.

Example 1:
coins = [1, 2, 5], amount = 11
return 3 (11 = 5 + 5 + 1)

Example 2:
coins = [2], amount = 3
return -1.

Note:
You may assume that you have an infinite number of each kind of coin.
```

- [53. Maximum Subarray](#53) | [Leetcode](https://leetcode.com/problems/maximum-subarray/description/)
```
Find the contiguous subarray within an array (containing at least one number) which has the largest sum.

For example, given the array [-2,1,-3,4,-1,2,1,-5,4],
the contiguous subarray [4,-1,2,1] has the largest sum = 6.
```

- [70. Climbing Stairs](#70) | [Leetcode](https://leetcode.com/problems/climbing-stairs/description/)
```
You are climbing a stair case. It takes n steps to reach to the top.

Each time you can either climb 1 or 2 steps. In how many distinct ways can you climb to the top?

Note: Given n will be a positive integer.
```

- [62. Unique Paths](#62) | [Leetcode](https://leetcode.com/problems/unique-paths/description/)
```
A robot is located at the top-left corner of a m x n grid (marked 'Start' in the diagram below).

The robot can only move either down or right at any point in time. The robot is trying to reach the bottom-right corner of the grid (marked 'Finish' in the diagram below).

How many possible unique paths are there?
```

- [140. Word Break II](#140) | [Leetcode](https://leetcode.com/problems/word-break-ii/description/)
```
Given a non-empty string s and a dictionary wordDict containing a list of non-empty words, add spaces in s to construct a sentence where each word is a valid dictionary word. You may assume the dictionary does not contain duplicate words.

Return all such possible sentences.

For example, given
s = "catsanddog",
dict = ["cat", "cats", "and", "sand", "dog"].

A solution is ["cats and dog", "cat sand dog"].
```

- [221. Maximal Square](#221) | [Leetcode](https://leetcode.com/problems/maximal-square/description/)
```
Given a 2D binary matrix filled with 0's and 1's, find the largest square containing only 1's and return its area.

For example, given the following matrix:

1 0 1 0 0
1 0 1 1 1
1 1 1 1 1
1 0 0 1 0
Return 4.
```

## SEARCH

- [74. Search a 2D Matrix](#74) | [Leetcode](https://leetcode.com/problems/search-a-2d-matrix/description/)
```
Write an efficient algorithm that searches for a value in an m x n matrix. This matrix has the following properties:

Integers in each row are sorted from left to right.
The first integer of each row is greater than the last integer of the previous row.
For example,

Consider the following matrix:

[
  [1,   3,  5,  7],
  [10, 11, 16, 20],
  [23, 30, 34, 50]
]
Given target = 3, return true.
```

- [240. Search a 2D Matrix II](#240) | [Leetcode](https://leetcode.com/problems/search-a-2d-matrix-ii/description/)
```
Write an efficient algorithm that searches for a value in an m x n matrix. This matrix has the following properties:

Integers in each row are sorted in ascending from left to right.
Integers in each column are sorted in ascending from top to bottom.
For example,

Consider the following matrix:

[
  [1,   4,  7, 11, 15],
  [2,   5,  8, 12, 19],
  [3,   6,  9, 16, 22],
  [10, 13, 14, 17, 24],
  [18, 21, 23, 26, 30]
]
Given target = 5, return true.
Given target = 20, return false.
```

- [378. Kth Smallest Element in a Sorted Matrix](#378) | [Leetcode](https://leetcode.com/problems/kth-smallest-element-in-a-sorted-matrix/discuss/)
```
Given a n x n matrix where each of the rows and columns are sorted in ascending order, find the kth smallest element in the matrix.

Note that it is the kth smallest element in the sorted order, not the kth distinct element.

Example:

matrix = [
   [ 1,  5,  9],
   [10, 11, 13],
   [12, 13, 15]
],
k = 8,

return 13.
```


## BACK TRACKING

- [78. Subsets](#78) | [Leetcode](https://leetcode.com/problems/subsets/description/) [Discussion](https://discuss.leetcode.com/topic/46159/a-general-approach-to-backtracking-questions-in-java-subsets-permutations-combination-sum-palindrome-partitioning?page=1)
```
Given a set of distinct integers, nums, return all possible subsets (the power set).

Note: The solution set must not contain duplicate subsets.

For example,
If nums = [1,2,3], a solution is:

[
  [3],
  [1],
  [2],
  [1,2,3],
  [1,3],
  [2,3],
  [1,2],
  []
]
```

- [90. Subsets II](#90) | [Leetcode](https://leetcode.com/problems/subsets-ii/description/)

- [39. Combination Sum](#39) | [Leetcode](https://leetcode.com/problems/combination-sum/description/)
```
Given a set of candidate numbers (C) (without duplicates) and a target number (T), find all unique combinations in C where the candidate numbers sums to T.

The same repeated number may be chosen from C unlimited number of times.

Note:
All numbers (including target) will be positive integers.
The solution set must not contain duplicate combinations.
For example, given candidate set [2, 3, 6, 7] and target 7, 
A solution set is: 
[
  [7],
  [2, 2, 3]
]
```

- [46. Permutations](#46) | [Leetcode](https://leetcode.com/problems/permutations/description/)
```
Given a collection of distinct numbers, return all possible permutations.

For example,
[1,2,3] have the following permutations:
[
  [1,2,3],
  [1,3,2],
  [2,1,3],
  [2,3,1],
  [3,1,2],
  [3,2,1]
]
```

- [47. Permutations II](#47) | [Leetcode](https://leetcode.com/problems/permutations-ii/description/)
```
Given a collection of numbers that might contain duplicates, return all possible unique permutations.

For example,
[1,1,2] have the following unique permutations:
[
  [1,1,2],
  [1,2,1],
  [2,1,1]
]
```

- [282. Expression Add Operators](#282) | [Leetcode](https://leetcode.com/problems/expression-add-operators/description/)
```
Given a string that contains only digits 0-9 and a target value, return all possibilities to add binary operators (not unary) +, -, or * between the digits so they evaluate to the target value.

Examples: 
"123", 6 -> ["1+2+3", "1*2*3"] 
"232", 8 -> ["2*3+2", "2+3*2"]
"105", 5 -> ["1*0+5","10-5"]
"00", 0 -> ["0+0", "0-0", "0*0"]
"3456237490", 9191 -> []

```

- [131. Palindrome Partitioning](#131) | [Leetcode](https://leetcode.com/problems/palindrome-partitioning/description/)
```
Given a string s, partition s such that every substring of the partition is a palindrome.

Return all possible palindrome partitioning of s.

For example, given s = "aab",
Return

[
  ["aa","b"],
  ["a","a","b"]
]

```

- [278. First Bad Version](#278) | [Leetcode](https://leetcode.com/problems/first-bad-version/description/)
```
You are a product manager and currently leading a team to develop a new product. Unfortunately, the latest version of your product fails the quality check. Since each version is developed based on the previous version, all the versions after a bad version are also bad.

Suppose you have n versions [1, 2, ..., n] and you want to find out the first bad one, which causes all the following ones to be bad.

You are given an API bool isBadVersion(version) which will return whether version is bad. Implement a function to find the first bad version. You should minimize the number of calls to the API.
```

- [268. Missing Number](#268) | [Leetcode](https://leetcode.com/problems/missing-number/description/) | [Discussion](https://discuss.leetcode.com/topic/23427/3-different-ideas-xor-sum-binary-search-java-code/2)
```
Given an array containing n distinct numbers taken from 0, 1, 2, ..., n, find the one that is missing from the array.

For example,
Given nums = [0, 1, 3] return 2.

Note:
Your algorithm should run in linear runtime complexity. Could you implement it using only constant extra space complexity?
```

- [241. Different Ways to Add Parentheses](#241) | [Leetcode](https://leetcode.com/problems/different-ways-to-add-parentheses/description/)
```
Given a string of numbers and operators, return all possible results from computing all the different possible ways to group numbers and operators. The valid operators are +, - and *.


Example 1
Input: "2-1-1".

((2-1)-1) = 0
(2-(1-1)) = 2
Output: [0, 2]


Example 2
Input: "2*3-4*5"

(2*(3-(4*5))) = -34
((2*3)-(4*5)) = -14
((2*(3-4))*5) = -10
(2*((3-4)*5)) = -10
(((2*3)-4)*5) = 10
Output: [-34, -14, -10, -10, 10]
```

- [22. Generate Parentheses](#22) | [Leetcode](https://leetcode.com/problems/generate-parentheses/description/)
```
Given n pairs of parentheses, write a function to generate all combinations of well-formed parentheses.

For example, given n = 3, a solution set is:

[
  "((()))",
  "(()())",
  "(())()",
  "()(())",
  "()()()"
]
```


## DFS, BFS

- [200. Number of Islands](#200) | [Leetcode](https://leetcode.com/problems/number-of-islands/description/) | [Discussion](https://discuss.leetcode.com/topic/33947/java-union-find-solution)
```
Given a 2d grid map of '1's (land) and '0's (water), count the number of islands. An island is surrounded by water and is formed by connecting adjacent lands horizontally or vertically. You may assume all four edges of the grid are all surrounded by water.

Example 1:

11110
11010
11000
00000
Answer: 1

Example 2:

11000
11000
00100
00011
Answer: 3
```

- [257. Binary Tree Paths](#257) | [Leetcode](https://leetcode.com/problems/binary-tree-paths/description/)
```
Given a binary tree, return all root-to-leaf paths.

For example, given the following binary tree:

   1
 /   \
2     3
 \
  5
All root-to-leaf paths are:

["1->2->5", "1->3"]

```

- [79. Word Search](#79) | [Leetcode](https://leetcode.com/problems/word-search/description/)
```
Given a 2D board and a word, find if the word exists in the grid.

The word can be constructed from letters of sequentially adjacent cell, where "adjacent" cells are those horizontally or vertically neighboring. The same letter cell may not be used more than once.

For example,
Given board =

[
  ['A','B','C','E'],
  ['S','F','C','S'],
  ['A','D','E','E']
]
word = "ABCCED", -> returns true,
word = "SEE", -> returns true,
word = "ABCB", -> returns false.
```

- [212. Word Search II](#212) | [Leetcode](https://leetcode.com/problems/word-search-ii/discuss/)
```
Given a 2D board and a list of words from the dictionary, find all words in the board.

Each word must be constructed from letters of sequentially adjacent cell, where "adjacent" cells are those horizontally or vertically neighboring. The same letter cell may not be used more than once in a word.

For example,
Given words = ["oath","pea","eat","rain"] and board =

[
  ['o','a','a','n'],
  ['e','t','a','e'],
  ['i','h','k','r'],
  ['i','f','l','v']
]
Return ["eat","oath"].
```

- [301. Remove Invalid Parentheses](#301) | [Leetcode](https://leetcode.com/problems/remove-invalid-parentheses/description/) | [Discussion](https://discuss.leetcode.com/topic/34875/easy-short-concise-and-fast-java-dfs-3-ms-solution/19)
```
Remove the minimum number of invalid parentheses in order to make the input string valid. Return all possible results.

Note: The input string may contain letters other than the parentheses ( and ).

Examples:
"()())()" -> ["()()()", "(())()"]
"(a)())()" -> ["(a)()()", "(a())()"]
")(" -> [""]
```

- [297. Serialize and Deserialize Binary Tree](#297) | [Leetcode](https://leetcode.com/problems/serialize-and-deserialize-binary-tree/description/) | [Discussion](https://discuss.leetcode.com/topic/34875/easy-short-concise-and-fast-java-dfs-3-ms-solution/19)
```
Remove the minimum number of invalid parentheses in order to make the input string valid. Return all possible results.

Note: The input string may contain letters other than the parentheses ( and ).

Examples:
"()())()" -> ["()()()", "(())()"]
"(a)())()" -> ["(a)()()", "(a())()"]
")(" -> [""]
```

## MATH

- [415. Add Strings](#415) | [Leetcode](https://leetcode.com/problems/add-strings/discuss/)
```
Given two non-negative integers num1 and num2 represented as string, return the sum of num1 and num2.

Note:

The length of both num1 and num2 is < 5100.
Both num1 and num2 contains only digits 0-9.
Both num1 and num2 does not contain any leading zero.
You must not use any built-in BigInteger library or convert the inputs to integer directly.
```

- [215. Kth Largest Element in an Array](#215) | [Leetcode](https://leetcode.com/problems/kth-largest-element-in-an-array/description/) | [Discussion](https://discuss.leetcode.com/topic/14597/solution-explained)
```
Find the kth largest element in an unsorted array. Note that it is the kth largest element in the sorted order, not the kth distinct element.

For example,
Given [3,2,1,5,6,4] and k = 2, return 5.
```

- [398. Random Pick Index](#398) | [Leetcode](https://leetcode.com/problems/random-pick-index/description/) | [Discussion](https://discuss.leetcode.com/topic/58301/simple-reservoir-sampling-solution/13) | [Wiki](https://en.wikipedia.org/wiki/Reservoir_sampling)
```
Given an array of integers with possible duplicates, randomly output the index of a given target number. You can assume that the given target number must exist in the array.

Note:
The array size can be very large. Solution that uses too much extra space will not pass the judge.

Example:

int[] nums = new int[] {1,2,3,3,3};
Solution solution = new Solution(nums);

// pick(3) should return either index 2, 3, or 4 randomly. Each index should have equal probability of returning.
solution.pick(3);

// pick(1) should return 0. Since in the array only nums[0] is equal to 1.
solution.pick(1);
```

- [208. Implement Trie (Prefix Tree)](#208) | [Leetcode](https://leetcode.com/problems/implement-trie-prefix-tree/description/)
```
Implement a trie with insert, search, and startsWith methods.
Note:
You may assume that all inputs are consist of lowercase letters a-z.
```

- [211. Add and Search Word - Data structure design](#211) | [Leetcode](https://leetcode.com/problems/add-and-search-word-data-structure-design/discuss/)
```
Design a data structure that supports the following two operations:

void addWord(word)
bool search(word)
search(word) can search a literal word or a regular expression string containing only letters a-z or .. A . means it can represent any one letter.

For example:

addWord("bad")
addWord("dad")
addWord("mad")
search("pad") -> false
search("bad") -> true
search(".ad") -> true
search("b..") -> true
```

- [43. Multiply Strings](#43) | [Leetcode](https://leetcode.com/problems/multiply-strings/description/) | [Discussion](https://discuss.leetcode.com/topic/30508/easiest-java-solution-with-graph-explanation)
```
Given two non-negative integers num1 and num2 represented as strings, return the product of num1 and num2.

Note:

The length of both num1 and num2 is < 110.
Both num1 and num2 contains only digits 0-9.
Both num1 and num2 does not contain any leading zero.
You must not use any built-in BigInteger library or convert the inputs to integer directly.
```

- [7. Reverse Integer](#7) | [Leetcode](https://leetcode.com/problems/reverse-integer/description/)
```
Reverse digits of an integer.

Example1: x = 123, return 321
Example2: x = -123, return -321

If the integer's last digit is 0, what should the output be? ie, cases such as 10, 100.

Did you notice that the reversed integer might overflow? Assume the input is a 32-bit integer, then the reverse of 1000000003 overflows. How should you handle such cases?

For the purpose of this problem, assume that your function returns 0 when the reversed integer overflows.
```

- [13. Roman to Integer](#13) | [Leetcode](https://leetcode.com/problems/roman-to-integer/description/)

- [12. Integer to Roman](#12) | [Leetcode](https://leetcode.com/problems/integer-to-roman/description/)

- [29. Divide Two Integers](#29) | [Leetcode](https://leetcode.com/problems/divide-two-integers/description/)

## LINKED LIST

- [237. Delete Node in a Linked List](#237) | [Leetcode](https://leetcode.com/problems/delete-node-in-a-linked-list/description/)
```
Write a function to delete a node (except the tail) in a singly linked list, given only access to that node.

Supposed the linked list is 1 -> 2 -> 3 -> 4 and you are given the third node with value 3, the linked list should become 1 -> 2 -> 4 after calling your function.
```

- [82. Remove Duplicates from Sorted List II](#82) | [Leetcode](https://leetcode.com/problems/remove-duplicates-from-sorted-list-ii/discuss/)
```
Given a sorted linked list, delete all nodes that have duplicate numbers, leaving only distinct numbers from the original list.

For example,
Given 1->2->3->3->4->4->5, return 1->2->5.
Given 1->1->1->2->3, return 2->3.
```

- [83. Remove Duplicates from Sorted List](#83) | [Leetcode](https://leetcode.com/problems/remove-duplicates-from-sorted-list/description/)
```
Given a sorted linked list, delete all duplicates such that each element appear only once.

For example,
Given 1->1->2, return 1->2.
Given 1->1->2->3->3, return 1->2->3.
```

- [206. Reverse Linked List](#206) | [Leetcode](https://leetcode.com/problems/reverse-linked-list/description/)

- [160. Intersection of Two Linked Lists](#160) | [Leetcode](https://leetcode.com/problems/intersection-of-two-linked-lists/description/)
```
Write a program to find the node at which the intersection of two singly linked lists begins.

For example, the following two linked lists:

A:          a1 → a2
                   ↘
                     c1 → c2 → c3
                   ↗            
B:     b1 → b2 → b3
begin to intersect at node c1.
```

- [143. Reorder List](#143) | [Leetcode](https://leetcode.com/problems/reorder-list/description/)
```
Given a singly linked list L: L0→L1→…→Ln-1→Ln,
reorder it to: L0→Ln→L1→Ln-1→L2→Ln-2→…

You must do this in-place without altering the nodes' values.

For example,
Given {1,2,3,4}, reorder it to {1,4,2,3}.
```

- [141. Linked List Cycle](#141) | [Leetcode](https://leetcode.com/problems/linked-list-cycle/description/)

- [142. Linked List Cycle II](#142) | [Leetcode](https://leetcode.com/problems/linked-list-cycle-ii/description/) | [Discussion](https://discuss.leetcode.com/topic/5284/concise-o-n-solution-by-using-c-with-detailed-alogrithm-description)
```
Given a linked list, return the node where the cycle begins. If there is no cycle, return null.

Note: Do not modify the linked list.
```

- [287. Find the Duplicate Number](#287) | [Leetcode](https://leetcode.com/problems/find-the-duplicate-number/description/)
```
Given an array nums containing n + 1 integers where each integer is between 1 and n (inclusive), prove that at least one duplicate number must exist. Assume that there is only one duplicate number, find the duplicate one.

Note:
You must not modify the array (assume the array is read only).
You must use only constant, O(1) extra space.
Your runtime complexity should be less than O(n2).
There is only one duplicate number in the array, but it could be repeated more than once.
```

- [2. Add Two Numbers](#2) | [Leetcode](https://leetcode.com/problems/add-two-numbers/description/)
```
You are given two non-empty linked lists representing two non-negative integers. The digits are stored in reverse order and each of their nodes contain a single digit. Add the two numbers and return it as a linked list.

You may assume the two numbers do not contain any leading zero, except the number 0 itself.

Input: (2 -> 4 -> 3) + (5 -> 6 -> 4)
Output: 7 -> 0 -> 8
```

- [445. Add Two Numbers II](#445) | [Leetcode](https://leetcode.com/problems/add-two-numbers-ii/description/)
```
You are given two non-empty linked lists representing two non-negative integers. The most significant digit comes first and each of their nodes contain a single digit. Add the two numbers and return it as a linked list.

You may assume the two numbers do not contain any leading zero, except the number 0 itself.

Follow up:
What if you cannot modify the input lists? In other words, reversing the lists is not allowed.

Example:

Input: (7 -> 2 -> 4 -> 3) + (5 -> 6 -> 4)
Output: 7 -> 8 -> 0 -> 7
```

- [Find the kth last element in a linked list](#ftkleill) | [Answer](http://www.growingwiththeweb.com/2015/08/find-the-kth-last-element-in-a-linked-list.html)
```
Find the kth to the last element on a single linked list

i.e. if the list is { 1, 4, 6, 3, 6, 7 }

when k = 2, kth to last is 6.

when k = 1, kth to last is 7.

when k = 10000, kth is null, since there aren't that many items on the list
```



## CODE

### <a name=""></a>
```java

```

### <a name=""></a>
```java

```

### <a name=""></a>
```java

```

### <a name=""></a>
```java

```

### <a name=""></a>
```java

```

### <a name=""></a>
```java

```

### <a name=""></a>
```java

```

### <a name=""></a>
```java

```

### <a name=""></a>
```java

```

### <a name=""></a>
```java

```

### <a name=""></a>
```java

```

### <a name=""></a>
```java

```

### <a name=""></a>
```java

```

### <a name=""></a>
```java

```

### <a name=""></a>
```java

```

### <a name=""></a>
```java

```
### <a name=""></a>
```java

```

### <a name=""></a>
```java

```

### <a name=""></a>
```java

```

### <a name=""></a>
```java

```

### <a name="383"></a>383. Ransom Note
```java
public class Solution {
    public boolean canConstruct(String ransomNote, String magazine) {
        int[] arr = new int[26];
        for (int i = 0; i < magazine.length(); i++) {
            arr[magazine.charAt(i) - 'a']++;
        }
        for (int i = 0; i < ransomNote.length(); i++) {
            if(--arr[ransomNote.charAt(i)-'a'] < 0) {
                return false;
            }
        }
        return true;
    }
}

// or using a map
public boolean canConstruct(String ransomNote, String magazine) {
        Map<Character, Integer> magM = new HashMap<>();
        for (char c:magazine.toCharArray()){
            int newCount = magM.getOrDefault(c, 0)+1;
            magM.put(c, newCount);
        }
        for (char c:ransomNote.toCharArray()){
            int newCount = magM.getOrDefault(c,0)-1;
            if (newCount<0)
                return false;
            magM.put(c, newCount);
        }
        return true;
    }
```

### <a name="41"></a>41. First Missing Positive
```java
public class Solution {
    public int firstMissingPositive(int[] A) {
        int i = 0;
        while(i < A.length){
            if(A[i] == i+1 || A[i] <= 0 || A[i] > A.length) i++;
            else if(A[A[i]-1] != A[i]) swap(A, i, A[i]-1);
            else i++;
        }
        i = 0;
        while(i < A.length && A[i] == i+1) i++;
        return i+1;
    }
    
    private void swap(int[] A, int i, int j){
        int temp = A[i];
        A[i] = A[j];
        A[j] = temp;
    }
}
```

### <a name="ftkleill"></a>Find the kth last element in a linked list
```java
/**
 * Gets the kth last element of a linked list.
 *
 * @param head The head of the linked list.
 * @param k The number of elements to count backward.
 * @return The kth last element of the linked list, if it is not large
 * enough, return 0.
 */
public static LinkedList getKthLastElement(LinkedList head, int k) {
    if (head == null || k < 1) {
        return null;
    }

    LinkedList current = head;
    LinkedList nBehindCurrent = head;

    for (int i = 0; i < k - 1; i++) {
        current = current.next;
        if (current == null) {
            return null;
        }
    }

    while (current.next != null) {
        nBehindCurrent = nBehindCurrent.next;
        current = current.next;
    }

    return nBehindCurrent;
}
```

### <a name="344"></a>344. Reverse String
```java
public class Solution {
    public String reverseString(String s) {
        char[] word = s.toCharArray();
        int i = 0;
        int j = s.length() - 1;
        while (i < j) {
            char temp = word[i];
            word[i] = word[j];
            word[j] = temp;
            i++;
            j--;
        }
        return new String(word);
    }
}
```


### <a name="funis"></a>First Unique Number In Stream
```java
public class Solution {
    /*
     * @param : a continuous stream of numbers
     * @param : a number
     * @return: returns the first unique number
     */
    public int firstUniqueNumber(int[] nums, int number) {
        // Write your code here
        if (nums == null || nums.length == 0) {
            return -1;
        }
        
        Deque<Integer> queue = new LinkedList<>();
        Set<Integer> hash = new HashSet<>();
        
        for (int n : nums) {
            if (hash.contains(n)) {
                // int index = queue.indexOf(n);
                // queue.remove(index);
                queue.removeFirstOccurrence(n);
            } else {
                hash.add(n);
                queue.offer(n);
            }
            if (n == number) {
                return queue.peek();
            }
        }
        
        return -1;
    }
};
```

### <a name="249"></a>249. Group Shifted Strings
```java
class Solution {
    public List<List<String>> groupStrings(String[] strings) {
        List<List<String>> result = new ArrayList<>();
        if (strings == null) return result;
        
        Map<String, List<String>> hm = new HashMap<>();
        for (String str : strings) {
            String code = encoder(str);
            List<String> group = hm.getOrDefault(code, new ArrayList<>());
            group.add(str);
            hm.put(code, group);
        }
        
        for (List<String> group : hm.values()) {
            result.add(group);
        }
        
        return result;
    }
    
    private String encoder(String input) {
        StringBuilder sb = new StringBuilder();
        for (int i = 0; i < input.length() - 1; i ++) {
            int diff = input.charAt(i + 1) - input.charAt(i);
            if (diff < 0) {
                diff = 26 + diff;
            }
            sb.append(String.valueOf(diff));
        }
        return sb.toString();
    }
}
```

### <a name="118"></a>118. Pascal's Triangle
```java
class Solution {
    public List<List<Integer>> generate(int numRows) {
        List<List<Integer>> result = new ArrayList<>();
        List<Integer> thisRow = new ArrayList<>();
        
        for (int i = 0; i < numRows; i ++) {
            thisRow.add(0, 1);
            for (int j = 1; j < thisRow.size() - 1; j ++) {
                thisRow.set(j, thisRow.get(j) + thisRow.get(j + 1));
            }
            result.add(new ArrayList<>(thisRow)); // avoid passing by reference
        }
        return result;
    }
}
```

### <a name="22"></a>22. Generate Parentheses
```java
/*
The idea here is to only add '(' and ')' that we know will guarantee us a solution (instead of adding 1 too many close). Once we add a '(' we will then discard it and try a ')' which can only close a valid '('. Each of these steps are recursively called.
*/
// O(2^n)
public List<String> generateParenthesis(int n) {
        List<String> list = new ArrayList<String>();
        backtrack(list, "", 0, 0, n);
        return list;
    }
    
    public void backtrack(List<String> list, String str, int open, int close, int max){
        
        if(str.length() == max*2){
            list.add(str);
            return;
        }
        
        if(open < max)
            backtrack(list, str+"(", open+1, close, max);
        if(close < open)
            backtrack(list, str+")", open, close+1, max);
    }
```

### <a name="435"></a>435. Non-overlapping Intervals
```java
/*
Sorting Interval.end in ascending order is O(nlogn), then traverse intervals array to get the maximum number of non-overlapping intervals is O(n). Total is O(nlogn).
*/
 public int eraseOverlapIntervals(Interval[] intervals) {
        if (intervals.length == 0)  return 0;

        Arrays.sort(intervals, new myComparator());
        int end = intervals[0].end;
        int count = 1;        

        for (int i = 1; i < intervals.length; i++) {
            if (intervals[i].start >= end) {
                end = intervals[i].end;
                count++;
            }
        }
        return intervals.length - count;
    }
    
    class myComparator implements Comparator<Interval> {
        public int compare(Interval a, Interval b) {
            return a.end - b.end;
        }
    }
```

### <a name="105"></a>105. Construct Binary Tree from Preorder and Inorder Traversal
```java
/*
The basic idea is here:
Say we have 2 arrays, PRE and IN.
Preorder traversing implies that PRE[0] is the root node.
Then we can find this PRE[0] in IN, say it's IN[5].
Now we know that IN[5] is root, so we know that IN[0] - IN[4] is on the left side, IN[6] to the end is on the right side.
Recursively doing this on subarrays, we can build a tree out of it :)
*/
public TreeNode buildTree(int[] preorder, int[] inorder) {
    return helper(0, 0, inorder.length - 1, preorder, inorder);
}

public TreeNode helper(int preStart, int inStart, int inEnd, int[] preorder, int[] inorder) {
    if (preStart > preorder.length - 1 || inStart > inEnd) {
        return null;
    }
    TreeNode root = new TreeNode(preorder[preStart]);
    int inIndex = 0; // Index of current root in inorder
    for (int i = inStart; i <= inEnd; i++) {
        if (inorder[i] == root.val) {
            inIndex = i;
        }
    }
    root.left = helper(preStart + 1, inStart, inIndex - 1, preorder, inorder);
    root.right = helper(preStart + inIndex - inStart + 1, inIndex + 1, inEnd, preorder, inorder);
    return root;
}
```

### <a name="378"></a>378. Kth Smallest Element in a Sorted Matrix
```java
public class Solution {
    public int kthSmallest(int[][] matrix, int k) {
        int lo = matrix[0][0], hi = matrix[matrix.length - 1][matrix[0].length - 1] + 1;//[lo, hi)
        while(lo < hi) {
            int mid = lo + (hi - lo) / 2;
            int count = 0,  j = matrix[0].length - 1;
            for(int i = 0; i < matrix.length; i++) {
                while(j >= 0 && matrix[i][j] > mid) j--;
                count += (j + 1);
            }
            if(count < k) lo = mid + 1;
            else hi = mid;
        }
        return lo;
    }
}
```

### <a name="221"></a>221. Maximal Square
```java
/*
Logic :

Top, Left, and Top Left decides the size of the square. If all of them are same, then the size of square increases by 1. If they're not same, they can increase by 1 to the minimal square. If you take an example and work it out, it'll be much easier to understand when it comes to dynamic programing. :)
*/
public int maximalSquare(char[][] a) {
    if(a.length == 0) return 0;
    int m = a.length, n = a[0].length, result = 0;
    int[][] b = new int[m+1][n+1];
    for (int i = 1 ; i <= m; i++) {
        for (int j = 1; j <= n; j++) {
            if(a[i-1][j-1] == '1') {
                b[i][j] = Math.min(Math.min(b[i][j-1] , b[i-1][j-1]), b[i-1][j]) + 1;
                result = Math.max(b[i][j], result); // update result
            }
        }
    }
    return result*result;
}


public int maximalSquare(char[][] a) {
  if (a == null || a.length == 0 || a[0].length == 0)
    return 0;
      
  int max = 0, n = a.length, m = a[0].length;
  
  // dp(i, j) represents the length of the square 
  // whose lower-right corner is located at (i, j)
  // dp(i, j) = min{ dp(i-1, j-1), dp(i-1, j), dp(i, j-1) }
  int[][] dp = new int[n + 1][m + 1];
  
  for (int i = 1; i <= n; i++) {
    for (int j = 1; j <= m; j++) {
      if (a[i - 1][j - 1] == '1') {
        dp[i][j] = Math.min(dp[i - 1][j - 1], Math.min(dp[i - 1][j], dp[i][j - 1])) + 1;
        max = Math.max(max, dp[i][j]);
      }
    }
  }
  
  // return the area
  return max * max;
}
```

### <a name="212"></a>212. Word Search II
```java
// the best solution
public List<String> findWords(char[][] board, String[] words) {
    List<String> res = new ArrayList<>();
    TrieNode root = buildTrie(words);
    for (int i = 0; i < board.length; i++) {
        for (int j = 0; j < board[0].length; j++) {
            dfs (board, i, j, root, res);
        }
    }
    return res;
}

public void dfs(char[][] board, int i, int j, TrieNode p, List<String> res) {
    char c = board[i][j];
    if (c == '#' || p.next[c - 'a'] == null) return;
    p = p.next[c - 'a'];
    if (p.word != null) {   // found one
        res.add(p.word);
        p.word = null;     // de-duplicate
    }

    board[i][j] = '#';
    if (i > 0) dfs(board, i - 1, j ,p, res); 
    if (j > 0) dfs(board, i, j - 1, p, res);
    if (i < board.length - 1) dfs(board, i + 1, j, p, res); 
    if (j < board[0].length - 1) dfs(board, i, j + 1, p, res); 
    board[i][j] = c;
}

public TrieNode buildTrie(String[] words) {
    TrieNode root = new TrieNode();
    for (String w : words) {
        TrieNode p = root;
        for (char c : w.toCharArray()) {
            int i = c - 'a';
            if (p.next[i] == null) p.next[i] = new TrieNode();
            p = p.next[i];
       }
       p.word = w;
    }
    return root;
}

class TrieNode {
    TrieNode[] next = new TrieNode[26];
    String word;
}

// need to implement Trie!!
public class Solution {
    Set<String> res = new HashSet<String>();
    
    public List<String> findWords(char[][] board, String[] words) {
        Trie trie = new Trie();
        for (String word : words) {
            trie.insert(word);
        }
        
        int m = board.length;
        int n = board[0].length;
        boolean[][] visited = new boolean[m][n];
        for (int i = 0; i < m; i++) {
            for (int j = 0; j < n; j++) {
                dfs(board, visited, "", i, j, trie);
            }
        }
        
        return new ArrayList<String>(res);
    }
    
    public void dfs(char[][] board, boolean[][] visited, String str, int x, int y, Trie trie) {
        if (x < 0 || x >= board.length || y < 0 || y >= board[0].length) return;
        if (visited[x][y]) return;
        
        str += board[x][y];
        if (!trie.startsWith(str)) return;
        
        if (trie.search(str)) {
            res.add(str);
        }
        
        visited[x][y] = true;
        dfs(board, visited, str, x - 1, y, trie);
        dfs(board, visited, str, x + 1, y, trie);
        dfs(board, visited, str, x, y - 1, trie);
        dfs(board, visited, str, x, y + 1, trie);
        visited[x][y] = false;
    }
}
```

### <a name="71"></a>71. Simplify Path
```java
class Solution {
    public String simplifyPath(String path) {
        if (path == null || path.length() == 0) return "";
        Stack<String> stack = new Stack<>();
        
        for (String dir : path.split("/")) {
            if (dir.equals("..")) {
                if (!stack.isEmpty()) {
                    stack.pop();
                }
                continue;
            }
            else if (!dir.equals("") && !dir.equals(".")) {
                stack.push(dir);
            }
        }
        
        String result = "";
        while (!stack.empty()) {
            result = "/" + stack.pop() + result;
        }
        
        return (result.equals("")) ? "/" : result;
    }
}
```

### <a name="14"></a>14. Longest Common Prefix
```java
// O(n * K^2) n: strs.length, K: average length of elements in strs
class Solution {
    public String longestCommonPrefix(String[] strs) {
        if (strs == null || strs.length == 0) return "";
        String commonPrefix = strs[0];
        
        for (int i = 1; i < strs.length; i ++) {
            while (strs[i].indexOf(commonPrefix) != 0) { // K + K -1 + K -2.... 1
                if (commonPrefix.length() == 0) return "";
                commonPrefix = commonPrefix.substring(0, commonPrefix.length() - 1);
            }
        }
        
        return commonPrefix;
    }
}

```

### <a name="205"></a>205. Isomorphic Strings
```java
// use a hashmap to store relationship between characters
// case 1: character in A point to another character in B
// case 2: character in B alreay been pointed by another character in A
class Solution {
    public boolean isIsomorphic(String s, String t) {
        if (s == null || t == null || s.length() != t.length()) return false;
        Map<Character, Character> hm = new HashMap<>();
        for (int i = 0; i < s.length(); i ++) {
            char charS = s.charAt(i);
            char charT = t.charAt(i);
            if (hm.containsKey(charS)) {
                if (!hm.get(charS).equals(charT)) {
                    return false;
                }
            } else {
                if (hm.containsValue(charT)) {
                    return false;
                } else {
                    hm.put(charS, charT);
                }
            }
        }
        return true;
    }
}


/* */
class Solution {
    public bool isIsomorphic(string s, string t) {
        int m1[256] = {0}, m2[256] = {0}, n = s.size();
        for (int i = 0; i < n; ++i) {
            if (m1[s[i]] != m2[t[i]]) return false;
            m1[s[i]] = i + 1;
            m2[t[i]] = i + 1;
        }
        return true;
    }
};
```

### <a name="241"></a>241. Different Ways to Add Parentheses
```java
class Solution {
    // private Map<String, List<Integer>> map = new HashMap<>(); Not helpful at all!!!
    
    public List<Integer> diffWaysToCompute(String input) {
        List<Integer> result = new ArrayList<>();
        for(int i = 0; i < input.length(); i++) {
            char c = input.charAt(i);
            if (c == '-' || c == '+' || c == '*') {
                String partA = input.substring(0, i);
                String partB = input.substring(i + 1, input.length());
                List<Integer> listA = diffWaysToCompute(partA);
                List<Integer> listB = diffWaysToCompute(partB);
                /*
                List<Integer> listA = map.getOrDefault(partA, diffWaysToCompute(partA));
                List<Integer> listB = map.getOrDefault(partB, diffWaysToCompute(partB));
                if (!map.containsKey(partA)) {
                    map.put(partA, listA);
                }
                if (!map.containsKey(partB)) {
                    map.put(partB, listB);
                }
                */

                for (Integer a : listA) {
                    for (Integer b : listB) {
                        if (c == '-') result.add(a - b);
                        else if (c == '+') result.add(a + b);
                        else result.add(a * b);
                    }
                }
            }
        }
        
        if (result.size() == 0) {
            result.add(Integer.valueOf(input));
        }
       // map.put(input, result);
        return result;
    }
}
```

### <a name="140"></a>140. Word Break II
```java
/*
Time complexity is O(len(wordDict) ^ len(s / minWordLenInDict)), because there're len(wordDict) possibilities for each cut
*/
class Solution {
    public List<String> wordBreak(String s, List<String> wordDict) {
        return DFS(s, wordDict, new HashMap<String, List<String>>());
    }
    
    public List<String> DFS(String s, List<String> wordDict, Map<String, List<String>> hm) {
        if (hm.containsKey(s)) {
            return hm.get(s);
        }
        
        List<String> result = new ArrayList<>();
        if (s.length() == 0) {
            result.add("");
            return result;
        }
        
        for (String word : wordDict) {
            if (s.startsWith(word)) {
                List<String> subResult = DFS(s.substring(word.length()), wordDict, hm);
                for (String sub : subResult) {
                    String sentence = word;
                    if (sub != "") {
                        sentence += " " + sub;
                    }
                    result.add(sentence);
                }
            }
        }
        hm.put(s, result);
        return result;
    }
}
```

### <a name="318"></a>318. Maximum Product of Word Lengths
```java
/*
ok,int has 32bits,but lower case letters only has 26 .we can use the lowest 26 bit of int indicates that the word has how many kinds of lower case letters .If the lowest bit of int is 1,it indicates the word has lower case letter 'a'.......the order of lower case letter is from right to left,like zyx.....cba.so value[i] indicates the condition of the word i having how many kinds of lower case letters .please vote me for this problem! If you have any question ,please follow up!

The reason use 1<< is that let the value of 'a' to be 1?
Yes, otherwise, 'a' will be missed since 'a' - 'a' = 0.

*/
class Solution {
    public int maxProduct(String[] words) {
        if (words == null || words.length == 0) return 0;
        int[] wordCode = new int[words.length];
        for (int i = 0; i < words.length; i ++) {
            int code = 0;
            for (char c : words[i].toCharArray()) {
                code |= 1 << (c - 'a');
            }
            wordCode[i] = code;
        }
        int maxProduct = Integer.MIN_VALUE;
        for (int i = 0; i < words.length; i++) {
            for (int j = i + 1; j < words.length; j++) {
                if ((wordCode[i] & wordCode[j]) == 0) {
                    maxProduct = Math.max(maxProduct, words[i].length() * words[j].length());
                }
            }
        }
        
        return (maxProduct == Integer.MIN_VALUE) ? 0 : maxProduct;
    }
}
```

### <a name="381"></a>381. Insert Delete GetRandom O(1) - Duplicates allowed
```java
class RandomizedCollection {
    private Random random;
    private List<Integer> values;
    private Map<Integer, Set<Integer>> locationMap;
    
    /** Initialize your data structure here. */
    public RandomizedCollection() {
        random = new Random();
        values = new ArrayList<>();
        locationMap = new HashMap<>();
    }
    
    /** Inserts a value to the collection. Returns true if the collection did not already contain the specified element. */
    public boolean insert(int val) {
        boolean exist = locationMap.containsKey(val);
        Set<Integer> locations = locationMap.getOrDefault(val, new HashSet<>());
        locations.add(values.size());
        locationMap.put(val, locations);
        values.add(val);
        
        return !exist;
    }
    
    /** Removes a value from the collection. Returns true if the collection contained the specified element. */
    public boolean remove(int val) {
        if (!locationMap.containsKey(val) || locationMap.get(val).size() == 0) {
            return false;
        }
        Set<Integer> locations = locationMap.get(val);
        // Get arbitary index of the ArrayList that contains val
        int index = locations.iterator().next();
        locations.remove(index);
        locationMap.put(val, locations);
        
        int replacedValue = values.remove(values.size() - 1);
        if (index != values.size()) {
            values.set(index, replacedValue);
            Set<Integer> replacedLocations = locationMap.get(replacedValue);
            replacedLocations.remove(values.size());
            replacedLocations.add(index);
            locationMap.put(replacedValue, replacedLocations);
        }
        
        return true;
    }
    
    /** Get a random element from the collection. */
    public int getRandom() {
        return values.get(random.nextInt(values.size()));
    }
}

/**
 * Your RandomizedCollection object will be instantiated and called as such:
 * RandomizedCollection obj = new RandomizedCollection();
 * boolean param_1 = obj.insert(val);
 * boolean param_2 = obj.remove(val);
 * int param_3 = obj.getRandom();
 */
```

### <a name="380"></a>380. Insert Delete GetRandom O(1)
```java
class RandomizedSet {
    private Random random;
    private Map<Integer, Integer> locationMap;
    private List<Integer> values;
    /** Initialize your data structure here. */
    public RandomizedSet() {
        this.random = new Random();
        this.locationMap = new HashMap<>();
        this.values = new ArrayList<>();
    }
    
    /** Inserts a value to the set. Returns true if the set did not already contain the specified element. */
    public boolean insert(int val) {
        if (locationMap.containsKey(val)) {
            return false;
        }
        locationMap.put(val, values.size());
        values.add(val);
        return true;
    }
    
    /** Removes a value from the set. Returns true if the set contained the specified element. */
    public boolean remove(int val) {
        if (!locationMap.containsKey(val)) {
            return false;
        }
        int index = locationMap.remove(val);
        int replacedValue = values.remove(values.size() - 1);
        
        if (index != values.size()) {
            locationMap.put(replacedValue, index);
            values.set(index, replacedValue);
        }
        return true;
    }
    
    /** Get a random element from the set. */
    public int getRandom() {
        return values.get(random.nextInt(values.size()));
    }
}

/**
 * Your RandomizedSet object will be instantiated and called as such:
 * RandomizedSet obj = new RandomizedSet();
 * boolean param_1 = obj.insert(val);
 * boolean param_2 = obj.remove(val);
 * int param_3 = obj.getRandom();
 */
```

### <a name="443"></a>443. String Compression
```java
class Solution {
    public int compress(char[] chars) {
        if (chars.length == 1) return 1;
        int left, right, count;
        for (left = 0, right = 0, count = 0; right < chars.length; right ++) {
            count ++;
            if (right == chars.length - 1 || chars[right + 1] != chars[right]) {
                chars[left ++] = chars[right];
                if (count != 1) {
                    char[] arr = String.valueOf(count).toCharArray();
                    for (char c : arr) {
                        chars[left ++] = c;
                    }
                }
                count = 0;
            }
        }
        return left;
    }
}
```

### <a name="126"></a>126. Word Ladder II
```java
/*
beginWord = "hit"
endWord = "cog"
wordList = ["hot","dot","dog","lot","log","cog"]

hot: [hit]
dot: [hot]
lot: [hot]
dog: [dot]
log: [lot]
cog: [dog, log]

cog, dog, dot, hot, hit
cog, log, lot, hot, hit

*/
class Solution {
    public List<List<String>> findLadders(String beginWord, String endWord, List<String> wordList) {
        if (beginWord == null || endWord == null || wordList == null || !wordList.contains(endWord)) return new ArrayList<>();
        Set<String> wordSet = new HashSet<>(wordList);
        Set<String> currentSet = new HashSet<>();
        Set<String> nextSet = new HashSet<>();
        Set<String> visitedSet = new HashSet<>();
        Map<String, List<String>> traceMap = new HashMap<>();
        List<List<String>> result = new ArrayList<>();
        boolean found = false;
        
        currentSet.add(beginWord);
        visitedSet.add(beginWord);
        
        while (!found && !currentSet.isEmpty()) {
            visitedSet.addAll(currentSet);
            
            for (String currentWord : currentSet) {
                List<String> neighbours = getValidNeighbours(currentWord, wordSet);
                for (String neighbour : neighbours) {
                    if (visitedSet.contains(neighbour)) continue;
                    
                    nextSet.add(neighbour);  
                    List<String> newList = traceMap.getOrDefault(neighbour, new ArrayList<>());
                    newList.add(currentWord);
                    traceMap.put(neighbour, newList);
                    if (neighbour.equals(endWord)) {
                        found = true;
                    }
                }
            }
            currentSet = new HashSet<>(nextSet);
            nextSet.clear();
        }
        if (found) {
            backTracking(result, new ArrayList<>(), traceMap, endWord);
        }
        return result;
    }
    
    public void backTracking(List<List<String>> result, List<String> oneSolution, Map<String, List<String>> traceMap, String word) {
        oneSolution.add(word);
        if (!traceMap.containsKey(word)) {
            ArrayList<String> solution = new ArrayList<>(oneSolution);
            Collections.reverse(solution);
            result.add(solution);
        } else {
            for (String neighbour : traceMap.get(word)) {
                backTracking(result, oneSolution, traceMap, neighbour);
            }
        }
        oneSolution.remove(oneSolution.size() - 1);
    }
    
    public List<String> getValidNeighbours(String word, Set<String> wordSet) {
        List<String> neighbours = new ArrayList<>();
        char[] wordCharArray = word.toCharArray();
        for (int i = 0; i < wordCharArray.length; i ++) {
            char replacedChar = wordCharArray[i];
            for (char c = 'a'; c <= 'z'; c ++) {
                wordCharArray[i] = c;
                String newWord = String.valueOf(wordCharArray);
                if (wordSet.contains(newWord)) {
                    neighbours.add(newWord);
                }
            }
            wordCharArray[i] = replacedChar;
        }
        return neighbours;
    }
}

// 
public List<List<String>> findLadders(String start, String end, List<String> wordList) {
   HashSet<String> dict = new HashSet<String>(wordList);
   List<List<String>> res = new ArrayList<List<String>>();         
   HashMap<String, ArrayList<String>> nodeNeighbors = new HashMap<String, ArrayList<String>>();// Neighbors for every node
   HashMap<String, Integer> distance = new HashMap<String, Integer>();// Distance of every node from the start node
   ArrayList<String> solution = new ArrayList<String>();

   dict.add(start);          
   bfs(start, end, dict, nodeNeighbors, distance);                 
   dfs(start, end, dict, nodeNeighbors, distance, solution, res);   
   return res;
}

// BFS: Trace every node's distance from the start node (level by level).
private void bfs(String start, String end, Set<String> dict, HashMap<String, ArrayList<String>> nodeNeighbors, HashMap<String, Integer> distance) {
  for (String str : dict)
      nodeNeighbors.put(str, new ArrayList<String>());

  Queue<String> queue = new LinkedList<String>();
  queue.offer(start);
  distance.put(start, 0);

  while (!queue.isEmpty()) {
      int count = queue.size();
      boolean foundEnd = false;
      for (int i = 0; i < count; i++) {
          String cur = queue.poll();
          int curDistance = distance.get(cur);                
          ArrayList<String> neighbors = getNeighbors(cur, dict);

          for (String neighbor : neighbors) {
              nodeNeighbors.get(cur).add(neighbor);
              if (!distance.containsKey(neighbor)) {// Check if visited
                  distance.put(neighbor, curDistance + 1);
                  if (end.equals(neighbor))// Found the shortest path
                      foundEnd = true;
                  else
                      queue.offer(neighbor);
                  }
              }
          }

          if (foundEnd)
              break;
      }
  }

// Find all next level nodes.    
private ArrayList<String> getNeighbors(String node, Set<String> dict) {
  ArrayList<String> res = new ArrayList<String>();
  char chs[] = node.toCharArray();

  for (char ch ='a'; ch <= 'z'; ch++) {
      for (int i = 0; i < chs.length; i++) {
          if (chs[i] == ch) continue;
          char old_ch = chs[i];
          chs[i] = ch;
          if (dict.contains(String.valueOf(chs))) {
              res.add(String.valueOf(chs));
          }
          chs[i] = old_ch;
      }

  }
  return res;
}

// DFS: output all paths with the shortest distance.
private void dfs(String cur, String end, Set<String> dict, HashMap<String, ArrayList<String>> nodeNeighbors, HashMap<String, Integer> distance, ArrayList<String> solution, List<List<String>> res) {
    solution.add(cur);
    if (end.equals(cur)) {
       res.add(new ArrayList<String>(solution));
    } else {
       for (String next : nodeNeighbors.get(cur)) {            
            if (distance.get(next) == distance.get(cur) + 1) {
                 dfs(next, end, dict, nodeNeighbors, distance, solution, res);
            }
        }
    }           
   solution.remove(solution.size() - 1);

```

### <a name="127"></a>127. Word Ladder
```java
class Solution {
    public int ladderLength(String beginWord, String endWord, List<String> wordList) {
        if (beginWord == null || endWord == null || wordList == null) return 0;
        if (wordList.size() == 0 || !wordList.contains(endWord)) return 0;
        
        // stupid question
        Set<String> wordSet = new HashSet<>();
        for (String word : wordList) {
            wordSet.add(word);
        }
        
        Set<String> beginSet = new HashSet<>();
        Set<String> endSet = new HashSet<>();
        Set<String> visitedSet = new HashSet<>();
        
        beginSet.add(beginWord);
        endSet.add(endWord);
        int distance = 1;
        
        while (!beginSet.isEmpty() && !endSet.isEmpty()) {
            if (beginSet.size() > endSet.size()) {
                Set<String> tmp = beginSet;
                beginSet = endSet;
                endSet = tmp;
            }
            
            Set<String> newBeginSet = new HashSet<>();
            for (String word : beginSet) {
                char[] charArray = word.toCharArray();
                for (int i = 0; i < charArray.length; i ++) {
                    char replacedChar = charArray[i];
                    for (char c = 'a'; c <= 'z'; c ++) {
                        charArray[i] = c;
                        String newWord = String.valueOf(charArray);
                        
                        if (endSet.contains(newWord)) {
                            return distance + 1;
                        }
                        
                        if (!visitedSet.contains(newWord) && wordSet.contains(newWord)) {
                            newBeginSet.add(newWord);
                            visitedSet.add(newWord);
                        }
                    }
                    charArray[i] = replacedChar;
                }
            }
            distance ++;
            beginSet = newBeginSet;
        }
        
        return 0;
    }
}
```

### <a name="82"></a>82. Remove Duplicates from Sorted List II
```java
public ListNode deleteDuplicates(ListNode head) {
        if(head==null) return null;
        ListNode FakeHead=new ListNode(0);
        FakeHead.next=head;
        ListNode pre=FakeHead;
        ListNode cur=head;
        while(cur!=null){
            while(cur.next!=null&&cur.val==cur.next.val){
                cur=cur.next;
            }
            if(pre.next==cur){
                pre=pre.next;
            }
            else{
                pre.next=cur.next;
            }
            cur=cur.next;
        }
        return FakeHead.next;
    }
```

### <a name="83"></a>83. Remove Duplicates from Sorted List
```java
// iterative
class Solution {
    public ListNode deleteDuplicates(ListNode head) {
        ListNode nextNode = head;
        while (nextNode != null) {
            while (nextNode.next != null && nextNode.next.val == nextNode.val) {
                nextNode.next = nextNode.next.next;
            }
            nextNode = nextNode.next;
        }
        return head;
    }
}
// recursion
public ListNode deleteDuplicates(ListNode head) {
        if(head == null || head.next == null)return head;
        head.next = deleteDuplicates(head.next);
        return head.val == head.next.val ? head.next : head;
}
```

### <a name="282"></a>282. Expression Add Operators
```java
/*
This problem has a lot of edge cases to be considered:

overflow: we use a long type once it is larger than Integer.MAX_VALUE or minimum, we get over it.
0 sequence: because we can't have numbers with multiple digits started with zero, we have to deal with it too.
a little trick is that we should save the value that is to be multiplied in the next recursion.
*/
public class Solution {
    public List<String> addOperators(String num, int target) {
        List<String> rst = new ArrayList<String>();
        if(num == null || num.length() == 0) return rst;
        helper(rst, "", num, target, 0, 0, 0);
        return rst;
    }
    public void helper(List<String> rst, String path, String num, int target, int pos, long eval, long multed){
        if(pos == num.length()){
            if(target == eval)
                rst.add(path);
            return;
        }
        for(int i = pos; i < num.length(); i++){
            if(i != pos && num.charAt(pos) == '0') break;
            long cur = Long.parseLong(num.substring(pos, i + 1));
            if(pos == 0){
                helper(rst, path + cur, num, target, i + 1, cur, cur);
            }
            else{
                helper(rst, path + "+" + cur, num, target, i + 1, eval + cur , cur);
                helper(rst, path + "-" + cur, num, target, i + 1, eval -cur, -cur);
                helper(rst, path + "*" + cur, num, target, i + 1, eval - multed + multed * cur, multed * cur );
            }
        }
    }
}
```

### <a name="26"></a>26. Remove Duplicates from Sorted Array
```java
public class Solution {
    public int removeDuplicates(int[] nums) {
        if(nums.length<=1) return nums.length;
        int count=1;
        for(int i=1;i<nums.length;i++){
            if(nums[i]!=nums[count-1]){
                nums[count++]=nums[i];
            }
        }
        return count;
    }
}
//move the pointer and update the value only when the nums are different
//if it's an unsorted array,use hashset(one pass with an index,if !contains,update nums[index++])or sort(then use above algo)

/*
Follow up for "Remove Duplicates":
What if duplicates are allowed at most twice?

For example,
Given sorted array nums = [1,1,1,2,2,3],

Your function should return length = 5, with the first five elements of nums being 1, 1, 2, 2 and 3. It doesn't matter what you leave beyond the new length.
*/

public int removeDuplicates(int[] nums) {
    int i = 0;
    for (int n : nums)
        if (i < 2 || n > nums[i-2])
            nums[i++] = n;
    return i;
}
```

### <a name="34"></a>34. Search for a Range
```java
public class Solution {
	public int[] searchRange(int[] A, int target) {
		int start = Solution.firstGreaterEqual(A, target);
		if (start == A.length || A[start] != target) {
			return new int[]{-1, -1};
		}
		return new int[]{start, Solution.firstGreaterEqual(A, target + 1) - 1};
	}

	//find the first number that is greater than or equal to target.
	//could return A.length if target is greater than A[A.length-1].
	//actually this is the same as lower_bound in C++ STL.
	private static int firstGreaterEqual(int[] A, int target) {
		int low = 0, high = A.length;
		while (low < high) {
			int mid = low + ((high - low) >> 1);
			//low <= mid < high
			if (A[mid] < target) {
				low = mid + 1;
			} else {
				//should not be mid-1 when A[mid]==target.
				//could be mid even if A[mid]>target because mid<high.
				high = mid;
			}
		}
		return low;
	}
}
```

### <a name="39"></a>39. Combination Sum
```java
public List<List<Integer>> combinationSum(int[] nums, int target) {
    List<List<Integer>> list = new ArrayList<>();
    Arrays.sort(nums);
    backtrack(list, new ArrayList<>(), nums, target, 0);
    return list;
}

private void backtrack(List<List<Integer>> list, List<Integer> tempList, int [] nums, int remain, int start){
    if(remain < 0) return;
    else if(remain == 0) list.add(new ArrayList<>(tempList));
    else{ 
        for(int i = start; i < nums.length; i++){
            tempList.add(nums[i]);
            backtrack(list, tempList, nums, remain - nums[i], i); // not i + 1 because we can reuse same elements
            tempList.remove(tempList.size() - 1);
        }
    }
}

// Can not reuse
public List<List<Integer>> combinationSum2(int[] nums, int target) {
    List<List<Integer>> list = new ArrayList<>();
    Arrays.sort(nums);
    backtrack(list, new ArrayList<>(), nums, target, 0);
    return list;
    
}

private void backtrack(List<List<Integer>> list, List<Integer> tempList, int [] nums, int remain, int start){
    if(remain < 0) return;
    else if(remain == 0) list.add(new ArrayList<>(tempList));
    else{
        for(int i = start; i < nums.length; i++){
            if(i > start && nums[i] == nums[i-1]) continue; // skip duplicates
            tempList.add(nums[i]);
            backtrack(list, tempList, nums, remain - nums[i], i + 1);
            tempList.remove(tempList.size() - 1); 
        }
    }
} 

```

### <a name="28"></a>28. Implement strStr()
```java
class Solution {
    public int strStr(String haystack, String needle) {
        // O(n^2)
        if (haystack == null || needle == null || needle.length() > haystack.length()) {
            return -1;
        }
        if (needle.length() == 0) {
            return 0;
        }
        for (int i = 0; i <= haystack.length() - needle.length(); i++) {
            if (haystack.substring(i, i + needle.length()).equals(needle)) {
                return i;
            }
        }
        return -1;
    }
}

public class Solution {// O(n^2)
    public int strStr(String haystack, String needle) {
        if(needle.length()==0) return 0;
        for(int i=0;i<=haystack.length()-needle.length();i++){
            if(haystack.substring(i,i+needle.length()).equals(needle)) return i;//substringO(N)
        }
        return -1;
    }
}
// o(n*h)
public int strStr(String haystack, String needle) {
  for (int i = 0; ; i++) {
    for (int j = 0; ; j++) {
      if (j == needle.length()) return i;
      if (i + j == haystack.length()) return -1;
      if (needle.charAt(j) != haystack.charAt(i + j)) break;
    }
  }
}
//find the first index in haystack that starts with an anagram of needle
//assume only lowercase letters in strings
//O(mn) time, O(m) space
public class Solution {
    public int strStr(String haystack, String needle) {
        if (needle.length() == 0) {
            return 0;
        }
        int m = haystack.length();
        int n = needle.length();
        HashMap<String, Integer> map = new HashMap<>();
        for (int i = 0; i <= m - n; i++) {//we use m - n to reduce time; should be <=, not < !
            String key = createKey(haystack, i, n);
            if (!map.containsKey(key)) {
                map.put(key, i);
            }
        }
        String target = createKey(needle, 0, n);
        if (map.containsKey(target)) {
            return map.get(target);
        }
        return -1;
    }
    
    private String createKey(String s, int start, int length) {
        int[] count = new int[26];//see this as O(1) space
        for (int i = 0; i < length; i++) {//O(n) time
            count[s.charAt(start + i) - 'a']++;
        }
        String key = "";
        for (int j = 0; j < count.length; j++) {//see this as O(1) time
            if (count[j] != 0) {
                key += String.valueOf(count[j]) + String.valueOf((char)('a' + j));
            }
        }
        return key;
    }
}
```

### <a name="572"></a>572. Subtree of Another Tree
```java
//For each node during pre-order traversal of s, use a recursive function isSame to validate if sub-tree started with this node is the same with t.

public class Solution {
    public boolean isSubtree(TreeNode s, TreeNode t) {
        if (s == null) return false;
        if (isSame(s, t)) return true;
        return isSubtree(s.left, t) || isSubtree(s.right, t);
    }
    
    private boolean isSame(TreeNode s, TreeNode t) {
        if (s == null && t == null) return true;
        if (s == null || t == null) return false;
        
        if (s.val != t.val) return false;
        
        return isSame(s.left, t.left) && isSame(s.right, t.right);
    }
}
```

### <a name="415"></a>415. Add Strings
```java
public class Solution {
    public String addStrings(String num1, String num2) {
        StringBuilder sb = new StringBuilder();
        int carry = 0;
        for(int i = num1.length() - 1, j = num2.length() - 1; i >= 0 || j >= 0 || carry == 1; i--, j--){
            int x = i < 0 ? 0 : num1.charAt(i) - '0';
            int y = j < 0 ? 0 : num2.charAt(j) - '0';
            sb.append((x + y + carry) % 10);
            carry = (x + y + carry) / 10;
        }
        return sb.reverse().toString();
    }
}
```

### <a name="237"></a>237. Delete Node in a Linked List
```java
/**
 * Definition for singly-linked list.
 * public class ListNode {
 *     int val;
 *     ListNode next;
 *     ListNode(int x) { val = x; }
 * }
 */
class Solution {
    public void deleteNode(ListNode node) {
        if (node.next == null) return;
        node.val = node.next.val;
        node.next = node.next.next;
    }
}
```

### <a name="38"></a>38. Count and Say
```java
class Solution {
    public String countAndSay(int n) {
        String result = "1";
        while (n > 1) {
            result = sayIt(result);
            n--;
        }
        return result;
    }
    
    public String sayIt(String s) {
        StringBuilder sb = new StringBuilder();
        int counter = 1;
        for (int i = 0; i < s.length() - 1; i ++) {
            if (s.charAt(i) == s.charAt(i + 1)) {
                counter++;
                continue;
            }
            sb.append(String.valueOf(counter));
            sb.append(s.charAt(i));
            counter = 1;
        }
        sb.append(String.valueOf(counter));
        sb.append(s.charAt(s.length() - 1));
        
        return sb.toString();
    }
}
```

### <a name="349"></a>349. Intersection of Two Arrays
```java
// Use two hash sets
// Time complexity: O(n)
public class Solution {
    public int[] intersection(int[] nums1, int[] nums2) {
        Set<Integer> set = new HashSet<>();
        Set<Integer> intersect = new HashSet<>();
        for (int i = 0; i < nums1.length; i++) {
            set.add(nums1[i]);
        }
        for (int i = 0; i < nums2.length; i++) {
            if (set.contains(nums2[i])) {
                intersect.add(nums2[i]);
            }
        }
        int[] result = new int[intersect.size()];
        int i = 0;
        for (Integer num : intersect) {
            result[i++] = num;
        }
        return result;
    }
}

// Sort both arrays, use two pointers
// Time complexity: O(nlogn)

public class Solution {
    public int[] intersection(int[] nums1, int[] nums2) {
        Set<Integer> set = new HashSet<>();
        Arrays.sort(nums1);
        Arrays.sort(nums2);
        int i = 0;
        int j = 0;
        while (i < nums1.length && j < nums2.length) {
            if (nums1[i] < nums2[j]) {
                i++;
            } else if (nums1[i] > nums2[j]) {
                j++;
            } else {
                set.add(nums1[i]);
                i++;
                j++;
            }
        }
        int[] result = new int[set.size()];
        int k = 0;
        for (Integer num : set) {
            result[k++] = num;
        }
        return result;
    }
}

// Binary search
// Time complexity: O(nlogn)

public class Solution {
    public int[] intersection(int[] nums1, int[] nums2) {
        Set<Integer> set = new HashSet<>();
        Arrays.sort(nums2);
        for (Integer num : nums1) {
            if (binarySearch(nums2, num)) {
                set.add(num);
            }
        }
        int i = 0;
        int[] result = new int[set.size()];
        for (Integer num : set) {
            result[i++] = num;
        }
        return result;
    }
    
    public boolean binarySearch(int[] nums, int target) {
        int low = 0;
        int high = nums.length - 1;
        while (low <= high) {
            int mid = low + (high - low) / 2;
            if (nums[mid] == target) {
                return true;
            }
            if (nums[mid] > target) {
                high = mid - 1;
            } else {
                low = mid + 1;
            }
        }
        return false;
    }
}

// follow up
public class Solution {
    public int[] intersection(int[] nums1, int[] nums2) {
        HashSet<Integer> set=new HashSet<>();
        ArrayList<Integer> arr=new ArrayList<>();
        for(int num:nums1) set.add(num);
        for(int num:nums2){
            if(set.contains(num)){
                set.remove(num);
                arr.add(num);
            }
        }
        int k=0;
        int[] res=new int[arr.size()];
        for(Integer num: arr){
            res[k++]=num;
        }
        return res;
    }
}
// What if the given array is already sorted? How would you optimize your algorithm?
// Use two pointers

// What if nums1's size is small compared to nums2's size? Which algorithm is better?
// Use hash on nums1 and scan nums2, less space but more time
// Use hash on nums2 and scan nums1, less time but more space
// Or maybe use binary search on nums2(if sorted)

// What if elements of nums2 are stored on disk, and memory is limited so that you can't load all elements into memory at once?
// Maybe use binary search on nums1(sort it first)
// Or maybe use hash on nums1(need space)

// Binary search如果找到了一个元素index，那就用这次的index作为下次binary search的开始。可以节约掉之前的东西，不用search了。
// 然后问，如果找不到呢，如何优化。说如果找不到，也返回上次search结束的index，然后下次接着search。
// 就是上一次找到了，就用这个index继续找这次的；如果找不到，也有一个ending index，就用那个index当starting index。
// 比如[1, 89，100]，去找90；如果不存在，那么binary search的ending index应该是89，所以下次就从那个index开始。
// 如果找不到，会返回要插入的位置index + 1，index是要插入的位置，我写的就是返回要插入的index的。
// 但是不管返回89还是100的index都无所谓，反正只差一个，对performance没有明显影响的。

// Sort one array & Binary Search it, O(mlogn) time and O(n) space
public class Solution {
    public int[] intersection(int[] nums1, int[] nums2) {
        if (nums1 == null || nums2 == null) {
            return new int[]{};
        }
        HashSet<Integer> set = new HashSet<>();//you can use ArrayList here as well
        Arrays.sort(nums1);
        for (int i : nums2) {
            if (!set.contains(i) && binarySearch(nums1, i)) {
                set.add(i);
            }
        }
        int[] res = new int[set.size()];
        int i = 0;
        for (int num : set) {
            res[i++] = num;//remember to i++ !!!
        }
        return res;
    }
    
    private boolean binarySearch(int[] a, int target) {
        if (a == null || a.length == 0) {//remember to check whether a is null or empty !!!
            return false;
        }
        int start = 0;
        int end = a.length - 1;
        while (start + 1 < end) {
            int mid = start + (end - start) / 2;
            if (a[mid] == target) {
                return true;
            } else if (a[mid] > target) {
                end = mid;
            } else {
                start = mid;
            }
        }
        if (a[start] == target || a[end] == target) {
            return true;
        }
        return false;
    }
}

// Sort & two pointers O(nlogn) time and O(n) space(if consider the arraylist which is used to store result)
public class Solution {
    public int[] intersection(int[] nums1, int[] nums2) {
        if (nums1 == null || nums2 == null) {
            return new int[]{};
        }
        ArrayList<Integer> list = new ArrayList<>();//you can use hashset here as well
        Arrays.sort(nums1);
        Arrays.sort(nums2);
        int i = 0;
        int j = 0;
        while (i < nums1.length && j < nums2.length) {
            if (nums1[i] < nums2[j]) {
                i++;
            } else if (nums1[i] > nums2[j]) {
                j++;
            } else {
                if (list.size() == 0 || list.get(list.size() - 1) != nums1[i]) {
                    list.add(nums1[i]);
                }
                i++;
                j++;
            }
        }
        int[] res = new int[list.size()];
        for (int k = 0; k < list.size(); k++) {
            res[k] = list.get(k);
        }
        return res;
    }
}
```

### <a name="560"></a>560. Subarray Sum Equals K
```java
/*
Solution 1. Brute force. We just need two loops (i, j) and test if SUM[i, j] = k. Time complexity O(n^2), Space complexity O(1). I bet this solution will TLE.

Solution 2. From solution 1, we know the key to solve this problem is SUM[i, j]. So if we know SUM[0, i - 1] and SUM[0, j], then we can easily get SUM[i, j]. To achieve this, we just need to go through the array, calculate the current sum and save number of all seen PreSum to a HashMap. Time complexity O(n), Space complexity O(n).
*/
class Solution {
    public int subarraySum(int[] nums, int k) {
        if (nums == null) return 0;
        Map<Integer, Integer> hm = new HashMap<>(); // key: sum, value: combinations
        hm.put(0, 1);
        int sum = 0, result = 0;
        for (int i = 0; i < nums.length; i ++) {
            sum += nums[i];
            if (hm.containsKey(sum - k)) {
                result += hm.get(sum - k);
            }
            hm.put(sum, hm.getOrDefault(sum, 0) + 1);
        }
        return result;
    }
}
```

### <a name="10"></a>10. Regular Expression Matching
```java
// 遇到了就写第一个dp的方案
// dp, O(mn) time, O(mn) space:
// this can be optimized to O(n) space as well
public class Solution {
    public boolean isMatch(String s, String p) {
        if (s == null || p == null) {
            return false;
        }
        int m = s.length();
        int n = p.length();
        boolean[][] dp = new boolean[m + 1][n + 1];
        dp[0][0] = true;//remember to initialize dp[0][0]: "" matches "" is true !!!
        for (int i = 0; i <= m; i++) {
            for (int j = 1; j <= n; j++) {
                if (p.charAt(j - 1) == '*') {//j=1? before checking dp[i][j-2],we check p[j-1]=='*',and no p starts with '*'
                    dp[i][j] = dp[i][j - 2] //dp[i][j - 2]:pattern match 0 time; or(below) match more than 0 time
                    || (i > 0 && (s.charAt(i - 1) == p.charAt(j - 2) || p.charAt(j - 2) == '.') && dp[i - 1][j]);
//1.dp[i][j-2]:check if we can skip this 2-char pattern,or pattern is used by last char of s(so in both cases should skip it)
//2.else if pattern shouldn't be skipped(which mean it should match more char),continue to try match 1 char with this pattern
//note that we match s.charAt(i - 1) and p.charAt(j - 2) here, because j-1 is '*' and j-2 is the char we need to match
//&& dp[i-1][j]:also need to make sure that s.substring(i-1) (which is before s.charAt(j-1)) should be matched by the pattern
                } else {
                    dp[i][j] = i > 0 && (s.charAt(i - 1) == p.charAt(j - 1) || p.charAt(j - 1) == '.') && dp[i - 1][j - 1];
//if we have to match char i-1 & j-1,we also make sure that dp[i - 1][j - 1]:s.substring(0,i-1) & p.substring(0,j-1) matches
                }
            }
        }
        return dp[m][n];
    }
}
```

### <a name="29"></a>29. Divide Two Integers
```java
// O(logN) * O(logN)
public int divide(int dividend, int divisor) {
	//Reduce the problem to positive long integer to make it easier.
	//Use long to avoid integer overflow cases.
	int sign = 1;
	if ((dividend > 0 && divisor < 0) || (dividend < 0 && divisor > 0))
		sign = -1;
	long ldividend = Math.abs((long) dividend);
	long ldivisor = Math.abs((long) divisor);
	
	//Take care the edge cases.
	if (ldivisor == 0) return Integer.MAX_VALUE;
	if ((ldividend == 0) || (ldividend < ldivisor))	return 0;
	
	long lans = ldivide(ldividend, ldivisor);
	
	int ans;
	if (lans > Integer.MAX_VALUE){ //Handle overflow.
		ans = (sign == 1)? Integer.MAX_VALUE : Integer.MIN_VALUE;
	} else {
		ans = (sign == 1)? ans : -ans;
	}
	return ans;
}

private long ldivide(long ldividend, long ldivisor) {
	// Recursion exit condition
	if (ldividend < ldivisor) return 0;
	
	//  Find the largest multiple so that (divisor * multiple <= dividend), 
	//  whereas we are moving with stride 1, 2, 4, 8, 16...2^n for performance reason.
	//  Think this as a binary search.
	long sum = ldivisor;
	long multiple = 1;
	while ((sum+sum) <= ldividend) {
		sum += sum;
		multiple += multiple;
	}
	//Look for additional value for the multiple from the reminder (dividend - sum) recursively.
	return multiple + ldivide(ldividend - sum, ldivisor);
}
```

### <a name="297"></a>297. Serialize and Deserialize Binary Tree
```java
/*
Here I use typical BFS method to handle a binary tree. I use string n to represent null values. The string of the binary tree in the example will be "1 2 3 n n 4 5 n n n n ".

When deserialize the string, I assign left and right child for each not-null node, and add the not-null children to the queue, waiting to be handled later.
*/
public class Solution {
    public String serialize(TreeNode root) {
        if (root == null) return "";
        Queue<TreeNode> q = new LinkedList<>();
        StringBuilder res = new StringBuilder();
        q.add(root);
        while (!q.isEmpty()) {
            TreeNode node = q.poll();
            if (node == null) {
                res.append("n ");
                continue;
            }
            res.append(node.val + " ");
            q.add(node.left);
            q.add(node.right);
        }
        return res.toString();
    }

    public TreeNode deserialize(String data) {
        if (data == "") return null;
        Queue<TreeNode> q = new LinkedList<>();
        String[] values = data.split(" ");
        TreeNode root = new TreeNode(Integer.parseInt(values[0]));
        q.add(root);
        for (int i = 1; i < values.length; i++) {
            TreeNode parent = q.poll();
            if (!values[i].equals("n")) {
                TreeNode left = new TreeNode(Integer.parseInt(values[i]));
                parent.left = left;
                q.add(left);
            }
            if (!values[++i].equals("n")) {
                TreeNode right = new TreeNode(Integer.parseInt(values[i]));
                parent.right = right;
                q.add(right);
            }
        }
        return root;
    }
}
```

### <a name="477"></a>477. Total Hamming Distance
```java
// O(n) time O(1) space
public int totalHammingDistance(int[] nums) {
    int total = 0, n = nums.length;
    for (int j=0;j<32;j++) {
        int bitCount = 0;
        for (int i=0;i<n;i++) 
            bitCount += (nums[i] >> j) & 1;
        total += bitCount*(n - bitCount);
    }
    return total;
}
```

### <a name="215"></a>215. Kth Largest Element in an Array
```java
public class Codec {
    public String serialize(TreeNode root) {
        if (root == null) return "";
        Queue<TreeNode> q = new LinkedList<>();
        StringBuilder res = new StringBuilder();
        q.add(root);
        while (!q.isEmpty()) {
            TreeNode node = q.poll();
            if (node == null) {
                res.append("n ");
                continue;
            }
            res.append(node.val + " ");
            q.add(node.left);
            q.add(node.right);
        }
        return res.toString();
    }

    public TreeNode deserialize(String data) {
        if (data == "") return null;
        Queue<TreeNode> q = new LinkedList<>();
        String[] values = data.split(" ");
        TreeNode root = new TreeNode(Integer.parseInt(values[0]));
        q.add(root);
        for (int i = 1; i < values.length; i++) {
            TreeNode parent = q.poll();
            if (!values[i].equals("n")) {
                TreeNode left = new TreeNode(Integer.parseInt(values[i]));
                parent.left = left;
                q.add(left);
            }
            if (!values[++i].equals("n")) {
                TreeNode right = new TreeNode(Integer.parseInt(values[i]));
                parent.right = right;
                q.add(right);
            }
        }
        return root;
    }
}
```

### <a name="15"></a>15. 3Sum
```java
// 1,two pointer O(n^2) time, O(1) space if not consider sorting's stack usage
class Solution {
    public List<List<Integer>> threeSum(int[] nums) {
        List<List<Integer>> result = new ArrayList<>();
        if (nums == null || nums.length == 0) {
            return result;
        }
        Arrays.sort(nums);
        for (int i = 0; i < nums.length - 1; i ++) {
            if (i > 0 && nums[i] == nums[i - 1]) continue;
            int j = i + 1;  // j = i if can use many times
            int k = nums.length - 1;
            while (j < k) {  // (j <= k>) if can use many times
                int target = -nums[i];
                int sum = nums[j] + nums[k];
                if (target == sum) {
                    result.add(Arrays.asList(nums[i], nums[j], nums[k]));
                    j ++;
                    k --;
                    while (j < k && nums[j] == nums[j - 1]) {j ++;}
                    while (j < k && nums[k] == nums[k + 1]) {k --;}
                } else if (target < sum) {
                    k --;
                } else {
                    j ++;
                }
            }
        }
        return result;
    }
}
// if each num can be used for any times(results should still be unique):
// sort and two pointers: O(n^2) time, O(1) space if not consider sorting's stack usage
public class Solution {
    public List<List<Integer>> threeSum(int[] nums) {
        List<List<Integer>> res = new ArrayList<>();
        if (nums == null || nums.length < 3) {
            return res;
        }
        Arrays.sort(nums);
        for (int i = 0; i < nums.length; i++) {//i < nums.length if each num can be used for any times
            if (i != 0 && nums[i] == nums[i - 1]) {//skip duplicated 3sum results
                continue;
            }
            int left = i;//start from i if each num can be used for any times
            int right = nums.length - 1;
            while (left <= right) {//left <= right if each num can be used for any times
                int sum = nums[i] + nums[left] + nums[right];
                if (sum == 0) {
                    List<Integer> list = new ArrayList<>();
                    list.add(nums[i]);
                    list.add(nums[left]);
                    list.add(nums[right]);
                    res.add(list);
                    left++;
                    right--;
                    while (left < right && nums[left] == nums[left - 1]) {//remember to skip dups after adding result
                        left++;
                    }
                    while (left < right && nums[right] == nums[right + 1]) {//remember to skip dups after adding result
                        right--;
                    }
                } else if (sum < 0) {
                    left++;
                } else {
                    right--;
                }
            }
        }
        return res;
    }
}


//2，hashmap做
// Use hashmap to store value and frequency
    public List<List<Integer>> threeSum(int[] n){
        Arrays.sort(n);
        List<List<Integer>> res = new ArrayList<>();
        Map<Integer, Integer> map = new HashMap<>();
        for(int i = 0 ; i < n.length; i++){
            if( !map.containsKey(n[i])){
                map.put(n[i],1);
            } else {
                map.put(n[i], map.get(n[i]) + 1 );
            }
        }
        for( int i = 0 ; i < n.length ; i ++){
            for( int j = i + 1 ; j < n.length ; j++){
                int rest = 0 - n[i] - n[j];
                int count = 0;
                if(n[i] == rest) count++;
                if(n[j] == rest) count++;
                if(map.containsKey(rest) && map.get(rest) > count && rest >= n[j]){
                    res.add(Arrays.asList(n[i],n[j],rest));
                }
                while( j < n.length - 1 && n[j] == n[j+1]) j++;    
            }
            while( i < n.length -1 && n[i] == n[i+1] ) i++;
        }
        return res;
    }

// can not sort, use 2 sum
// Complexity - O(n^2), Space Complexity - O(n^2)
    private int[] findTriple_3(int[] A) {
        Map<Integer, int[]> map = new HashMap<Integer, int[]>();
        for (int i = 0, l = A.length; i < l; i++) {
            map.clear();
            for (int j = i + 1; j < l; j++) {
                if (map.containsKey(A[j])) {
                    int[] pair = map.get(A[j]);
                    return new int[]{pair[0], pair[1], A[j]};
                } else
                    map.put(-A[i] - A[j], new int[]{A[i], A[j]});
            }
        }
        return null;
    }
```

### <a name="261"></a>261. Graph Valid Tree
```java
/*
To tell whether a graph is a valid tree, we have to:

Make sure there is no cycle in the graph - this has to be a none-cyclic graph;
Make sure every node is reached - this has to be a connected graph;

Solution:

To test cyclic, we can make an array for each node (as array index), and the array will store the parent of the node (as array index). Every time we fetch a new pair of nodes, we trace the root node (the deepest parent node) of these two nodes, if it has the same root, then is will be a cycle; otherwise, we set the parent of second node to be the first node;
After we make sure there is node cycle in the graph, we simple test if there is enough edges to make this graph connected.
*/

// O(V*E)
class Solution {
    public boolean validTree(int n, int[][] edges) {
        // initialize n isolated islands
        int[] parents = new int[n];
        Arrays.fill(parents, -1);
        
        // perform union find
        for (int i = 0; i < edges.length; i++) {
            int x = find(parents, edges[i][0]);
            int y = find(parents, edges[i][1]);
            
            // if two vertices happen to be in the same set
            // then there's a cycle
            if (x == y) return false;
            
            // union
            parents[x] = y;
        }
        
        return edges.length == n - 1;
    }
    
    int find(int parents[], int i) {
        if (parents[i] == -1) return i;
        return find(parents, parents[i]);
    }
}

// DFS
public class Solution {
    public boolean validTree(int n, int[][] edges) {
        // initialize adjacency list
        List<List<Integer>> adjList = new ArrayList<List<Integer>>(n);
        
        // initialize vertices
        for (int i = 0; i < n; i++)
            adjList.add(i, new ArrayList<Integer>());
        
        // add edges    
        for (int i = 0; i < edges.length; i++) {
            int u = edges[i][0], v = edges[i][1];
            adjList.get(u).add(v);
            adjList.get(v).add(u);
        }
        
        boolean[] visited = new boolean[n];
        
        // make sure there's no cycle
        if (hasCycle(adjList, 0, visited, -1))
            return false;
        
        // make sure all vertices are connected
        for (int i = 0; i < n; i++) {
            if (!visited[i]) 
                return false;
        }
        
        return true;
    }
    
    // check if an undirected graph has cycle started from vertex u
    boolean hasCycle(List<List<Integer>> adjList, int u, boolean[] visited, int parent) {
        visited[u] = true;
        
        for (int i = 0; i < adjList.get(u).size(); i++) {
            int v = adjList.get(u).get(i);
            
            if ((visited[v] && parent != v) || (!visited[v] && hasCycle(adjList, v, visited, u)))
                return true;
        }
        
        return false;
    }
}
```

### <a name="283"></a>283. Move Zeroes
```java
//output is length of non-zero part;if we only care whether all non-zero are in length,don't care what nums are after length
//num of operations: num of zero
public class Solution {
    public int moveZeroes(int[] nums) {
        if (nums == null || nums.length == 0) {
            return 0;
        }
        int left = 0;
        int right = nums.length - 1;
        while (left < right) {
            while (left < right&&nums[left] != 0) {
                left++;
            }
            while (left < right&&nums[right] == 0) {
                right--;
            }
            if (left < right) {
                nums[left++] = nums[right--];//we only write non-zero to left part
                //if we only care zero, only use nums[right--] = nums[left++] above, and return right
                /*
                nums[left++]=nums[right];
                nums[right--]=0;//前面是数，后面是0的情况这么写，但不是排序的了
                */
            }
        }
        return left;
    }
}

//solution 1: write (optimal, cuz operations reduced)
//num of operations: nums.length, if there are lots of non-zeros in array, use this
// bad when: 102020222222
// good when: 
public class Solution {
    public void moveZeroes(int[] nums) {
        if (nums == null || nums.length == 0) {
            return;
        }
        int insert = 0;
        for (int i = 0; i < nums.length; i++) {
            if (nums[i] != 0) {
                nums[insert++] = nums[i];
            }
        }
        while (insert < nums.length) {
            nums[insert++] = 0;
        }
    }
}

//solution 2: swap
//num of operations: 2 * (num of non-zero), if there are lots of zeros in array, use this
// good when 000010002
// bad when 10202222022
public class Solution {
    public void moveZeroes(int[] nums) {
        if (nums == null || nums.length == 0) {
            return;
        }
        for (int i = 0, j = 0; i < nums.length; i++) {
            if (nums[i] != 0) {
                int temp = nums[j];
                nums[j++] = nums[i];
                nums[i] = temp;
            }
        }
    }
}

// moveZero to front, moveOne to back, maintain the order of other non-zero and non-one elements

// move all non-one to front, fill the rest with one
// for all non-one in the front, move all non-zero to center
// fill the front with zero

public class Solution {
    public void moveZeroes(int[] nums) {
        if (nums == null || nums.length == 0) {
            return;
        }
        
        int insert = 0;
        for (int i = 0; i < nums.length; i++) {//move all non-one to front
            if (nums[i] != 1) {
                nums[insert++] = nums[i];
            }
        }
        int temp = insert - 1;//save the position before all one
        while (insert < nums.length) {//fill one to back
            nums[insert++] = 1;
        }
        
        insert = temp;//skip all one at the back
        for (int i = insert; i >= 0; i--) {//move all non-zero to center (start from index before all one)
            if (nums[i] != 0) {
                nums[insert--] = nums[i];
            }
        }
        while (insert >= 0) {//fill zero to front
            nums[insert--] = 0;
        }
    }
}
```

### <a name="523"></a>523. Continuous Subarray Sum
```java
class Solution {
    public boolean checkSubarraySum(int[] nums, int k) {
        if (nums == null || nums.length == 0) return false;
        // check k == 0 !!!
        Map<Integer, Integer> hm = new HashMap<>(); // key: sum, value: subarray length
        hm.put(0, 0);
        
        int sum = 0;
        for (int i = 0; i < nums.length; i ++) {
            sum += nums[i];
            if (k != 0) {
                sum = sum % k;
            }
            if (hm.containsKey(sum)) {
                if (i + 1 - hm.get(sum) >= 2) {
                    return true;
                }
            } else { // do not need to update value, since we want max length
                hm.put(sum, i + 1);
            }
        }
        return false;
    }
}
```

### <a name="159"></a>159. Longest Substring with At Most Two Distinct Characters
```java
class Solution {
    public int lengthOfLongestSubstringTwoDistinct(String s) {
        if (s == null || s.length() == 0) return 0;
        Map<Character, Integer> hm = new HashMap<>();
        int maxLength = Integer.MIN_VALUE;
        
        int left, right;
        int distinctCount = 0;
        for (left = 0, right = 0; right < s.length(); right ++) {
            char newChar = s.charAt(right);
            if (hm.getOrDefault(newChar, 0) == 0) {
                distinctCount ++;
            }
            hm.put(newChar, hm.getOrDefault(newChar, 0) + 1);
            
            while (distinctCount > 2) {
                char removedChar = s.charAt(left);
                if (hm.get(removedChar) == 1) {
                    distinctCount --;
                }
                hm.put(removedChar, hm.get(removedChar) - 1);
                left ++;
            }
            
            maxLength = Math.max(maxLength, right - left + 1);
        }
        
        return maxLength;
    }
}
```

### <a name="3"></a>3. Longest Substring Without Repeating Characters
```java
// O(n)
class Solution {
    public int lengthOfLongestSubstring(String s) {
        if (s == null || s.length() == 0) return 0;
        Map<Character, Integer> hm = new HashMap<>();
        
        int i, j;
        int longestLength = Integer.MIN_VALUE;
        
        for (i = 0, j = 0; i < s.length(); i++) {
            if (hm.containsKey(s.charAt(i))) {
                j = Math.max(j, hm.get(s.charAt(i)) + 1);
            }
            longestLength = Math.max(longestLength, i - j + 1);
            hm.put(s.charAt(i), i);
        }
        
        return longestLength;
    }
}
```

### <a name="76"></a>76. Minimum Window Substring
```java
// O(n)
public class Solution {    
    public String minWindow(String s, String t) {
        int[] count = new int[256];  //char 有256个数
        for (char c : t.toCharArray()) {
            count[c]++;
        }
        int remain = t.length();
        int minLength = Integer.MAX_VALUE, windowIndex = 0;
        
        for (int right = 0, left = 0; right < s.length(); right++) {
            char newChar = s.charAt(right); // move right pointer one step, include a new character
            if (count[newChar] -- > 0) {
                remain --;
            }
            
            while (remain == 0) {  // all requirements are fufilled, valid window
                if (right - left + 1 < minLength) {//try to update the min length
                    minLength = right - left + 1;
                    windowIndex = left;
                }
                // try to move left pointer, but remain valid
                char removedChar = s.charAt(left);
                if (count[removedChar] ++ == 0) {
                    remain ++;
                }
                left ++;
            }
        }
        return (minLength == Integer.MAX_VALUE) ? "" : s.substring(windowIndex, windowIndex + minLength);
    }
}

// maintain dict for both source and target
class Solution {
    public String minWindow(String s, String t) {
        if (s == null || t == null) return "";
        int[] sourceDic = new int[256];
        int[] targetDic = new int[256];
        
        for (char c : t.toCharArray()) {
            targetDic[c] ++;
        }
        
        int right = 0, left = 0, found = 0, minLength = Integer.MAX_VALUE, begin = 0;
        for (right = 0; right < s.length(); right ++) {
            sourceDic[s.charAt(right)] ++;
            if (sourceDic[s.charAt(right)] <= targetDic[s.charAt(right)]) {
                found ++;
            }
            while (found == t.length() && left <= right) {
                int windowLength = right - left + 1;
                if (windowLength < minLength) {
                    minLength = windowLength;
                    begin = left;
                }
                
                if (targetDic[s.charAt(left)] > 0) {
                    sourceDic[s.charAt(left)] --;
                    if (sourceDic[s.charAt(left)] < targetDic[s.charAt(left)]) {
                        found --;
                        left ++;
                        break;
                    }
                }
                left ++;
            }
        }
        return (minLength == Integer.MAX_VALUE) ? "" : s.substring(begin, begin + minLength);
    }
}
```

### <a name="209"></a>209. Minimum Size Subarray Sum
```java

// O(n)
class Solution {
    public int minSubArrayLen(int s, int[] nums) {
        if (nums == null || nums.length == 0 || s <= 0) return 0;
        
        int minLength = Integer.MAX_VALUE;
        int i = 0, j = 0, sum = 0;
        while (j < nums.length) {
            sum += nums[j++];
            
            while (sum >= s) {
                minLength = Math.min(minLength, j - i);
                sum -= nums[i++];
            }
        }
        return (minLength == Integer.MAX_VALUE) ? 0 : minLength;
    }
}
/*
As to NLogN solution, logN immediately reminds you of binary search. In this case, you cannot sort as the current order actually matters. How does one get an ordered array then? Since all elements are positive, the cumulative sum must be strictly increasing. Then, a subarray sum can expressed as the difference between two cumulative sum. Hence, given a start index for the cumulative sum array, the other end index can be searched using binary search.
*/
// O(logN)
class Solution {
    public int minSubArrayLen(int s, int[] nums) {
        int[] sums = new int[nums.length + 1];
        for (int i = 1; i < sums.length; i++) sums[i] = sums[i - 1] + nums[i - 1];
        int minLen = Integer.MAX_VALUE;
        for (int i = 0; i < sums.length; i++) {
            int end = binarySearch(i + 1, sums.length - 1, sums[i] + s, sums);
            if (end == sums.length) break;
            minLen = Math.min(end - i, minLen);
        }
        return minLen == Integer.MAX_VALUE ? 0 : minLen;
    }
    
    private int binarySearch(int low, int high, int key, int[] sums) {
        while (low <= high) {
           int mid = low + (high - low) / 2;
           if (sums[mid] >= key){
               high = mid - 1;
           } else {
               low = mid + 1;
           }
        }
        return low;
    }
}
```

### <a name="75"></a>75. Sort Colors
```java
/*
The idea is to sweep all 0s to the left and all 2s to the right, then all 1s are left in the middle.

It is hard to define what is a "one-pass" solution but this algorithm is bounded by O(2n), meaning that at most each element will be seen and operated twice (in the case of all 0s). You may be able to write an algorithm which goes through the list only once, but each step requires multiple operations, leading the total operations larger than O(2n).
*/
// O(n)
class Solution {
    public void sortColors(int[] nums) {
        if (nums == null) return;
        int i, zeroIndex, secondIndex;
        i = zeroIndex = 0;
        secondIndex = nums.length - 1;
        while (i <= secondIndex) {
            if (nums[i] == 0) {
                swap(nums, i++, zeroIndex++);
            } else if (nums[i] == 2) {
                swap(nums, i, secondIndex--);
            } else {
                i ++;
            }
        }
    }
    
    public void swap(int[] nums, int i, int j) {
        int tmp = nums[i];
        nums[i] = nums[j];
        nums[j] = tmp;
    }
}

// sort K colors
// 简单的办法可以利用two pass, 相当于counting sort，计数每个color的个数，再依次填入到原来的array中；这种方法空间复杂度为 O(k), 时间复杂度为 O(n)。

// version 1: O(nlogk), the best algorithm based on comparing
class Solution {
    /**
     * @param colors: A list of integer
     * @param k: An integer
     * @return: nothing
     */
    public void sortColors2(int[] colors, int k) {
        if (colors == null || colors.length == 0) {
            return;
        }
        rainbowSort(colors, 0, colors.length - 1, 1, k);
    }
    
    public void rainbowSort(int[] colors,
                            int left,
                            int right,
                            int colorFrom,
                            int colorTo) {
        if (colorFrom == colorTo) {
            return;
        }
        
        if (left >= right) {
            return;
        }
        
        int colorMid = (colorFrom + colorTo) / 2;
        int l = left, r = right;
        while (l <= r) {
            while (l <= r && colors[l] <= colorMid) {
                l++;
            }
            while (l <= r && colors[r] > colorMid) {
                r--;
            }
            if (l <= r) {
                int temp = colors[l];
                colors[l] = colors[r];
                colors[r] = temp;
                
                l++;
                r--;
            }
        }
        
        rainbowSort(colors, left, r, colorFrom, colorMid);
        rainbowSort(colors, l, right, colorMid + 1, colorTo);
    }
}

// version 2: O(nk), not efficient, will get Time Limit Exceeded error. But you should try to implement the following algorithm for practicing purpose.

    public void sortColors2(int[] colors, int k) { // 00110344032124
        if (colors == null || colors.length <= 1 || k == 1) {
            return;
        }
        int left = 0;
        int right = colors.length - 1;
        while (left < right) {                  // 00110344032124   // 00001133212444
            int max = Integer.MIN_VALUE;        // 4                // 3
            int min = Integer.MAX_VALUE;        // 0                // 1
            for (int i = left; i <= right; i++) {
                max = Math.max(max, colors[i]);
                min = Math.min(min, colors[i]);
            }
            int i = left;
            while (i <= right) {                // 00001133212444   // 00001112233444
                if (colors[i] == min) {
                    swap(colors, i, left);
                    left++;
                    i++;
                } else if (colors[i] > min && colors[i] < max) {
                    i++;
                } else {
                    swap(colors, i, right);
                    right--;
                }
            }
        }
    }

// 4，isHigh(), isMid(), isLow()
// http://www.1point3acres.com/bbs/thread-209155-1-1.html
public class Solution {
    // 如果是给的string，化成char[] 再做
    // given three functions: isHigh(), isMid(), isLow()
    // sort 3 categories in descending order
    public void sortColors(int[] nums, int left, int right) {//we assume input left is 0 and right is nums.length - 1
        if (nums == null || nums.length <= 1) {
            return;
        }
        int i = left;
        while (i <= right) {//should be i <= right, not i < nums.length !!!eg.[2, 2]; not i < right !!!eg.[1,0];
            if (isLow(nums[i])) {
                swap(nums, i, left);
                left++;//left side of left pointer are all 0, between left & i are all 1
                i++;//i++ cuz we know what we swap from left pointer is either 0 or 1, i's left side are all 0 and 1
            } else if (isMid(nums[i])) {
                i++;
            } else {//isHigh(nums[i])
                swap(nums, i, right);
                right--;//we can't i++ cuz we don't know what we swapped from right pointer, so we still need to check later
            }
        }
    }
    
    private void swap(int[] nums, int i, int j) {
        int temp = nums[i];
        nums[i] = nums[j];
        nums[j] = temp;
    }
}

// 5,getCategory
public class Solution {    
    //int getCategory(int n), outputs the category(1 to k) of given n
    //sort k categories in descending order
    public void sortKColors(int[] nums, int k) {//we assume input left is 0 and right is nums.length - 1
        if (nums == null || nums.length <= 1 || k <= 1) {
            return;
        }
        int left = 0;
        int right = nums.length - 1;
        int min = 1;
        int max = k;
        while (left < right) {
            int i = left;
            while (i <= right) {
                if (getCategory(nums[i]) == min) {
                    swap(nums, i, left);
                    left++;
                    i++;
                } else if (getCategory(nums[i]) > min && getCategory(nums[i]) < max) {
                    i++;
                } else {
                    swap(nums, i, right);
                    right--;
                }
            }
            min++;
            max--;
        }
    }
}

```

### <a name="341"></a>341. Flatten Nested List Iterator
```java
/**
 * // This is the interface that allows for creating nested lists.
 * // You should not implement it, or speculate about its implementation
 * public interface NestedInteger {
 *
 *     // @return true if this NestedInteger holds a single integer, rather than a nested list.
 *     public boolean isInteger();
 *
 *     // @return the single integer that this NestedInteger holds, if it holds a single integer
 *     // Return null if this NestedInteger holds a nested list
 *     public Integer getInteger();
 *
 *     // @return the nested list that this NestedInteger holds, if it holds a nested list
 *     // Return null if this NestedInteger holds a single integer
 *     public List<NestedInteger> getList();
 * }
 */
public class NestedIterator implements Iterator<Integer> {

    private Stack<NestedInteger> stack;
    public NestedIterator(List<NestedInteger> nestedList) {
        stack = new Stack<>();
        for (NestedInteger i : nestedList) {
            stack.push(i);
        }
    }

    @Override
    public Integer next() {
        return stack.pop().getInteger();
    }

    @Override
    public boolean hasNext() {
        while (!stack.isEmpty()) {
            NestedInteger thisInteger = stack.peek();
            if (thisInteger.isInteger()) return true;
            stack.pop();
            for (int i = thisInteger.getList().size() - 1; i >= 0; i --) {
                stack.push(thisInteger.getList().get(i)); // reverse order!!!
            }
        }
        return false;
    }
}

/**
 * Your NestedIterator object will be instantiated and called as such:
 * NestedIterator i = new NestedIterator(nestedList);
 * while (i.hasNext()) v[f()] = i.next();
 */
```


### <a name="12"></a>12. Integer to Roman
```java
class Solution {
    public String intToRoman(int num) {
        int[] values = {1000,900,500,400,100,90,50,40,10,9,5,4,1};
        String[] strs = {"M","CM","D","CD","C","XC","L","XL","X","IX","V","IV","I"};
        
        StringBuilder sb = new StringBuilder();
        
        for (int i = 0; i < values.length; i ++) {
            while (num >= values[i]) {
                num -= values[i];
                sb.append(strs[i]);
            }
        }
        return sb.toString();
    }
}
```

### <a name="13"></a>13. Roman to Integer
```java
class Solution {
    public int romanToInt(String s) {
        if (s == null) return 0;
        int [] nums = new int [s.length()];
        for (int i = 0; i < s.length(); i++) {
            switch (s.charAt(i)) {
                case 'M':
                    nums[i]=1000;
                    break;
                case 'D':
                    nums[i]=500;
                    break;
                case 'C':
                    nums[i]=100;
                    break;
                case 'L':
                    nums[i]=50;
                    break;
                case 'X' :
                    nums[i]=10;
                    break;
                case 'V':
                    nums[i]=5;
                    break;
                case 'I':
                    nums[i]=1;
                    break;
            }
        }
        int sum = 0;
        for (int j = 0; j < nums.length - 1; j++) {
          if (nums[j] < nums[j + 1]) {
              sum -= nums[j];
          } else {
              sum += nums[j];
          }
        } 
        return sum + nums[nums.length-1];
    }
}
```
### <a name="7"></a>7. Reverse Integer
```java
// If overflow exists, the new result will not equal previous one.
class Solution {
    public int reverse(int x) {
        int result = 0;
        while (x != 0) {
            int increment = x % 10;
            int newResult = 10 * result + increment;
            if ((newResult - increment) / 10 != result) {
                return 0;
            }
            result = newResult;
            x = x / 10;
        }
        return result;
    }
}

// use long
public int reverse(int x) {
        long rev= 0;
        while( x != 0){
            rev= rev*10 + x % 10;
            x= x/10;
            if( rev > Integer.MAX_VALUE || rev < Integer.MIN_VALUE)
                return 0;
        }
        return (int) rev;
    }
```

### <a name="43"></a>43. Multiply Strings
```java
/*
Start from right to left, perform multiplication on every pair of digits, and add them together. Let's draw the process! From the following draft, we can immediately conclude:

 `num1[i] * num2[j]` will be placed at indices `[i + j`, `i + j + 1]` 

         1  2  3
            4  5
        --------
            1  5
        1  0
     0  5
        1  2
     0  8
  0  4
*/
// O(mn) time, O(m+n) space int m = num1.length(), n = num2.length();
class Solution {
    public String multiply(String num1, String num2) {
        int length_1 = num1.length();
        int length_2 = num2.length();
        
        int[] production = new int [length_1 + length_2];
        for (int i = length_1 - 1; i >=0; i --) {
            for (int j = length_2 - 1; j >= 0; j --) {
                int position1 = i + j;
                int position2 = position1 + 1;
                
                int thisProduct = (num1.charAt(i) - '0') * (num2.charAt(j) - '0');
                int newSum = production[position2] + thisProduct;
                production[position2] = newSum % 10;
                production[position1] += newSum / 10;
            }
        }

        StringBuilder sb = new StringBuilder();
        for (int digit : production) {
            if (sb.length() == 0 && digit == 0) continue;
            sb.append(String.valueOf(digit));
        }
        return (sb.length() == 0) ? "0" : sb.toString();
    }
}
```

### <a name="445"></a>445. Add Two Numbers II
```java
/**
 * Definition for singly-linked list.
 * public class ListNode {
 *     int val;
 *     ListNode next;
 *     ListNode(int x) { val = x; }
 * }
 */

// reverse input lists and same as question 2

// without reverse
class Solution {
    public ListNode addTwoNumbers(ListNode l1, ListNode l2) {
        Stack<Integer> stack_1 = new Stack<>();
        Stack<Integer> stack_2 = new Stack<>();
        
        while (l1 != null) {
            stack_1.push(l1.val);
            l1 = l1.next;
        }
        
        while (l2 != null) {
            stack_2.push(l2.val);
            l2 = l2.next;
        }
        
        int carry = 0;
        ListNode newHead = null;
        
        while(!stack_1.isEmpty() || !stack_2.isEmpty()) {
            int value1 = (stack_1.isEmpty()) ? 0 : stack_1.pop();
            int value2 = (stack_2.isEmpty()) ? 0 : stack_2.pop();
            
            int result = value1 + value2 + carry;
            ListNode cur = new ListNode(result % 10);
            carry = result / 10;
            cur.next = newHead;
            newHead = cur;
        }
        if (carry != 0) {
            ListNode cur = new ListNode(carry);
            cur.next = newHead;
            newHead = cur;
        }
        return newHead;
    }
}
```
### <a name="2"></a>2. Add Two Numbers
```java
/**
 * Definition for singly-linked list.
 * public class ListNode {
 *     int val;
 *     ListNode next;
 *     ListNode(int x) { val = x; }
 * }
 */
 /*
    Two things to make the code simple:
    Whenever one of the two ListNode is null, replace it with 0.
    Keep the while loop going when at least one of the three conditions is met.
 */
class Solution {
    public ListNode addTwoNumbers(ListNode l1, ListNode l2) {
        ListNode newHead = new ListNode(0);
        ListNode pre = newHead;
        int carry = 0;
        while (l1 != null || l2 != null || carry != 0) {
            ListNode cur = new ListNode(0);
            int sum = ((l1 == null) ? 0 : l1.val) + ((l2 == null) ? 0 : l2.val) + carry;
            carry = sum / 10;
            cur.val = sum % 10;
            
            pre.next = cur;
            pre = cur;
            l1 = (l1 == null) ? null : l1.next;
            l2 = (l2 == null) ? null : l2.next;
        }
        return newHead.next;
    }
}
```

### <a name="287"></a>287. Find the Duplicate Number
```java
// linked list, O(n)
class Solution {
    public int findDuplicate(int[] nums) {
        if (nums == null || nums.length == 0) return -1;
        int fast = nums[nums[0]];
        int slow = nums[0];
        
        while (fast != slow) {
            fast = nums[nums[fast]];
            slow = nums[slow];
        }
        
        fast = 0;
        while (fast != slow) {
            fast = nums[fast];
            slow = nums[slow];
        }
        return slow;
    }
}

//Java O(1)space using Binary-Search
public int findDuplicate(int[] nums) {
	int low = 1, high = nums.length - 1;
    while (low <= high) {
        int mid = (int) (low + (high - low) / 2);
        int count = 0;
        for (int a : nums) {
            if (a <= mid) ++count;
        }
        if (count <= mid) low = mid + 1;
        else high = mid - 1;
    }
    return low;
}
```
### <a name="142"></a>142. Linked List Cycle II
```java
/*
Suppose the first meet at step k,the length of the Cycle is r. so..2k-k=nr,k=nr

Now, the distance between the start node of list and the start node of cycle is s. the distance between the start of list and the first meeting node is k(the pointer which wake one step at a time waked k steps).the distance between the start node of cycle and the first meeting node is m, so...s=k-m,

s=nr-m=(n-1)r+(r-m),here we takes n = 1..so, using one pointer start from the start node of list, another pointer start from the first meeting node, all of them wake one step at a time, the first time they meeting each other is the start of the cycle.
*/

/**
 * Definition for singly-linked list.
 * class ListNode {
 *     int val;
 *     ListNode next;
 *     ListNode(int x) {
 *         val = x;
 *         next = null;
 *     }
 * }
 */
public class Solution {
    public ListNode detectCycle(ListNode head) {
        ListNode fast = head;
        ListNode slow = head;
        while (fast != null && fast.next != null) {
            slow = slow.next;
            fast = fast.next.next;
            
            if (slow == fast) {
                fast = head;
                while (fast != slow) {
                    fast = fast.next;
                    slow = slow.next;
                }
                return slow;
            }
        }
        return null;
    }
}
```
### <a name="141"></a>141. Linked List Cycle
```java
/**
 * Definition for singly-linked list.
 * class ListNode {
 *     int val;
 *     ListNode next;
 *     ListNode(int x) {
 *         val = x;
 *         next = null;
 *     }
 * }
 */
public class Solution {
    public boolean hasCycle(ListNode head) {
        ListNode fasterNode = head;
        ListNode slowerNode = head;
        while (fasterNode != null && fasterNode.next != null && slowerNode != null) {
            fasterNode = fasterNode.next.next;
            slowerNode = slowerNode.next;
            if (fasterNode == slowerNode) {
                return true;
            }
        }
        
        return false;
    }
}
```
### <a name="143"></a>143. Reorder List
```java
/**
 * Definition for singly-linked list.
 * public class ListNode {
 *     int val;
 *     ListNode next;
 *     ListNode(int x) { val = x; }
 * }
 */
 /*
 we can solve this problem in 4 steps:
1. use fast and slow pointers find the mid node
2. then divide the list into two parts from the mid node
3. reverse the second part
4. merge these two parts one by one eg: 1234 --> 12 and 34 --> 12 and 43 --> 1423

 */
class Solution{
	public ListNode reorderList(ListNode head){
		if(head == null || head.next == null){
			return;
		}
		//find the mid node, using fast and slow pointer
		ListNode slow = head;
		ListNode fast = head;
		while(fast.next != null && fast.next.next != null){
			slow = slow.next;
			fast = fast.next.next;
		}

		//establish two heads
		ListNode head1 = head;
		ListNode head2 = slow.next;
		//disconnect the list
		slow.next = null;

		//reverse the list start with head2
		head2 = reverseList(head2);

		//merge two list
		while(head1 != null && head2 != null){
			ListNode nextHead2 = head2.next;
			head2.next = head1.next;
			head1.next = head2;
			head1 = head2.next;
			head2 = nextHead2;
		}
	}

	private ListNode reverseList(ListNode cur){
		ListNode pre = null;
		while(cur != null){
			ListNode next = cur.next;
			cur.next = pre;
			pre = cur;
			cur = next;
		}
		return pre;
	}
}
```
### <a name="206"></a>206. Reverse Linked List
```java
/**
 * Definition for singly-linked list.
 * public class ListNode {
 *     int val;
 *     ListNode next;
 *     ListNode(int x) { val = x; }
 * }
 */
class Solution {
    //iterative
    public ListNode reverseList(ListNode head) {
        ListNode newHead = null;
        while (head != null) {
            ListNode savedNext = head.next;
            head.next = newHead;
            newHead = head;
            head = savedNext;
        }
        return newHead;
        
        //return reverse(head, null);
    }
    // recursive
    //from the iteration we notice that the pointer for head and newHead is change recursively so we can solve this problem in recursion
    public ListNode reverse(ListNode head, ListNode newHead) {
        if (head == null) return newHead;
        ListNode savedNext = head.next;
        head.next = newHead;
        return reverse(savedNext, head);
    }
}
```
### <a name="160"></a>160. Intersection of Two Linked Lists
```java
// Use length
/**
 * Definition for singly-linked list.
 * public class ListNode {
 *     int val;
 *     ListNode next;
 *     ListNode(int x) {
 *         val = x;
 *         next = null;
 *     }
 * }
 */
public class Solution {
    public ListNode getIntersectionNode(ListNode headA, ListNode headB) {
        int lengthA = 0;
        ListNode tailA = headA;
        while (tailA != null) {
            lengthA++;
            tailA = tailA.next;
        }
        
        int lengthB = 0;
        ListNode tailB = headB;
        while (tailB != null) {
            lengthB++;
            tailB = tailB.next;
        }
        
        if (tailA != tailB) {return null;}
        
        if (lengthA > lengthB) {
            int dis = lengthA - lengthB;
            while (dis > 0) {
                headA = headA.next;
                dis --;
            }
        } else {
            int dis = lengthB - lengthA;
            while (dis > 0) {
                headB = headB.next;
                dis --;
            }
        }
        
        while (headA != null && headB != null) {
            if (headA == headB) {
                return headA;
            }
            headA = headA.next;
            headB = headB.next;
        }
        
        return null;
    }
}

// Without using length
/* We can use two iterations to do that. In the first iteration, we will reset the pointer of one linkedlist to the head of another linkedlist after it reaches the tail node. In the second iteration, we will move two pointers until they points to the same node. Our operations in first iteration will help us counteract the difference. So if two linkedlist intersects, the meeting point in second iteration must be the intersection point. If the two linked lists have no intersection at all, then the meeting pointer in second iteration must be the tail node of both lists, which is null */

public ListNode getIntersectionNode(ListNode headA, ListNode headB) {
    //boundary check
    if(headA == null || headB == null) return null;
    
    ListNode a = headA;
    ListNode b = headB;
    
    //if a & b have different len, then we will stop the loop after second iteration
    while( a != b){
    	//for the end of first iteration, we just reset the pointer to the head of another linkedlist
        a = a == null? headB : a.next;
        b = b == null? headA : b.next;    
    }
    
    return a;
}

// O(m + n) sum of parts before intersection
// without traversal
    public ListNode getIntersectionNode(ListNode headA, ListNode headB) {
        List<ListNode> visited = new ArrayList<>();
        
        while (headA != null || headB != null) {
            if (headA != null) {
                if (visited.contains(headA)) {
                    return headA;
                }
                visited.add(headA);
                headA = headA.next;
            }
            
            if (headB != null) {
                if (visited.contains(headB)) {
                    return headB;
                }
                visited.add(headB);
                headB = headB.next;
            }
        }
        
        return null;
    }

```

### <a name="211"></a>211. Add and Search Word - Data structure design
```java

/*
* For add -> O(n) : n is the length of added word
* For search -> max O(26^n)
// add / search: O(wordLength) time; O(numOfTrieNode * 26) = O(numOfWords * wordLength * 26) space
*/
class TrieNode {
    public char val;
    public boolean isWord;
    public TrieNode [] children = new TrieNode[26];
    public TrieNode() {};
    public TrieNode(char c) {
        TrieNode node = new TrieNode();
        node.val = c;
    }
}

public class WordDictionary {
    TrieNode root;
    
    /** Initialize your data structure here. */
    public WordDictionary() {
        root = new TrieNode();    
    }
    
    /** Adds a word into the data structure. */
    public void addWord(String word) {
        if (word == null) return;
        TrieNode node = root;
        for (char c : word.toCharArray()) {
            if (node.children[c - 'a'] == null) {
                node.children[c - 'a'] = new TrieNode(c);
            }
            node = node.children[c - 'a'];
        }
        node.isWord = true;
    }
    
    /** Returns if the word is in the data structure. A word could contain the dot character '.' to represent any one letter. */
    public boolean search(String word) {
        return doSearchFromNode(word, root);
    }
    
    public boolean doSearchFromNode(String word, TrieNode node) {
        if (word == null || node == null) return false;
        for (int i = 0; i < word.length(); i ++) {
            char c = word.charAt(i);
            if (c != '.') {
                if (node.children[c - 'a'] == null) {
                    return false;
                }
                node = node.children[c - 'a'];
            } else {
                String newWord = word.substring(i + 1);
                for (TrieNode child : node.children) {
                    if (doSearchFromNode(newWord, child)) {
                        return true;
                    }
                }
                return false;
            }
        }
        return node.isWord;
    }
}

/**
 * Your WordDictionary object will be instantiated and called as such:
 * WordDictionary obj = new WordDictionary();
 * obj.addWord(word);
 * boolean param_2 = obj.search(word);
 */
```
### <a name="208"></a>208. Implement Trie (Prefix Tree)
```java
class TrieNode {
    public char val;
    public boolean isWord;
    public TrieNode[] children = new TrieNode[26];
    public TrieNode () {}
    public TrieNode (char c) {
        TrieNode node = new TrieNode();
        node.val = c;
    }
}

public class Trie {

    TrieNode root;
    /** Initialize your data structure here. */
    public Trie() {
        root = new TrieNode();
    }
    
    /** Inserts a word into the trie. */
    public void insert(String word) {
        if (word == null) return;
        TrieNode node = root;
        for (char c : word.toCharArray()) {
            if (node.children[c - 'a'] == null) {
                node.children[c - 'a'] = new TrieNode(c);
            }
            node = node.children[c - 'a'];
        }
        node.isWord = true;
    }
    
    /** Returns if the word is in the trie. */
    public boolean search(String word) {
        if (word == null) return false;
        TrieNode node = root;
        for (char c : word.toCharArray()) {
            if (node.children[c - 'a'] == null) {
                return false;
            }
            node = node.children[c - 'a'];
        }
        return node.isWord;
    }
    
    /** Returns if there is any word in the trie that starts with the given prefix. */
    public boolean startsWith(String prefix) {
        if (prefix == null) return false;
        TrieNode node = root;
        for (char c : prefix.toCharArray()) {
            if (node.children[c - 'a'] == null) {
                return false;
            }
            node = node.children[c - 'a'];
        }
        return true;
    }
}

/**
 * Your Trie object will be instantiated and called as such:
 * Trie obj = new Trie();
 * obj.insert(word);
 * boolean param_2 = obj.search(word);
 * boolean param_3 = obj.startsWith(prefix);
 */
```
### <a name="398"></a>398. Random Pick Index
```java
/*
To those who don't understand why it works. Consider the example in the OJ
{1,2,3,3,3} with target 3, you want to select 2,3,4 with a probability of 1/3 each.

2 : It's probability of selection is 1 * (1/2) * (2/3) = 1/3
3 : It's probability of selection is (1/2) * (2/3) = 1/3
4 : It's probability of selection is just 1/3

So they are each randomly selected.
*/
class Solution {
    private int[] nums;
    private Random random;
    public Solution(int[] nums) {
        this.nums = nums;
        this.random = new Random();
    }
    
    public int pick(int target) {
        int result = -1;
        int count = 0;
        
        for (int i = 0; i < nums.length; i ++) {
            if (nums[i] != target) continue;
            /*
            For the nth target, ++count is n. Then the probability that rnd.nextInt(++count)==0 is 1/n. Thus, the probability that return nth target is 1/n.
            For (n-1)th target, the probability of returning it is (n-1)/n * 1/(n-1)= 1/n.
            */
            if (random.nextInt(++count) == 0) {
                result = i;
            }
        }
        return result;
    }
}

/**
 * Your Solution object will be instantiated and called as such:
 * Solution obj = new Solution(nums);
 * int param_1 = obj.pick(target);
 */
```
### <a name="215"></a>215. Kth Largest Element in an Array
```java
/*
O(N) best case / O(N^2) worst case running time + O(1) memory
The smart approach for this problem is to use the selection algorithm (based on the partion method - the same one as used in quicksort).

// quickSelect(optimized quickSort,iterative):average O(n) time,worst case(all nums are are the same) O(n^2) time, O(1) space
*/
class Solution {
    public int findKthLargest(int[] nums, int k) {
        if (nums == null || nums.length < k) return 0;
        k = nums.length - k;
        int low = 0;
        int high = nums.length - 1;
        while (low < high) {
            int pivotIndex = partition(nums, low, high);
            if (pivotIndex == k) break;
            if (pivotIndex > k) {
                high = pivotIndex - 1;
            } else {
                low = pivotIndex + 1;
            }
        }
        return nums[k];
    }
    
    public int partition(int[] nums, int low, int high) {
        int pivot = nums[high];
        int i = low;
        for (int j = low; j < high; j ++) {
            if (nums[j] <= pivot) {
                swap(nums, i++, j);
            }
        }
        swap(nums, i, high);
        return i;
    }
    
    public void swap(int[] nums, int i, int j) {
        int tmp = nums[i];
        nums[i] = nums[j];
        nums[j] = tmp;
    }
}

/* O(N lg K) running time + O(K) memory
Other possibility is to use a min oriented priority queue that will store the K-th largest values. The algorithm iterates over the whole input and maintains the size of priority queue.
*/

public int findKthLargest(int[] nums, int k) {

    final PriorityQueue<Integer> pq = new PriorityQueue<>();
    for(int val : nums) {
        pq.offer(val);

        if(pq.size() > k) {
            pq.poll();
        }
    }
    return pq.peek();
}
```
### <a name="692"></a>692. Top K Frequent Words
```java
// O(nlogK)
class Solution {
    public List<String> topKFrequent(String[] words, int k) {
        List<String> result = new ArrayList<>();
        Map<String, Integer> hm = new HashMap<>();
        for (String word : words) {
            hm.put(word, hm.getOrDefault(word, 0) + 1);
        }
        
        PriorityQueue<Map.Entry<String, Integer>> pq = new PriorityQueue<>((a, b) -> (a.getValue() == b.getValue()) ? b.getKey().compareTo(a.getKey()) : a.getValue() - b.getValue());
        // or max heap , set size to k
        for(Map.Entry<String, Integer> entry: hm.entrySet()) {
            pq.offer(entry);
            if(pq.size()>k)
                pq.poll();
        }
        
        while (!pq.isEmpty()) {
            result.add(pq.poll().getKey());
        } 
        Collections.reverse(result);
        return result;
    }
}
```


### <a name="347"></a>347. Top K Frequent Elements
```java
// Bucket Sort O(n)
class Solution {
    public List<Integer> topKFrequent(int[] nums, int k) {
        List<Integer> result = new ArrayList<>();
        if (nums == null || nums.length == 0) return result;
        
        Map<Integer, Integer> hm = new HashMap<>();
        for (int num : nums) {
            hm.put(num, hm.getOrDefault(num, 0) + 1);
        }
        
        List<Integer>[] frequencyBuckets = new List[nums.length + 1];
        for (int key : hm.keySet()) {
            int frequency = hm.get(key);
            if (frequencyBuckets[frequency] == null) {
                frequencyBuckets[frequency] = new ArrayList<Integer>();
            }
            frequencyBuckets[frequency].add(key);
        }
        
        for (int i = frequencyBuckets.length - 1; i >= 0 && result.size() < k; i --) {
            if (frequencyBuckets[i] != null) {
                result.addAll(frequencyBuckets[i]);
            }
        }
        return result;
    }
}

// use maxHeap. Put entry into maxHeap so we can always poll a number with largest frequency
// O(nlogk)
public class Solution {
    public List<Integer> topKFrequent(int[] nums, int k) {
        Map<Integer, Integer> map = new HashMap<>();
        for(int n: nums){
            map.put(n, map.getOrDefault(n,0)+1);
        }
           
        PriorityQueue<Map.Entry<Integer, Integer>> maxHeap = 
                         new PriorityQueue<>((a,b)->(a.getValue() - b.getValue()));
        
        for(Map.Entry<Integer,Integer> entry: map.entrySet()) {
            maxHeap.offer(entry);
            while (maxHeap.size() > k) { // keep k elements, O(logk)
                maxHeap.poll();
            }
        }
        
        List<Integer> res = new ArrayList<>();
        while(res.size()<k){
            Map.Entry<Integer, Integer> entry = maxHeap.poll();
            res.add(entry.getKey());
        }
        return res;
    }
}

// use treeMap. Use freqncy as the key so we can get all freqencies in order
public class Solution {
    public List<Integer> topKFrequent(int[] nums, int k) {
        Map<Integer, Integer> map = new HashMap<>();
        for(int n: nums){
            map.put(n, map.getOrDefault(n,0)+1);
        }
        
        TreeMap<Integer, List<Integer>> freqMap = new TreeMap<>();
        for(int num : map.keySet()){
           int freq = map.get(num);
           if(!freqMap.containsKey(freq)){
               freqMap.put(freq, new LinkedList<>());
           }
           freqMap.get(freq).add(num);
        }
        
        List<Integer> res = new ArrayList<>();
        while(res.size()<k){
            Map.Entry<Integer, List<Integer>> entry = freqMap.pollLastEntry();
            res.addAll(entry.getValue());
        }
        return res;
    }
}
```
### <a name="155"></a>155. Min Stack
```java
class MinStack {
    int min = Integer.MAX_VALUE;
    Stack<Integer> stack;
    /** initialize your data structure here. */
    public MinStack() { 
        this.stack = new Stack<>();
    }
    
    public void push(int x) {
        // only push the old minimum value when the current 
        // minimum value changes after pushing the new value x
        if (x <= min) {
            stack.push(min);
            min = x;
        }
        stack.push(x);
    }
    
    public void pop() {
        // if pop operation could result in the changing of the current minimum value, 
        // pop twice and change the current minimum value to the last minimum value.
        if (min == stack.pop()) {
            min = stack.pop();
        }
    }
    
    public int top() {
        return stack.peek();
    }
    
    public int getMin() {
        return min;
    }
}

/**
 * Your MinStack object will be instantiated and called as such:
 * MinStack obj = new MinStack();
 * obj.push(x);
 * obj.pop();
 * int param_3 = obj.top();
 * int param_4 = obj.getMin();
 */
```

### <a name="301"></a>301. Remove Invalid Parentheses
```java
/*
"()())()" -> ["()()()", "(())()"]
"(a)())()" -> ["(a)()()", "(a())()"]
")(" -> [""]
*/
/*
Explanation:
1. Use a counter.
The counter will increase when it is ‘(‘ and decrease when it is ‘)’. Whenever the counter is negative, we have more ‘)’ than ‘(‘ in the prefix.

2.
To make the prefix valid, we need to remove a ‘)’. However, if we remove any one, we will generate duplicate results, for example: s = ()), we can remove s[1] or s[2] but the result is the same (). Thus, we restrict ourself to remove the first ) in a series of concecutive )s.

3.
After the removal, the prefix is then valid. We then call the function recursively to solve the rest of the string. However, we need to keep another information: the last removal position. If we do not have this position, we will generate duplicate by removing two ‘)’ in two steps only with a different order.

For this, we keep tracking the last removal position and only remove ‘)’ after that.


Now one may ask. What about ‘(‘? What if s = ‘(()(()’ in which we need remove ‘(‘?
The answer is: do the same from right to left.
However a cleverer idea is: reverse the string and reuse the code!
Here is the final implement in Java.
*/
/*
Every path in the search generates one valid answer. The whole search space is a tree with k leaves. The number of nodes in the tree is roughly O(k). But this is not always true, for example a degenerated tree.

To generate one node it requires O(n) time from the string concatenation among other things. So roughly O(nk). Accurately O(nm) where m is the total "number of recursive calls" or "nodes in the search tree". Then you need to relate m to n in the worst case.
*/
// DFS
class Solution {
    public List<String> removeInvalidParentheses(String s) {
        List<String> result = new ArrayList<>();
        remove(s, result, 0, 0, new char[] {'(', ')'});
        return result;
    }
    
    public void remove(String s, List<String> result, int last_i, int last_j, char [] pair) {
        for (int i = last_i, counter = 0; i < s.length(); i ++) {
            if (s.charAt(i) == pair[0]) counter ++;
            if (s.charAt(i) == pair[1]) counter --;
            if (counter >= 0) continue;
            for (int j = last_j; j <= i; j ++) {
                if (s.charAt(j) == pair[1] && (j == last_j || s.charAt(j - 1) != pair[1])) {
                    remove(s.substring(0, j) + s.substring(j + 1), result, i, j, pair);
                }
            }
            return;
        }
        String reversed = new StringBuilder(s).reverse().toString();
        if (pair[0] == '(') {
            remove(reversed, result, 0, 0, new char[] {')', '('});
        }
        else {
            result.add(reversed);
        }
    }   
}
```

### <a name="79"></a>79. Word Search
```java
// ask whether allowed to edit board !!!!
// dfs backtracking solution: O(4^n) time, O(n) stack space, n is word.length
class Solution {
    public boolean exist(char[][] board, String word) {
        if (board == null || board.length == 0 || board[0].length == 0 || word == null) return false;
        if (word.length() == 0) return true;
        
        for (int i = 0; i < board.length; i ++) {
            for (int j = 0; j < board[0].length; j ++) {
                if (searchAround(board, i, j, word, 0)) {
                    return true;
                }
            }
        }
        return false;
    }
    
    public boolean searchAround(char[][] board, int i, int j, String word, int index) {
        if (index > word.length() - 1) return true; // This line should be placed on TOP !!!!
        if (i < 0 || i > board.length - 1 || j < 0 || j > board[0].length - 1) return false;
        
        if (board[i][j] == word.charAt(index)) {
            board[i][j] = '0';
            if (searchAround(board, i + 1, j, word, index + 1) || 
                searchAround(board, i - 1, j, word, index + 1) ||
                searchAround(board, i, j + 1, word, index + 1) ||
                searchAround(board, i, j - 1, word, index + 1)) {
                return true;
            }
            board[i][j] = word.charAt(index);
        }
        return false;
    }
}
```

### <a name="257"></a>257. Binary Tree Paths
```java
/*
1，最简单的解法 O(n)
如果是print full tree O(nlogn)一条线：O(n^2) 优化：StringBuilder
*/

/**
 * Definition for a binary tree node.
 * public class TreeNode {
 *     int val;
 *     TreeNode left;
 *     TreeNode right;
 *     TreeNode(int x) { val = x; }
 * }
 */
class Solution {
    public List<String> binaryTreePaths(TreeNode root) {
        List<String> result = new ArrayList<>();
        if (root == null) {
            return result;
        }
        for (String s : binaryTreePaths(root.left)) {
            result.add(String.valueOf(root.val) + "->" + s);
        }
        for (String s : binaryTreePaths(root.right)) {
            result.add(String.valueOf(root.val) + "->" + s);
        }
        if (result.size() == 0) {
            result.add(String.valueOf(root.val));
        }
        return result;
    }
}

// iterative (dfs pre-order)
public class Solution {
    public List<String> binaryTreePaths(TreeNode root) {
        List<String> res = new ArrayList<>();
        if (root == null) {
            return res;
        }
        Stack<TreeNode> stack = new Stack<>();
        Stack<StringBuilder> paths = new Stack<>();
        stack.push(root);
        paths.push(new StringBuilder(root.val + ""));//remember to add + "" !!!
        while (!stack.empty()) {
            TreeNode node = stack.pop();
            StringBuilder path = paths.pop();
            if (node.left == null && node.right == null) {
                res.add(path.toString());
            }
            if (node.right != null) {
                stack.push(node.right);
                StringBuilder newPath = new StringBuilder(path);
                paths.push(newPath.append("->" + node.right.val));
            }
            if (node.left != null) {
                stack.push(node.left);
                StringBuilder newPath = new StringBuilder(path);
                paths.push(newPath.append("->" + node.left.val));
            }
        }
        return res;
    }
}

// iterative (bfs), use queue to store ArrayList<TreeNode>, which is the path
public class Solution {
    public List<String> binaryTreePaths(TreeNode root) {
        List<String> res = new ArrayList<>();
        if (root == null) {
            return res;
        }
        Queue<ArrayList<TreeNode>> queue = new LinkedList<>();
        queue.offer(new ArrayList<>(Arrays.asList(root)));
        while (!queue.isEmpty()) {
            ArrayList<TreeNode> path = queue.poll();
            TreeNode curr = path.get(path.size() - 1);
            if (curr.left == null && curr.right == null) {
                StringBuilder sb = new StringBuilder();
                for (TreeNode node : path) {
                    sb.append(node.val + "->");
                }
                sb.setLength(sb.length() - 2);//it's void type !!!
                res.add(sb.toString());
                continue;
            }
            if (curr.left != null) {
                ArrayList<TreeNode> newPath = new ArrayList<>(path);
                newPath.add(curr.left);
                queue.offer(newPath);
            }
            if (curr.right != null) {
                ArrayList<TreeNode> newPath = new ArrayList<>(path);
                newPath.add(curr.right);
                queue.offer(newPath);
            }
        }
        return res;
    }
}

// follow up, print + append
// 比如有一个 root to leaf path 是 1 2 5 2，target 是2，那么这个 path 就应该打印成 1 1 2 5 1 2 5 2。每次遇到 2 就把前面的路径重新 append 一下: 1 (1 2) 5 (1 2 5 2).
public class Solution {
    public List<String> binaryTreePaths(TreeNode root,int target) {
        List<String> res=new ArrayList<>();
        if(root==null) return res;
        helper(res,root,"","",target);
        return res;
    }
    public void helper(List<String> res,TreeNode root,String s,String target_s,int target){
        if(root.left==null&&root.right==null){
            if(root.val==target){
                res.add(target_s+s+root.val);
            }else res.add(target_s+root.val);
        }
        if(root.left!=null){
            if(root.val==target){
                helper(res,root.left,s+root.val+"->",target_s+s+root.val+"->",target);
            }else helper(res,root.left,s+root.val+"->",target_s+root.val+"->",target);
        }
        if(root.right!=null){
            if(root.val==target){
                helper(res,root.right,s+root.val+"->",target_s+s+root.val+"->",target);
            }else helper(res,root.right,s+root.val+"->",target_s+root.val+"->",target);
        }
    }
}
```

### <a name="200"></a>200. Number of Islands
```java
/*
The time complexity is O(m*n), where m and n are the width and height of the grid, respectively. The time complexity is only "linear" in the number of cells in the grid.
*/
// DFS
class Solution {
    public int numIslands(char[][] grid) {
        if (grid == null || grid.length == 0 || grid[0].length == 0) {
            return 0;
        }
        int height = grid.length;
        int width = grid[0].length;
        
        int count = 0;
        for (int i = 0; i < height; i ++) {
            for (int j = 0; j < width; j ++) {
                if (exploreArea(grid, i, j)) {
                    count ++;
                }
            }
        }
        return count;
    }
    
    public boolean exploreArea(char[][] grid, int i, int j) {
        if (i < 0 || i > grid.length - 1 || j < 0 || j > grid[0].length - 1 || grid[i][j] == '0') {
            return false;
        }
        grid[i][j] = '0';
        exploreArea(grid, i + 1, j);
        exploreArea(grid, i, j + 1);
        exploreArea(grid, i - 1, j);
        exploreArea(grid, i, j - 1);
        return true;
    }
}
//1, 如果加上斜的也可以。dfs加四种情况
        dfs(grid,i-1,j-1);
        dfs(grid,i+1,j+1);
        dfs(grid,i-1,j+1);
        dfs(grid,i+1,j-1);
//2, 不让改变原有的input，我就说那就建一个相同size的2d boolean array。或者visited[][]设成global
//4, dfs，有可能stack overflow

// union
class UF {
    public int count = 0;
    public int[] id = null;

    public UF(int m, int n, char[][] grid) {
        for(int i = 0; i < m; i++) {
            for(int j = 0; j < n; j++) {
                if(grid[i][j] == '1') count++;
            }
        }
        id = new int[m * n];
        for(int i = 0; i < m * n; i++) {
            id[i] = i;
        }
    }

    public int find(int p) {
        while(p != id[p]) {
            id[p] = id[id[p]];
            p = id[p];
        }
        return p;
    }

    public boolean isConnected(int p, int q) {
        int pRoot = find(p);
        int qRoot = find(q);
        if(pRoot != qRoot) return false;
        else return true;
    }

    public void union(int p, int q) {
        int pRoot = find(p);
        int qRoot = find(q);
        if(pRoot == qRoot) return;
        id[pRoot] = qRoot;
        count--;
    }
}

public int numIslands(char[][] grid) {
    if(grid.length == 0 || grid[0].length == 0) return 0;
    int m = grid.length, n = grid[0].length;
    UF uf = new UF(m , n, grid);
    
    for(int i = 0; i < m; i++) {
        for(int j = 0; j < n; j++) {
            if(grid[i][j] == '0') continue;
            int p = i * n + j;
            int q;
            if(i > 0 && grid[i - 1][j] == '1') {
                q = p - n;
                uf.union(p, q);
            }
            if(i < m - 1 && grid[i + 1][j] == '1') {
                q = p + n;
                uf.union(p, q);
            }
            if(j > 0 && grid[i][j - 1] == '1') {
                q = p - 1;
                uf.union(p, q);
            }
            if(j < n - 1 && grid[i][j + 1] == '1') {
                q = p + 1;
                uf.union(p, q);
            }
        }
    }
    return uf.count;
}
```

### <a name="268"></a>268. Missing Number
```java
// 1.XOR
public int missingNumber(int[] nums) { //xor
    int res = nums.length;
    for(int i=0; i<nums.length; i++){
        res ^= i;
        res ^= nums[i];
    }
    return res;
}

// 2.SUM
public int missingNumber(int[] nums) { //sum
    int len = nums.length;
    int sum = (0+len)*(len+1)/2;
    for(int i=0; i<len; i++)
        sum-=nums[i];
    return sum;
}

// 3.Binary Search
public int missingNumber(int[] nums) { //binary search
    Arrays.sort(nums);
    int left = 0, right = nums.length, mid= (left + right)/2;
    while(left<right){
        mid = (left + right)/2;
        if(nums[mid]>mid) right = mid;
        else left = mid+1;
    }
    return left;
}
```

### <a name="278"></a>278. First Bad Version
```java
/* The isBadVersion API is defined in the parent class VersionControl.
      boolean isBadVersion(int version); */
// O(logN)
public class Solution extends VersionControl {
    public int firstBadVersion(int n) {
        int start = 1;
        int end = n;
        while (start < end) {
            int middle = start + (end - start) / 2;
            if (isBadVersion(middle)) {
                end = middle;
            } else {
                start = middle + 1;
            }
        }
        return start;
    }
}

//if the boundary n is unknown, we can use 2^n (2^1,2^2...2^n) until we shrink the range into 2^n and 2^(n-1),
//then we use binary search in the range to find the boundary, after boundary found, the rest is the same as below
public class Solution extends VersionControl {
    public int firstBadVersion(int n) {
        if (n < 1) {
            return -1;
        }
        int start = 1;
        int end = n;
        while (start + 1 < end) {
            int mid = start + (end - start) / 2;
            if (isBadVersion(mid)) {
                end = mid;
            } else {
                start = mid;
            }
        }
        if (isBadVersion(start)) {
            return start;
        }
        if (isBadVersion(end)) {
            return end;
        }
        return -1;
    }
}
```

### <a name="131"></a>131. Palindrome Partitioning
```java
class Solution {
    public List<List<String>> partition(String s) {
        List<List<String>> result = new ArrayList<>();
        search(result, new ArrayList<String>(), s, 0);
        return result;
    }
    
    public void search(List<List<String>> result, List<String> tmpList, String s, int index) {
        if (index == s.length()) {
            result.add(new ArrayList<>(tmpList));
        } else {
            for (int i = index; i < s.length(); i ++) {
                if (isPalindrome(s, index, i)) {
                    tmpList.add(s.substring(index, i + 1));
                    search(result, tmpList, s, i + 1);
                    tmpList.remove(tmpList.size() - 1);
                }
            }
        }
    }
    
    public boolean isPalindrome(String s, int start, int end) {
        while (start < end) {
            if (s.charAt(start) != s.charAt(end)) {
                return false;
            }
            start ++;
            end --;
        }
        return true;
    }
}
```
### <a name="47"></a>47. Permutations II
```java
class Solution {
    public List<List<Integer>> permuteUnique(int[] nums) {
        List<List<Integer>> result = new ArrayList<>();
        Arrays.sort(nums);
        search(result, new ArrayList<>(), nums, new boolean [nums.length]);
        return result;
    }
    
    public void search(List<List<Integer>> list, List<Integer>tmpList, int[] nums, boolean[] used) {
        if (tmpList.size() == nums.length) {
            list.add(new ArrayList<>(tmpList));
        } else {
            for (int i = 0; i < nums.length; i ++) {
                if (used[i]) continue;
                if (i > 0 && nums[i] == nums[i - 1] && !used[i - 1]) continue;
                used[i] = true;
                tmpList.add(nums[i]);
                search(list, tmpList, nums, used);
                tmpList.remove(tmpList.size() - 1);
                used[i] = false;
            }
        }
    }
}
```

### <a name="46"></a>46. Permutations
```java
class Solution {
    public List<List<Integer>> permute(int[] nums) {
        List<List<Integer>> result = new ArrayList<>();
        search(result, new ArrayList<>(), nums);
        return result;
    }
    
    public void search(List<List<Integer>> list, List<Integer> tmpList, int[] nums) {
        if (tmpList.size() == nums.length) {
            list.add(new ArrayList<>(tmpList));
        } else {
            for (int i = 0; i < nums.length; i ++) {
                if (tmpList.contains(nums[i])) continue;
                tmpList.add(nums[i]);
                search(list, tmpList, nums);
                tmpList.remove(tmpList.size() - 1);
            }
        }
    }
}
```

### <a name="90"></a>90. Subsets II
```java
class Solution {
    public List<List<Integer>> subsetsWithDup(int[] nums) {
        List<List<Integer>> result = new ArrayList<>();
        Arrays.sort(nums);
        search(result, new ArrayList<Integer>(), nums, 0);
        return result;
    }
    
    public void search(List<List<Integer>> list, List<Integer> tmpList, int[] nums, int index) {
        list.add(new ArrayList<>(tmpList));
        for (int i = index; i < nums.length; i ++) {
            if (i != index && nums[i] == nums[i - 1]) continue;
            tmpList.add(nums[i]);
            search(list, tmpList, nums, i + 1);
            tmpList.remove(tmpList.size() - 1);
        }
    }
}
```

### <a name="78"></a>78. Subsets
```java
/*
Pick a starting point.
while(Problem is not solved)
    For each path from the starting point.
        check if selected path is safe, if yes select it
        and make recursive call to rest of the problem
        before which undo the current move.
    End For
If none of the move works out, return false, NO SOLUTON.
*/
class Solution {
    public List<List<Integer>> subsets(int[] nums) {
        List<List<Integer>> result = new ArrayList<>();
        search(result, new ArrayList<Integer>(), nums, 0);
        return result;
    }
    
    public void search(List<List<Integer>> list, List<Integer> tmpList, int[] nums, int index) {
        list.add(new ArrayList<>(tmpList));
        for (int i = index; i < nums.length; i ++) {
            tmpList.add(nums[i]);
            search(list, tmpList, nums, i + 1);
            tmpList.remove(tmpList.size() - 1);
        }
    }
}
```
### <a name="240"></a>240. Search a 2D Matrix II
```java
class Solution {
    public boolean searchMatrix(int[][] matrix, int target) {
        if (matrix == null || matrix.length == 0 || matrix[0].length == 0) return false;
        int row = matrix.length;
        int coloum = matrix[0].length;
        
        int start_row = row - 1;
        int start_coloum = 0;
        
        while (start_row >= 0 && start_coloum < coloum) {
            int value = matrix[start_row][start_coloum];
            if (value == target) {
                return true;
            }
            if (value > target) {
                start_row --;
            } else {
                start_coloum ++;
            }
        }
        return false;
    }
}
```

### <a name="74"></a>74. Search a 2D Matrix
```java
class Solution {
    public boolean searchMatrix(int[][] matrix, int target) {
        if (matrix == null || matrix.length == 0 || matrix[0].length == 0) return false;
        int row = matrix.length;
        int coloum = matrix[0].length;
        
        int start = 0;
        int end = row * coloum - 1;
        
        while (start < end) {
            int middle = start + (end - start) / 2;
            int value = matrix[middle / coloum][middle % coloum];
            if (value == target) {
                return true;
            } else if (value < target) {
                start = middle + 1;
            } else {
                end = middle - 1;
            }
        }
        return matrix[start / coloum][start % coloum] == target;
    }
}
```

### <a name="62"></a>62. Unique Paths
```java
// O(n*m)
class Solution {
    public int uniquePaths(int m, int n) {
        int[][] dp = new int[m][n];
        for (int i = 0; i < m; i ++) {
            dp[i][0] = 1;
        }
        for (int j = 0; j < n; j ++) {
            dp[0][j] = 1;
        }
        for (int i = 1; i < m; i ++) {
            for (int j = 1; j < n; j ++) {
                dp[i][j] = dp[i - 1][j] + dp[i][j - 1];
            }
        }
        return dp[m - 1][n - 1];
    }
}
```

### <a name="70"></a>70. Climbing Stairs
```java
class Solution {
    public int climbStairs(int n) {
        if (n <= 0) return 0;
        if (n <= 1) return 1;
        int[] dp = new int [n + 1];
        dp[0] = 1;
        dp[1] = 1;
        
        for (int i = 2; i <= n; i ++) {
            dp[i] = dp[i - 1] + dp[i - 2];
        }
        return dp[n];
    }
}
```
### <a name="53"></a>53. Maximum Subarray
```java
class Solution {
    public int maxSubArray(int[] nums) {
        if (nums == null || nums.length == 0) return 0;
        int[] dp = new int[nums.length]; //dp[i] means the maximum subarray ending with A[i];
        dp[0] = nums[0];
        int max = dp[0];
        
        for (int i = 1; i < nums.length; i ++) {
            dp[i] = nums[i] + ((dp[i - 1] > 0) ? dp[i - 1] : 0);
            max = Math.max(dp[i], max);
        }
        return max;
    }
}

// without DP
public class Solution {
    public int maxSubArray(int[] A) {
        int max = Integer.MIN_VALUE, sum = 0;
        for (int i = 0; i < A.length; i++) {
            if (sum < 0) 
                sum = A[i];
            else 
                sum += A[i];
            if (sum > max)
                max = sum;
        }
        return max;
    }
}
```

### <a name="322"></a>322. Coin Change
```java
class Solution {
    public int coinChange(int[] coins, int amount) {
        if (amount == 0) return 0;
        if (coins == null || coins.length == 0 || amount < 0) return -1;
        
        return findCoinChange(coins, amount, new HashMap<Integer, Integer>());
    }
    
    public int findCoinChange(int[] coins, int remain, Map<Integer, Integer> hm) {
        if (remain < 0) return -1;
        if (remain == 0) return 0;
        
        if (hm.containsKey(remain)) {
            return hm.get(remain);
        }
        
        int min = Integer.MAX_VALUE;
        for (int coin : coins) {
            int result = findCoinChange(coins, remain - coin, hm);
            if (result == 0) {
                min = 1;
                break;
            } else if (result > 0) {
                min = Math.min(min, result + 1);
            }
        }
        min = (min == Integer.MAX_VALUE) ? -1 : min;
        hm.put(remain, min);
        return min;
    }
}
```
### <a name="17"></a>17. Letter Combinations of a Phone Number
```java
// O(k^n) k: average length of KEYS
class Solution {
    String [] mapping = new String [] {"0", "1", "abc", "def", "ghi", "jkl", "mno", "pqrs", "tuv", "wxyz"};
    
    public List<String> letterCombinations(String digits) {
        if (digits == null || digits.length() == 0) return new ArrayList<String>();
        return findCombinations(digits, 0);
    }
    
    public List<String> findCombinations(String digits, int index) {
        List<String> combinations = new ArrayList<>();
        if (index == digits.length()) {
            combinations.add("");
            return combinations;
        }
        List<String> subCombinations = findCombinations(digits, index + 1);
        for (char c : mapping[digits.charAt(index) - '0'].toCharArray()) {
            for (String s : subCombinations) {
                combinations.add(String.valueOf(c) + s);
            }
        }
        return combinations;
    }
}
// iteration, Queue
public class Solution {
    public List<String> letterCombinations(String digits) {
        LinkedList<String> ans = new LinkedList<String>();
        if (digits.length()==0) return ans;
        String[] mapping = new String[] {"0", "1", "abc", "def", "ghi", "jkl", "mno", "pqrs", "tuv", "wxyz"};
        ans.add("");
        for(int i =0; i<digits.length();i++){
            int x = Character.getNumericValue(digits.charAt(i));
            while(ans.peek().length()==i){
                String t = ans.remove();
                for(char s : mapping[x].toCharArray())
                    ans.add(t+s);
            }
        }
        return ans;
    }
}
// getNumericValue = char c - '0'

public class Solution {
    	private static final String[] KEYS = { "", "", "abc", "def", "ghi", "jkl", "mno", "pqrs", "tuv", "wxyz" };
    
    	public List<String> letterCombinations(String digits) {
    		List<String> ret = new LinkedList<String>();
    		combination("", digits, 0, ret);
    		return ret;
    	}
    
    	private void combination(String prefix, String digits, int offset, List<String> ret) {
    		if (offset >= digits.length()) {
    			ret.add(prefix);
    			return;
    		}
    		String letters = KEYS[(digits.charAt(offset) - '0')];
    		for (int i = 0; i < letters.length(); i++) {
    			combination(prefix + letters.charAt(i), digits, offset + 1, ret);
    		}
    	}
    }
```

### <a name="357"></a>357. Count Numbers with Unique Digits
```java
/*
This is a digit combination problem. Can be solved in at most 10 loops.

When n == 0, return 1. I got this answer from the test case.

When n == 1, _ can put 10 digit in the only position. [0, ... , 10]. Answer is 10.

When n == 2, _ _ first digit has 9 choices [1, ..., 9], second one has 9 choices excluding the already chosen one. So totally 9 * 9 = 81. answer should be 10 + 81 = 91

When n == 3, _ _ _ total choice is 9 * 9 * 8 = 684. answer is 10 + 81 + 648 = 739

When n == 4, _ _ _ _ total choice is 9 * 9 * 8 * 7.

...

When n == 10, _ _ _ _ _ _ _ _ _ _ total choice is 9 * 9 * 8 * 7 * 6 * 5 * 4 * 3 * 2 * 1

When n == 11, _ _ _ _ _ _ _ _ _ _ _ total choice is 9 * 9 * 8 * 7 * 6 * 5 * 4 * 3 * 2 * 1 * 0 = 0
*/

class Solution {
    public int countNumbersWithUniqueDigits(int n) {
        if (n == 0) {
            return 1;
        }
        int ans = 10; 
        int base = 9;
        for (int i = 2; i <= n && i <=10; i++) {
            base = base * (11 - i);
            ans += base;
        }
        return ans;
    }
}
```
### <a name="91"></a>91. Decode Ways
```java
// O(1) Space
class Solution {
    public int numDecodings(String s) {
        if (s == null || s.length() == 0) return 0;
        
        int minusOne = (s.charAt(0) == '0') ? 0 : 1;
        int minusTwo = (s.charAt(0) == '0') ? 0 : 1;
        
        for (int i = 1; i < s.length(); i ++) {
            int combination = 0;
            int thisDigit = s.charAt(i) - '0';
            int preDigit = s.charAt(i - 1) - '0';
            
            if (thisDigit == 0 && preDigit == 0) {
                return 0;
            }
            if (thisDigit != 0) {
                combination += minusOne;
            }
            if (preDigit != 0 && preDigit * 10 + thisDigit <= 26) {
                combination += minusTwo;
            }
            minusTwo = minusOne;
            minusOne = combination;
        }
        
        return minusOne;
    }
}
/*
I used a dp array of size n + 1 to save subproblem solutions. dp[0] means an empty string will have one way to decode, dp[1] means the way to decode a string of size 1. I then check one digit and two digit combination and save the results along the way. In the end, dp[n] will be the end result.
*/
// normal DP, O(n) space
public class Solution {
    public int numDecodings(String s) {
        if(s == null || s.length() == 0) {
            return 0;
        }
        int n = s.length();
        int[] dp = new int[n+1];
        dp[0] = 1;
        dp[1] = s.charAt(0) != '0' ? 1 : 0;
        for(int i = 2; i <= n; i++) {
            int first = Integer.valueOf(s.substring(i-1, i));
            int second = Integer.valueOf(s.substring(i-2, i));
            if(first >= 1 && first <= 9) {
               dp[i] += dp[i-1];  
            }
            if(second >= 10 && second <= 26) {
                dp[i] += dp[i-2];
            }
        }
        return dp[n];
    }
}

```

### <a name="494"></a>494. Target Sum
```java
class Solution {
public int findTargetSumWays(int[] nums, int S) {
        if (nums == null || nums.length == 0){
            return 0;
        }
        return helper(nums, 0, 0, S, new HashMap<>());
    }
    private int helper(int[] nums, int index, int sum, int S, Map<String, Integer> map){
        String encodeString = index + "->" + sum;
        if (map.containsKey(encodeString)){
            return map.get(encodeString);
        }
        if (index == nums.length){
            if (sum == S){
                return 1;
            }else {
                return 0;
            }
        }
        int curNum = nums[index];
        int add = helper(nums, index + 1, sum - curNum, S, map);
        int minus = helper(nums, index + 1, sum + curNum, S, map);
        map.put(encodeString, add + minus);
        return add + minus;
    }
}
```
### <a name="647"></a>647. Palindromic Substrings
```java

/*
for the Time Complexity, I think the worst case should be O(n^2)

for example if we have an input as 'aaaa...aaaaa' (n times a)
then complexity in the helper function for each a should be:
1, 2, 3, ..., n/2, n/2, ..., 3, 2, 1

if we sum them up, it should be sth related to O(n^2)
*/
public class Solution {
    int count = 0;
    
    public int countSubstrings(String s) {
        if (s == null || s.length() == 0) return 0;
        
        for (int i = 0; i < s.length(); i++) { // i is the mid point
            extendPalindrome(s, i, i); // odd length;
            extendPalindrome(s, i, i + 1); // even length
        }
        
        return count;
    }
    
    private void extendPalindrome(String s, int left, int right) {
        while (left >=0 && right < s.length() && s.charAt(left) == s.charAt(right)) {
            count++; left--; right++;
        }
    }
}
```

### <a name="64"></a>64. Minimum Path Sum
```java
public int minPathSum(int[][] grid) {
	int m = grid.length;// row
	int n = grid[0].length; // column
	for (int i = 0; i < m; i++) {
		for (int j = 0; j < n; j++) {
			if (i == 0 && j != 0) {
				grid[i][j] = grid[i][j] + grid[i][j - 1];
			} else if (i != 0 && j == 0) {
				grid[i][j] = grid[i][j] + grid[i - 1][j];
			} else if (i == 0 && j == 0) {
				grid[i][j] = grid[i][j];
			} else {
				grid[i][j] = Math.min(grid[i][j - 1], grid[i - 1][j])
						+ grid[i][j];
			}
		}
	}

	return grid[m - 1][n - 1];
}
```
### <a name="120"></a>120. Triangle
```java
class Solution {
    public int minimumTotal(List<List<Integer>> triangle) {
        if (triangle == null || triangle.size() == 0 || triangle.get(0).size() == 0) return 0;
        for (int i = triangle.size() - 2; i >= 0 ; i --) {
            List<Integer> thisLevel = triangle.get(i);
            List<Integer> subLevel = triangle.get(i + 1);
            for (int j = 0; j < thisLevel.size(); j ++) {
               thisLevel.set(j, thisLevel.get(j) + Math.min(subLevel.get(j), subLevel.get(j + 1)));
            }
        }
        return triangle.get(0).get(0);
    }
}
```

### <a name="122"></a>122. Best Time to Buy and Sell Stock II
```java
public class Solution {
    public int maxProfit(int[] prices) {
        if (prices == null || prices.length < 2) {
            return 0;
        }
        int profit = 0;
        for (int i = 1; i < prices.length; i++) {
            if (prices[i] > prices[i - 1]) {
                profit += prices[i] - prices[i - 1];//each time we meet prices[i] that is larger than last day's prices[i - 1]
            }//we will choose to buy stock on i - 1 day and sell stock on i day
        }
        return profit;
    }
}

// followup - transaction fee
// Calculate everytime when prices[i] < prices[i+1] - cost
public int maxProfit(int[] prices, int[] transFee) {
    if(prices == null || prices.length == 0) {
        return 0;
    }
    int maxProfit = 0;
    for(int i=1; i < prices.length; i++) {
        int buy = prices[i-1]+transFee[i-1];
        int sell = prices[i]-transFee[i-1];
        if(sell > buy) {
            maxProfit += sell-buy;
        }
    }    
    return maxProfit;
}
```

### <a name="121"></a>121. Best Time to Buy and Sell Stock
```java
// find the min price
public int maxProfit(int[] prices) {
    if (prices.length == 0) {
        return 0 ;
    }		
    int max = 0 ;
    int sofarMin = prices[0] ;
    for (int i = 0 ; i < prices.length ; ++i) {
        if (prices[i] > sofarMin) {
            max = Math.max(max, prices[i] - sofarMin);
        } else{
            sofarMin = prices[i];  
        }
    }	     
    returnmax;
}

//Kadane's Algorithm
/*
All the straight forward solution should work, but if the interviewer twists the question slightly by giving the difference array of prices, Ex: for {1, 7, 4, 11}, if he gives {0, 6, -3, 7}, you might end up being confused.

Here, the logic is to calculate the difference (maxCur += prices[i] - prices[i-1]) of the original array, and find a contiguous subarray giving maximum profit. If the difference falls below 0, reset it to zero.

*maxCur = current maximum value
*maxSoFar = maximum value found so far
*/
    public int maxProfit(int[] prices) {
        int maxCur = 0, maxSoFar = 0;
        for(int i = 1; i < prices.length; i++) {
            maxCur = Math.max(0, maxCur += prices[i] - prices[i-1]);
            maxSoFar = Math.max(maxCur, maxSoFar);
        }
        return maxSoFar;
    }
```

### <a name="31"></a>31. Next Permutation
```java
/*
1. Start from its last element, traverse backward to find the first one with index i that satisfy num[i-1] < num[i]. This is the element we are going to move to back

2. To find the next permutation, we search from the end and find the first element which is bigger than the one we found in step 1, then we swap these two numbers.

3. The last step is to make the remaining higher position part as small as possible, we just have to reversely sort the num[i,n-1]
*/
// O(n)
class Solution {
    public void nextPermutation(int[] nums) {
        if (nums == null) return;
        int head = findHead(nums);
        int tail = findTail(nums, head);
        
        if (head != -1 && tail != -1) {
            swap(nums, head, tail);
        }
        reverse(nums, head + 1);
    }
    
    public int findHead(int[] nums) {
        for(int i = nums.length - 1; i > 0; i --) {
            if (nums[i] > nums[i - 1]) {
                return i - 1;
            }
        }
        return -1;
    }
    
    public int findTail(int[] nums, int headIndex) {
        if (headIndex == -1) return -1;
        for(int i = nums.length - 1; i >= 0; i --) {
            if (nums[i] > nums[headIndex]) {
                return i;
            }
        }
        return -1;
    }
    
    public void swap(int[] nums, int i, int j) {
        int tmp = nums[i];
        nums[i] = nums[j];
        nums[j] = tmp;
    }
    
    public void reverse(int[] nums, int index) {
        int i = index;
        int j = nums.length - 1;
        while (i < j) {
            swap(nums, i ++, j --);
        }
    }
}
```

### <a name="215"></a>215. Kth Largest Element in an Array
```java
// QuickSelct
/* O(N) best case / O(N^2) worst case running time + O(1) memory
The smart approach for this problem is to use the selection algorithm (based on the partion method - the same one as used in quicksort). 
*/

class Solution {
    public int findKthLargest(int[] nums, int k) {
        if (nums == null || nums.length < k) return 0;
        k = nums.length - k;
        int low = 0;
        int high = nums.length - 1;
        while (low < high) {
            int pivotIndex = partition(nums, low, high);
            if (pivotIndex == k) break;
            if (pivotIndex > k) {
                high = pivotIndex - 1;
            } else {
                low = pivotIndex + 1;
            }
        }
        return nums[k];
    }
    
    public int partition(int[] nums, int low, int high) {
        int pivot = nums[high];
        int i = low;
        for (int j = low; j < high; j ++) {
            if (nums[j] <= pivot) {
                swap(nums, i++, j);
            }
        }
        swap(nums, i, high);
        return i;
    }
    
    public void swap(int[] nums, int i, int j) {
        int tmp = nums[i];
        nums[i] = nums[j];
        nums[j] = tmp;
    }
}
```

### <a name="33"></a>33. Search in Rotated Sorted Array
```java
// O(logN)
class Solution {
    public int search(int[] nums, int target) {
        if (nums == null || nums.length == 0) return -1;
        int start = 0;
        int end = nums.length -1;
        while (start < end) {
            int middle = start + (end - start) / 2;
            if (nums[middle] == target) return middle;
            
            if (nums[middle] < nums[end]) { //6780 1 2345
                if (target > nums[middle] && target <= nums[end]) {
                    start = middle + 1;
                } else {
                    end = middle - 1;
                }
            } else { // 2345601
                if (target < nums[middle] && target >= nums[start]) {
                    end = middle - 1;
                } else {
                    start = middle + 1;
                }
            }
        }
        return (nums[start] == target) ? start : -1;
    }
}
```

### <a name="277"></a>277. Find the Celebrity
```java
/* The knows API is defined in the parent class Relation.
      boolean knows(int a, int b); */
/*
each time we call knows(a, b), we will know at least one fact, so for each call, a possible person will be left
1.if a knows b, a is not possible to be the celebrity
2.if a don't know b, b is not possible to be the celebrity
*/

// O(n)
public class Solution extends Relation { // a b c d e f
    public int findCelebrity(int n) {
        if (n <= 0) return -1;
        if (n == 0) return 0;
        
        int candidate = 0;
        for (int i = 1; i < n; i ++) {
            if (knows(candidate, i)) {
                candidate = i;
            }
        }
        
        for (int i = 0; i < n; i ++) {
            if (candidate == i) continue;
            if (knows(candidate, i) || !knows(i, candidate)) return -1;
        }
        return candidate;
    }
}
```

### <a name="670"></a>670. Maximum Swap
```java
/*
Input: 2736
Output: 7236
*/
class Solution {
    public int maximumSwap(int num) {
        if (num == 0) return 0;
        char[] digitCharArray = String.valueOf(num).toCharArray();
        
        int[] digitIndex = new int [10];
        for (int i = 0; i < digitCharArray.length; i ++) {
            digitIndex[digitCharArray[i] - '0'] = i;
        }
        
        for (int i = 0; i < digitCharArray.length; i ++) {
            for (int k = 9; k > digitCharArray[i] - '0'; k --) {
                if (digitIndex[k] > i) {
                    char tmp = digitCharArray[i];
                    digitCharArray[i] = digitCharArray[digitIndex[k]];
                    digitCharArray[digitIndex[k]] = tmp;
                    return Integer.valueOf(new String(digitCharArray));
                }
            }
        }
        return num;
    }
}
```

### <a name="252"></a>252. Meeting Rooms
```java
/**
 * Definition for an interval.
 * public class Interval {
 *     int start;
 *     int end;
 *     Interval() { start = 0; end = 0; }
 *     Interval(int s, int e) { start = s; end = e; }
 * }
 */
class Solution {
    public boolean canAttendMeetings(Interval[] intervals) {
        Arrays.sort(intervals, (i1, i2) -> Integer.compare(i1.start, i2.start));
        for (int i = 1; i < intervals.length; i ++) {
            if (intervals[i - 1].end > intervals[i].start) {
                return false;
            }
        }
        return true;
    }
}
```

### <a name="56"></a>56. Merge Intervals
```java
/**
 * Definition for an interval.
 * public class Interval {
 *     int start;
 *     int end;
 *     Interval() { start = 0; end = 0; }
 *     Interval(int s, int e) { start = s; end = e; }
 * }
 */
// O(nlogn)
class Solution {
    public List<Interval> merge(List<Interval> intervals) {
        List<Interval> result = new ArrayList<>();
        if (intervals == null || intervals.size() == 0) {
            return result;
        }
        
        intervals.sort((a, b) -> Integer.compare(a.start, b.start));
        
        Interval pre = null;
        for (Interval thisInterval : intervals) {
            if (pre == null) {
                pre = thisInterval;
                continue;
            }
            if (pre.end >= thisInterval.start) {
                pre.end = Math.max(pre.end, thisInterval.end); // !!!!
            } else {
                result.add(pre);
                pre = thisInterval;
            }
        }
        result.add(pre);
        return result;
    }
}
// 返回总时间
// input is unsorted and has some overlapping intervals, output is the total non-overlapping time; O(nlogn) time, O(1) space
public class Solution {
    public int totalTime(List<Interval> intervals) {
        if (intervals == null || intervals.size() <= 1) {//size(), not length !!!
            return intervals;
        }
        Collections.sort(intervals, new Comparator<Interval>(){
            public int compare(Interval a, Interval b) {
                return a.start - b.start;
            }
        });
        //you can also merge intervals before calculating,which makes calculation easier,but takes some memory(new arraylist)
        int total = 0;
        Interval prev = new Interval(0, 0);
        for (Interval curr : intervals) {
            if (prev.end < curr.start) {
                total += curr.end - curr.start;//add the whole part(non-overlapping)
                prev = curr;
            } else if (curr.end > prev.end) {
                total += curr.end - prev.end;//only add the non overlapping part after prev.end
                prev = curr;
            }
            //else curr.end<=prev.end(curr inside prev),don't calculate anything,and prev isn't updated(prev.end is bigger)
        }
        return total;
    }
}
```

### <a name="207"></a>207. Course Schedule
```java
Kahn's algorithm
L ← Empty list that will contain the sorted elements
S ← Set of all nodes with no incoming edge
while S is non-empty do
    remove a node n from S
    add n to tail of L
    for each node m with an edge e from n to m do
        remove edge e from the graph
        if m has no other incoming edges then
            insert m into S
if graph has edges then
    return error (graph has at least one cycle)
else 
    return L (a topologically sorted order)
```
```java
// BFS Topological sort
class Solution {
    public boolean canFinish(int numCourses, int[][] prerequisites) {
        if (numCourses == 0) return true;
        int[][] matrix = new int [numCourses][numCourses];
        int[] indegree = new int [numCourses];
        
        for (int i = 0; i < prerequisites.length; i ++) { //requiredCourse -> thisCourse
            int thisCourse = prerequisites[i][0];
            int requiredCourse = prerequisites[i][1];
            
            matrix[requiredCourse][thisCourse] = 1;
            indegree[thisCourse] += 1;
        }
        
        Queue<Integer> q = new LinkedList<>();
        for (int i = 0; i < indegree.length; i ++) {
            if (indegree[i] == 0) {
                q.offer(i);
            }
        }
        
        int count = 0;
        while (!q.isEmpty()) {
            Integer thisCourse = q.poll();
            count ++;
            for (int i = 0; i < numCourses; i ++) {
                if (matrix[thisCourse][i] == 1) {
                    matrix[thisCourse][i] = 0;
                    if (--indegree[i] == 0) {
                        q.offer(i);
                    }
                }
            }
        }
        
        return count == numCourses;
    }
}
```

### <a name="210"></a>210. Course Schedule II
```java
public int[] findOrder(int numCourses, int[][] prerequisites) { 
    if (numCourses == 0) return null;
    // Convert graph presentation from edges to indegree of adjacent list.
    int indegree[] = new int[numCourses], order[] = new int[numCourses], index = 0;
    for (int i = 0; i < prerequisites.length; i++) // Indegree - how many prerequisites are needed.
        indegree[prerequisites[i][0]]++;    

    Queue<Integer> queue = new LinkedList<Integer>();
    for (int i = 0; i < numCourses; i++) 
        if (indegree[i] == 0) {
            // Add the course to the order because it has no prerequisites.
            order[index++] = i;
            queue.offer(i);
        }

    // How many courses don't need prerequisites. 
    while (!queue.isEmpty()) {
        int prerequisite = queue.poll(); // Already finished this prerequisite course.
        for (int i = 0; i < prerequisites.length; i++)  {
            if (prerequisites[i][1] == prerequisite) {
                indegree[prerequisites[i][0]]--; 
                if (indegree[prerequisites[i][0]] == 0) {
                    // If indegree is zero, then add the course to the order.
                    order[index++] = prerequisites[i][0];
                    queue.offer(prerequisites[i][0]);
                }
            } 
        }
    }

    return (index == numCourses) ? order : new int[0];
}
```

### <a name="253"></a>253. Meeting Rooms II
```java
/**
 * Definition for an interval.
 * public class Interval {
 *     int start;
 *     int end;
 *     Interval() { start = 0; end = 0; }
 *     Interval(int s, int e) { start = s; end = e; }
 * }
 */
 //1,最常见两种解法 O(nlogn) time, O(n) space
class Solution {
    public int minMeetingRooms(Interval[] intervals) {
        if (intervals == null || intervals.length == 0) return 0;
        Arrays.sort(intervals, (a, b) -> Integer.compare(a.start, b.start));
        
        PriorityQueue<Interval> pq = new PriorityQueue<>(intervals.length, (a, b) -> Integer.compare(a.end, b.end));
        pq.offer(intervals[0]);
        
        for (int i = 1; i < intervals.length; i ++) {
            Interval endFirst = pq.poll(); // get the meeting room that finishes earliest
            if (endFirst.end <= intervals[i].start) {
                // if the current meeting starts right after 
                // there's no need for a new room, merge the interval
                endFirst.end = intervals[i].end;
            } else {
                // otherwise, this meeting needs a new room
                pq.offer(intervals[i]);
            }
            
            // don't forget to put the meeting room back
            pq.offer(endFirst);
        }
        
        return pq.size();
    }
}

public class Solution {
    public int minMeetingRooms(Interval[] intervals) {
        int[] starts=new int[intervals.length];
        int[] ends=new int[intervals.length];
        for(int i=0;i<intervals.length;i++){
            starts[i]=intervals[i].start;
            ends[i]=intervals[i].end;
        }
        Arrays.sort(starts);
        Arrays.sort(ends);
        int room=0,endsIt=0;
        for(int i=0;i<intervals.length;i++){
            if(starts[i]<ends[endsIt]){
                room++;
            }else endsIt++;
        }
        return room;
    }
}
```

### <a name="621"></a>621. Task Scheduler
```java
class Solution {
    public int leastInterval(char[] tasks, int n) {
        if (tasks == null || tasks.length == 0) return 0;
        if (n < 1) return tasks.length;
        
        PriorityQueue<Integer> pq = new PriorityQueue<>((a, b) -> b - a);
        int[] jobCount = new int[26];
        for (char c : tasks) {
            jobCount[c - 'A'] += 1;
        }
        
        for (int count : jobCount) {
            if (count == 0) continue;
            pq.offer(count);
        }
        
        int timeCount = 0;
        while (!pq.isEmpty()) {
            int k = n + 1;
            List<Integer> assignedWork = new ArrayList<>();
            while (k > 0 && !pq.isEmpty()) {
                Integer task = pq.poll(); // most frequency task
                assignedWork.add(task - 1); // decrease frequency, meaning it got executed
                k --;
                timeCount ++; //successfully executed task
            }
            
            for (Integer task : assignedWork) {
                if (task != 0) {
                    pq.offer(task); // add unfinished tasks 
                }
            }
            
            if (pq.isEmpty()) break;
            timeCount = timeCount + k; // if k > 0, then it means we need to be idle
        }
        return timeCount;
    }
}
```

### <a name="554"></a>554. Brick Wall
```java
class Solution {
    public int leastBricks(List<List<Integer>> wall) {
        if (wall == null) return 0;
        Map<Integer, Integer> hm = new HashMap<>();
        int max = 0;
        for (List<Integer> level : wall) {
            int lengthSum = 0;
            for (int i = 0; i < level.size() - 1; i ++) {
                lengthSum += level.get(i);
                hm.put(lengthSum, hm.getOrDefault(lengthSum, 0) + 1);
                max = Math.max(max, hm.get(lengthSum));
            }
        }
        return wall.size() - max;
    }
}
```

### <a name="1"></a>1. Two Sum
```java

// no duplicates
class Solution {
    public int[] twoSum(int[] nums, int target) {
        if (nums == null || nums.length < 2) return new int [] {-1, -1};
        Map<Integer, Integer> hm = new HashMap<>();
        
        for (int i = 0; i < nums.length; i ++) {
            int remain = target - nums[i];
            if (hm.containsKey(remain)) {
                return new int[] {i, hm.get(remain)};
            } else {
                hm.put(nums[i], i);
            }
        }
        return new int[] {-1, -1};
    }
}

// duplicates, O(n^2)
//two sum with duplicate numberO(n^2)
public ArrayList<int[]> findNumbersThatSumToTarget(int[] arr, int target) {
    Map<Integer, Set<Integer>> map = new HashMap<Integer, Set<Integer>>();
    List<int[]> res = new ArrayList<int[]>();
    for(int i=0; i<arr.length; i++){
            if(!map.containsKey(arr)){
                    Set<Integer> set = new HashSet<Integer>();
                    set.add(i);
                    map.put(arr, set);
            }else{
                    map.get(arr).add(i);
            }

            if(map.containsKey(target-arr)){-google 1point3acres
                    for(Integer j: map.get(target-arr)){
                            if(j!=i){
                                    int[] item = new int[2];
                                    item.add(i);
                                    item.add(j);
                                    res.add(item);
                            }
                    }
            }
    }
}

```

### <a name="167"></a>167. Two Sum II - Input array is sorted
```java
class Solution {
    public int[] twoSum(int[] nums, int target) {
        if (nums == null || nums.length < 2) return new int [] {-1, -1};
        
        int i = 0;
        int j = nums.length - 1;
        while (i < j) {
            int sum = nums[i] + nums[j];
            if (sum == target) {
                return new int [] {i + 1, j + 1};
            }
            if (sum < target) {
                i ++;
            } else {
                j --;
            }
        }
        return new int[] {-1, -1};
    }
}
```

### <a name="314"></a>314. Binary Tree Vertical Order Traversal
```java
// O(n)
/**
 * Definition for a binary tree node.
 * public class TreeNode {
 *     int val;
 *     TreeNode left;
 *     TreeNode right;
 *     TreeNode(int x) { val = x; }
 * }
 */
class Solution {
    public List<List<Integer>> verticalOrder(TreeNode root) {
        List<List<Integer>> result = new ArrayList<>();
        if (root == null) {return result;}
        
        Queue<TreeNode> nodeQueue = new LinkedList<>();
        Queue<Integer> positionQueue = new LinkedList<>();
        Map<Integer, List<Integer>> hm = new HashMap<>();
        int min = 0;
        int max = 0;
        
        nodeQueue.offer(root);
        positionQueue.offer(0);
        
        while (!nodeQueue.isEmpty()) {
            TreeNode node = nodeQueue.poll();
            Integer position = positionQueue.poll();
            
            if (!hm.containsKey(position)) {
                hm.put(position, new ArrayList<Integer>());
            }
            hm.get(position).add(node.val);
            
            if (node.left != null) {
                nodeQueue.offer(node.left);
                positionQueue.offer(position - 1);
                min = Math.min(min, position - 1);
            }
            
            if (node.right != null) {
                nodeQueue.offer(node.right);
                positionQueue.offer(position + 1);
                max = Math.max(max, position + 1);
            }
        }
        
        while (min <= max) {
            result.add(hm.get(min++));
        }
        
        return result;
    }
}
```

### <a name="311"></a>311. Sparse Matrix Multiplication
```java
class Solution {
    public int[][] multiply(int[][] A, int[][] B) {
        if (A == null || B == null || A.length == 0 || B.length == 0) return new int[0][0];
        int[][] result = new int [A.length][B[0].length];
        
        for (int i = 0; i < A.length; i ++) {
            for (int j = 0; j < A[0].length; j ++) {
                if (A[i][j] == 0) {
                    continue;
                }
                for (int k = 0; k < B[0].length; k ++) {
                    result[i][k] += A[i][j] * B[j][k];
                }
            }
        }
        return result;
    }
}

// advanced
/*
A sparse matrix can be represented as a sequence of rows, each of which is a sequence of (column-number, value) pairs of the nonzero values in the row.
So let's create a non-zero array for A, and do multiplication on B.
*/

public int[][] multiply(int[][] A, int[][] B) {
    int m = A.length, n = A[0].length, nB = B[0].length;
    int[][] result = new int[m][nB];

    List[] indexA = new List[m];
    for(int i = 0; i < m; i++) {
        List<Integer> numsA = new ArrayList<>();
        for(int j = 0; j < n; j++) {
            if(A[i][j] != 0){
                numsA.add(j); 
                numsA.add(A[i][j]);
            }
        }
        indexA[i] = numsA;
    }

    for(int i = 0; i < m; i++) {
        List<Integer> numsA = indexA[i];
        for(int p = 0; p < numsA.size() - 1; p += 2) {
            int colA = numsA.get(p);
            int valA = numsA.get(p + 1);
            for(int j = 0; j < nB; j ++) {
                int valB = B[colA][j];
                result[i][j] += valA * valB;
            }
        }
    }

    return result;   
}

// Sparce, long and short
class Tuple{
        int val,x;
        Tuple(int val,int x){
            this.val=val;
            this.x=x;
        }
    }
public int dotProduct(int[] a, int[] b){
        int len = a.length;
        int res = 0;
        for( int i = 0 ; i < len ; i++){
            res += a[i] * b[i];
        }
        return res;
    }
// O(m*n)
public int SparseVectorProduct(int[] a,int[] b){
            int res=0;
            List<Tuple> l1=new ArrayList<>();
            List<Tuple> l2=new ArrayList<>();
            for(int i=0;i<a.length;i++){
                if(a[i]!=0) l1.add(new Tuple(a[i],i));
            }
            for(int i=0;i<b.length;i++){
                if(b[i]!=0) l2.add(new Tuple(b[i],i));
            }
            for(Tuple t1:l1){
                for(Tuple t2:l2){
                    if(t1.x==t2.x) res+=t1.val*t2.val;
                }
            }
            return res;
        }

// 这个是O（m+n） sparce
int i=0,j=0;
while(i<l1.size()&&j<l2.size()){
    while(l1.get(i).x<l2.get(j).x) i++;
    if(l1.get(i).x==l2.get(j).x){
        res+=l1.get(i).val*l2.get(j).val;
        i++;j++;
    }
    while(l1.get(i).x>l2.get(j).x) j++;
}

//O(n*logm) long and short
int i=0,j=l2.size()-1;
for(Tuple t1:l1){//短的那个
    while(i<=j){
        int mid=(j-i)/2+i;
        if(l2.get(mid).x==t1.x) res+=t1.val*l2.get(mid).val;
        if(l2.get(mid)<t1.x) j=mid;
        else i=mid+1;
    }
}

```

### <a name="325"></a>325. Maximum Size Subarray Sum Equals k
```java
// O(n)
class Solution {
    public int maxSubArrayLen(int[] nums, int k) {
        if (nums == null || nums.length == 0) return 0;
        HashMap<Integer, Integer> hm = new HashMap<>();
        int sum = 0;
        int maxLength = 0;
        
        for (int i = 0; i < nums.length; i ++) {
            sum += nums[i];
            if (!hm.containsKey(sum)) {
                hm.put(sum, i);
            }
            if (sum == k) maxLength = i + 1;
            else if (hm.containsKey(sum - k)) {
                maxLength = Math.max(maxLength, i - hm.get(sum - k));
            }
        }
        return maxLength;
    }
}
```

### <a name="49"></a>49. Group Anagrams
```java
// naive solution
// hash+sort solution: O(mnlogn) time, O(m) space, m is the num of strs, n is the max length of strs
class Solution {
    public List<List<String>> groupAnagrams(String[] strs) {
        if (strs == null || strs.length == 0) return new ArrayList<List<String>>();
        
        HashMap<String, List<String>> hm = new HashMap<>();
        
        for (String str : strs) {
            char[] charArray = str.toCharArray();
            Arrays.sort(charArray); // O(nlogn)
            String key = String.valueOf(charArray);
            if (!hm.containsKey(key)) {
                hm.put(key, new ArrayList<>());
            }
            hm.get(key).add(str);
        }
        return new ArrayList<List<String>> (hm.values());
        
    }
}

// hash+counting sort: O(mn) time, O(m) space, m is the num of strs, n is the length of strs
public class Solution {
    public List<List<String>> groupAnagrams(String[] strs) {
        List<List<String>> res = new ArrayList<>();
        if (strs == null || strs.length == 0) return res;
        HashMap<String, ArrayList<String>> map = new HashMap<>();
        for (String s : strs) {
            int[] count = new int[26];//cuz inputs are lowercase letters, we only need 26
            for (int i = 0; i < s.length(); i++) {
                count[s.charAt(i) - 'a']++;//count the occurrences of each char
            }
            String anagram = "";//build a string key, eg."aabcccdd" -> 2a1b3c2d
            for (int i = 0; i < count.length; i++) {
                if (count[i] != 0) {//remember to add this !!! we only need chars that exist in the string !!! else get TLE!!!
                    anagram += String.valueOf(count[i]) + String.valueOf((char)('a' + i));//use (char)('a'+i) to build string!
                }
            }
            if (!map.containsKey(anagram)) {
                map.put(anagram, new ArrayList<>());
            }
            map.get(anagram).add(s);
        }
        for (Map.Entry<String, ArrayList<String>> entry : map.entrySet()) {//Map.Entry, not Map.entry !!!!!
            res.add(entry.getValue());
        }
        return res;
    }
}


```

### <a name="139"></a>139. Word Break
```java
// basic solution
/*
k = S.length(), n = dict.size().

The run time complexity for the first DP is k*n and the complexity for the second DP is k^2. The performance has nothing to do with how strings are generated. So I don't think it will matter whether the strings are randomly generated or not.
*/
public class Solution {
    public boolean wordBreak(String s, Set<String> dict) {
        
        boolean[] f = new boolean[s.length() + 1];
        
        f[0] = true;
        
        
        /* First DP
        for(int i = 1; i <= s.length(); i++){
            for(String str: dict){
                if(str.length() <= i){
                    if(f[i - str.length()]){
                        if(s.substring(i-str.length(), i).equals(str)){
                            f[i] = true;
                            break;
                        }
                    }
                }
            }
        }*/
        
        //Second DP
        for(int i=1; i <= s.length(); i++){
            for(int j=0; j < i; j++){
                if(f[j] && dict.contains(s.substring(j, i))){
                    f[i] = true;
                    break;
                }
            }
        }
        
        return f[s.length()];
    }
}

// O(K^2)   K = length of String
// naive solution
public class Solution {
    public boolean wordBreak(String s, Set<String> wordDict) {
        boolean[] res=new boolean[s.length()+1];
        res[0]=true;
        for(int i=1;i<=s.length();i++){
            for(int j=0;j<i;j++){
                if(res[j]&&wordDict.contains(s.substring(j,i))){
                    res[i]=true;
                    break;
                }
            }
        }
        return res[s.length()];
    }
}

// better solution
//O(lengthOfString * maxLength) time and O(lengthOfString) space
public class Solution {
    public boolean wordBreak(String s, Set<String> dict) {
        if (s == null || s.length() == 0) {
            return true;
        }
        int maxLength = getMaxLength(dict);
        boolean[] dp = new boolean[s.length() + 1];//dp[i]:whether 0 to i part of string can be segmented into words in dict
        dp[0] = true;
        for (int i = 1; i <= s.length(); i++) {//O(n) * O(maxLength)
            for (int lastWordLength = 1; lastWordLength <= maxLength && lastWordLength <= i; lastWordLength++) {//<= i !!!
                if (dp[i - lastWordLength] && dict.contains(s.substring(i - lastWordLength, i))) {//need add s.substring !!!
                    dp[i] = true;//if string from 0 to i-lastWordLength is segmentable, and i-lastWordLength to i is in dict
                    break;//eg. 0 L E E T C O D E -> L(F),i++ -> E(F),LE(F),i++ -> E(F),EE(F),LEE(F),i++ -> .....,LEET(T)
                }         //    T F F F T F F F T
            }
        }
        return dp[s.length()];
    }
    
    private int getMaxLength(Set<String> dict) {
        int max = 0;
        for (String s : dict) {
            max = Math.max(max, s.length());
        }
        return max;
    }
}
```

### <a name="158"></a>158. Read N Characters Given Read4 II - Call multiple times
```java
/* The read4 API is defined in the parent class Reader4.
      int read4(char[] buf); */
////readN函数会被call很多次，那就意味着，如果buffer里存的char上次并没有用完，下次call的时候必须先把buffer里的读完才可以开始读新的char
//use a queue to store readed characters, every time we needed number of character into the buf

public class Solution extends Reader4 {
    /**
     * @param buf Destination buffer
     * @param n   Maximum number of characters to read
     * @return    The number of characters read
     */
    
    public int read(char[] buf, int n) {
        int total = 0;
        Queue<Character> buff = new LinkedList<Character>();
        while(true){
            char[] temp = new char[4];
            int in = read4(temp);
            for(int i = 0; i < in; i++) buff.add(temp[i]);
            
            // 判断还需要写入多少个到结果， 比如读了4个，但是只要3个；或者要4个，只有3个了。
            in = Math.min(n - total, buff.size());
            
            for(int i = 0; i < in; i++) buf[total++] = buff.poll();
            if(in == 0) break;
        }
        return total;
    }
}
```

### <a name="157"></a>157. Read N Characters Given Read4
```java
/* The read4 API is defined in the parent class Reader4.
      int read4(char[] buf); */
/*
解题思路：
two situation:
n is the character that we want to read
1. source file length < n, we need to check if we have reach the end of file or not
2. source file length > n, we read 4 characters from file and store them into buf, we also need to check the number of characters we need to store into buf
for example: the file length is 200, and the total number of character we want is 5, so first time we read 4 characters, and still need 1 character,
so this time, even if we have read 4 characters from file, we need to get only 1 character, we handle this by compare the readed and needed.
*/
public class Solution extends Read4{
    public int read(chr[] buf, int n){
        //想要读n个字符，但是让我们读的源文件有好几种情况
        //1. 源文件的长度大于n,剩下的不读了
        //2. 源文件的长度小于n 有了r!=4的判断
        int readIndex = 0;
        char[] buffer4 = new char[4];//给read4一个buf，每次读取4个字符
        boolean eof = false;
        while(!eof && count < n){
        	int readed = read4(buffer4);
        	//读到文件尾了
        	if(readed != 4){
        		eof = true;
        	}
        	int toRead = Math.min(readed, n - count);//比如file是200，要求读5个，此时读取了第二个4，但只剩下了1个需要的，所以要取两者的最小
        	for(int i = 0; i < toRead; i++){
        		buf[count++] = buffer4[i];
        	}
        }
        return count;//actual number of character read
    }
}
```

### <a name="189"></a>189. Rotate Array
```java
// Pay attention to very big K value!!!
class Solution {
    public void rotate(int[] nums, int k) {
        while (k > nums.length) {
            k = k - nums.length;
        }
        reverse(nums, 0, nums.length - 1);
        reverse(nums, 0, k - 1);
        reverse(nums, k, nums.length - 1);
    }
    
    public void reverse(int[] nums, int start, int end) {
        while (start < end) {
            int tmp = nums[start];
            nums[start] = nums[end];
            nums[end] = tmp;
            
            start ++;
            end --;
        }
    }
}
```

### <a name="186"></a>186. Reverse Words in a String II
```java
class Solution {
    public void reverseWords(char[] str) {
        reverse(str, 0, str.length - 1);
        
        int i,j;
        for (i = 0, j = 0; i < str.length; i ++) {
            if (str[i] == ' ') {
                reverse(str, j, i - 1);
                j = i + 1;
            }
        }
        reverse(str, j, i - 1);
    }
    
    public void reverse(char[] str, int start, int end) {
        while (start < end) {
            char tmp = str[start];
            str[start] = str[end];
            str[end] = tmp;
            start ++;
            end --;
        }
    }
}
```

### <a name="151"></a>151. Reverse Words in a String
```java
public class Solution {
    public String reverseWords(String s) {
        char[] reversed = s.toCharArray();
        reverse(reversed, 0, s.length() - 1);
        
        int i, j;
        for (i = 0, j = 0; i < s.length(); i ++) {
            if (s.charAt(i) == ' ') {
                reverse(reversed, i, j - 1);
                i = j + 1;
            }
        }
        reverse(reversed, i, j);
        return cleanSpace(reversed);
    }
    
    public void reverse(char[] charArray, int start, int end) {
        while (start < end) {
            char tmp = charArray[start];
            charArray[start] = charArray[end];
            charArray[end] = tmp;
            start ++;
            end --;
        }
    }
    
    public String cleanSpace(char[] charArray) {
        int length = charArray.length;
        int i = 0;
        int j = 0;
        while (i < length) {
            while (i < length && charArray[i] == ' ') i ++;
            while (i < length && charArray[i] != ' ') charArray[j ++] = charArray[i ++];
            while (i < length && charArray[i] == ' ') i ++;
            if (i < length) charArray[j ++] = ' ';
        }
    }
}
```

### <a name="680"></a>680. Valid Palindrome II
```java
class Solution {
    public boolean validPalindrome(String s) {
        int start = 0;
        int end = s.length() - 1;
        while (start < end) {
            if (s.charAt(start) == s.charAt(end)) {
                start ++;
                end --;
            } else {
                return isPalindrome(s, start, end - 1) || isPalindrome(s, start + 1, end);
            }
        }
        return true;
    }
    
    public boolean isPalindrome(String s, int start, int end) {
        while (start < end) {
            if (s.charAt(start) == s.charAt(end)) {
                start ++;
                end --;
            }
            else {
                return false;
            }
        }
        return true;
    }
}
```

### <a name="125"></a>125. Valid Palindrome
```java
// O(n)
class Solution {
    public boolean isPalindrome(String s) {
        if (s == null) return true;
        int start = 0;
        int end = s.length() - 1;
        while (start < end) {
            while(start < end && !Character.isLetterOrDigit(s.charAt(start))) {
                start ++;
            }
            while(start < end && !Character.isLetterOrDigit(s.charAt(end))) {
                end --;
            }
            char c_1 = s.charAt(start++);
            char c_2 = s.charAt(end--);
            
            if (Character.toLowerCase(c_1) != Character.toLowerCase(c_2)) {
                    return false;
            }
        }
        return true;
    }
}
```

### <a name="20"></a>20. Valid Parentheses
```java
class Solution {
    public boolean isValid(String s) {
        if (s == null) return false;
        Stack<Character> stack = new Stack<>();
        for (char c : s.toCharArray()) {
            if (c == '(') {
                stack.push(')');
            } else if (c == '{') {
                stack.push('}');
            } else if (c == '[') {
                stack.push(']');
            } else {
                if (stack.isEmpty() || stack.pop() != c) {
                    return false;
                }
            }
        }
        return stack.isEmpty();
    }
}
```

### <a name="161"></a>161. One Edit Distance
```java
/*
 * There're 3 possibilities to satisfy one edit distance apart: 
 * 
 * 1) Replace 1 char:
      s: a B c
      t: a D c
 * 2) Delete 1 char from s: 
      s: a D  b c
      t: a    b c
 * 3) Delete 1 char from t
      s: a   b c
      t: a D b c
 */

class Solution {
    public boolean isOneEditDistance(String s, String t) {
        if (s == null || t == null || s.equals(t)) return false;
        if (Math.abs(s.length() - t.length()) >= 2) return false;
        
        String longerStr = (s.length() > t.length()) ? s : t;
        String shorterStr = (s.length() > t.length()) ? t : s;
        int longerLength = longerStr.length();
        int shorterLength = shorterStr.length();
        
        for (int i = 0; i < shorterStr.length(); i ++) {
            if (longerStr.charAt(i) != shorterStr.charAt(i)) {
                if (longerLength == shorterLength) {
                    return longerStr.substring(i + 1, longerLength).equals(shorterStr.substring(i + 1, shorterLength));
                } else {
                    return longerStr.substring(i + 1, longerLength).equals(shorterStr.substring(i, shorterLength));
                }
            }
        }
        return true;
    }
}
```

### <a name="67"></a>67. Add Binary
```java
// string做的时间复杂度是多少。我说n+(n-1)+...+1 = O(n^2)java string是immutable，所以需要更多时间复杂度
class Solution {
    public String addBinary(String a, String b) {
        if (a == null || b == null) return null;
        int i = a.length() - 1;
        int j = b.length() - 1;
        
        int carry = 0;
        StringBuilder sb = new StringBuilder();
        
        while (i >= 0 || j >= 0) {
            int sum = carry;
            if (j >= 0) sum += b.charAt(j--) - '0';
            if (i >= 0) sum += a.charAt(i--) - '0';
            sb.append(sum % 2);
            carry = sum / 2;
        }
        
        if (carry != 0) {
            sb.append(carry);
        }
        
        return sb.reverse().toString();
    }
}
```

### <a name="5"></a>5. Longest Palindromic Substring
```java
class Solution {
    private int low = 0;
    private int length = 0;
    
    public String longestPalindrome(String s) {
        if (s == null) return null;
        
        for (int i = 0; i < s.length(); i ++) {
            findPalindrome(s, i, i);
            findPalindrome(s, i, i + 1);
        }
        return s.substring(low, low + length);
    }
    
    public void findPalindrome(String s, int j, int k) {
        while(j >= 0 && k < s.length() && s.charAt(j) == s.charAt(k)) {
            j --;
            k ++;
        }
            
        if (k - j - 1 > length) {
            low = j + 1;
            length = k - j - 1;
        }
    } 
}
```

### <a name="232"></a>232. Implement Queue using Stacks
```java
class MyQueue {
    
    Stack<Integer> stack;
    /** Initialize your data structure here. */
    public MyQueue() {
        this.stack = new Stack<>();
    }
    
    /** Push element x to the back of queue. */
    public void push(int x) {
        Stack<Integer> tmp = new Stack<>();
        while (!stack.empty()) {
            tmp.push(stack.pop());
        }
        stack.push(x);
        while (!tmp.empty()) {
            stack.push(tmp.pop());
        }
    }
    
    /** Removes the element from in front of queue and returns that element. */
    public int pop() {
        return stack.pop();
    }
    
    /** Get the front element. */
    public int peek() {
        return stack.peek();
    }
    
    /** Returns whether the queue is empty. */
    public boolean empty() {
        return stack.empty();
    }
}

/**
 * Your MyQueue object will be instantiated and called as such:
 * MyQueue obj = new MyQueue();
 * obj.push(x);
 * int param_2 = obj.pop();
 * int param_3 = obj.peek();
 * boolean param_4 = obj.empty();
 */
```

### <a name="complete-binary-tree"></a>
```java
class Solution {
    /* This function counts the number of nodes in a binary tree */
    private int countNodes(TreeNode root) {
        if (root == null)
            return 0;
        return (1 + countNodes(root.left) + countNodes(root.right));
    }
     
    /* This function checks if the binary tree is complete or not */
    public boolean isComplete (TreeNode root, int index, int number_nodes) {
        // An empty tree is complete
        if (root == null)
            return true;
     
        // If index assigned to current node is more than
        // number of nodes in tree, then tree is not complete
        if (index >= number_nodes)
            return false;
     
        // Recur for left and right subtrees
        return (isComplete(root.left, 2*index + 1, number_nodes) &&
                isComplete(root.right, 2*index + 2, number_nodes));
    }

}
```

### <a name="222"></a>222. Count Complete Tree Nodes
```java
/**
 * Definition for a binary tree node.
 * public class TreeNode {
 *     int val;
 *     TreeNode left;
 *     TreeNode right;
 *     TreeNode(int x) { val = x; }
 * }
 */
class Solution {
    public int countNodes(TreeNode root) {
        int left = leftDepth(root);
        int right = rightDepth(root);
        
        if (left == right) {
            return (1 << left) - 1;
        } else {
            return countNodes(root.left) + countNodes(root.right) + 1;
        }
    }
    
    public int rightDepth(TreeNode node) {
        int depth = 0;
        while (node != null) {
            node = node.right;
            depth ++;
        }
        return depth;
    }
    
    public int leftDepth(TreeNode node) {
        int depth = 0;
        while (node != null) {
            node = node.left;
            depth ++;
        }
        return depth;
    }
}
```

### <a name="199"></a>199. Binary Tree Right Side View
```java
/**
 * Definition for a binary tree node.
 * public class TreeNode {
 *     int val;
 *     TreeNode left;
 *     TreeNode right;
 *     TreeNode(int x) { val = x; }
 * }
 */
class Solution {
    public List<Integer> rightSideView(TreeNode root) {
        List<Integer> result = new ArrayList<>();
        if (root == null) return result;
        
        Queue<TreeNode> queue = new LinkedList<>();
        queue.offer(root);
        
        while(!queue.isEmpty()) {
            int size = queue.size();
            for (int i = 0; i < size; i ++) {
                TreeNode node = queue.poll();
                if (i == 0) result.add(node.val);
                if (node.right != null) {
                    queue.offer(node.right);
                }
                if (node.left != null) {
                    queue.offer(node.left);
                }
            }
        }
        
        return result;
    }
}

// recursion

// The core idea of this algorithm:
// 1.Each depth of the tree only select one node.
// 2.View depth is current size of result list.

public class Solution {
    public List<Integer> rightSideView(TreeNode root) {
        List<Integer> result = new ArrayList<Integer>();
        rightView(root, result, 0);
        return result;
    }
    
    public void rightView(TreeNode curr, List<Integer> result, int currDepth){
        if(curr == null){
            return;
        }
        if(currDepth == result.size()){
            result.add(curr.val);
        }
        
        rightView(curr.right, result, currDepth + 1);
        rightView(curr.left, result, currDepth + 1);
        
    }
}
```






### <a name="117"></a>117. Populating Next Right Pointers in Each Node II
```java
/**
 * Definition for binary tree with next pointer.
 * public class TreeLinkNode {
 *     int val;
 *     TreeLinkNode left, right, next;
 *     TreeLinkNode(int x) { val = x; }
 * }
 */
public class Solution {
    public void connect(TreeLinkNode root) {
        TreeLinkNode levelHead = root;
        while(levelHead != null) {
            TreeLinkNode nextHead = null;
            TreeLinkNode pre = null;
            TreeLinkNode cur = levelHead;
            
            while (cur != null) {
                if (cur.left != null) {
                    if (nextHead == null) nextHead = cur.left;
                    if (pre != null) {
                        pre.next = cur.left;
                    }
                    pre = cur.left;
                }
                
                if (cur.right != null) {
                    if (nextHead == null) nextHead = cur.right;
                    if (pre != null) {
                        pre.next = cur.right;
                    }
                    pre = cur.right;
                }
                cur = cur.next;
            }
            levelHead = nextHead;
        }
    }
}
```

### <a name="116"></a>116. Populating Next Right Pointers in Each Node
```java
/**
 * Definition for binary tree with next pointer.
 * public class TreeLinkNode {
 *     int val;
 *     TreeLinkNode left, right, next;
 *     TreeLinkNode(int x) { val = x; }
 * }
 */
public class Solution {
    public void connect(TreeLinkNode root) {
        TreeLinkNode levelHead = root;
        while (levelHead != null) {
            TreeLinkNode cur = levelHead;
            while (cur != null) {
                if (cur.left != null) {
                    cur.left.next = cur.right;
                }
                if (cur.right != null && cur.next != null) {
                    cur.right.next = cur.next.left;
                }
                cur = cur.next;
            }
            levelHead = levelHead.left;
        }
    }
}
```

### <a name="236"></a>236. Lowest Common Ancestor of a Binary Tree
```java
/**
 * Definition for a binary tree node.
 * public class TreeNode {
 *     int val;
 *     TreeNode left;
 *     TreeNode right;
 *     TreeNode(int x) { val = x; }
 * }
 */
class Solution {
    public TreeNode lowestCommonAncestor(TreeNode root, TreeNode p, TreeNode q) {
        if (root == null || p == null || q == null) return null;
        if (root == p || root == q) return root;
        
        TreeNode L = lowestCommonAncestor(root.left, p, q);
        TreeNode R = lowestCommonAncestor(root.right, p, q);
        
        if (L != null && R != null) return root;
        return (L != null) ? L : R;
        
    }
}
```

### <a name="235"></a>235. Lowest Common Ancestor of a Binary Search Tree
```java
/**
 * Definition for a binary tree node.
 * public class TreeNode {
 *     int val;
 *     TreeNode left;
 *     TreeNode right;
 *     TreeNode(int x) { val = x; }
 * }
 */
class Solution {
    public TreeNode lowestCommonAncestor(TreeNode root, TreeNode p, TreeNode q) {
        if (root == null || p == null || q == null) return null;
        while ((root.val - p.val) * (root.val - q.val) > 0) {
            root = root.val > p.val ? root.left : root.right;
        }
        return root;
    }
}
```

### <a name="">543</a>543. Diameter of Binary Tree
```java
/**
 * Definition for a binary tree node.
 * public class TreeNode {
 *     int val;
 *     TreeNode left;
 *     TreeNode right;
 *     TreeNode(int x) { val = x; }
 * }
 */
class Solution {
    private int maxDiameter = 0;
    public int diameterOfBinaryTree(TreeNode root) {
        findDiameter(root);
        return maxDiameter;
    }
    
    public int findDiameter(TreeNode node) {
        if (node == null) return 0;
        int leftLength = findDiameter(node.left);
        int rightLength = findDiameter(node.right);
        
        maxDiameter = Math.max(maxDiameter, leftLength + rightLength);
        return Math.max(leftLength, rightLength) + 1;
    }
}
```

### <a name="653"></a>653. Two Sum IV - Input is a BST
```java
/**
 * Definition for a binary tree node.
 * public class TreeNode {
 *     int val;
 *     TreeNode left;
 *     TreeNode right;
 *     TreeNode(int x) { val = x; }
 * }
 */
class Solution {
    public boolean findTarget(TreeNode root, int k) {
        return dfs(root, root, k);
    }
    
    public boolean dfs(TreeNode root, TreeNode cur, int k) {
        if (cur == null) return false;
        return search(root, cur, k - cur.val) || dfs(root, cur.left, k) || dfs(root, cur.right, k);
    }
    
    public boolean search(TreeNode root, TreeNode cur, int value) {
        if (root == null) return false;
        if (root.val == value && root != cur) return true;
        if (root.val < value && search(root.right, cur, value)) return true;
        if (root.val > value && search(root.left, cur, value)) return true;
        return false;
    }
}
```

### <a name="285"></a>285. Inorder Successor in BST
```java
/**
 * Definition for a binary tree node.
 * public class TreeNode {
 *     int val;
 *     TreeNode left;
 *     TreeNode right;
 *     TreeNode(int x) { val = x; }
 * }
 */
class Solution {
    public TreeNode inorderSuccessor(TreeNode root, TreeNode p) {
        if (root == null || p == null) return null;

        TreeNode res = null;
        while (root != null) {
            if (p.val >= root.val) {
                root = root.right;
            } else {
                res = root;
                root = root.left;
            }
        }
        return res;
    }
}

// recursion
// successor
public TreeNode successor(TreeNode root, TreeNode p) {
  if (root == null)
    return null;

  if (root.val <= p.val) {
    return successor(root.right, p);
  } else {
    TreeNode left = successor(root.left, p);
    return (left != null) ? left : root;
  }
}

// preecessor
public TreeNode predecessor(TreeNode root, TreeNode p) {
  if (root == null)
    return null;

  if (root.val >= p.val) {
    return predecessor(root.left, p);
  } else {
    TreeNode right = predecessor(root.right, p);
    return (right != null) ? right : root;
  }
}
```

### <a name="144"></a>144. Binary Tree Preorder Traversal
```java
/**
 * Definition for a binary tree node.
 * public class TreeNode {
 *     int val;
 *     TreeNode left;
 *     TreeNode right;
 *     TreeNode(int x) { val = x; }
 * }
 */
class Solution {
    public List<Integer> preorderTraversal(TreeNode root) {
        List<Integer> result = new ArrayList<>();
        Stack<TreeNode> stack = new Stack<>();
        while (root != null || !stack.isEmpty()) {
            while (root != null) {
                result.add(root.val);
                stack.push(root);
                root = root.left;
            }
            root = stack.pop();
            root = root.right;
        }
        
        return result;
    }
}

// recursion
class Solution {
    public List<Integer> preorderTraversal(TreeNode root) {
        List<Integer> pre = new LinkedList<Integer>();
        preHelper(root,pre);
        return pre;
    }
    public void preHelper(TreeNode root, List<Integer> pre) {
        if(root==null) return;
        pre.add(root.val);
        preHelper(root.left,pre);
        preHelper(root.right,pre);
    }
}
```

### <a name="173"></a>173. Binary Search Tree Iterator
```java
/**
 * Definition for binary tree
 * public class TreeNode {
 *     int val;
 *     TreeNode left;
 *     TreeNode right;
 *     TreeNode(int x) { val = x; }
 * }
 */

public class BSTIterator {
    Stack<TreeNode> stack = new Stack<>();
    public BSTIterator(TreeNode root) {
        pushAllLeft(root);
    }

    public void pushAllLeft(TreeNode node) {
        while (node != null) {
            stack.push(node);
            node = node.left;
        }
    }
    /** @return whether we have a next smallest number */
    public boolean hasNext() {
        return !stack.isEmpty();
    }

    /** @return the next smallest number */
    public int next() {
        if (hasNext()) {
            TreeNode n = stack.pop();
            pushAllLeft(n.right);
            return n.val;
        }
        return 0;
    }
}

/**
 * Your BSTIterator will be called like this:
 * BSTIterator i = new BSTIterator(root);
 * while (i.hasNext()) v[f()] = i.next();
 */
```

### <a name="94"></a>94. Binary Tree Inorder Traversal
```java
/**
 * Definition for a binary tree node.
 * public class TreeNode {
 *     int val;
 *     TreeNode left;
 *     TreeNode right;
 *     TreeNode(int x) { val = x; }
 * }
 */

// Interative, in order
class Solution {
    public List<Integer> inorderTraversal(TreeNode root) {
        List<Integer> result = new LinkedList<>();
        if (root == null) return result;
        
        Stack<TreeNode> stack = new Stack<>();
        while (root != null || !stack.isEmpty()) {
            while (root != null) {
                stack.push(root);
                root = root.left;
            }
            root = stack.pop();
            result.add(root.val);
            root = root.right;
        }
        
        return result;
    }
}

// Recursion
public List<Integer> inorderTraversal(TreeNode root) {
    List<Integer> res = new ArrayList<>();
    // method 1: recursion

    helper(root, res);
    return res;

    //helper function for method 1
    private void helper(TreeNode root, List<Integer> res) {
        if (root != null) {
            if (root.left != null) {
                helper(root.left, res);
            }
            res.add(root.val);
            if (root.right != null) {
                helper(root.right, res);
           }
       }
   }

```

### <a name="98"></a>98. Validate Binary Search Tree
```java
/**
 * Definition for a binary tree node.
 * public class TreeNode {
 *     int val;
 *     TreeNode left;
 *     TreeNode right;
 *     TreeNode(int x) { val = x; }
 * }
 */

// Iterative, in order
// O(n)
class Solution {
    public boolean isValidBST(TreeNode root) {
        Stack<TreeNode> stack = new Stack<>();
        TreeNode pre = null;
        while(root != null || !stack.isEmpty()) {
            while(root != null) {
                stack.push(root);
                root = root.left;
            }
            root = stack.pop();
            if (pre != null && root.val <= pre.val) {
                return false;
            }
            pre = root;
            root = root.right;
        }
        return true;
    }
}

// Recursive
public class Solution {
    public boolean isValidBST(TreeNode root) {
        return isValidBST(root, Long.MIN_VALUE, Long.MAX_VALUE);
    }
    
    public boolean isValidBST(TreeNode root, long minVal, long maxVal) {
        if (root == null) return true;
        if (root.val >= maxVal || root.val <= minVal) return false;
        return isValidBST(root.left, minVal, root.val) && isValidBST(root.right, root.val, maxVal);
    }
}
```


### <a name="230"></a>230. Kth Smallest Element in a BST
```java
/**
 * Definition for a binary tree node.
 * public class TreeNode {
 *     int val;
 *     TreeNode left;
 *     TreeNode right;
 *     TreeNode(int x) { val = x; }
 * }
 */
// DFS O(n)
class Solution {
    public int kthSmallest(TreeNode root, int k) {
        if (root == null) return 0;
        
        Stack<TreeNode> stack = new Stack<>();
        while (root != null || !stack.isEmpty()) {
            while (root != null) {
                stack.push(root);
                root = root.left;
            }
            root = stack.pop();
            if (--k == 0) return root.val;
            root = root.right;
        }
        return -1;
    }
}
```

### <a name="133"></a> 133. Clone Graph
```java
/**
 * Definition for undirected graph.
 * class UndirectedGraphNode {
 *     int label;
 *     List<UndirectedGraphNode> neighbors;
 *     UndirectedGraphNode(int x) { label = x; neighbors = new ArrayList<UndirectedGraphNode>(); }
 * };
 */

//O(m+n) time: num of nodes + num of edges, O(m) space: num of nodes
// DFS  O(V+E)
public class Solution {
    Map<Integer, UndirectedGraphNode> hm;
    public UndirectedGraphNode cloneGraph(UndirectedGraphNode node) {
        hm = new HashMap<>();
        return cloneNode(node);
    }
    
    public UndirectedGraphNode cloneNode(UndirectedGraphNode node) {
        if (node == null) return null;
        if (hm.containsKey(node.label)) return hm.get(node.label);
        
        UndirectedGraphNode newNode = new UndirectedGraphNode(node.label);
        hm.put(newNode.label, newNode);
        
        for (UndirectedGraphNode neighbor : node.neighbors) {
            newNode.neighbors.add(cloneNode(neighbor));
        }
        return newNode;
    }
}

// BFS  O(V+E)
public class Solution {
    private Map<Integer, UndirectedGraphNode> hm;
    public UndirectedGraphNode cloneGraph(UndirectedGraphNode node) {
        if (node == null) return null;
        hm = new HashMap<>();
        
        UndirectedGraphNode newHead = new UndirectedGraphNode(node.label);
        hm.put(newHead.label, newHead); //hm will always save cloned node
        
        Queue<UndirectedGraphNode> queue = new LinkedList<>();
        queue.offer(node); //queue will always save node to be cloned
        
        //this is also at most O(m+n) time
        while(!queue.isEmpty()) {
            UndirectedGraphNode originalNode = queue.poll();
            for (UndirectedGraphNode neighbor : originalNode.neighbors) {
                if (!hm.containsKey(neighbor.label)) {
                    UndirectedGraphNode newNeighbor = new UndirectedGraphNode(neighbor.label);
                    hm.put(newNeighbor.label, newNeighbor);
                    queue.offer(neighbor);
                }
                hm.get(originalNode.label).neighbors.add(hm.get(neighbor.label));
            }
        }
        return newHead;
    }
}
```

### <a name="273"></a> 273. Integer to English Words
```java
// 273. Integer to English Words
class Solution {
    private final String[] LESS_THAN_20 = {"", "One", "Two", "Three", "Four", "Five", "Six", "Seven", "Eight", "Nine", "Ten", "Eleven", "Twelve", "Thirteen", "Fourteen", "Fifteen", "Sixteen", "Seventeen", "Eighteen", "Nineteen"};
    private final String[] TENS = {"", "Ten", "Twenty", "Thirty", "Forty", "Fifty", "Sixty", "Seventy", "Eighty", "Ninety"};
    private final String[] THOUSANDS = {"", "Thousand", "Million", "Billion"};
    
    public String numberToWords(int num) {
        if (num == 0) return "Zero";
        int i = 0;
        String result = "";
        while (num > 0) {
            if (num % 1000 != 0) {
                result = helper(num % 1000) + THOUSANDS[i] + " " + result;
            }
            i ++;
            num = num / 1000;
        }
        return result.trim();
    }
    
    public String helper(int num) {
        if (num == 0) {
            return "";
        }
        else if (num < 20) {
            return LESS_THAN_20[num] + " ";
        } else if (num < 100) {
            return TENS[num / 10] + " " + helper(num % 10);
        } else {
            return LESS_THAN_20[num / 100] + " Hundred " + helper(num % 100);
        }
    }
}

// negative input
public class Solution {
    private final String[] LESS_THAN_20 = new String[]{"", "One", "Two", "Three", "Four", "Five", "Six", "Seven", "Eight", "Nine", "Ten", "Eleven", "Twelve", "Thirteen", "Fourteen", "Fifteen", "Sixteen", "Seventeen", "Eighteen", "Nineteen"};
    private final String[] TENS = new String[]{"", "Ten", "Twenty", "Thirty", "Forty", "Fifty", "Sixty", "Seventy", "Eighty", "Ninety"};//the "TEN" in this array may not be used, but adding it here will be convienient for us to use the index
    private final String[] THOUSANDS = new String[]{"", "Thousand", "Million", "Billion"};
    
    public String numberToWords(int n) {
        long num = n;//avoid overflow of case MIN_VALUE to positive; you can also directly output a string without using long
        if (num == 0) {
            return "Zero";
        }
        int i = 0;//use i to record how many three digits have been counted.
        String res = "";
        if (num < 0) {
            res += "Negative ";
            num = -num;
        }
        while (num > 0) {//loops at most four times, cuz int has at most 10 digits
            if (num % 1000 != 0) {//if curr three digits are not all zero
                res = helper(num % 1000) + THOUSANDS[i] + " " + res;//each time we count three digits, remember to add " "!!!
            }//if curr three digits(can be 3,2,1 though) are all 0, we should skip curr three digits,add nothing to res
            num /= 1000;//delete three digits which has been counted on the right
            i++;//we increment i for each three digits
        }
        return res.trim();//The tail may still have a redundant " "
    }
    
    private String helper(long num) {
        if (num == 0) {//if the digits left are all zero, return ""
            return "";
        } else if (num < 20) {
            return LESS_THAN_20[num] + " ";//remember to add " " cuz after this may be followed by THOUSANDS[i]
        } else if (num < 100) {
            return TENS[num / 10] + " " + helper(num % 10);//TENS[num/10] + " " + (LESS_THAN_20[num%10] + " ",or ""(num == 0))
        } else {
            return LESS_THAN_20[num / 100] + " Hundred " + helper(num % 100);//remember to use LESS_THAN_20[num / 100] here
        }//LESS_THAN_20[num/100] + " Hundred " + (TENS[num/10] + " " + (LESS_THAN_20[num%10] + " ",or ""(num == 0)))
    }
}


```
### <a name="168"></a>168. Excel sheet column title
```java
/**
instead of 1-A, 26-Z
we can assume 0-A, 25-Z therefore come to the base 26 representation
and do n%26 operation to find which character it represent, update n by n/26, until the given n=0 we terminate.
for example, if we are given 76 --> BX
time:O(n), space:O(1)
 */
class Solution{
    public String convertToTitle(int n){
        StringBuilder sb = new StringBuilder();
        while(n > 0){
            n--;//75 // 2-1=1
            sb.insert(0, (char)('A' + n % 26));//('A' + 23) --> X // ('A' + 1) --> B
            n /= 26;//2 // 0
        }
        return sb.toString();
    }
}
```

### <a name="348"></a>348. Tic-Tac-Toe
```java
/*
test case:
input:
["TicTacToe","move","move","move","move","move","move","move"]
[[3],       [0,0,1],                     [0,2,2],[2,2,1],[1,1,2],[2,0,1],[1,0,2],[2,1,1]]
 3x3的grid, player1 makes move at (0,0)   player2 makes move at (0,2)
output:
[null,0,0,0,0,0,0,1]
*/
/*
解题思路：
use two arrays, one for row, one for column; and two integers one for diagnal, one for anti-diagnal, these four counters to represent the status of a player
add 1 if it is player1 move, add -1 if it is player2 move
when the any of the counter is n/-n, current player win otherwise return 0.
用两个数组和两个整数表示一个player目前达到的状态。 
这样空间复杂度就可以降低到O(n)，
而move的时间复杂度竟然可以降低到O(1)。
创建一个行数组一个列数组，一个对角线变量，一个反对角线变量，
每次若是玩家1操作则计数器加一，若玩家2则计数器减一，
当计数器为n或-n时操作玩家取得胜利
*/
class TicTacToe {
    /** Initialize your data structure here. */
    private int[] rows;
    private int[] cols;
    private int diag;
    private int antidiag;
    private int n;
    
    public TicTacToe(int n) {
        this.n = n;
        diag = 0;
        antidiag = 0;
        rows = new int[n];
        cols = new int[n];
    }
    
    /** Player {player} makes a move at ({row}, {col}).
        @param row The row of the board.
        @param col The column of the board.
        @param player The player, can be either 1 or 2.
        @return The current winning condition, can be either:
                0: No one wins.
                1: Player 1 wins.
                2: Player 2 wins. */
    public int move(int row, int col, int player) {
        int add = player == 1 ? 1 : -1;
        rows[row] += add;
        cols[col] += add;
        if(col == row){
            diag += add;
        }
        if(row + col == n - 1){
            antidiag += add;
        }
        return (Math.abs(rows[row]) == n || Math.abs(cols[col]) == n || Math.abs(diag) == n || Math.abs(antidiag) == n) ? player : 0;
    }
}

/**
 * Your TicTacToe object will be instantiated and called as such:
 * TicTacToe obj = new TicTacToe(n);
 * int param_1 = obj.move(row,col,player);
 */

```
