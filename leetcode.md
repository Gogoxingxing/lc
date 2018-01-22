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
- [418. Sentence Screen Fitting](#418) | [Leetcode](https://leetcode.com/problems/sentence-screen-fitting/description/)
```
Given a rows x cols screen and a sentence represented by a list of non-empty words, find how many times the given sentence can be fitted on the screen.

Note:

A word cannot be split into two lines.
The order of words in the sentence must remain unchanged.
Two consecutive words in a line must be separated by a single space.
Total words in the sentence won't exceed 100.
Length of each word is greater than 0 and won't exceed 10.
1 ≤ rows, cols ≤ 20,000.
Example 1:

Input:
rows = 2, cols = 8, sentence = ["hello", "world"]

Output: 
1

Explanation:
hello---
world---

The character '-' signifies an empty space on the screen.
Example 2:

Input:
rows = 3, cols = 6, sentence = ["a", "bcd", "e"]

Output: 
2

Explanation:
a-bcd- 
e-a---
bcd-e-

The character '-' signifies an empty space on the screen.
```

## DESIGN
- [MineSweeper](#1001)
```
Generate a game board for Minesweeper where
    SIZE is the width & height of the board (i.e., the board is SIZE x SIZE), and
    BOMB_COUNT is the number of mines/bombs that are randomly placed in the board

0 < SIZE
0 <= BOMB_COUNT <= SIZE * SIZE


Example I/O -- SIZE = 3 & BOMB_COUNT = 2

F F F
T F F
F F T
```
- [1006. reservior-sampling](#1006)
```

```
- [362. Design Hit Counter](#362) | [Leetcode](https://leetcode.com/problems/design-hit-counter/description/) 
```
Design a hit counter which counts the number of hits received in the past 5 minutes.

Each function accepts a timestamp parameter (in seconds granularity) and you may assume that calls are being made to the system in chronological order (ie, the timestamp is monotonically increasing). You may assume that the earliest timestamp starts at 1.

It is possible that several hits arrive roughly at the same time.

Example:
HitCounter counter = new HitCounter();

// hit at timestamp 1.
counter.hit(1);

// hit at timestamp 2.
counter.hit(2);

// hit at timestamp 3.
counter.hit(3);

// get hits at timestamp 4, should return 3.
counter.getHits(4);

// hit at timestamp 300.
counter.hit(300);

// get hits at timestamp 300, should return 4.
counter.getHits(300);

// get hits at timestamp 301, should return 3.
counter.getHits(301); 
```

- [251. Flatten 2D Vector](#251) | [Leetcode](https://leetcode.com/problems/flatten-2d-vector/description/) | [Discussion](https://leetcode.com/problems/flatten-2d-vector/discuss/67669)
```
Implement an iterator to flatten a 2d vector.

For example,
Given 2d vector =

[
  [1,2],
  [3],
  [4,5,6]
]
By calling next repeatedly until hasNext returns false, the order of elements returned by next should be: [1,2,3,4,5,6].
```

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

- [314. Binary Tree Vertical Order Traversal
](#314) | [Leetcode](https://leetcode.com/problems/binary-tree-vertical-order-traversal/description/)

- [Check complete binary tree](#complete-binary-tree) | [Solution](http://www.geeksforgeeks.org/check-whether-binary-tree-complete-not-set-2-recursive-solution/)

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
- [32. Longest Valid Parentheses](#32) | [Leetcode](https://leetcode.com/problems/longest-valid-parentheses/solution/)
```
Given a string containing just the characters '(' and ')', find the length of the longest valid (well-formed) parentheses substring.

For "(()", the longest valid parentheses substring is "()", which has length = 2.

Another example is ")()())", where the longest valid parentheses substring is "()()", which has length = 4.
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
- [15. Three Sum](#1) | [Leetcode](https://leetcode.com/problems/3sum/description/)
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


- [290. Word Pattern](#290) | [Leetcode](https://leetcode.com/problems/word-pattern/description/)
```
Given a pattern and a string str, find if str follows the same pattern.

Here follow means a full match, such that there is a bijection between a letter in pattern and a non-empty word in str.

Examples:
pattern = "abba", str = "dog cat cat dog" should return true.
pattern = "abba", str = "dog cat cat fish" should return false.
pattern = "aaaa", str = "dog cat cat dog" should return false.
pattern = "abba", str = "dog dog dog dog" should return false.
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

- [88. Merge Sorted Array](#88) | [Leetcode](https://leetcode.com/problems/merge-sorted-array/description/)
```
Given two sorted integer arrays nums1 and nums2, merge nums2 into nums1 as one sorted array.
```

- [28. Implement strStr()](#28) | [Leetcode](https://leetcode.com/problems/implement-strstr/description/)
```
Implement strStr().

Return the index of the first occurrence of needle in haystack, or -1 if needle is not part of haystack.

Example 1:

Input: haystack = "hello", needle = "ll"
Output: 2
Example 2:

Input: haystack = "aaaaa", needle = "bba"
Output: -1
```

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
- [332. Reconstruct Itinerary](#332) | [Leetcode](https://leetcode.com/problems/reconstruct-itinerary/discuss/78799)
```
Given a list of airline tickets represented by pairs of departure and arrival airports [from, to], reconstruct the itinerary in order. All of the tickets belong to a man who departs from JFK. Thus, the itinerary must begin with JFK.

Note:
If there are multiple valid itineraries, you should return the itinerary that has the smallest lexical order when read as a single string. For example, the itinerary ["JFK", "LGA"] has a smaller lexical order than ["JFK", "LGB"].
All airports are represented by three capital letters (IATA code).
You may assume all tickets form at least one valid itinerary.
Example 1:
tickets = [["MUC", "LHR"], ["JFK", "MUC"], ["SFO", "SJC"], ["LHR", "SFO"]]
Return ["JFK", "MUC", "LHR", "SFO", "SJC"].
Example 2:
tickets = [["JFK","SFO"],["JFK","ATL"],["SFO","ATL"],["ATL","JFK"],["ATL","SFO"]]
Return ["JFK","ATL","JFK","SFO","ATL","SFO"].
Another possible reconstruction is ["JFK","SFO","ATL","JFK","ATL","SFO"]. But it is larger in lexical order.
```

- [547. Friend Circles](#547) | [Leetcode](https://leetcode.com/problems/friend-circles/description/)
```
There are N students in a class. Some of them are friends, while some are not. Their friendship is transitive in nature. For example, if A is a direct friend of B, and B is a direct friend of C, then A is an indirect friend of C. And we defined a friend circle is a group of students who are direct or indirect friends.

Given a N*N matrix M representing the friend relationship between students in the class. If M[i][j] = 1, then the ith and jth students are direct friends with each other, otherwise not. And you have to output the total number of friend circles among all the students.

Example 1:
Input: 
[[1,1,0],
 [1,1,0],
 [0,0,1]]
Output: 2
Explanation:The 0th and 1st students are direct friends, so they are in a friend circle. 
The 2nd student himself is in a friend circle. So return 2.
```


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
- [1004. topological sorting](#1004)
```
5 4 2 3 1 0

5->0<-4
|      \
*       \>
2 -> 3 -> 1
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
- [300. Longest increasing Subsequence](#300) | [Leetcode](https://leetcode.com/problems/longest-increasing-subsequence/description/)
```
Given an unsorted array of integers, find the length of longest increasing subsequence.

For example,
Given [10, 9, 2, 5, 3, 7, 101, 18],
The longest increasing subsequence is [2, 3, 7, 101], therefore the length is 4. Note that there may be more than one LIS combination, it is only necessary for you to return the length.

Your algorithm should run in O(n2) complexity.

Follow up: Could you improve it to O(n log n) time complexity?
```

- [525. Continuous Array](#525) | [Leetcode](https://leetcode.com/problems/contiguous-array/description/)
```
Given a binary array, find the maximum length of a contiguous subarray with equal number of 0 and 1.

Example 1:
Input: [0,1]
Output: 2
Explanation: [0, 1] is the longest contiguous subarray with equal number of 0 and 1.
Example 2:
Input: [0,1,0]
Output: 2
Explanation: [0, 1] (or [1, 0]) is a longest contiguous subarray with equal number of 0 and 1.
```
- [674. Longest Continuous Increasing Subsequence](#674) | [Leetcode](https://leetcode.com/problems/longest-continuous-increasing-subsequence/description/)
```
Given an unsorted array of integers, find the length of longest continuous increasing subsequence (subarray).

Example 1:
Input: [1,3,5,4,7]
Output: 3
Explanation: The longest continuous increasing subsequence is [1,3,5], its length is 3. 
Even though [1,3,5,7] is also an increasing subsequence, it's not a continuous one where 5 and 7 are separated by 4. 
```

- [128. Longest Consecutive Sequence](#128) | [Leetcode](https://leetcode.com/problems/longest-consecutive-sequence/description/)
```
Given an unsorted array of integers, find the length of the longest consecutive elements sequence.

For example,
Given [100, 4, 200, 1, 3, 2],
The longest consecutive elements sequence is [1, 2, 3, 4]. Return its length: 4.

Your algorithm should run in O(n) complexity.
```

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
- [57. Insert Intervals](#57) | [Leetcode](https://leetcode.com/problems/merge-intervals/description/)
```
 Example 1:
 Given intervals [1,3],[6,9], insert and merge [2,5] in as [1,5],[6,9].
 Example 2:
 Given [1,2],[3,5],[6,7],[8,10],[12,16], insert and merge [4,9] in as [1,2],[3,10],[12,16].
 This is because the new interval [4,9] overlaps with [3,5],[6,7],[8,10].
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
- [72. Edit Distance](#72) | [Leetcode](https://leetcode.com/problems/edit-distance/description/)
```
Given two words word1 and word2, find the minimum number of steps required to convert word1 to word2. (each operation is counted as 1 step.)

You have the following 3 operations permitted on a word:

a) Insert a character
b) Delete a character
c) Replace a character
```

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
- [309. Best Time to Buy and Sell Stock with Cooldown](#309) | [Leetcode](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-with-cooldown/description/)
```
Say you have an array for which the ith element is the price of a given stock on day i.

Design an algorithm to find the maximum profit. You may complete as many transactions as you like (ie, buy one and sell one share of the stock multiple times) with the following restrictions:

You may not engage in multiple transactions at the same time (ie, you must sell the stock before you buy again).
After you sell your stock, you cannot buy stock on next day. (ie, cooldown 1 day)
Example:

prices = [1, 2, 3, 0, 2]
maxProfit = 3
transactions = [buy, sell, cooldown, buy, sell]
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
- [639. Decode ways II](#639) | [Leetcode](https://leetcode.com/problems/decode-ways-ii/description/)
[Solution](https://leetcode.com/problems/decode-ways-ii/solution/)
```
A message containing letters from A-Z is being encoded to numbers using the following mapping way:

'A' -> 1
'B' -> 2
...
'Z' -> 26
Beyond that, now the encoded string can also contain the character '*', which can be treated as one of the numbers from 1 to 9.

Given the encoded message containing digits and the character '*', return the total number of ways to decode it.

Also, since the answer may be very large, you should return the output mod 10^9 + 7.

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
- [1005. All combination / password](#1005)
```
"A17s" --> A17s, A17S, a17s, a17S
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
- [1002. Yelp-Movie](#1002)
```
/*
给定一组电影和他的开始时间，假设都是1小时，返回一个电影日程表（不会时间冲突）。
输入：
Movie("Shining", [14, 15, 16])
Movie("Baby driver", [14, 15])
Movie("Pulp fiction", [14, 15])
 */

```


- [93. Restore IP Addresses](#93) | [Leetcode](https://leetcode.com/problems/restore-ip-addresses/description/) [Discussion tricy solution](https://leetcode.com/problems/restore-ip-addresses/discuss/30949)
```
Given a string containing only digits, restore it by returning all possible valid IP address combinations.

For example:
Given "25525511135",

return ["255.255.11.135", "255.255.111.35"]. (Order does not matter)
```


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
- [77. Combinations](#77) | [Leetcode](https://leetcode.com/problems/combinations/description/)
```
Given two integers n and k, return all possible combinations of k numbers out of 1 ... n.

For example,
If n = 4 and k = 2, a solution is:

[
  [2,4],
  [3,4],
  [2,3],
  [1,2],
  [1,3],
  [1,4],
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
- [146. LRU Cache](#146) | [Leetcode](https://leetcode.com/problems/lru-cache/description/)
```
Design and implement a data structure for Least Recently Used (LRU) cache. It should support the following operations: get and put.

get(key) - Get the value (will always be positive) of the key if the key exists in the cache, otherwise return -1.
put(key, value) - Set or insert the value if the key is not already present. When the cache reached its capacity, it should invalidate the least recently used item before inserting a new item.

Follow up:
Could you do both operations in O(1) time complexity?

Example:

LRUCache cache = new LRUCache( 2 /* capacity */ );

cache.put(1, 1);
cache.put(2, 2);
cache.get(1);       // returns 1
cache.put(3, 3);    // evicts key 2
cache.get(2);       // returns -1 (not found)
cache.put(4, 4);    // evicts key 1
cache.get(1);       // returns -1 (not found)
cache.get(3);       // returns 3
cache.get(4);       // returns 4
```


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
解释：
use backtracking to solve this problem:
only add open or close when we know it will remain a valid sequence. 
We can do this by keeping track of the number of opening and closing bracket we have placed so far. 
We can start an opening bracket if we still have one (of n) left to place. 
And we can start a closing bracket if it would not exceed the number of opening brackets.
*/
// O(2^n)
class Solution {
    public List<String> generateParenthesis(int n) {
        List<String> res = new ArrayList<>();
        if(n <= 0){
            return res;
        }
        helper(new StringBuilder(), res, 0, 0, n);
        return res;
    }
    
    private void helper(StringBuilder s, List<String> res, int lp, int rp, int n){
        if(lp == n && rp == n){
            res.add(s.toString());
            return;
        }
        if(lp < n){
            s.append("(");
            helper(s, res, lp + 1, rp, n);
            s.setLength(s.length()-1);
        }
        if(rp < lp){
            s.append(")");
            helper(s, res, lp, rp + 1, n);
            s.setLength(s.length()-1);
        }
    }
}
```

### <a name="435"></a>435. Non-overlapping Intervals
```java
/*
解释：
sort by the (ascending) end time of interval and find the compatible intervals, 
then the incompatible intervals should be the total number minus the compatible numbers.

why sort by end? : 
e.g. [ [1,4], [2,3], [3,4] ], 
the interval with early start might be very long 
and incompatible with many intervals. 
But if we choose the interval that ends early, 
we’ll have more space left to accommodate more intervals. 

Sorting Interval.end in ascending order is O(nlogn), 
then traverse intervals array to get the maximum number of non-overlapping intervals is O(n). 
Total is O(nlogn).

例子：
Input: [ [1,2], [2,3], [3,4], [1,3] ]
Output: 1
Explanation: [1,3] can be removed and the rest of intervals are non-overlapping.
*/
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
    public int eraseOverlapIntervals(Interval[] intervals) {
        if(intervals == null || intervals.length == 0){
            return 0;
        }
        int count = 1;
        //sort intervas by end time
        Arrays.sort(intervals, new Comparator<Interval>(){
            public int compare(Interval a, Interval b) {
                return a.end - b.end;
            }
        });
        Interval last = intervals[0];
        for(int i = 1; i < intervals.length; i++){
            if(intervals[i].start >= last.end){
                count++;
                last = intervals[i];
            }
        }
        return intervals.length - count;
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
/*
Solution 1:
minHeap
define a new datastructure named tuple,
it include information like the row index, col index and value
Build a minHeap of elements from the first row.
Do the following operations k-1 times :
Every time when you poll out the root(Top Element in Heap), 
you need to know the row number and column number of that element(so we can create a tuple class here), 
replace that root with the next element from the same column.
time: O(nlogk)
*/
public class Solution {
    public int kthSmallest(int[][] matrix, int k) {
        int n = matrix.length;
        PriorityQueue<Tuple> pq = new PriorityQueue<Tuple>();
        for(int j = 0; j <= n-1; j++) pq.offer(new Tuple(0, j, matrix[0][j]));
        for(int i = 0; i < k-1; i++) {
            Tuple t = pq.poll();
            if(t.x == n-1) continue;
            pq.offer(new Tuple(t.x+1, t.y, matrix[t.x+1][t.y]));
        }
        return pq.poll().val;
    }
}

class Tuple implements Comparable<Tuple> {
    int x, y, val;
    public Tuple (int x, int y, int val) {
        this.x = x;
        this.y = y;
        this.val = val;
    }
    
    @Override
    public int compareTo (Tuple that) {
        return this.val - that.val;
    }
}
/*
Solution 2:
priorityQueue, maxHeap
*/
class Solution {
    public int kthSmallest(int[][] matrix, int k) {
        if(matrix == null || matrix[0].length == 0){
            return 0;
        }
        int row = matrix.length, col = matrix[0].length;
        PriorityQueue<Integer> pq = new PriorityQueue<>(k, new Comparator<Integer>(){
            public int compare(Integer a, Integer b){
                return b - a;
            }
        });
        for(int i = matrix.length - 1; i >= 0; i--){
            for(int j = matrix[0].length - 1; j >= 0; j--){
                if(pq.size() >= k){
                    pq.poll();
                }
                pq.offer(matrix[i][j]);
            }
        }
        return pq.poll();
    }
}
/*
basically, Binary Search can be conducted in a certain searching space, this space is from smallest number to the biggest number. because in this problem, array is sorted in two direction, therefore we cannot directly use index as the search space, so we have to do the BS in certain number range.
*/
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
解题思路：
We initialize another matrix (dp) with the same dimensions 
as the original one initialized with all 0’s.

dp(i,j) represents the side length of the maximum square 
whose bottom right corner is the cell with index (i,j) 
in the original matrix.

Starting from index (0,0), 
for every 1 found in the original matrix, 
we update the value of the current element as:
dp(i, j) = min(dp(i-1, j), dp(i - 1, j - 1), dp(i, j - 1)) + 1

0 1 1 1 0           0 1 1 1 0
1 1 1 1 0           1 1 2 2 0
0 1 1 1 1           0 1 2 3 1
0 1 1 1 1           0 1 2 3 2
0 0 1 1 1           0 0 1 2 3

We also remember the size of the largest square found so far. 
In this way, 
we traverse the original matrix once 
and find out the required maximum size. 
This gives the side length of the square (say maxsqlenmaxsqlen). 
The required result is the area maxsqlen^2.

time:O(mn), space:O(mn)
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
/*
[
  ['o','a','a','n'],
  ['e','t','a','e'],
  ['i','h','k','r'],
  ['i','f','l','v']
]
words = ["oath","pea","eat","rain"]

Solution 1 (backtracking):
解题思路：
For each word in the words list, 
we search it in the board, 
the searching process can using backtracking, 
the terminate condition is we have searched the last index of the word.
For example, here is the board, 
and I will use word “oath” to go through my solution. 
Find the first character ‘o’ in the board, 
and start from here, 
using Deep First Search searching the four position around the current position. 
If we find a match to the second character of the word,
we go to the next level. 
When we find the all word in the board, 
return true and add it to the result list. 
We use the same way to search the rest of word in the word list.

Time complexity:O(m * N^2 * 4^K), 4 to the power of k
m is the words.length, N^2 is the board size, k is the average length of word in the word list
First we have to find the first letter to start, which gives time O(N^2),then for each search step it has 2~4 neighbours to go, and it has k steps, where k is the length of the word to be searched.
*/
class Solution {
    public List<String> findWords(char[][] board, String[] words) {
        List<String> res = new ArrayList<>();
        int row = board.length;
        int col = board[0].length;
        for(String word : words){
            if(find(word, board)){
                if(!res.contains(word)){ //for test case: [["a"]] ["a","a"] return --> ["a"]
                    res.add(word);
                }
            }
        }
        return res;
    }
    
    public boolean find(String word, char[][] board){
        int row = board.length;
        int col = board[0].length;
        char[] wordChar = word.toCharArray();
        boolean[][] visited = new boolean[row][col];
        for(int i = 0; i < row; i++){
            for(int j = 0; j < col; j++){
                if(board[i][j] == wordChar[0]){
                    if(search(i, j, board, wordChar, visited, 0)){
                        return true;
                    }
                }
            }
        }
        return false;
    }
    
    public boolean search(int x, int y, char[][] board, char[] wordChar, boolean[][] visited, int start){
        if(start == wordChar.length) return true;
        if(x >= board.length || y >= board[0].length || x < 0 || y < 0 || wordChar[start] != board[x][y] || visited[x][y]){
            return false;
        }
        
        visited[x][y] = true;
        if(search(x + 1, y, board, wordChar, visited, start + 1) || search(x, y + 1, board, wordChar, visited, start + 1) || search(x - 1, y, board, wordChar, visited, start + 1) || search(x, y - 1, board, wordChar, visited, start + 1)){
            return true;
        }
        visited[x][y] = false;
        return false;
    } 
}

/* the best solution
we can use trie tree to solve this problem, 
if we solve it just by dfs, 
we need to do many duplicate findings during the process, 
and it is time consuming, 
so we insert every words in the words list to a trie tree 
to reduce the searching times of the same characters. 
And we also store the word itself at the leaf node. 
Base on the trie tree, 
we use the depth first search go through the board, 
if the word sequence is in the trietree, 
add it to the result list.
*/
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
```

### <a name="71"></a>71. Simplify Path
```java
//解题思路：data structure i will use is set and stack. 
//we split the path with / into subPath, 
//and the set we store the non-letter character: ".", ".." and "". 
//we check subPath and if it not in the set, we push them into stack as one of the path. 
//during this process, we also need to handle the ".." case, 
//when meet this, we have to pop the top element out.
//time: O(n)
class Solution {
    public String simplifyPath(String path) {
        if(path == null || path.length() == 0){
            return "";
        }
        Set<String> set = new HashSet<>(Arrays.asList(".","..",""));
        //set.add("."); set.add(".."); set.add("");存""因为有//的情况
        Stack<String> stack = new Stack<>();
        String[] subPaths = path.split("/");
        for(String dir : subPaths){
            if(dir.equals("..") && !stack.isEmpty()){
                stack.pop();
            }else if(!set.contains(dir)){
                stack.push(dir);
            }
        }
        List<String> list = new ArrayList(stack);
        return "/"+String.join("/", list);
    }
}
/*
String joinString1=String.join("-","welcome","to","javatpoint");  
System.out.println(joinString1);  

output:
welcome-to-javatpoint
*/

```

### <a name="14"></a>14. Longest Common Prefix
```java
/*
first set commonprefix as the first element, if the following strings do not have this commonprefix, we reduce the length of current commonprefix until we have a match.
*/
//O(S) , where S is the sum of all characters in all strings.
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
// use a hashmap to store relationship between characters, if there are two case which are conflictions and will return false:
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
/*
解题思路：
we go through the input string, and divide the string into two part at the operation index, then using recursion, find all possibilities and record the result.

for example: 2*2-1
1.
*: a = 2, b = 2-1 ----> 1
al = 2, bl = 1 ---> 2

2.
-:
a = 2*2, b = 1
al = 4, b = 1 ---> 3
*/
public class Solution {
    public List<Integer> diffWaysToCompute(String input) {
        List<Integer> res = new ArrayList<Integer>();
        for (int i = 0; i < input.length(); i++) {
            char c = input.charAt(i);
            if (c == '-' || c == '+' || c == '*') {
                String a = input.substring(0, i);
                String b = input.substring(i + 1);
                List<Integer> al = diffWaysToCompute(a);
                List<Integer> bl = diffWaysToCompute(b);
                for (int x : al) {
                    for (int y : bl) {
                        if (c == '-') {
                            res.add(x - y);
                        } else if (c == '+') {
                            res.add(x + y);
                        } else if (c == '*') {
                            res.add(x * y);
                        }
                    }
                }
            }
        }
        if (res.size() == 0) res.add(Integer.valueOf(input));
        return res;
    }
}
```

### <a name="140"></a>140. Word Break II
```java
/*
例子：
c   a   t   s   a   n   d   d   o   g
0   1   2   3   4   5   6   7   8   9

start: 0    map: empty       另一层dfs end:4  start:4.....
end: 1   (0,1)-->c 没有 end++
end: 2   (0,2)-->ca 没有 end++
end：3    (0,3)-->cat --> next dfs
          start: 3 map:empty    “sand dog”
          end: 4----直到7 --> dfs
                    start:7  map: empty      7“dog”
                    end:8 ----直到end=10  res有dog
                    


Time complexity is O(len(wordDict) ^ len(s / minWordLenInDict)), because there're len(wordDict) possibilities for each cut

brute force solution:
check every possible prefix of string in the dictionary of words, 
if it is found in the dictionary, let say it is s1, 
then the recursive function is called for the for the remaining portion of that string. 
if the remaining portion is a substring 
which can lead to the formation of a valid sentence as per the dictionary
this function returns the prefix s1 appended by the result of 
recursive call using the remaining portion of the string which is (s - s1). 
Otherwise, empty list is returned.

Time complexity : O(n^n). Consider the worst case where s=``aaaaaaa"s=‘‘aaaaaaa" and every prefix of ss is present in the dictionary of words, then the recursion tree can grow up to n^n.

Space complexity : O(n^3). In worst case the depth of recursion tree can go up to nn and nodes can contain nn strings each of length nn.
*/
public class Solution {
    public List<String> wordBreak(String s, Set<String> wordDict) {
        return word_Break(s, wordDict, 0);
    }
    public List<String> word_Break(String s, Set<String> wordDict, int start) {
        LinkedList<String> res = new LinkedList<>();
        if (start == s.length()) {
            res.add("");
        }
        for (int end = start + 1; end <= s.length(); end++) {
            if (wordDict.contains(s.substring(start, end))) {
                List<String> list = word_Break(s, wordDict, end);
                for (String l : list) {
                    res.add(s.substring(start, end) + (l.equals("") ? "" : " ") + l);
                }
            }
        }
        return res;
    }
}

/*
In the previous approach we can see that many subproblems were redundant, i.e we were calling the recursive function multiple times for the same substring appearing through multiple paths. To avoid this we can use memorization method, where we are making use of a hashmap to store the results in the form of a key:value pair. In this hashmap, the key used is the starting index of the string currently considered and the valuevalue contains all the sentences which can be formed using the substring from this starting index onwards. Thus, if we encounter the same starting index from different function calls, we can return the result directly from the hashmap rather than going for redundant function calls.

Time complexity : O(n^3). Size of recursion tree can go up to n^2. The creation of list takes n time.

Space complexity : O(n^3).The depth of the recursion tree can go up to nn and each activation record can contains a string list of size n.
*/

/*
test:
s = "catsanddog",
dict = ["cat", "cats", "and", "sand", "dog"].

A solution is ["cats and dog", "cat sand dog"].
*/

public class Solution{
    public List<String> wordBreak(String s, Set<String> wordDict){
        return word_Break(s, wordDict, 0);
    }
    Map<Integer, List<String>> map = new HashMap<>();

    public List<String> word_Break(String s, Set<String> wordDict, int start){
        if(map.containsKey(start)){
            return map.get(start);
        }
        List<String> res = new LinkedList<>();
        if(start == s.length()){
            res.add("");
        }
        for(int end = start + 1; end <= s.length(); end++){
            if(wordDict.contains(s.substring(start,end))){
                List<String> list = word_Break(s, wordDict, end);
                for(String l : list){
                    res.add(s.substring(start, end) + (l.equals("") ? "" : " ") + l);
                }
            }
        }
        map.put(start, res);
        return res;
    }
}

```

### <a name="318"></a>318. Maximum Product of Word Lengths
```java
/*
use a array to record bit value of every word in the words array, if one character is in the word, then we set it as 1. for example, for string "abcd",we should have bit value 00000000000..01111(only abcd this four character should be 1). And then go through every pair of two words, if the words don’t share common characters update the maxproduct when needed.

ok,int has 32bits,but lower case letters only has 26. we can use the lowest 26 bit of int indicates that the word has how many kinds of lower case letters.

The reason use 1<< is that let the value of 'a' to be 1?
Yes, otherwise, 'a' will be missed since 'a' - 'a' = 0.

*/
class Solution {
    public int maxProduct(String[] words) {
        if(words == null || words.length == 0){
            return 0;
        }
        int[] hasCharacter = new int[words.length];
        for(int i = 0; i < words.length; i++){
            String word = words[i];
            for(int j = 0; j < word.length(); j++){
                // | means or, when 0 | 1 = 1
                hasCharacter[i] = hasCharacter[i] | 1 << (word.charAt(j) - 'a');
            }
        }
        
        int max = 0;
        for(int i = 0; i < words.length; i++){
            String w1 = words[i];
            for(int j = i + 1; j < words.length; j++){
                String w2 = words[j];
                //use brackets to inclue the bit manipulation!
                //& means they do not have 1 at same position
                if((hasCharacter[i] & hasCharacter[j]) == 0 && (w1.length() * w2.length() > max)){
                    max = w1.length() * w2.length();
                }
            }
        }
        return max;
    }
}
```

### <a name="381"></a>381. Insert Delete GetRandom O(1) - Duplicates allowed
```java
/*
using arraylist to store insert value, 
hashmap to map element to index, 
because there maybe duplicates, 
therefore, the value of map should be a set
*/

class RandomizedCollection {
      /** Initialize your data structure here. */
    List<Integer> list;
	Map<Integer, Set<Integer>> map;
    //同一个数的index可能有多个，所以value改成set，存所有的index
    public RandomizedCollection() {
        map = new HashMap<Integer, Set<Integer>>();
        list = new ArrayList<Integer>();
    }

    /** Inserts a value to the collection. Returns true if the collection did not already contain the specified element. */
    public boolean insert(int val) {
        //判断在不在mapli，若不在里面
        //插入新的数
        boolean contain = map.containsKey(val);
        if(!contain){
            map.put(val, new HashSet<>());
        }
        //把当前list中的index给hashset
        map.get(val).add(list.size());
        list.add(val);
        return !contain;
    }

/*
list: 2,3,3,4  remove val = 3
map: 2:0
     3:1,2   index = 2
     4:3
    |||||||
    lastVal = 4
    变成    list：2，3，4
    2：0
    3：1
    4：3
  */  
    /** Removes a value from the collection. Returns true if the collection contained the specified element. */
    public boolean remove(int val) {
        //如果没有则返回false
        if(!map.containsKey(val)) return false;
        //若找到了，把index拿出来
        //因为是hashset，所以我们随机取出任何一个数
        int index = map.get(val).iterator().next();
        //把当前index的数删除
        map.get(val).remove(index);
        //若删除之后size为0，直接把这个value全部删除即可
        if(map.get(val).size() == 0){
            map.remove(val);
        }
        //把结尾的数取出来
        int lastVal = list.remove(list.size() - 1);
        //调换位置
        if(index != list.size()){
            list.set(index, lastVal);
            map.get(lastVal).remove(list.size());
            map.get(lastVal).add(index);
        }
        return true;
    }
    
   	Random r = new Random();
	public int getRandom() {
		return list.get(r.nextInt(list.size()));
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
/*
解释：
because need to do the operation in constant time, therefore, 
I will use a arraylist and hashmap to solve this problem. 
arraylist to record each value we do the insert operation. 
because the delete operation of hashmap is O(1) while arraylist is not constant time, therefore, 
inorder to make the delete is also constant time, 
we need to exchange the position of the number need to be deleted with the last number of list, 
then change the corresponding value in hashmap. 
therefore we only need to delete the last element of list.
*/
class RandomizedSet {
    private Random random;
    private Map<Integer, Integer> locationMap;
    //key:number we want to insert   
    //value: position in arraylist
    //used to build mapping between each number and it position in the arraylist

    private List<Integer> values;//store value
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
        //if it is not in the map, 
        //we insert it into the end of list, 
        //and build mapping relation
        locationMap.put(val, values.size());
        values.add(val);
        return true;
    }
    
    /** Removes a value from the set. Returns true if the set contained the specified element. */
    public boolean remove(int val) {
        if (!locationMap.containsKey(val)) {
            return false;
        }
        
        //将要删除的数字和数组的最后一个数字调换个位置，
        //然后修改对应的哈希表中的值，
        //这样我们只需要删除数组的最后一个元素即可，保证了常数时间内的删除。
        int index = locationMap.remove(val); 
        int replacedValue = values.remove(values.size() - 1);
        
        if (index != values.size()) {
            //means that the list still have value, 
            //so we need to update
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

*/
//建立邻居关系：使用hashMap，key是每个词，对于每个词 用26个字母一一替换，如果正好在wordList里，则加入map value neighborlist里
//利用bfs找到minLen，同时标记结点的depth
//再利用dfs从后往前找到所有的解，有标记且depth - 1（相邻）


class Solution {
    Map<String, List<String>> map = new HashMap<>();//use to store the relation
    Set<String> doneSet = new HashSet<>();//use to store the node that we have already process
    Map<String, Integer> deepsMap = new HashMap<>();//use to store the depth of node
    public List<List<String>> findLadders(String beginWord, String endWord, List<String> wordList) {
        buildMap(wordList, beginWord);
        int minLen = bfs(beginWord, endWord, wordList);
        doneSet.clear();
        LinkedList<String> curList = new LinkedList<>();
        List<List<String>> res = new LinkedList<>();
        curList.add(endWord);
        doneSet.add(endWord);
        dfs(curList, res, beginWord, minLen, 1);
        return res;
    }
    
    public void dfs(LinkedList<String> curList, List<List<String>> res, String target, int minLen, int curDeep){
        String curStr = curList.get(0);
        if(curList.size() > minLen) return;
        else if (curList.size() == minLen){
            if(curStr.equals(target))//is end word
                res.add(new ArrayList<>(curList));
        }else{
            // curStr = endWord "cog"
            //map.get("cog) -- "dog" "log"
            for(String str : map.get(curStr)){
                //剪枝：当前的邻居结点是有标记的并且标记是我们想要的标记，进行dfs
                if(!doneSet.contains(str) && deepsMap.containsKey(str) && deepsMap.get(str) + curDeep < minLen){
                    curList.addFirst(str);
                    doneSet.add(str);
                    dfs(curList, res, target, minLen, curDeep + 1);
                    //backtracking
                    doneSet.remove(str);
                    curList.removeFirst();
                }
            }
        }
    }
    //set map, for each word find its all neighbors
    public void buildMap(List<String> wordList, String beginWord){
        HashSet<String> wordSet = new HashSet<>();//to avoid duplicate word
        for(String str : wordList){
            wordSet.add(str);
        }
        wordSet.add(beginWord);
        for(String str : wordSet){
            map.put(str, new ArrayList<>());
            diff(str, wordSet);
        }
    } 
    //find everyword possible neighbor in the wordList
    public void diff(String s, HashSet<String> wordSet){
        for(int i = 0; i < s.length(); i++){
            StringBuilder sb = new StringBuilder(s);
            char cur = sb.charAt(i);
            for(char c = 'a'; c <= 'z'; c++){//替换字符
                if(cur != c){//当前的字符和替换字符不相等的时候再替换
                    sb.setCharAt(i, c);
                    if(wordSet.contains(sb.toString())){
                        map.get(s).add(sb.toString());
                    }
                }
            }
        }
    }
    //find the min path meanwhile mark depth of every node
    public int bfs(String beginWord, String endWord, List<String> wordList){
        if(beginWord.equals(endWord)) return 0;
        Queue<String> queue = new LinkedList<>();
        queue.offer(beginWord);
        doneSet.add(beginWord);
        deepsMap.put(beginWord, 0);
        int steps = 1;
        while(!queue.isEmpty()){
            int size = queue.size();
            for(int i = 0; i < size; i++){
                String cur = queue.poll();
                if(cur.equals(endWord)) return steps;
                if(map.containsKey(cur)){
                    List<String> nxtStrList = map.get(cur);
                    for(String nxtStr : nxtStrList){
                        if(!deepsMap.containsKey(nxtStr)){
                            queue.offer(nxtStr);
                            deepsMap.put(nxtStr, steps);
                        }
                    }
                }
            }
            steps++;
        }
        return 0;
    }
}

```

### <a name="127"></a>127. Word Ladder
```java
/*
解释：
build a map for words and words in list which has one different character with the current word.
then use BFS, start from the beginWord, find the minimum step that could reach the endWord.

time compelxity:O(|V|+|E|)
*/
class Solution {
    public int ladderLength(String beginWord, String endWord, List<String> wordList) {
        if(beginWord.equals(endWord)){
            return 0;
        }
        Map<String, List<String>> map = buildMap(beginWord, wordList);
        Set<String> set = new HashSet<>();
        Queue<String> queue = new LinkedList<>();
        set.add(beginWord);
        queue.offer(beginWord);
        int step = 1;
        while(!queue.isEmpty()){
            int size = queue.size();
            for(int i = 0; i < size; i++){
                String curWord = queue.poll();
                if(curWord.equals(endWord)){
                    return step;
                }
                for(String nextStr : map.get(curWord)){
                    if(!set.contains(nextStr)){
                        set.add(nextStr);
                        queue.offer(nextStr);
                    }
                }
            }
            step++;
        }
        return 0;
    }
    
    public Map buildMap(String beginWord, List<String> wordList){
        Map<String, List<String>> map = new HashMap<>();
        for(String str : wordList){
            List<String> list = new ArrayList<>();
            map.put(str, list);
            for(String nextStr : wordList){
                if(diff(str, nextStr) == 1){
                    map.get(str).add(nextStr);
                }
            }
        }
        
        if(!map.containsKey(beginWord)){
            List<String> list = new ArrayList<>();
            map.put(beginWord, list);
            for(String str : wordList){
                if(diff(beginWord, str) == 1){
                    map.get(beginWord).add(str);
                }
            }
        }
        return map;
    }
    
    public int diff(String str1, String str2){
        int count = 0;
        for(int i = 0; i < str1.length(); i++){
            if(str1.charAt(i) != str2.charAt(i)){
                count++;
            }
        }
        return count;
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
/*
find all combinations and compare with target,
if it is valid add to result list.
nums has size n
time: 2^n
*/
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
            //for example:
            /*
            1,2,2',3  t=7
            1(7) -> 2(6) -> 2'(4) -> 3(2)...
                         \  3(4)...
                 \2'(6) -> 3(4)...         
            duplicate therefore we use nums[i] == nums[i-1] to skip
            but donot want to skip 122'4, therefore we also need i>start
            current index not equals to current level first index
            */
            tempList.add(nums[i]);
            backtrack(list, tempList, nums, remain - nums[i], i + 1);
            tempList.remove(tempList.size() - 1); 
        }
    }
} 

```
### <a name="77"></a>77. Combinations
```java
//test n = 3, k = 2
//[1,2,3] -- [1,2][1,3][2,3]

class Solution {
    public List<List<Integer>> combine(int n, int k) {
        List<List<Integer>> res = new ArrayList<>();
        if(n == 0 || k == 0){
            return res;
        }
        List<Integer> tmpList = new ArrayList<>();
        backtracking(n, k, 1, tmpList, res);
        return res;
    }
    public void backtracking(int n, int k, int start, List<Integer> tmpList, List<List<Integer>> res){
        if(tmpList.size() == k){
            res.add(new ArrayList<>(tmpList));
            return;
        }
        for(int i = start; i <= n; i++){
            tmpList.add(i);//1 // 2 //3
            backtracking(n, k, i + 1, tmpList, res);//try 2 -- end remove 2 -- try 3 -- end remove 3 -- end remove 1 //try 3 -- end remove 2 // cannot enter for loop in next level just remove 3 end.
            tmpList.remove(tmpList.size() - 1);
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
//time:O(n)
//space: O(n)
class Solution {
    public int subarraySum(int[] nums, int k) {
        if(nums == null || nums.length == 0){
            return 0;
        }
        //map store the key---sum, value---total number of situations which works
        Map<Integer, Integer> map = new HashMap<>();
        map.put(0, 1);//with no numbers, we have one situation meets
        int sum = 0;
        int count = 0;
        for(int i = 0; i < nums.length; i++){
            sum += nums[i];
            //not from the begining, but from some position in this array to the index i, its sum equals k
            if(map.containsKey(sum - k)){
                count += map.get(sum - k);
            }
            if(!map.containsKey(sum)){
                map.put(sum, 1);
            }else{
                map.put(sum, map.get(sum) + 1);
            }
        }
        return count;
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
Here I use typical BFS method to handle a binary tree. 
I use string n to represent null values. 
The string of the binary tree in the example will be "1 2 3 n n 4 5 n n n n ".

When deserialize the string, 
I assign left and right child for each not-null node, and add the not-null children to the queue, waiting to be handled later.
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
/*
Sorted the given array, for each number in the array, set two pointers after the fixed number, one from the start and one from the end. Every calculation we compare with 0, if larger, we move the end pointer, otherwise move the start pointer until we find the sum of this two pointers equals to the opposite number. Also we need to pay attention to the duplicates situation. Handle it by compare whether the current number is the same with previous one. If yes, just skip it.
*/
class Solution {
    public List<List<Integer>> threeSum(int[] nums) {
        List<List<Integer>> res = new ArrayList<>();
        if(nums == null || nums.length == 0){
            return res;
        }
        Arrays.sort(nums);
        for(int i = 0; i < nums.length - 2; i++){
            if(i == 0 || nums[i] != nums[i - 1]){
                int nd = i + 1;
                int rd = nums.length - 1;
                while(nd < rd){
                    int sum = nums[i] + nums[nd] + nums[rd];
                    if(sum == 0){
                        res.add(Arrays.asList(nums[i], nums[nd], nums[rd]));
                        nd++;
                        rd--;
                        while(nd < rd && nums[nd] == nums[nd - 1]) nd++;
                        while(nd < rd && nums[rd] == nums[rd + 1]) rd--;
                    }else if(sum < 0){
                        nd++;
                    }else{
                        rd--;
                    }
                }
            }
        }
        return res;
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
//代码只需要返回最后有效数组的长度，有效长度之外的数字是什么无所谓，原先input里面的数字不一定要保持原来的相对顺序。
//1.不用保持非零元素的相对顺序
//2.不用把0移到右边
//思路：把右边的非0元素移动到左边的0元素位置。这样就可以minimize writes.
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
//思路：Move all the non-zero elements to the left side of the array and fill the rest of the array by zero.
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
/*
思路：we can use the two pointers approach. 
The left point will always mark the next available location for the non-zero element. 
The right pointer will traverse the array and switch the non-zero elements to the location pointed by the left pointer

num of operations: 2 * (num of non-zero), if there are lots of zeros in array, use this
good when： 000010002
bad when： 10202222022
*/
public class Solution {
    public void moveZeroes(int[] nums) {
        if (nums == null || nums.length == 0) {
            return;
        }
        for (int right = 0, left = 0; i < nums.length; right++) {
            if (nums[right] != 0) {
                int temp = nums[left];
                nums[left++] = nums[right];
                nums[right] = temp;
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
/*
use hashmap to record the character and its appear times, use left and right pointers, right used to move forward, update the map, if we find distinctNum > k , keep moving forward left and update the map until the distinctNum <= k. also update the maxLen value.
*/
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
/*
like a sliding window, use hashset to store the valid substring, two pointers, one use to add character to substring, other used to remove character in the set once there exist duplicate.
maintain a maxLen and update it everytime we add new character.
*/
class Solution {
    public int lengthOfLongestSubstring(String s) {
        int maxLen = 0;
        if(s == null || s.length() == 0){
            return maxLen;
        }
        int i = 0;
        int j = 0;
        Set<Character> set = new HashSet<>();
        while(j < s.length()){
            char cur = s.charAt(j);
            if(!set.contains(cur)){
                set.add(cur);
                j++;
                maxLen = Math.max(maxLen, set.size());
            }else{
                set.remove(s.charAt(i++));
            }
        }
        return maxLen;
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

 /*
 解题思路：Use a stack to store the nested integer from last to first. When call hasnext check if it is integer yes return no flatten it again.
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
/*
time:O(n), space:O(n)
解释：
use a set to solve this problem, we iterate over the array and insert each element into set. Before inserting it, we check whether it is already there. If it is, then we found our duplicate, so we return it.
*/
class Solution {
    public int findDuplicate(int[] nums) {
        Set<Integer> set = new HashSet<Integer>();
        for (int num : nums) {
            if (set.contains(num)) {
                return num;
            }
            set.add(num);
        }

        return -1;
    }
}

// linked list, time:O(n), space:O(1)
/*
index 0 1 2 3 4 5 6
value 1 4 6 6 6 2 3
*/
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
//every time get themiddle number count how many numbers are smaller than mid, count <= mid means the duplicate is on the right side, else is in the left side.
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
// use minHeap and map. 
// map, key is the number, value is frequency
// Put map entry into minHeap so we can always poll a number with minimum frequency
// O(nlogK) n is length of words
class Solution {
    public List<String> topKFrequent(String[] words, int k) {
        List<String> result = new ArrayList<>();
        Map<String, Integer> hm = new HashMap<>();
        for (String word : words) {
            hm.put(word, hm.getOrDefault(word, 0) + 1);
        }
        //if two words have same freq, I will follow the alphabetical order, and that comes first.
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
        //because we used minHeap, so if we want to output order from large to small, we need to reverse
        Collections.reverse(result);
        return result;
    }
}
```


### <a name="347"></a>347. Top K Frequent Elements
```java
// Bucket Sort O(n)
/*
build map to match the relation between element and frequency
then use an list array to store the element which has same frequency, and the index of this array
is the frequency.
and finally we just need to put first k elements from the array into result list
*/
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

// 解题思路：
// use minHeap and map. 
// map, key is the number, value is frequency
// Put map entry into maxHeap so we can always poll a number with largest frequency
// O(nlogk)
class Solution {
    public List<Integer> topKFrequent(int[] nums, int k) {
        List<Integer> res = new ArrayList<>();
        if(nums == null || nums.length == 0){
            return res;
        }
        Map<Integer, Integer> map = new HashMap<>();
        for(int n : nums){
            map.put(n, map.getOrDefault(n, 0) + 1);
        }
        
        PriorityQueue<Map.Entry<Integer, Integer>> pq = new PriorityQueue<>(k, new Comparator<Map.Entry<Integer, Integer>>(){
            public int compare(Map.Entry<Integer, Integer> a, Map.Entry<Integer, Integer> b){
                return a.getValue() - b.getValue();
            }
        });
        for(Map.Entry<Integer, Integer> entry : map.entrySet()){
            pq.offer(entry);
            if(pq.size() > k){
                pq.poll();
            }
        }
        while(!pq.isEmpty()){
            res.add(pq.poll().getKey());
        }
        Collections.reverse(res);
        return res;
    }
}

//time: O(n)
//space: O(n)
//use Map to record every numbers and their frequency and then use TreeMap<Integer, List> to store the frequency and numbers with that frequency
// use pollLastEntry to traverse from the tail of the treemap value list
//must use TreeMap<> ... = new TreeMap<>() to indicate since we need to use the pollLastEnry method
class Solution {
    public List<Integer> topKFrequent(int[] nums, int k) {
        List<Integer> res = new ArrayList<>();
        Map<Integer, Integer> map = new HashMap<>();
        for(int num : nums){
            if(map.containsKey(num)){
                map.put(num, map.get(num) + 1);
            }else{
                map.put(num, 1);
            }
        }
        TreeMap<Integer, List<Integer>> tm = new TreeMap<>();
        for(int key : map.keySet()){
            int freq = map.get(key);
            if(!tm.containsKey(freq)){
                tm.put(freq, new ArrayList<>());
            }
            tm.get(freq).add(key);
        }
        while(res.size() != k){
            Map.Entry<Integer, List<Integer>> entry = tm.pollLastEntry();
            res.addAll(entry.getValue());
        }
        return res;
    }
}
```
### <a name="155"></a>155. Min Stack
```java
/*
use stack to store elements, one int variable to keep min, when we offer a number <= min, we push min to the minstack then update the min; when we pop an element, if it == min, update the min to the first element in the stack.
*/
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
/*
解题思路：
We can traverse the board until we find the board value equals to the first character of the target word. Then we can apply a Depth First Search to the surrounding positions in order to find the rest of the characters.

test case:
[
  ['A','B','C','P'],
  ['G','F','C','S'],
  ['A','D','E','E']
]
if we want to find "SEE" true

*/
// ask whether allowed to edit board !!!!
// dfs backtracking solution: O(4^n) time, O(n) stack space, n is word.length

class Solution {
    int row;
    int col;
    boolean[][] visited;
    public boolean exist(char[][] board, String word) {
        if(board == null || board.length == 0){
            return false;
        }
        row = board.length;
        col = board[0].length;
        visited = new boolean[row][col];
        for(int i = 0; i < row; i++){
            for(int j = 0; j < col; j++){
                if(board[i][j] == word.charAt(0)){
                    if(check(board, word, i, j, 0)){
                        return true;
                    }
                }
            }
        }
        return false;
    }
    //word length:3
    //start:0
    //x:2
    //y:3

    public boolean check(char[][] board, String word, int x, int y, int start){
        if(word.length() == start){
            return true;
        }
        if(x >= row || x < 0 || y >= col || y < 0 || visited[x][y] || word.charAt(start) != board[x][y]){
            return false;
        }
        visited[x][y] = true;
        //not reach boundary   "E"                            not reach boundry "P"                      not reach boundary   "C"                       false
        if(check(board, word, x + 1, y, start + 1) || check(board, word, x - 1, y, start + 1) || check(board, word, x, y - 1, start + 1) || check(board, word, x, y + 1, start + 1)){
            return true;
        }
        visited[x][y] = false;
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
/*
Time: O(logn)
Use binary search, everytime check the mid is bad or not, if yes, update right, otherwise update left. Finally, the left should be the answer.
*/
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
            //两个数字相同
            //前一个数字在前一轮没被取到，但是后一个数字在这一轮被取到
            //会出现重复
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

null -> null -> null -> null / 3
             -> 2    -> 2 / 23
    ->  1    -> 1    -> 1 / 13
             -> 12   -> 12 / 123  


*/
class Solution {
    public List<List<Integer>> subsets(int[] nums) {
        List<List<Integer>> result = new ArrayList<>();
        search(result, new ArrayList<Integer>(), nums, 0);
        return result;
    }
    
    public void search(List<List<Integer>> list, List<Integer> tmpList, int[] nums, int index) {
        //templist is a parameter
        //forjava if this parameter is object, then it will pass the
        //reference of this object
        //if it is add(tmplist), which means add reference
        //but after the backtracking, templist life cycle ended
        //so it equals not adding anything
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
/*
再说这个：
we can use a pointer at (row, col) to the bottom left of the matrix,
then if the currently pointed value is larger than target 
we can move one row up; 
if it is smaller, we move one col right

先说这个：why this algorithm works?
because the rows are sorted from left-to-right, 
we know that every value to the right of the current value is larger.
Therefore, if the current value is already larger than target, 
we know that every value to its right will also be too large. 
Same for the columns, 
so this manner of search will always find target in the matrix (if it is present)

time:O(m+n): on every iteration (during which we do not return true) either row or col is is decremented/incremented exactly once. 
Because row can only be decremented mm times and col can only be incremented n times before causing the while loop to terminate, 
the loop cannot run for more than n+m iterations. 
Because all other work is constant, 
the overall time complexity is linear in the sum of the dimensions of the matrix.
space: O(1)
*/

class Solution {
    public boolean searchMatrix(int[][] matrix, int target) {
        if (matrix == null || matrix.length == 0 || matrix[0].length == 0) return false;
        // start our "pointer" in the bottom-left
        int row = matrix.length-1;
        int col = 0;

        while (row >= 0 && col < matrix[0].length) {
            if (matrix[row][col] > target) {
                row--;
            } else if (matrix[row][col] < target) {
                col++;
            } else { // found it
                return true;
            }
        }

        return false;
    }
}
```

### <a name="74"></a>74. Search a 2D Matrix
```java
/*
解题思路：
use binary search
Eliminating one row/one column at a time. 
start from top-rightmost element in matrix (matrix[0][n-1]) 
and remove row if target is greater than matrix[0][n-1] 
or remove column if target is lesser than matrix[0][n-1].
repeat step 1 until you find the element!

test case: target = 3
[
  [1,   3,  5,  7],
  [10, 11, 16, 20],
  [23, 30, 34, 50]
]
start at 7, p = 0, q = 3
target3 < 7, p = 0, q = 2
target3 < 5, p = 0, q = 1
target3 == 3
*/
public boolean searchMatrix(int[][] matrix, int target){
    if(matrix == null || matrix.length == 0) return false;
    int row = matrix.length, col = matrix[0].length;
    int p = 0, q = col - 1;
    while(p >= 0 && q >= 0 && p < row && q < col){
        if(target == matrix[p][q]) return true;
        else if(target > matrix[p][q]) p++;
        else q--;
    }
    return false;
}


/*
解释：
instead of treat it as a 2d matrix, 
we treat it just as a sorted list and then use binary search.
n * m matrix convert to an array => matrix[x][y] => a[x * m + y]
an array convert to n * m matrix => a[x] =>matrix[x / m][x % m];
*/
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
/*
time:O(n), space:O(n)
we can use dynamica programming to solve this problem, use a array to record the max value at each index. we initialize the array with the first number and set it as the max value. for the rest of the array, we check whether the current number could add to the current sum. We also need to update max value.  
*/
class Solution {
    public int maxSubArray(int[] nums) {
        if(nums == null || nums.length <= 1){
            return nums.length == 0 ? 0 : nums[0];
        }
        int[] dp = new int[nums.length];
        dp[0] = nums[0];
        int max = dp[0];
        for(int i = 1; i < nums.length; i++){
            dp[i] = nums[i] + (dp[i - 1] > 0 ? dp[i - 1] : 0);
            max = Math.max(max, dp[i]);
        }
        return max;
    }
}

// without DP
//from the dp solution, we notice that we just use the previous one sum, so we can use constant space to replace the record array.
public int maxSubArray(int[] nums) {
    int max = Integer.MIN_VALUE, sum = 0;
    for (int i = 0; i < nums.length; i++) {
        if (sum < 0) 
            sum = nums[i];
        else 
            sum += nums[i];
        if (sum > max)
            max = sum;
    }
    return max;
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
/*
Using backtracking to solve this problem. The terminateend condition when the current index is the index equals the length of input digits, which means we already reached the end of the input phone number. For example, if the input is “23” -- “def””ghi”, we start from “2” -- d, “3” -- “g””h””i” , return back to previous level, then we goes to the 2 -- “e”, 3 -- “g””h””i”, then “f”..

*/
class Solution {
    String[] map = new String[]{"", "", "abc", "def", "ghi", "jkl", "mno", "pqrs", "tuv", "wxyz"};
    public List<String> letterCombinations(String digits) {
        List<String> res = new ArrayList<>();
        if(digits == null || digits.length() == 0){
            return res;
        }
        helper(res, digits, "", 0);
        return res;
    }
    private void helper(List<String> res, String digits, String item, int index){
      if(index >= digits.length()){
          res.add(new String(item));
          return;
      }
        String letter = map[digits.charAt(index) - '0'];
        for(int i = 0; i < letter.length(); i++){
            helper(res, digits, item + letter.charAt(i), index + 1);
        }
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
/*
   3
  7 4
 2 4 6
8 5 9 3

Step 1 :
3 0 0 0
7 4 0 0
2 4 6 0
8 5 9 3

Step 2 :
3  0  0  0
7  4  0  0
10 13 15 0

Step 3 :
3  0  0  0
20 19 0  0

Step 4:
23 0 0 0

output : 23

use bottom-up method, everytime, we check for current level, we check which number 
in the next level should be added to this number, there should be 2 numbers which next
to this number, we choose the minimum one

*/

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
//basic idea is to set start and end pointer, using binary search in the interval which is sequencial
//time: O(logn)
class Solution {
    public int search(int[] nums, int target) {
        if(nums == null || nums.length == 0){
            return -1;
        }
        int s = 0;
        int e = nums.length - 1;
        //search in the [s,e]
        while(s <= e){
            int mid = s + (e - s)/2;
            if(nums[mid] == target){
                return mid;
            }
            if(nums[mid] >= nums[s]){ //which means this part[s,mid] is sequencial and we can search in this interval
                if(target < nums[mid] && target >= nums[s]){
                    e = mid - 1;
                }else {
                    s = mid + 1;
                }
            }
            if(nums[mid] <= nums[e]){
                if(target > nums[mid] && target <= nums[e]){
                    s = mid + 1;
                }else{
                    e = mid - 1;
                }
            }
        }
        return -1;
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
//O(n)
class Solution {
    public int maximumSwap(int num) {
        String s = String.valueOf(num);
        int[] nums = new int[s.length()];
        //we store every digit into array
        for(int i = 0; i < nums.length; i++){
            nums[i] = s.charAt(i) - '0';
        }
        //search for the first index where (next value > pre)
        //if it keep decreasing, which means there is no max swap
        //'9631'
        int min = nums[0];
        int minIndex = 0;
        for(int i = 0; i < nums.length - 1; i++){
            if(nums[i + 1] > nums[i]){
                minIndex = i;
                min = nums[i];
                break;
            }else if(i == nums.length - 2){
                //which means the every digit is decreasing
                return num;
            }
        }
        
        //From the minIndex, we start our search for the greatest digit in the remaining digits. 
        //This will be our max and its index, maxIndex.
        //'97482, where the min is 4 and max is 8.'
        int max = nums[minIndex];
        int maxIndex = minIndex;
        for(int i = minIndex; i < nums.length; i++){
            if(nums[i] >= max){
                maxIndex = i;
                max = nums[i];
            }
        }
        
        //There could be a digit < max whose index < minIndex
        //'7'
        int swapIndex = 0;
        for(int i = 0; i <= minIndex; i++){
            if(nums[i] < max){
                swapIndex = i;
                break;
            }
        }
        
        //swap the two digits
        int tmp = nums[swapIndex];
        nums[swapIndex] = nums[maxIndex];
        nums[maxIndex] = tmp;
        
        //convert nums array to stringbuilder then to int
        StringBuilder sb = new StringBuilder();
        for(int i : nums){
            sb.append(i);
        }
        int res = Integer.valueOf(sb.toString());
        return res;
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

 /*
 解题思路：
 Sort the given interval array by its start time, compare previous interval end time with current interval start time,  and check if they have overlap or not, if yes, return false;
time:O(n)
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
 Sort the given interval list by its start time, 
 then compare previous interval.end with current interval.start, 
 if they are overlapping, merge them(update the end);
  if not, add the previous one, and go to the next comparison.
 */
// O(nlogn)
class Solution {
    public List<Interval> merge(List<Interval> intervals) {
        List<Interval> res = new ArrayList<>();
        if(intervals == null || intervals.size() <= 1){
            return intervals;
        }
        //sort the intervals with the start
        //从小王大
        Collections.sort(intervals, new Comparator<Interval>(){
            public int compare(Interval a, Interval b){
                return a.start - b.start;
            }
        });
        Interval last = intervals.get(0);
        for(int i = 1; i < intervals.size(); i++){
            if(intervals.get(i).start <= last.end){ //this means that the current interval has overlap with the previous interval
                last.end = Math.max(intervals.get(i).end, last.end); // update this overlapped interval's end.
            }else{
                res.add(last);//没有重叠的部分，所以直接把前一个interval加入到res里
                last = intervals.get(i);//更新last到当前的cur进行下一次循环
            }
        }
        res.add(last);
        return res;
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
### <a name="57"></a>57. Insert Intervals
```java
/**
 * Definition for an interval.
 * public class Interval {
 *     int start;
 *     int end;
 *     Interval() { start = 0; end = 0; }
 *     Interval(int s, int e) { start = s; end = e; }
 * }
此题思路就是非常straight forward的三步：
1.add newInterval之前的
2.add 和newInterval重叠的
3.add newInterval之后的
 */
public List<Interval> insert(List<Interval> intervals, Interval newInterval) {
    List<Interval> res = new ArrayList<>();
    int i = 0;
    while (i < intervals.size() && intervals.get(i).end < newInterval.start)
        res.add(intervals.get(i++));
    while (i < intervals.size() && intervals.get(i).start <= newInterval.end) {
        newInterval.start = Math.min(intervals.get(i).start, newInterval.start);
        newInterval.end = Math.max(intervals.get(i).end, newInterval.end);
        i++;
    }
    res.add(newInterval);
    while (i < intervals.size())    res.add(intervals.get(i++));
    return res;
}
//Find the intersection of two interval list
/*
given 2 list of interval representing users online offline timestamp e.g (already sorted), 
find all intervals that both of users are online.
e.g A= [(3, 5), (7, 11)] B=[(2, 4), (9, 10)] --> [(3, 4), (9, 10)]
Using two pointers, point to two intervals in the lists, and check the start time and end time between them, if they do not have overlap, move the pointer of the smaller one, and compare the next two intervals. 
Eg: [(1, 2), (7, 11)] B=[(3, 4), (9, 10)] --> [(9, 10)]
             I			j
Find that 2 < 3, move i to the next interval
                          I                 j
Find that 11 > 4 && 7 > 4, therefore the (3,4) is the smaller one,
 move j.
*/
public List<Interval> overlap(Interval[] a, Interval[] b){
	List<Interval> res = new ArrayList<>();
	int i = 0, j = 0;
	while(i < a.size() && b < size()){
		if(a[i].end <= b[j].end){
			i++;
		}else if(a[i].start >= b[j].end){
			j++;
			//these two conditions judge whether two intervals have overlap or not.
		}else{
			//a[i].end > b[j].end && a[i].start < b[j].end
			Interval tmp = new Interval(Math.max(a[i].start, b[j].start), Math.min(a[i].end, b[j].end));
			res.add(tmp);
			if(a[i].end >= b[j].end){
				j++;
			}else{
				i++;
			}
		}
		return res;
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
/*
because topological sort usually used to determine 
the sequence of things which have dependency with each other. 
And topological sort have two condition: directed and acyclic. 
we need to find all the nodes whose indegree is 0, 
put them into sequence, 
and delete these nodes and edge which start from these nodes
check whether have loop or not, 
if there are remained nodes, which means it have cycle.
and in this question, 
after we applying topological sort, 
if there is remaining courses, 
which means cannot finish the course.

2, [[1,0]]
*/
   public boolean canFinish(int numCourses, int[][] prerequisites) {
        if (null == prerequisites || numCourses == 0 || prerequisites.length == 0) {
                return true;
            }
            int[] preCourses = new int[numCourses];
            //[1,0] 
            // store the in-degree: # of precourses of one course 
            // prerequisite[0] means the post-course, 
            //preCourses of xx course is yy
            for (int[] prerequisite : prerequisites) {
                preCourses[prerequisite[0]]++; //the preCourse of index(course) is how many
            }
        //add all courses which do not have any prerequist course into queue
            Queue<Integer> queue = new LinkedList<Integer>();
            for (int i = 0; i < preCourses.length; i++) {
                if (preCourses[i] == 0) {
                    queue.add(i);
                }
            }
            //try to find these nodes postCourses and update their in-degree.
            int remaining = numCourses;
            while (!queue.isEmpty()) {
                int top = queue.poll();
                remaining--;
                for (int[] prerequisite : prerequisites) {
                    if (prerequisite[1] == top) {//寻找每一个后序课程
                        preCourses[prerequisite[0]]--;//update in-degree(prerequist course)
                        if (preCourses[prerequisite[0]] == 0) {
                            queue.add(prerequisite[0]);// if becomes 0, add to queue.
                        }
                    }
                }
            }
            return remaining==0;
    }
}
```

### <a name="210"></a>210. Course Schedule II
```java
/*
Basic idea is to build a graph,  
the node is every courses, 
and if they have relation, we add edge between them. 
And in  a valid graph, there should be one node which in-degree is 0,
this means it has no prerequisite course, 
so we start from this course then using Breadth First Search 
find the sequence of taking courses. 
And finally we also need to check 
if we have taken all the courses or not, 
if not, which means have circle in the graph, 
and it is impossible to take all courses.
*/
class Solution {
    public int[] findOrder(int numCourses, int[][] prerequisites) {
        //build graph
        List<Node> graph = new ArrayList<>();
        //add node
        for(int i = 0; i < numCourses; i++){
            graph.add(new Node(i));
        }
        //construct the edge for each node
        for(int i = 0; i < prerequisites.length; i++){
            int prev = prerequisites[i][1];
            int cur = prerequisites[i][0];
            graph.get(prev).outEdge.add(cur);
            graph.get(cur).inDegree++;
        }
        
        Queue<Node> queue = new LinkedList<>();//store all course that can take
        for(int i = 0; i < graph.size(); i++){
            if(graph.get(i).inDegree == 0){//means this course have no prerequisite course to take
                queue.offer(graph.get(i));
            }
        }
        
        int p = 0;
        int[] res = new int[numCourses];
        while(!queue.isEmpty()){
            Node n = queue.poll();
            res[p++] = n.index;
            for(int i = 0; i < n.outEdge.size(); i++){
                Node next = graph.get(n.outEdge.get(i));
                next.inDegree--;
                // when in coming edge number is 0
                // add this course into queue
                if(next.inDegree == 0){
                    queue.offer(next);
                }
            }
        }
        //check if we have all courses taken, 
        //if not which means we have circle in the graph which means it
        //is impossible to take all course
        return p == numCourses ? res : new int[0];
    }
}

    class Node{
            //a node represent a course
            int index; 
            // course label
            int inDegree; 
            //means the # of edges point to the course, which means this course can be taken after finish the number of inDegree courses
            List<Integer> outEdge;
            // this course points to other courses, which means this course is other courses prerequisite course
            public Node(int index){
                inDegree = 0;
                this.index = index;
                outEdge = new ArrayList<>();
            }
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
 /*1,最常见两种解法 O(nlogn) time, O(n) space
Using PriorityQueue to solve this problem, 
we first sort the given time intervals by their start time, 
and then use min heap which compare the end time of each interval 
and keep the interval which has the minimum end time on the top of the heap. 
Then compare the interval on the top of the heap with other interval,
merge the intervals which have intersection. 
The queue.size() is the final result.
 */
class Solution {
    public int minMeetingRooms(Interval[] intervals) {
        if (intervals == null || intervals.length == 0) return 0;
        //if not sort, [[7,10],[2,4]] may wrong, because everytime we compare current end time with next start time
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
/*
Ask before explain: Do we need to care about the order of task or not?
不用管相对顺序的解法：统计频率
P -- number of tasks which has same frequency with the maxFreq
N -- cooldown time
Count every task frequency and maintain the max frequency of task. 
Also, record the tasks count which has the same frequency with the max frequency. 
We have k A so we set (k - 1) groups, 
and each group has n + 1 positions
like: |A # # # #...| |A # # # #...| ....... A ...
             n个#            n个#                
             p（具有与最大频率相同的p个tasks直接全加在后面assume we have p tasks have the same frequency with A, add them to the end）
ans = (k - 1)*(n + 1) + p
*/
    public int leastInterval(char[] tasks, int n) {
         Map<Character, Integer> map = new HashMap<>();
        for(char t : tasks){
            map.put(t, map.getOrDefault(t, 0) + 1);
        }
        int maxFreq = 0;
        int maxCount = 0;
        for(int freq : map.values()){
            if(freq > maxFreq){
                maxFreq = freq;
                maxCount = 1;
            }else if(maxFreq == freq){
                maxCount++;
            }
        }
        int res = (maxFreq - 1)*(n + 1) + maxCount;
        //当tasks > ans的时候，说明我们已经把最高频率的task 安排完需要的槽数，如果这个螬数小于总的tasks，说明剩下的task不需要idle就可以安排
        return Math.max(res, tasks.length);
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

            if(map.containsKey(target-arr)){
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
### <a name="15"></a>15. Three Sum
```java
/*
Sorted the given array, 
for each number in the array, 
set two pointers after the fixed number, 
one from the start and one from the end. 
Every calculation we compare with 0, if larger, 
we move the end pointer, 
otherwise move the start pointer until we find the sum of this two pointers equals to the opposite number. 
Also we need to pay attention to the duplicates situation. 
Handle it by compare whether the current number is the same with previous one. 
If yes, just skip it
Time: O(n^2)

*/
class Solution {
    public List<List<Integer>> threeSum(int[] nums) {
        List<List<Integer>> res = new ArrayList<>();
        if(nums == null || nums.length == 0){
            return res;
        }
        Arrays.sort(nums);
        for(int i = 0; i < nums.length - 2; i++){
            if(i == 0 || nums[i] != nums[i - 1]){
                int nd = i + 1;
                int rd = nums.length - 1;
                while(nd < rd){
                    int sum = nums[i] + nums[nd] + nums[rd];
                    if(sum == 0){
                        res.add(Arrays.asList(nums[i], nums[nd], nums[rd]));
                        nd++;
                        rd--;
                        while(nd < rd && nums[nd] == nums[nd - 1]) nd++;
                        while(nd < rd && nums[rd] == nums[rd + 1]) rd--;
                    }else if(sum < 0){
                        nd++;
                    }else{
                        rd--;
                    }
                }
            }
        }
        return res;
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
/*
naive solution
hash+sort solution: O(mnlogn) time, O(m) space, m is the num of strs, n is the max length of strs
解题思路：Build a map, the key is character-sorted string and the value is all string that has the same characters with the key, We can do this by sorting the string and compare with the key value.. Eg: “eat” -- “aet” is the key, so “eat”,”ate”,”tea”is the value
*/
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
//use hashmap, the key is a string key, we can generate this string key by counting the occurences of each character in a string, for example, "aabcccdd" --> "2a1b3c2d", uniquely represent strings with same number of same character. the value of map is strings with the same stringkey. 
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
        
        return new ArrayList<List<String>> (map.values());
    }
}


```

### <a name="139"></a>139. Word Break
```java
/*
k = S.length(), n = dict.size().
time:O(k^2)

        “Iamace” --- [I, a, am, ace]
             0   1   2   3   4   5
        0    T   T

        1        T   T

        2            F   F 

        3                T   F

        4                    F    F 

        5                         F

        if the input[i...j] is in the dict, then T[i][j] = T
        else (if input[i..j] is not in the dict)
        then T[i][j] = T if has a K such that T[i][k] && T[k+1][j] is true
        

The run time complexity for the first DP is k*n and the complexity for the second DP is k^2. The performance has nothing to do with how strings are generated. So I don't think it will matter whether the strings are randomly generated or not.
*/
public class Solution {
    public boolean wordBreak(String s, Set<String> dict) {
        boolean[] f = new boolean[s.length() + 1];
        f[0] = true; // substring with length 0 is true
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
/*
解释：
using dynamic programming:
dp(i, j) represents whether s(i ... j) can form a palindromic substring, dp(i, j) is true when s(i) equals to s(j) and s(i+1 ... j-1) is a palindromic substring. When we found a palindrome, check if it’s the longest one. 

Time complexity O(n^2), space: O(n^2)
*/
public String longestPalindrome(String s) {
  int n = s.length();
  String res = null;
    
  boolean[][] dp = new boolean[n][n];
// dp[i][j] indicates whether substring s starting at index i and ending at j is palindrome

  for (int i = n - 1; i >= 0; i--) {// keep increasing the possible palindrome string
    for (int j = i; j < n; j++) {// find the max palindrome within this window of (i,j)
      //check if substring between (i,j) is palindrome
      dp[i][j] = s.charAt(i) == s.charAt(j) && (j - i < 3 || dp[i + 1][j - 1]);
            // if window is less than or equal to 3, just end chars should match
            // if window is > 3, substring (i+1, j-1) should be palindrome too

            //update max palindrome string
      if (dp[i][j] && (res == null || j - i + 1 > res.length())) {
        res = s.substring(i, j + 1);
      }
    }
  }
    
  return res;
}

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
/*
use stack to store directed left children from root
when next() been called, i just pop one element and process its right child as new root

hasNext() in O(1) time
next() in O(h) time

*/

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
//DFS O(n)
//use inorder tranversal
//iteration
class Solution {
    public int kthSmallest(TreeNode root, int k) {
        if(root == null){
            return 0;
        }
        Stack<TreeNode> stack = new Stack<>();
        TreeNode cur = root;
        while(cur != null){
            stack.push(cur);
            cur = cur.left;
        }
        while(!stack.isEmpty()){
            TreeNode tmp = stack.pop();
            k--;
            if(k == 0){
                return tmp.val;
            }
            while(tmp.right != null){
                stack.push(tmp.right);
                tmp.right = tmp.right.left;
            }
        }
        return -1;
    }
}

//recursion
class Solution{
    int res;
    int count;
    public class int findKSmall(TreeNode root, int k){
        res = 0;
        count = k;
        if(root == null){
            return 0;
        }
        helper(root);
        return res;
    }
    private void helper(TreeNode node){
        if(node.left != null){
            helper(node.left);
        }
        count--;
        if(count == 0){
            res = root.val;
            return;
        }
        if(node.right != null){
            helper(node.right);
        }
    }
}
//Follow up: 在查询多和更改多的情况下，我们可以为BST的每个节点增加一个int count，然后进行二分查找。
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
/*
Group the number by thousands (3 digits), and highest should be "billion", so we just need to process 4 groups
set three translation arrays to seperately store 1-9; 10-19; 20,30,40..90
use a helper function to deal with the group number
for example if we have number N with 3 digits, then the Hundred digits should be n/100, last two digis should be n%100
tenth digit should be n%100/10, last digit should be n%100%10, then we check whether the last two digits smaller than 20 or not
then pick them from the translation array.
*/
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
            num = num / 1000;//check if the current number is bigger than 1000 or not.
        }
        return result.trim();//check if there is a space at last, if yes, delete the space
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


//only for number from 1-999
public class IntegerToWord {
    private final String[] LESS_THAN_20 = {"", "One", "Two", "Three", "Four", "Five", "Six", "Seven", "Eight", "Nine", "Ten", "Eleven", "Twelve", "Thirteen", "Fourteen", "Fifteen", "Sixteen", "Seventeen", "Eighteen", "Nineteen"};
    private final String[] TENS = {"", "Ten", "Twenty", "Thirty", "Forty", "Fifty", "Sixty", "Seventy", "Eighty", "Ninety"};
    private final String[] HUNDREDS = {"", "Hundred"};
    public String numberToWords(int num){
        if (num == 0){
            return "Zero";
        }
        int i = 0;
        String res = "";
        while (num > 0){
            if (num % 100 != 0){
                res = helper(num % 100) + HUNDREDS[i] + " " + res;
            }
            i++;
            num = num / 100;
        }
        return res.trim();
    }
    public String helper(int num){
        if (num == 0){
            return "";
        }
        else if (num < 20){
            return LESS_THAN_20[num] + " ";
        }else {
            return TENS[num/10] + " " + helper(num % 10);
        }
    }
    public static void main(String args[]){
        IntegerToWord i = new IntegerToWord();
        System.out.println(i.numberToWords(146));
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
### <a name="93"></a>93. Restore IP Addresses
```java
/**
find all combination
we can use backtracking to solve this problem. The terminate condition is we have use all the characters in the given string and form the four parts of the ip address.
for example:"255255113"
we start from index = 0, we check whether the substring from 0 to 0 is a valid IP or not, if yes, we add to the tmpList as one part of the ip address, then goes to the next level,start from index = 0 + 1, and "5" also is a valid IP, so add to tmpList...keep going so we will get first possible combination which is "2.5.5.2" but it not use all the characters of the input, therefore we end this level searching. backtrack to previous level, and try the 25/255/2551...is also not valid.
 */
class Solution {
    public List<String> restoreIpAddresses(String s) {
        if(s == null || s.length() == 0 || s.length() > 12){
            return new ArrayList<>();
        }
        List<String> res = new ArrayList<>();
        List<String> tmpList = new ArrayList<>();
        backtracking(s, res, tmpList, 0);
        return res;
    }
    
    private void backtracking(String s, List<String> res, List<String> tmpList, int index){
        if(tmpList.size() == 4 && index < s.length()){
    		return;
    	}
        if(index == s.length() && tmpList.size() == 4){
            res.add(convert(tmpList));
        }else{
            for(int i = index; i < s.length(); i++){
                if(isValidIp(s, index, i)){
                    tmpList.add(s.substring(index, i + 1));
                    backtracking(s, res, tmpList, i + 1);
                    tmpList.remove(tmpList.size() - 1);
                }
            }
        }
    }
    
    private boolean isValidIp(String s, int start, int end){
        if(start > end || end > s.length()) return false;
        if(end - start + 1 > 3) return false;
        int value = Integer.valueOf(s.substring(start, end + 1));
        if(value < 0 || value > 255) return false;
        if(start != end && value == 0) return false;
        if(end != start && s.charAt(start) == '0') return false;
        return true;
    }
    
    private String convert(List<String> tmpList){
        String ret = "";
        for(String s : tmpList){
            ret += s + ".";
        }
        return ret.substring(0, ret.length() - 1);
    }
}

//tricy method: using three loop to solve this problem.
class Solution {
    public List<String> restoreIpAddresses(String s) {
        List<String> ans = new ArrayList<String>();
	    int len = s.length();
	    for (int i = 1; i <=3; ++i){  // first cut
		    if (len-i > 9) continue;//beacuse every part should not longer than 3 digits.		
		    for (int j = i+1; j<=i+3; ++j){  //second cut
			    if (len-j > 6) continue;    			
			    for (int k = j+1; k<=j+3 && k<len; ++k){  // third cut
				    int a,b,c,d;                // the four int's seperated by "."
				    a = Integer.parseInt(s.substring(0,i));  
				    b = Integer.parseInt(s.substring(i,j)); // notice that "01" can be parsed into 1. Need to deal with that later.
				    c = Integer.parseInt(s.substring(j,k));
				    d = Integer.parseInt(s.substring(k));
				    if (a>255 || b>255 || c>255 || d>255) continue; 
				    String ip = a+"."+b+"."+c+"."+d;
				    if (ip.length()<len+3) continue;  // this is to reject those int's parsed from "01" or "00"-like substrings, +3 means add three dot"." in the result
				    ans.add(ip);
			    }
		    }
	    }
	return ans;
    }
}
```
### <a name="28"></a>28. Implement strStr()
```java
/**
everytime we compare needle with equal length substring of haystack
time:O(n) space:O(1)
 */
class Solution {
    public int strStr(String haystack, String needle) {
        int hlen = haystack.length();
        int nlen = needle.length();
        if(hlen < nlen){
            return -1;
        }
        for(int i = 0; i <= hlen - nlen; i++){
            if(needle.equals(haystack.substring(i, i + nlen))){
                return i;
            }
        }
        return -1;
    }
}
```
### <a name="88"></a>88. Merge Sorted Array
```java
/**
three pointers
1. track the pos of nums1
2. track the pos of nums2
3. track which pos the numbers store in nums1, everytime we store the larger number of the first two pointers numbers
they both start from the end of array
ended when we finish go through one of array
and also which one is finished also matters, if nums2 not finish, we still need to merge rest of them to the nums1 array

time:O(n) space:O(1)
 */
class Solution {
    public void merge(int[] nums1, int m, int[] nums2, int n) {
        int i = m - 1;
        int j = n - 1;
        int k = m + n - 1;
        while(i >= 0 && j >= 0){
            nums1[k--] = nums1[i] >= nums2[j] ? nums1[i--] : nums2[j--];
        }
        //如果还有i的话那么就直接留在数组了
        //但是如果还有j没有merge的话 需要如下操作
        while(j >= 0){
            nums1[k--] = nums2[j--];
        }
    }
}

//merge sorted array 的平方存在负数
public void merge(int[] nums1, int m, int[] nums2, int n){
    nums1 = sortSquare(nums1);
    nums2 = sortSquare(nums2);
    int i = m - 1;
    int j = n - 1;
    int k = m + n - 1;
    while(i >= 0 && j >= 0){
        nums1[k--] = nums1[i] >= nums2[j] ? nums1[i--] : nums2[j--];
    }
    while(j >= 0){
        nums1[k--] = nums2[j--];
    }
}
//对数字的平方后排序
private int[] sortSquare(int[] nums){
    int left = 0;
    int right = nums.length - 1;
    int index = right;
    int[] res = new int[nums.length];
    while(index >= 0){
        if(nums[left] * nums[left] < nums[right] * nums[right]){
            res[index--] = nums[right] * nums[right--];
        }else{
            res[index--] = nums[left] * nums[left++];
        }
    }
    return res;
}

```

### <a name="314"></a>2314. Binary Tree Vertical Order Traversal
```java
/**
We marked root as 0, left node of root marked as root value -1,  right node marked as root value +1. For each subtree we do the same operation. Finally, we add nodes with the same marked number into one list, and add all list to the return result.
use two map, one to record each node and its marked value, other map to record marked value and list of nodes that has this value
或者再画图解释一下
  3
  /\
 /  \
 9  20
    /\
   /  \
  15   7
time:O(n)
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
    public List<List<Integer>> verticalOrder(TreeNode root) {
        List<List<Integer>> res = new ArrayList<>();
        if(root == null){
            return res;
        }
        //used to record each node and its tag number
        Map<TreeNode, Integer> recordNum = new HashMap<>();
        //used to record nodes that have same tag number
        Map<Integer, List<Integer>> map = new HashMap<>();
        recordNum.put(root, 0);
        Queue<TreeNode> queue = new LinkedList<>();
        queue.offer(root);
        int min = 0;
        while(!queue.isEmpty()){
            TreeNode cur = queue.poll();
            int w = recordNum.get(cur);
            if(!map.containsKey(w)){
                map.put(w, new ArrayList<>());
            }
            map.get(w).add(cur.val);
            if(cur.left != null){
                queue.add(cur.left);
                recordNum.put(cur.left, w - 1);
            }
            if(cur.right != null){
                queue.add(cur.right);
                recordNum.put(cur.right, w + 1);
            }
            //因为我们仍然需要找到最小的tag number
            min = Math.min(min, w);
        }
        //从最小（也就是最左的index开始）开始加入res的list中
        while(map.containsKey(min)){
            res.add(map.get(min++));
        }
        return res;
    }
}
```
### <a name="91"></a>91. Decode ways
```java
/**
Using dynamic programming to solve this problem, since the next result depend on the previous result. Check current character is in 1-9 or not, yes therefore there is one way to decode, then check previous one and current character if this number is in 10-26 or not, yes, then this is another way to decode. 
 Eg: input string is “321” dp[0] = 1, dp[1] = 1, dp[2] = dp[1], dp[3] = dp[3 - 1] + dp[3 - 2]
specially, dp[0] = 1 is just an initialization to make sure our solution works for all strings for lengths >= 2, which means dp[0] is not the number of ways to decode an empty string, it is an initialization as strings with length 0 or 1 will not even enter the loop.

 */
public class Solution {
    public int numDecodings(String s) {
        if(s == null || s.length() == 0) {
            return 0;
        }
        int n = s.length();
        int[] dp = new int[n+1];//num of ways of decoding s.substring(0, i)
        dp[0] = 1;
        dp[1] = s.charAt(0) != '0' ? 1 : 0;
        for(int i = 2; i <= n; i++) {
            int first = Integer.valueOf(s.substring(i-1, i));
            int second = Integer.valueOf(s.substring(i-2, i));
            if (first >= 1 && first <= 9) {//can form a one-digit num
                dp[i] += dp[i-1];  
            }
            if (second >= 10 && second <= 26) {//can form a two-digit num
                dp[i] += dp[i-2];
            }
        }
        return dp[n];
    }
}
/*
optimization
Optimization: 
Pre1 ⇒ f(a[i - 1])
Pre2 => f(a[i - 2])
Because we only use the result of f(a[i-1]), f(a[i - 2])，therefore we can replace them with constant variable pre1, pre2.
time: O(n), space: O(1)
*/
class Solution {
    public int numDecodings(String s) {
        if(s == null || s.length() == 0){
            return 0;
        }
        int pre1 = 1;
        int pre2 = 0;
        int cur = 0;
        for(int i = 0; i < s.length(); i++){
            int count1 = s.charAt(i) != '0'? pre1:0;
            int count2 = i >= 1 && s.charAt(i-1) != '0' && Integer.valueOf(s.substring(i-1,i+1)) <= 26 ? pre2 : 0;
            cur = count1+count2;
            pre2 = pre1;
            pre1 = cur;
            
        }
        return cur;
    }
}
```
### <a name="639"></a>639. Decode ways II
```java
/**
we can observe that the number of decodings possible upto any index, ii, is dependent only on the characters upto the index ii and not on any of the characters following it. This leads us to the idea that this problem can be solved by making use of Dynamic Programming.

p[i]: 前i个字符的解码方法的个数，初始化为字符串的长度+1
special case:
dp[0] = 1;
dp[1] = s.charAt(0) == '*' ? 9 : 1;
general case:
从i=2开始遍历，当前遍历到的字符s[i-1]有三种情况：
1. s[i-1] = 0：0不能单独拆开，只能跟前面的数字一起，而且前面的数字只能是1或2，其他的直接返回0即可。
那么当前面的数字是1或2的时候，dp[i]的种类数就跟dp[i-2]相等
s[i-2] = '*', 那么前面的数可以为1或者2，这样就相等于两倍的dp[i-2]；如果前面的数也为0，直接返回0即可。

2.s[i-1] = '*', 
如果当前数字为星号，那么就创造9种可以单独拆分的方法，所以那么dp[i]至少是等于9倍的dp[i-1]
如果s[i-2] = 1，那么当前的9种情况都可以跟前面的数字组成两位数，所以dp[i]需要加上9倍的dp[i-2]
s[i-2] = 2, if s[i - 1] <= 6,才可以组成两位数，所以+=6*dp[i - 2]
s[i-2] = '*', 前面两种情况的总和，dp[i] += 15*dp[i-2];

3. s[i-1] = 1~9, 数字是可以单独拆分出来的，那么dp[i]至少是等于dp[i-1]的
讨论前面一个数字的种类，
1)如果当前数字可以跟前面的数字组成一个小于等于26的两位数的话，dp[i]还需要加上dp[i-2]；
2)如果前面的数字为星号的话，那么要看当前的数字是否小于等于6，如果是小于等于6，那么前面的数字就可以是1或者2了，此时dp[i]需要加上两倍的dp[i-2]; 如果大于6，那么前面的数字只能是1，所以dp[i]只能加上dp[i-2]。
 */
class Solution {
    public int numDecodings(String s) {
        long M = 1000000007;
        char[] arr = s.toCharArray();
        long[] dp = new long[s.length() + 1];
        dp[0] = 1;
        if(arr[0] == '0'){
            return 0;
        }
        dp[1] = (arr[0] == '*') ? 9 : 1;
        for(int i = 2; i <= arr.length; ++i){
        	//s[i-1] = '0'
            if(arr[i - 1] == '0'){
                if(arr[i - 2] == '1' || arr[i - 2] == '2'){
                    dp[i] += dp[i - 2];
                }else if (arr[i - 2] == '*') {
                    dp[i] += 2 * dp[i - 2];
                }else{
                    return 0;
                }
            }//s[i - 1] = 1~9
            else if(arr[i - 1] >= '1' && arr[i - 1] <= '9'){
                dp[i] += dp[i - 1];
                if(arr[i - 2] == '1' || arr[i - 2] == '2' && arr[i - 1] <= '6'){
                    dp[i] += dp[i - 2];
                }
                if(arr[i - 2] == '*'){
                    dp[i] += (arr[i - 1] <= '6') ? (2 * dp[i - 2]) : dp[i - 2];
                }
            }else{//s[i - 1] = '*'
                dp[i] += 9 * dp[i - 1];
                if (arr[i - 2] == '1'){
                    dp[i] += 9 * dp[i - 2];
                }else if (arr[i - 2] == '2') {
                    dp[i] += 6 * dp[i - 2];
                }else if (arr[i - 2] == '*') 
                    dp[i] += 15 * dp[i - 2];
            }
            dp[i] %= M;
        }
        return (int)dp[s.length()];
    }
}
```
### <a name="251"></a>251.Flatten 2D Vector
```java
/**
use row as the list iterator, use vector as the List<List<>> iterator, 
everytime we call hasnext before next let j find a not empty list then return next.
 */

import java.util.*;
public class Vector2D implements Iterator<Integer> {
    Iterator<List<Integer>> vector;
    Iterator<Integer> row;
    public Vector2D(List<List<Integer>> vec2d) {
        vector = vec2d.iterator();
    }

    @Override
    public Integer next() {
        hasNext();
        return row.next();
    }

    @Override
    public boolean hasNext() {
        while((row == null || !row.hasNext()) && vector.hasNext()){
            row = vector.next().iterator();
        }
        return row != null && row.hasNext();
    }
    public static void main(String[] args){
        List<Integer> a1 = Arrays.asList(1,2,3);
        List<Integer> a2 = Arrays.asList(4,5);
        List<List<Integer>> vec2d = Arrays.asList(a1,a2);
        Vector2D i = new Vector2D(vec2d);
        while (i.hasNext()){
            System.out.print(i.next());
        }
    }
}

```
### <a name="128"></a>128. Longest Consecutive Sequence
```java
/**
use a set to record all the numbers in the nums, 
and go through all the array, 
when the curNum is th start of the sequence, 
we keep checking whether the following numbers are in the array or not. maintain the maxLen.

time:O(n), space: O(n)
Although the time complexity appears to be quadratic due to the while loop nested within the for loop, closer inspection reveals it to be linear. Because the while loop is reached only when currentNum marks the beginning of a sequence (i.e. currentNum-1 is not present in nums), the while loop can only run for nn iterations throughout the entire runtime of the algorithm. This means that despite looking like O(n∗n) complexity, the nested loops actually run in O(n+n)=O(n) time. All other computations occur in constant time, so the overall runtime is linear.
 */
class Solution {
    public int longestConsecutive(int[] nums) {
        if(nums == null || nums.length == 0){
            return 0;
        }
        Set<Integer> set = new HashSet<>();
        for(int i = 0; i < nums.length; i++){
            set.add(nums[i]);
        }
        int maxLen = 0;
        for(int i = 0; i < nums.length; i++){
            int len = 1;
            int curNum = nums[i];
            if(!set.contains(curNum - 1)){//only start while when the curNum is the start of the sequence
                while(set.contains(curNum + 1)){
                    len++;
                    curNum = curNum + 1;
                }
                maxLen = Math.max(maxLen, len);
            }
        }
        return maxLen;
    }
}

```
### <a name="1001"></a>Mine Sweeper
```java
/**

 */
import java.util.Random;

class MineSweeper {
      char[][] mMinefield; // 2-dimensional array of chars for our board

      public MineSweeper(int mWidth, int mHeight, int mMines) {
            System.out.println("Generating minefield...");

            mMinefield = new char[mHeight][mWidth];

            System.out.println("Clearing minefield...");

            clearMinefield(mHeight,mWidth);

            System.out.println("Placing mines...");

            placeMines(mMines,mWidth,mHeight);
            drawMinefield(mHeight,mWidth);

            System.out.println("Display minefield...");

            displayMinefield(mHeight,mWidth);
            drawMinefield(mHeight,mWidth);
      }

      public void placeMines(int mMines, int mWidth, int mHeight) {
            int minesPlaced = 0;
            Random random = new Random(); // this generates random numbers for us
            while(minesPlaced < mMines) {
                  int x = random.nextInt(mWidth); // a number between 0 and mWidth - 1
                  int y = random.nextInt(mHeight);
                  // make sure we don't place a mine on top of another
                  if(mMinefield[y][x] != 'F') {
                        mMinefield[y][x] = 'F';
                        minesPlaced ++;
                  }
            }
      }

      public void clearMinefield(int mHeight, int mWidth) {
            // Set every grid space to a space character.
            for(int y = 0; y < mHeight; y ++) {
                  for(int x = 0; x < mWidth; x ++) {
                        mMinefield[y][x] = ' ';
                  }
            }
      }

      public void drawMinefield(int mHeight, int mWidth) {
            for(int y = 0; y < mHeight; y ++) {
                  for(int x = 0; x < mWidth; x ++) {
                        System.out.print(mMinefield[y][x]);
                  }
                  System.out.print("\n");
            }
      }

      public void displayMinefield(int mHeight, int mWidth) {
            for(int y = 0; y < mHeight; y ++) {
                  for(int x = 0; x < mWidth; x ++) {
                        if(mMinefield[y][x] != 'F') {
                              mMinefield[y][x] = 'T';
                        }
                  }
            }
      }

      // this starts the command line application
      public static void main(String[] args) {
            MineSweeper mineSweeper = new MineSweeper(3,3,2);
      }
}

```
### <a name="146"></a>146. LRU Cache
```java
/**
最近用的缓存
无论插入还是取出（分为存在或者不存在），只要存在都要重新排序
HashMap + double linkedlist（用arraylist的话不可以是O(1)的操作，
所以要用linkedlist，）
1-》2-》3-》4
通过hasmap找到3，若要删除3的话不知道3前面的元素，所以要用double linkedlist
通过3找到2再删除

LRU has two properties: 
1. maintain sequence -- FIFO,(array, linkedlist)
2. quick search, giving specific key do the search(BST, Hashtable)

put(1,1) --> (1,1) is a entry

We use a double linked list which enables us to quickly move nodes,
because we need to move or add node one by one, 
and it is not suitabe to use array, 
so we use double linkedlist. 
Insert, remove, is O(1), randomly visit is O(n). 

we use hashtable of keys(what element in the cache) 
and value(pointer point to the element in linkedlist)
double linked nodes to search
 */
class Node{
    int key;
    int value;
    Node next;
    Node pre;
    public Node(int key, int value){
        this.key = key;
        this.value = value;
    }
}
private HashMap<Integer, Node> map;
private int capacity;
private Node head;
private Node tail;

public LRUCache(int capacity){
    map = new HashMap<>();
    this.capacity = capacity;
    head = null;
    tail = null;
}

public int get(int key){
    Node node = map.get(key);
    if(node == null){
        return -1;
    }
    //re order the cache
    if(node != tail){//当等于尾部的时候 不需要排序直接更新就好
        //但不等于尾部的时候
            if(node == head){
                head = head.next;
            }else{
                //不是头部 需要移除尾部元素
                node.pre.next = node.next;
                node.next.pre = node.pre;
            }
            tail.next = node;
            node.pre = tail;
            node.next = null;
            tail = node;
        }
        return node.value;
}

/*
capacity: 2 --- 1
map: 
1,1 进入head = newNode，所以1就是newNode
h,t

再加入(2,2)
1,1 -> 2,2 -> null
h       t

再加入(3,3)要删除（1，1）


*/
//插入的存在还是不存在
public void put(int key, int value){
    Node node = map.get(key);//存在的话，node！= null
    /*
    2,2 -> 3,3 -> null
    */

    if(node != null){
        node.value = value;
        if(node != tail){//当等于尾部的时候 不需要排序直接更新就好
        //但不等于尾部的时候
            if(node == head){
                head = head.next;
            }else{
                //不是头部 需要移除尾部元素
                node.pre.next = node.next;
                node.next.pre = node.pre;
            }
            tail.next = node;
            node.pre = tail;
            node.next = null;
            tail = node;
        }
    }else{
        //插入新值
        Node newNode = new Node(key, value);
        //check capacity
        if(capacity == 0){//add and remove
            Node temp = head;
            head = head.next;
            map.remove(temp.key);
            capacity++;
        }
        //cache里没东西
        if(head == null && tail == null){
            head = newNode;
        }else{//cahce有值
            tail.next = newNode;
            newNode.pre = tail;
            newNode.next = null;
        }
        tail = newNode;
        map.put(key, newNode);
        capacity--;
    }
}

```
### <a name="418"></a>418 sentence screen fitting
```java
//1.顺序不变 2. 不可拆开单词 
//改造 ["ab","cde","f"] --> "ab cde f"
//count: how many char of the reformatted sentence is on the screen
//count % length of reformatted sentence: 
//the starting position of the next row
//answer: count / len of reformatted sentence
//time: O(row * word len), space: O(n)
/*
len = 8
rows: 5, cols: 4
ab cde f ab cde f ab cde f...
xxx-
   xxxx // try to place 4 characters, 最后一个字符是空格，所以不在一个单词中间
       xxxxx // next line start with c
            xxxx
                xxxx
*/
class Solution {
    public int wordsTyping(String[] sentence, int rows, int cols) {
        String s = String.join(" ", sentence) + " ";
        int len = s.length();
        int count = 0;
        for(int i = 0; i < rows; i++){
            count += cols;
            //可以放，不在单词中间
            if(s.charAt((count % len)) == ' '){
                count++;
            }else{//可能在某个单词的中间，所以要看看当前字符后面的字符是否是空格
                while(count > 0 && s.charAt(((count - 1) % len)) != ' '){
                    count--;//后退直到碰到空格
                }
            }
        }
        return count / len;
    }
}

```
### <a name="547"></a>547. Friend Circles
```java
/*
this is a graph problem, and represent in a matrix. 
we search every people in the row, 
and marked all the connected friends as "visited" and 
start from this person do the depth first searching, 
find all the conected friend, these friends are a circle.

Time complexity : O(n^2). The complete matrix of size n^2 is traversed.
Space complexity : O(n). visited array of size n is used.
*/
public class Solution {
    public void dfs(int[][] M, int[] visited, int i) {
        for (int j = 0; j < M.length; j++) {
            if (M[i][j] == 1 && visited[j] == 0) {
                visited[j] = 1;
                dfs(M, visited, j);
            }
        }
    }
    public int findCircleNum(int[][] M) {
        int[] visited = new int[M.length];
        int count = 0;
        for (int i = 0; i < M.length; i++) {
            if (visited[i] == 0) {
                dfs(M, visited, i);
                count++;
            }
        }
        return count;
    }
}

```
### <a name="290"></a>290. Word Pattern
```java
/*
use two map to store the mapping between pattern and give string, 
if map1 already have the relation of current pattern,
then we need to check if the pattern match to this character.
for example:
map1 ----- (a, cat)
map2 ----- (cat, a)

aa
cat dog
already have a in map1, but cat != dog return false;

ab
cat cat
already do not have b in map1, 
but map2 have (b, cat) which is a mismatch so return false;
*/
public boolean wordPattern(String pattern, String str) {
    String[] strs = str.split(" ");
    
    if(pattern.length() != strs.length) return false;
    
    HashMap<Character, String> hm1 = new HashMap<Character, String>();
    HashMap<String, Character> hm2 = new HashMap<String, Character>();
    for(int i=0; i<pattern.length(); ++i) {
        if(hm1.containsKey(pattern.charAt(i))) {
            if(!hm1.get(pattern.charAt(i)).equals(strs[i])) return false;
        }
        else {
            if(hm2.containsKey(strs[i])) return false;
            else {
                hm1.put(pattern.charAt(i), strs[i]);
                hm2.put(strs[i], pattern.charAt(i));
            }
        }
    }
    
    return true;
}

/*
单个字符匹配即可：isomorphic string
foo - abb
 */
import java.util.*;
public class WordPattern {
    public static boolean match(String pattern, String input){
        if(pattern == null || pattern.length() == 0 || input == null || input.length() == 0 || pattern.length() != input.length())
            return false;
        Map<Character, Character> map = new HashMap<>();
        for(int i = 0; i < pattern.length(); i++){
            if (!map.containsKey(pattern.charAt(i))){
                map.put(pattern.charAt(i), input.charAt(i));
            }else{
                if (input.charAt(i) != map.get(pattern.charAt(i)))
                    return false;
            }
        }
        return true;
    }

    public static void main(String args[]){
        System.out.println(WordPattern.match("app","abc"));
    }
}


```
### <a name="32"></a>32. Longest Valid Parentheses
```java
/*
Instead of finding every possible string and checking its validity,
we can make use of stack while scanning the given string 
to check if the string scanned so far is valid, 
and also the length of the longest valid string. 
In order to do so, we start by pushing -1 onto the stack.

For every ‘(’ encountered, 
we push its index onto the stack.

For every ‘)’ encountered,
 we pop the topmost element and 
 subtract the current element's index from the top element of the stack,
 which gives the length of the currently encountered valid string of parentheses. 
 If while popping the element, 
 the stack becomes empty, 
 we push the current element's index onto the stack. 
 In this way, we keep on calculating the lengths of the valid substrings
 and return the length of the longest valid string at the end.

time:O(n), space: O(n)

test case:
0 1 2 3 4 5 6 7
( ) ) ( ( ( ) )
stack: -1
       -1 0
       -1        maxLen = 1-(-1) = 2
       空
       2
       2 3
       2 3 4
       2 3 4 5
       2 3 4  maxLen = 6 - 4 = 2
       2 3    maxLen = 7 - 3 = 4
*/
public class Solution {

    public int longestValidParentheses(String s) {
        int maxans = 0;
        Stack<Integer> stack = new Stack<>();
        stack.push(-1);
        for (int i = 0; i < s.length(); i++) {
            if (s.charAt(i) == '(') {
                stack.push(i);
            } else {
                stack.pop();
                if (stack.empty()) {
                    stack.push(i);
                } else {
                    maxans = Math.max(maxans, i - stack.peek());
                }
            }
        }
        return maxans;
    }
}
```
### <a name="418"></a>418. Sentence Screen Fitting
```java
//1.顺序不变 2. 不可拆开单词 
//改造 ["ab","cde","f"] --> "ab cde f"
//count: how many char of the reformatted sentence is on the screen
//count % length of reformatted sentence: the starting position of the next row
//answer: count / len of reformatted sentence
//time: O(row * word len), space: O(n)
/*
len = 8
rows: 5, cols: 4
ab cde f ab cde f ab cde f...
xxx-
   xxxx // try to place 4 characters, 最后一个字符是空格，所以不在一个单词中间
       xxxxx // next line start with c
            xxxx
                xxxx
*/
class Solution {
    public int wordsTyping(String[] sentence, int rows, int cols) {
        String s = String.join(" ", sentence) + " ";
        int len = s.length();
        int count = 0;
        for(int i = 0; i < rows; i++){
            count += cols;
            //可以放，不在单词中间
            if(s.charAt((count % len)) == ' '){
                count++;
            }else{//可能在某个单词的中间，所以要看看当前字符后面的字符是否是空格
                while(count > 0 && s.charAt(((count - 1) % len)) != ' '){
                    count--;//后退直到碰到空格
                }
            }
        }
        return count / len;
    }
}
```
### <a name="332"></a>332. Reconstruct Itinerary
```java
/*
In this problem, the path we are going to find is an itinerary which:
1. uses all tickets to travel among airports
2. preferably in ascending lexical order of airport code
think about the “backtracking” feature of DFS. We start by building a graph and then sorting vertices in the adjacency list so that when we traverse the graph later, we can guarantee the lexical order of the itinerary can be as good as possible. When we have generated an itinerary, we check if we have used all our airline tickets. If not, we revert the change and try another ticket. We keep trying until we have used all our tickets.
*/
public class Solution {
    private HashMap<String, List<String>> adjList = new HashMap<>();
    private LinkedList<String> route = new LinkedList<>();
    private int numTickets = 0;
    private int numTicketsUsed = 0;
    
    public List<String> findItinerary(String[][] tickets) {
        if (tickets == null || tickets.length == 0) return route;
        // build graph
        numTickets = tickets.length;
        for (int i = 0; i < tickets.length; ++i) {
            if (!adjList.containsKey(tickets[i][0])) {
                // create a new list
                List<String> list = new ArrayList<>();
                list.add(tickets[i][1]);
                adjList.put(tickets[i][0], list);
            } else {
                // add to existing list
                adjList.get(tickets[i][0]).add(tickets[i][1]);
            }
        }
        // sort vertices in the adjacency list so they appear in lexical order
        for (Map.Entry<String, List<String>> entry : adjList.entrySet()) {
            Collections.sort(entry.getValue());
        }
        
        // start DFS
        route.add("JFK");
        dfsRoute("JFK");
        return route;
    }
    
    private void dfsRoute(String v) {
        // base case: vertex v is not in adjacency list
        // v is not a starting point in any itinerary, or we would have stored it
        // thus we have reached end point in our DFS
        if (!adjList.containsKey(v)) return;
        List<String> list = adjList.get(v);
        for (int i = 0; i < list.size(); ++i) {
            String neighbor = list.get(i);
            // remove ticket(route) from graph
            list.remove(i);
            route.add(neighbor);
            numTicketsUsed++;
            dfsRoute(neighbor);
            // we only return when we have used all tickets
            if (numTickets == numTicketsUsed) return;
            // otherwise we need to revert the changes and try other tickets
            list.add(i, neighbor);
            // This line took me a long time to debug
            // we must remove the last airport, since in an itinerary, the same airport can appear many times!!
            route.removeLast();
            numTicketsUsed--;
        }
    }
}
/*
起点终点肯定不一样且不确定
*/
class Solution {
    public List<String> findItinerary(String[][] tickets) {
        Map<String, String> f2t = new HashMap<>();
        Set<String> end = new HashSet<String>();
        List<String> res = new ArrayList<>();
        if(tickets == null || tickets.length == 0){
            return res;   
        }
        for(int i = 0; i < tickets.length; i++){
            f2t.put(tickets[i][0], tickets[i][1]);
            end.add(tickets[i][1]);
        }
        String from = "";
        for(String str : f2t.keySet()){
            if(!end.contains(str)){
                from = str;
                break;
            }
        }
        boolean[] visited = new boolean[tickets.length];
        Queue<String> queue = new LinkedList<>();
        queue.offer(from);
        while(!queue.isEmpty()){
            String cur = queue.poll();
            res.add(cur);
            for(int i = 0; i < tickets.length; i++){
                if(!visited[i] && tickets[i][0].equals(cur)){
                    visited[i] = true;
                    String next = f2t.get(cur);
                    queue.offer(next);
                    break;
                }
            }
        }
        //res.remove(res.size() - 1);
        return res;
    }
}
```
### <a name="1002"></a>1002 yelp-Movie
```java
import java.util.*;
public class Movie {
    class MoviePlay{
        String name;
        int time;

        public MoviePlay(String name, int time){
            this.name = name;
            this.time = time;
        }

        public String toString(){
            return name + ":" + time;
        }
    }
    public List<MoviePlay> arrange(Map<String, List<Integer>> movies) throws Exception{
        List<MoviePlay> rlt = new ArrayList<>();
        if(helper(rlt, new HashSet<>(), movies, new ArrayList<>(movies.keySet()), 0)) return rlt;
        throw new Exception("No valid arrangement");
    }

    public boolean helper(List<MoviePlay> rlt, Set<Integer> timeTaken, Map<String, List<Integer>> times, List<String> movieList, int index){
        if(index == movieList.size()) return true;
        String movie = movieList.get(index);
        List<Integer> playtime = times.get(movie);
        for(Integer time: playtime){
            if(!timeTaken.contains(time)){
                timeTaken.add(time);
                rlt.add(new MoviePlay(movie, time));
                if(helper(rlt, timeTaken, times, movieList, index + 1)) return true;
                rlt.remove(rlt.size()-1);
                timeTaken.remove(time);
            }
        }
        return false;
    }

    public static void main(String[] args){
        Map<String, List<Integer>> movies = new HashMap<>();
        movies.put("A", new ArrayList());
        movies.put("B", new ArrayList());
        movies.put("C", new ArrayList());
        movies.put("D", new ArrayList());
        movies.get("A").addAll(Arrays.asList(14, 15, 16, 17));
        movies.get("B").addAll(Arrays.asList(14, 15));
        movies.get("C").addAll(Arrays.asList(14, 15));
        movies.get("D").addAll(Arrays.asList(14, 15, 16, 17));
        Movie m = new Movie();
        try{
            List<MoviePlay> rlt = m.arrange(movies);
            System.out.println(rlt);
        }catch (Exception e){
            e.printStackTrace();
        }
    }
}

```
### <a name="309"></a>309 best time to buy and sell stock with cooldown
```java
/*
price 当前的价格
buy[i] = max(buy[i - 1], rest[i - 1] - price)
sell[i] = max(buy[i - 1] + price, sell[i - 1])
rest[i] = max(sell[i - 1], buy[i - 1], rest[i - 1]) --》 买东西花钱 所以可以化简为：max(sell[i - 1], rest[i - 1])
由于冷冻期存在 所以rest[i] = sell[i-1]
故 buy[i] = max(buy[i-1], sell[i-2] - price)
sell[i] = max(buy[i-1]+price, sell[i-1])
*/
class Solution {
    public int maxProfit(int[] prices) {
        int maxPro = 0;
        int sell = 0, preSell = 0;
        int buy = Integer.MIN_VALUE, preBuy = 0;
        for(int price : prices){
            preBuy = buy;
            buy = Math.max(preBuy, preSell - price);
            preSell = sell;
            sell = Math.max(preBuy + price, preSell);
        }
        return sell;
    }
}
```
### <a name="525"></a>525. Continuous Array 
```java
/*
The idea is to change 0 in the original array to -1. 
Thus, if we find SUM[i, j] == 0
then we know there are even number of -1 and 1 between index i and j. 
Also put the sum to index mapping to a HashMap to make search faster.
time:O(n) Presum + HashMap
*/
class Solution{
    public int findMaxLength(int[] nums){
        int maxLen = 0;
        if(nums == null || nums.length == 0){
            return maxLen;
        }
        int sum = 0;
        Map<Integer, Integer> map = new HashMap<>();
        for(int i = 0; i < nums.length; i++){
            if(nums[i] == 0){
                nums[i] = -1;
            }
            sum += nums[i];
            if(sum == 0) maxLen = i + 1;
            //说明这里和前面某一个地方的和相同，那么他们之间的和为0
            if(map.containsKey(sum)){
                maxLen = Math.max(maxLen, i - map.get(sum));
            }
            if(!map.containsKey(sum)){
                map.put(sum, i);
            }
        }
        return maxLen;
    }
}
```
### <a name="674"></a>674. Longest Continuous Increasing Subsequence
```java
/*

*/
class Solution {
    public int findLengthOfLCIS(int[] nums) {
        if(nums == null || nums.length == 0){
            return 0;
        }
        int cnt = 0;
        int max = 0;
        for(int i = 0; i < nums.length; i++){
            if(i == 0 || nums[i - 1] < nums[i]){
                cnt++;
                max = Math.max(max, cnt);
            }else{
                cnt = 1;
            }
        }
        return max;
    }
}
```
### <a name="300"></a>300. Longest increasing Subsequence
```java
/*
We make use of a dp array to store the required data. dp[i]  represents the length of the longest increasing subsequence possible considering the array elements upto the i index only ,by necessarily including the i element. In order to find out dp[i], we need to try to append the current element(nums[i]) in every possible increasing subsequences upto the (i-1) index(including the (i-1) index), such that the new sequence formed by adding the current element is also an increasing subsequence. Thus, we can easily determine dp[i] using:
dp[i] = max(dp[j]) + 1 where 0 <= j < i
*/
public class Solution {
    public int lengthOfLIS(int[] nums) {
        if (nums.length == 0) {
            return 0;
        }
        int[] dp = new int[nums.length];
        dp[0] = 1;
        int maxans = 1;
        for (int i = 1; i < dp.length; i++) {
            int maxval = 0;
            for (int j = 0; j < i; j++) {
                if (nums[i] > nums[j]) {
                    maxval = Math.max(maxval, dp[j]);
                }
            }
            dp[i] = maxval + 1;
            maxans = Math.max(maxans, dp[i]);
        }
        return maxans;
    }
}

//O(nlogn)
// The idea is that as we iterate the sequence, we keep track of the minimum value a subsequence of given length might end with, for all so far possible subsequence lengths. So dp[i] is the minimum value a subsequence of length i+1 might end with. 
// Having this info, for each new number we iterate to, we can determine the longest subsequence where it can be appended using binary search. 
// The final answer is the length of the longest subsequence we found so far.
public int lengthOfLIS(int[] nums){
	int dp[] = new int[nums.length];
	int len = 0;
	for(int n : nums){
		int i = Arrays.binarySearch(dp, 0, len, n);
		if(i < 0){
			i = -(i + 1);
		}
		dp[i] = n;
		if(i == len){
			len++;
		}
	}
	return len;
}

```
### <a name="362"></a>362. Design Hit Counter
```java
class HitCounter {
    private Queue<Integer> q;
    /** Initialize your data structure here. */
    public HitCounter() {
        q = new LinkedList<>();
    }
    
    /** Record a hit.
        @param timestamp - The current timestamp (in seconds granularity). */
    public void hit(int timestamp) {
        q.offer(timestamp);
    }
    
    /** Return the number of hits in the past 5 minutes.
        @param timestamp - The current timestamp (in seconds granularity). */
    public int getHits(int timestamp) {
        while(!q.isEmpty() && timestamp - q.peek() >= 300){
            q.poll();
        }
        return q.size();
    }
}

/**
 * Your HitCounter object will be instantiated and called as such:
 * HitCounter obj = new HitCounter();
 * obj.hit(timestamp);
 * int param_2 = obj.getHits(timestamp);
 */

```
### <a name="72"></a>72. Edit Distance
```java
/*
dynamic programming to solve this problem
if we have two strings like: abodef and azced, so what we do is 
*/

class Solution {
    public int minDistance(String word1, String word2) {
        if(word1 == null || word2 == null || word1.length() == 0 || word2.length() == 0){
            return Math.abs(word1.length() - word2.length());
        }
        int[][] dp = new int[word1.length() + 1][word2.length() + 1];
        //initialize the table
        dp[0][0] = 0;
        for(int i = 1; i < dp.length; i++){
            dp[i][0] = i;
        }
        for(int j = 1; j < dp[0].length; j++){
            dp[0][j] = j;
        }
        
        for(int i = 1; i < dp.length; i++){
            for(int j = 1; j < dp[0].length; j++){
                if(word1.charAt(i -1) != word2.charAt(j - 1)){
                    dp[i][j] = Math.min(Math.min(dp[i-1][j-1], dp[i-1][j]), dp[i][j-1]) + 1;
                }else{
                    dp[i][j] = dp[i-1][j-1];
                }
            }
        }
        return dp[word1.length()][word2.length()];
    }
}
```
### <a name="1003"></a>1003 implement a BST(add, find, delete function)
```java
/*
Find(int n): O(logn)
Its very simple operation to perform.
start from the root and compare root.data with n
if root.data is greater than n that means we need to go to the left of the root.
if root.data is smaller than n that means we need to go to the right of the root.
if any point of time root.data is equal to the n then we have found the node, return true.
if we reach to the leaves (end of the tree) return false, we didn’t find the element

Insert(int n):

Very much similar to find() operation.
To insert a node our first task is to find the place to insert the node.
Take current = root .
start from the current and compare root.data with n
if current.data is greater than n that means we need to go to the left of the root.
if current.data is smaller than n that means we need to go to the right of the root.
if any point of time current is null that means we have reached to the leaf node, insert your node here with the help of parent node.

Delete(int n):

Here we have to deal with 3 cases.
Node to be deleted is a leaf node ( No Children):
if a node to be deleted has no children then just traverse to that node, 
keep track of parent node and the side in which the node exist(left or right) and set parent.left = null or parent.right = null;

Node to be deleted has only one child: if a node to be deleted(deleteNode) has only one child then just traverse to that node, 
keep track of parent node and the side in which the node exist(left or right).
check which side child is null (since it has only one child).
Say node to be deleted has child on its left side . T
hen take the entire sub tree from the left side and add it to the parent and the side on which deleteNode exist, see step 1 and example.

Node to be deleted has two childrens.
Find The Successor,is the smaller node in the right sub tree of the node to be deleted.
*/

public class BinarySearchTree {
	public static  Node root;
	public BinarySearchTree(){
		this.root = null;
	}
	
	public boolean find(int id){
		Node current = root;
		while(current!=null){
			if(current.data==id){
				return true;
			}else if(current.data>id){
				current = current.left;
			}else{
				current = current.right;
			}
		}
        //if we reach to the leaves (end of the tree) return false, we didn’t find the element
		return false;
	}
	public boolean delete(int id){
		Node parent = root;
		Node current = root;
		boolean isLeftChild = false;
        //locate the node which need to be deleted
		while(current.data!=id){
			parent = current;
			if(current.data>id){
				isLeftChild = true;
				current = current.left;
			}else{
				isLeftChild = false;
				current = current.right;
			}
			if(current ==null){
				return false;
			}
		}
		//if i am here that means we have found the node
		//Case 1: if node to be deleted has no children
		if(current.left==null && current.right==null){
			if(current==root){
				root = null;
			}
			if(isLeftChild ==true){
				parent.left = null;
			}else{
				parent.right = null;
			}
		}
		//Case 2 : if node to be deleted has only one child
		else if(current.right==null){
			if(current==root){
				root = current.left;
			}else if(isLeftChild){
				parent.left = current.left;
			}else{
				parent.right = current.left;
			}
		}
		else if(current.left==null){
			if(current==root){
				root = current.right;
			}else if(isLeftChild){
				parent.left = current.right;
			}else{
				parent.right = current.right;
			}
		}else if(current.left!=null && current.right!=null){
			
			//now we have found the minimum element in the right sub tree
			Node successor	 = getSuccessor(current);
			if(current==root){
				root = successor;
			}else if(isLeftChild){
				parent.left = successor;
			}else{
				parent.right = successor;
			}			
			successor.left = current.left;
		}		
		return true;		
	}
	
	public Node getSuccessor(Node deleleNode){
		Node successsor =null;
		Node successsorParent =null;
		Node current = deleleNode.right;
		while(current!=null){
			successsorParent = successsor;
			successsor = current;
			current = current.left;
		}
		//check if successor has the right child, it cannot have left child for sure
		// if it does have the right child, add it to the left of successorParent.
//		successsorParent
		if(successsor!=deleleNode.right){
			successsorParent.left = successsor.right;
			successsor.right = deleleNode.right;
		}
		return successsor;
	}
	public void insert(int id){
		Node newNode = new Node(id);
		if(root==null){
			root = newNode;
			return;
		}
		Node current = root;
		Node parent = null;
		while(true){
			parent = current;
            //if current.data is greater than n that 
            //means we need to go to the left of the root.
			if(id<current.data){				
				current = current.left;
				if(current==null){
                    //if any point of time current is null that means we have reached to the leaf node, 
                    //insert your node here with the help of parent node
					parent.left = newNode;
					return;
				}
			}else{//if current.data is smaller than n that 
            //means we need to go to the right of the root.
				current = current.right;
				if(current==null){
					parent.right = newNode;
					return;
				}
			}
		}
	}
	public void display(Node root){
		if(root!=null){
			display(root.left);
			System.out.print(" " + root.data);
			display(root.right);
		}
	}
	public static void main(String arg[]){
		BinarySearchTree b = new BinarySearchTree();
		b.insert(3);b.insert(8);
		b.insert(1);b.insert(4);b.insert(6);b.insert(2);b.insert(10);b.insert(9);
		b.insert(20);b.insert(25);b.insert(15);b.insert(16);
		System.out.println("Original Tree : ");
		b.display(b.root);		
		System.out.println("");
		System.out.println("Check whether Node with value 4 exists : " + b.find(4));
		System.out.println("Delete Node with no children (2) : " + b.delete(2));		
		b.display(root);
		System.out.println("\n Delete Node with one child (4) : " + b.delete(4));		
		b.display(root);
		System.out.println("\n Delete Node with Two children (10) : " + b.delete(10));		
		b.display(root);
	}
}

class Node{
	int data;
	Node left;
	Node right;	
	public Node(int data){
		this.data = data;
		left = null;
		right = null;
	}
}

/*
Original Tree : 
 1 2 3 4 6 8 9 10 15 16 20 25
Check whether Node with value 4 exists : true
Delete Node with no children (2) : true
 1 3 4 6 8 9 10 15 16 20 25
 Delete Node with one child (4) : true
 1 3 6 8 9 10 15 16 20 25
 Delete Node with Two children (10) : true
 1 3 6 8 9 15 16 20 25
*/
```
### <a name="1004"></a>1004. topological sorting
```java
/*
We can modify DFS to find Topological Sorting of a graph. In DFS, we start from a vertex, we first print it and then recursively call DFS for its adjacent vertices. In topological sorting, we use a temporary stack. We don’t print the vertex immediately, we first recursively call topological sorting for all its adjacent vertices, then push it to a stack. Finally, print contents of stack. Note that a vertex is pushed to stack only when all of its adjacent vertices (and their adjacent vertices and so on) are already in stack.
*/

// A Java program to print topological sorting of a DAG
import java.io.*;
import java.util.*;
 
// This class represents a directed graph using adjacency
// list representation
class Graph
{
    private int V;   // No. of vertices
    private LinkedList<Integer> adj[]; // Adjacency List
 
    //Constructor
    Graph(int v)
    {
        V = v;
        adj = new LinkedList[v];
        for (int i=0; i<v; ++i)
            adj[i] = new LinkedList();
    }
 
    // Function to add an edge into the graph
    void addEdge(int v,int w) { adj[v].add(w); }
 
    // A recursive function used by topologicalSort
    void topologicalSortUtil(int v, boolean visited[],
                             Stack stack)
    {
        // Mark the current node as visited.
        visited[v] = true;
        Integer i;
 
        // Recur for all the vertices adjacent to this
        // vertex
        Iterator<Integer> it = adj[v].iterator();
        while (it.hasNext())
        {
            i = it.next();
            if (!visited[i])
                topologicalSortUtil(i, visited, stack);
        }
 
        // Push current vertex to stack which stores result
        stack.push(new Integer(v));
    }
 
    // The function to do Topological Sort. It uses
    // recursive topologicalSortUtil()
    void topologicalSort()
    {
        Stack stack = new Stack();
 
        // Mark all the vertices as not visited
        boolean visited[] = new boolean[V];
        for (int i = 0; i < V; i++)
            visited[i] = false;
 
        // Call the recursive helper function to store
        // Topological Sort starting from all vertices
        // one by one
        for (int i = 0; i < V; i++)
            if (visited[i] == false)
                topologicalSortUtil(i, visited, stack);
 
        // Print contents of stack
        while (stack.empty()==false)
            System.out.print(stack.pop() + " ");
    }
 
    // Driver method
    public static void main(String args[])
    {
        // Create a graph given in the above diagram
        Graph g = new Graph(6);
        g.addEdge(5, 2);
        g.addEdge(5, 0);
        g.addEdge(4, 0);
        g.addEdge(4, 1);
        g.addEdge(2, 3);
        g.addEdge(3, 1);
 
        System.out.println("Following is a Topological " +
                           "sort of the given graph");
        g.topologicalSort();
    }
}
```
### <a name="1005"></a>1005. all combination / password problem
```java
/*
use backtracing, find all possiblity
*/
import java.util.*;
public class allCombination {
    public List<String> combination(String input){
        List<String> res = new ArrayList<>();
        if(input == null || input.length() == 0){
            return res;
        }
        helper(res, input, "", 0);
        return res;
    }
    public void helper(List<String> res, String input, String item, int index){
        if (index >= input.length()){
            res.add(new String(item));
            return;
        }

        char cur = input.charAt(index);
        String letter = "" + cur;
        if (!Character.isDigit(input.charAt(index))){
            char add = Character.isUpperCase(cur) ? Character.toLowerCase(cur) : Character.toUpperCase(cur);
            letter += add;
        }
        for(int i = 0; i < letter.length(); i++){
            helper(res, input, item + letter.charAt(i), index + 1);
        }
    }
    public static void main(String args[]){
        String input = "A17s";
        allCombination ac = new allCombination();
        List<String> res = ac.combination(input);
        for(String str : res){
            System.out.println(str);
        }
    }
}
```
### <a name="1006"></a>1006. Reservoir Sampling
```java
/*
O(n) time. 
1) Create an array reservoir[0..k-1] 
and copy first k items of stream[] to it.
2) Now one by one consider all items from (k+1)th item to nth item.
a) Generate a random number from 0 to i 
where i is index of current item in stream[]. 
Let the generated random number is j.
b) If j is in range 0 to k-1, 
replace reservoir[j] with arr[i]
*/

// An efficient Java program to randomly
// select k items from a stream of items
import java.util.Arrays;
import java.util.Random;
public class ReservoirSampling 
{
    // A function to randomly select k items from stream[0..n-1].
    static void selectKItems(int stream[], int n, int k)
    {
        int i;   // index for elements in stream[]
         
        // reservoir[] is the output array. Initialize it with
        // first k elements from stream[]
        int reservoir[] = new int[k];
        for (i = 0; i < k; i++)
            reservoir[i] = stream[i];
         
        Random r = new Random();
         
        // Iterate from the (k+1)th element to nth element
        for (; i < n; i++)
        {
            // Pick a random index from 0 to i.
            int j = r.nextInt(i + 1);
             
            // If the randomly  picked index is smaller than k,
            // then replace the element present at the index
            // with new element from stream
            if(j < k)
                reservoir[j] = stream[i];           
        }
         
        System.out.println("Following are k randomly selected items");
        System.out.println(Arrays.toString(reservoir));
    }
     
    //Driver Program to test above method
    public static void main(String[] args) {
        int stream[] = {1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12};
        int n = stream.length;
        int k = 5;
        selectKItems(stream, n, k);
    }
}

```
### <a name="1007"></a>1007. judge square
```java
/*
if two opposite line they are equal which means it is Parallelogram
under this condition, if adjacent lines are perpendicular
it should be square or ranctangular
under this condition, id adjacent lines are equal, square
otherwise is ranctangular
if adjacent lines are not perpendicualr but equal it is diamond
*/
public class JudgeSquare {
    public String check(Point[] p) {
        String res = "";
        int px = (p[1].x - p[0].x);
        int py = (p[1].y - p[0].y);

        int qx = (p[2].x - p[3].x);
        int qy = (p[2].y - p[3].y);

        int rx = (p[2].x - p[1].x);
        int ry = (p[2].y - p[1].y);

        int tx = p[3].x - p[0].x;
        int ty = p[3].y - p[0].y;

        if (px == qx && py == qy && rx == tx && ry == ty)//两组对边分别相等-->平行四边形
        {
            if (px * rx + py * ry == 0)//+邻边垂直-->矩形或正方形
            {
                if (px * px + py * py == rx * rx + ry * ry)//+邻边相等-->正方形
                {
                    res = "Square";
                } else
                    res = "Rectangle";
            } else if (px * px + py * py == rx * rx + ry * ry)//+邻边不垂直但相等-->菱形
            {
                res = "Diamond";
            } else//平行四边形
                res = "Parallelogram";
        } else
            res = "Others";
        return res;
    }
}

class Point{
    int x,y;
    Point(int x, int y){
        this.x = x;
        this.y = y;
    }
}
```
