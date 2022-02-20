# LeetCode Notes

> This project is for personal note making for LeetCode questions.



> 刷题顺序参考 [Leetcode-retag](https://github.com/resumejob/Leetcode-retag)

---

## Leetcode 高频题 2021 版

重新分类 

- 题目按照面试频率降序排列
- 增加难度分类，适合从Easy:开始学习
- 增加细分类别，例如单调栈，前缀树等，一道题目可能会有多个类别

## Tags
  - [Linked List](#linked-list)
    - 单链表 (Singly Linked List)
    - 双链表 (Doubly Linked List)
  - [Tree](#tree)
    - 遍历 (Traversal)
    - 构造 (Construction)
    - 路径 | 深度 | 翻转 (Path | Depth | Invert)
    - 二叉搜索树 (Binary Search Tree)
    - 前缀树 (Trie)
    - * 线段树 (Segment Tree)
  - [Stack](#stack)
    - 基础 (Basic)
    - 单调栈 (Monotone Stack)
  - [Heap](#heap)
    - 基础 (Basic)
  - [Binary Search](#binary-search)
  - [Bitwise Operation](#bitwise-operation)
  - [Two-Pointer and Sliding Window](#two-pointer-and-sliding-window)
  - [Matrix](#matrix)
  - [Dynamic Programming](#dynamic-programming)
    - 一维 (1 Dimensional)
    - 二维 (2 Dimensional)
  - [Graph](#graph)
    - DFS (Depth First Search)
    - BFS (Breath First Search)
    - *Dijkstra
    - 拓扑排序 (Topological Sort)
  - [Disjoint Set](#disjoint-set)
  - [Design](#design)
  - [Greedy](#greedy)
  - [Backtracking](#backtracking)
  - [Clone](#clone)
  - [Math](#math)
  - [Minimax](#minimax)
  - [Geometry](#geometry)

## Linked List
- Singly Linked List:
  - Easy:
    - [206. Reverse Linked List](https://leetcode.com/problems/reverse-linked-list)
    - [141. Linked List Cycle](https://leetcode.com/problems/linked-list-cycle/)
    - [83. Remove Duplicates from Sorted List](https://leetcode.com/problems/remove-duplicates-from-sorted-list/)
    - [234. Palindrome Linked List](https://leetcode.com/problems/palindrome-linked-list/)
    - [203. Remove Linked List Elements](https://leetcode.com/problems/remove-linked-list-elements/)
    - [237. Delete Node in a Linked List](https://leetcode.com/problems/delete-node-in-a-linked-list/)
    - [876. Middle of the Linked List](https://leetcode.com/problems/middle-of-the-linked-list/)
  - Medium:
    - [92. Reverse Linked List II](https://leetcode.com/problems/reverse-linked-list-ii/)
    - [143. Reorder List](https://leetcode.com/problems/reorder-list/)
    - [82. Remove Duplicates from Sorted List II](https://leetcode.com/problems/remove-duplicates-from-sorted-list-ii/)
    - [19. Remove Nth Node From End of List](https://leetcode.com/problems/remove-nth-node-from-end-of-list/)
    - [148. Sort List](https://leetcode.com/problems/sort-list/)
    - [86. Partition List](https://leetcode.com/problems/partition-list/)
    - [61. Rotate List](https://leetcode.com/problems/rotate-list/)
    - [142. Linked List Cycle II](https://leetcode.com/problems/linked-list-cycle-ii/)
    - [147. Insertion Sort List](https://leetcode.com/problems/insertion-sort-list/)
    - [138. Copy List with Random Pointer](https://leetcode.com/problems/copy-list-with-random-pointer/)
    - [24. Swap Nodes in Pairs](https://leetcode.com/problems/swap-nodes-in-pairs/)
    - [328. Odd Even Linked List](https://leetcode.com/problems/odd-even-linked-list/)
    - [707. Design Linked List](https://leetcode.com/problems/design-linked-list/)
    - [109. Convert Sorted List to Binary Search Tree](https://leetcode.com/problems/convert-sorted-list-to-binary-search-tree/)
    - [430. Flatten a Multilevel Doubly Linked List](https://leetcode.com/problems/flatten-a-multilevel-doubly-linked-list/)
    - [725. Split Linked List in Parts](https://leetcode.com/problems/split-linked-list-in-parts/)
  - Hard:
    - [25. Reverse Nodes in k-Group](https://leetcode.com/problems/reverse-nodes-in-k-group/)

- Doubly Linked List:
  - Easy:
    - [21. Merge Two Sorted Lists](https://leetcode.com/problems/merge-two-sorted-lists/)
    - [160. Intersection of Two Linked Lists](https://leetcode.com/problems/intersection-of-two-linked-lists/)
  - Medium:
    - [2. Add Two Numbers](https://leetcode.com/problems/add-two-numbers/)
    - [445. Add Two Numbers II](https://leetcode.com/problems/add-two-numbers-ii/)
    - [1669. Merge In Between Linked Lists](https://leetcode.com/problems/merge-in-between-linked-lists/)
  - Hard:
    - [23. Merge k Sorted Lists](https://leetcode.com/problems/merge-k-sorted-lists/)

## Tree
- Traversal:
  - Easy:
    - [145. Binary Tree Postorder Traversal](https://leetcode.com/problems/binary-tree-postorder-traversal/)
    - [94. Binary Tree Inorder Traversal](https://leetcode.com/problems/binary-tree-inorder-traversal/)
    - [589.  N-ary Tree Preorder Traversal](https://leetcode.com/problems/n-ary-tree-preorder-traversal/)
    - [144. Binary Tree Preorder Traversal](https://leetcode.com/problems/binary-tree-preorder-traversal/)
    - [590. N-ary Tree Postorder Traversal](https://leetcode.com/problems/n-ary-tree-postorder-traversal/)
  - Medium:
    - [102. Binary Tree Level Order Traversal](https://leetcode.com/problems/binary-tree-level-order-traversal/)
    - [103. Binary Tree Zigzag Level Order Traversal](https://leetcode.com/problems/binary-tree-zigzag-level-order-traversal/)
    - [107. Binary Tree Level Order Traversal II](https://leetcode.com/problems/binary-tree-level-order-traversal-ii/)

- Construction
  - Easy:
    - [108. Convert Sorted Array to Binary Search Tree](https://leetcode.com/problems/convert-sorted-array-to-binary-search-tree/)
  - Medium:
    - [105. Construct Binary Tree from Preorder and Inorder Traversal](https://leetcode.com/problems/construct-binary-tree-from-preorder-and-inorder-traversal/)
    - [106. Construct Binary Tree from Inorder and Postorder Traversal](https://leetcode.com/problems/construct-binary-tree-from-inorder-and-postorder-traversal/)
    - [114. Flatten Binary Tree to Linked List](https://leetcode.com/problems/flatten-binary-tree-to-linked-list/)
    - [889. Construct Binary Tree from Preorder and Postorder Traversal](https://leetcode.com/problems/construct-binary-tree-from-preorder-and-postorder-traversal/)
    - [1008. Construct Binary Search Tree from Preorder Traversal](https://leetcode.com/problems/construct-binary-search-tree-from-preorder-traversal/)
  - Hard:
    - [297. Serialize and Deserialize Binary Tree](https://leetcode.com/problems/serialize-and-deserialize-binary-tree/)

- Path | Depth | Invert
  - Easy:
    - [104. Maximum Depth of Binary Tree](https://leetcode.com/problems/maximum-depth-of-binary-tree/)
    - [101. Symmetric Tree](https://leetcode.com/problems/symmetric-tree/)
    - [226. Invert Binary Tree](https://leetcode.com/problems/invert-binary-tree/)
    - [543. Diameter of Binary Tree](https://leetcode.com/problems/diameter-of-binary-tree/)
    - [257. Binary Tree Paths](https://leetcode.com/problems/binary-tree-paths/)
    - [110. Balanced Binary Tree](https://leetcode.com/problems/balanced-binary-tree/)
    - [617. Merge Two Binary Trees](https://leetcode.com/problems/merge-two-binary-trees/)
    - [100. Same Tree](https://leetcode.com/problems/same-tree/)
    - [112. Path Sum](https://leetcode.com/problems/path-sum/)
    - [111. Minimum Depth of Binary Tree](https://leetcode.com/problems/minimum-depth-of-binary-tree/)
  - Medium:
    - [236. Lowest Common Ancestor of a Binary Tree](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-tree/)
    - [222. Count Complete Tree Nodes](https://leetcode.com/problems/count-complete-tree-nodes/)
    - [113. Path Sum II](https://leetcode.com/problems/path-sum-ii/)
    - [437. Path Sum III](https://leetcode.com/problems/path-sum-iii/)
    - [129. Sum Root to Leaf Numbers](https://leetcode.com/problems/sum-root-to-leaf-numbers/)
    - [662. Maximum Width of Binary Tree](https://leetcode.com/problems/maximum-width-of-binary-tree/)
    - [114. Flatten Binary Tree to Linked List](https://leetcode.com/problems/flatten-binary-tree-to-linked-list/)
    - [199. Binary Tree Right Side View](https://leetcode.com/problems/binary-tree-right-side-view/)
    - [116. Populating Next Right Pointers in Each Node](https://leetcode.com/problems/populating-next-right-pointers-in-each-node/)
    - [515. Find Largest Value in Each Tree Row](https://leetcode.com/problems/find-largest-value-in-each-tree-row/)
  - Hard:
    - [124. Binary Tree Maximum Path Sum](https://leetcode.com/problems/binary-tree-maximum-path-sum/)
    - [297. Serialize and Deserialize Binary Tree](https://leetcode.com/problems/serialize-and-deserialize-binary-tree/)

- Binary Search Tree
  - Easy:
    - [108. Convert Sorted Array to Binary Search Tree](https://leetcode.com/problems/convert-sorted-array-to-binary-search-tree/)
  - Medium:
    - [98. Validate Binary Search Tree](https://leetcode.com/problems/validate-binary-search-tree/)
    - [96. Unique Binary Search Trees](https://leetcode.com/problems/unique-binary-search-trees/)
    - [95. Unique Binary Search Trees II](https://leetcode.com/problems/unique-binary-search-trees-ii/)
    - [173. Binary Search Tree Iterator](https://leetcode.com/problems/binary-search-tree-iterator/)
    - [230. Kth Smallest Element in a BST](https://leetcode.com/problems/kth-smallest-element-in-a-bst/)
    - [99. Recover Binary Search Tree](https://leetcode.com/problems/recover-binary-search-tree/)

- Dictionary Tree
  - Easy:
    - [720. Longest Word in Dictionary](https://leetcode.com/problems/longest-word-in-dictionary/)
  - Medium:
    - [208. Implement Trie (Prefix Tree)](https://leetcode.com/problems/implement-trie-prefix-tree/)
    - [692. Top K Frequent Words](https://leetcode.com/problems/top-k-frequent-words/)
    - [421. Maximum XOR of Two Numbers in an Array](https://leetcode.com/problems/maximum-xor-of-two-numbers-in-an-array/)
  - Hard:
    - [212. Word Search II](https://leetcode.com/problems/word-search-ii/)

- Segment Tree
  - Medium:
    - [1353. Maximum Number of Events That Can Be Attended](https://leetcode.com/problems/maximum-number-of-events-that-can-be-attended/)
    - [307. Range Sum Query - Mutable](https://leetcode.com/problems/range-sum-query-mutable/)
  - Hard:
    - [315. Count of Smaller Numbers After Self](https://leetcode.com/problems/count-of-smaller-numbers-after-self/)
    - [493. Reverse Pairs](https://leetcode.com/problems/reverse-pairs/)
    - [218. The Skyline Problem](https://leetcode.com/problems/the-skyline-problem/)
    - [715. Range Module](https://leetcode.com/problems/range-module/)
    - [850. Rectangle Area II](https://leetcode.com/problems/rectangle-area-ii/)
    - [1157. Online Majority Element In Subarray](https://leetcode.com/problems/online-majority-element-in-subarray/)
    - [699. Falling Squares](https://leetcode.com/problems/falling-squares/)
    - [327. Count of Range Sum](https://leetcode.com/problems/count-of-range-sum/)
  
## Stack
- Basic
  - Easy:
    - [20. Valid Parentheses](https://leetcode.com/problems/valid-parentheses/)
    - [1047. Remove All Adjacent Duplicates In String](https://leetcode.com/problems/remove-all-adjacent-duplicates-in-string/)
    - [232. Implement Queue using Stacks](https://leetcode.com/problems/implement-queue-using-stacks/)
    - [155. Min Stack](https://leetcode.com/problems/min-stack/)
    - [225. Implement Stack using Queues](https://leetcode.com/problems/implement-stack-using-queues/)
    - [1021. Remove Outermost Parentheses](https://leetcode.com/problems/remove-outermost-parentheses/)
    - [682. Baseball Game](https://leetcode.com/problems/baseball-game/)
    - [844. Backspace String Compare](https://leetcode.com/problems/backspace-string-compare/)
  - Medium:
    - [1190. Reverse Substrings Between Each Pair of Parentheses](https://leetcode.com/problems/reverse-substrings-between-each-pair-of-parentheses/)
    - [394. Decode String](https://leetcode.com/problems/decode-string/)
    - [456. 132 Pattern](https://leetcode.com/problems/132-pattern/)
    - [227. Basic Calculator II](https://leetcode.com/problems/basic-calculator-ii/)
    - [150. Evaluate Reverse Polish Notation](https://leetcode.com/problems/evaluate-reverse-polish-notation/)
    - [503. Next Greater Element II](https://leetcode.com/problems/next-greater-element-ii/)
    - [71. Simplify Path](https://leetcode.com/problems/simplify-path/)
    - [856. Score of Parentheses](https://leetcode.com/problems/score-of-parentheses/)
    - [907.Sum of Subarray Minimums](https://leetcode.com/problems/sum-of-subarray-minimums/)
    - [385. Mini Parser](https://leetcode.com/problems/mini-parser/)
    - [1249. Minimum Remove to Make Valid Parentheses](https://leetcode.com/problems/minimum-remove-to-make-valid-parentheses/)
    - [636. Exclusive Time of Functions](https://leetcode.com/problems/exclusive-time-of-functions/)
    - [341. Flatten Nested List Iterator](https://leetcode.com/problems/flatten-nested-list-iterator/)
  - Hard:
    - [224. Basic Calculator](https://leetcode.com/problems/basic-calculator/)
    - [726. Number of Atoms](https://leetcode.com/problems/number-of-atoms/)


- Monotone Stack
  - Easy:
    - [496. Next Greater Element I](https://leetcode.com/problems/next-greater-element-i/)
  - Medium:
    - [739. Daily Temperatures](https://leetcode.com/problems/daily-temperatures/)
    - [402. Remove K Digits](https://leetcode.com/problems/remove-k-digits/)
    - [316. Remove Duplicate Letters](https://leetcode.com/problems/remove-duplicate-letters/)
    - [1124. Longest Well-Performing Interval](https://leetcode.com/problems/longest-well-performing-interval/)
  - Hard:
    - [42. Trapping Rain Water](https://leetcode.com/problems/trapping-rain-water/)
    - [84. Largest Rectangle in Histogram](https://leetcode.com/problems/largest-rectangle-in-histogram/)
    - [85. Maximal Rectangle](https://leetcode.com/problems/maximal-rectangle/)
    - [321. Create Maximum Number](https://leetcode.com/problems/create-maximum-number/)


## Heap
- Basic
  - Easy:
    - [1046. 1046. Last Stone Weight](https://leetcode.com/problems/last-stone-weight/)
    - [703. Kth Largest Element in a Stream](https://leetcode.com/problems/kth-largest-element-in-a-stream/)
  - Medium:
    - [215. Kth Largest Element in an Array](https://leetcode.com/problems/kth-largest-element-in-an-array/)
    - [347. Top K Frequent Elements](https://leetcode.com/problems/top-k-frequent-elements/)
    - [692. Top K Frequent Words](https://leetcode.com/problems/top-k-frequent-words/)
    - [378. Kth Smallest Element in a Sorted Matrix](https://leetcode.com/problems/kth-smallest-element-in-a-sorted-matrix/)
    - [451. Sort Characters By Frequency](https://leetcode.com/problems/sort-characters-by-frequency/)
    - [743. Network Delay Time](https://leetcode.com/problems/network-delay-time/)
    - [787. Cheapest Flights Within K Stops](https://leetcode.com/problems/cheapest-flights-within-k-stops/)
    - [973. K Closest Points to Origin](https://leetcode.com/problems/k-closest-points-to-origin/)
  - Hard:
    - [239. Sliding Window Maximum](https://leetcode.com/problems/sliding-window-maximum/)
    - [295. Find Median from Data Stream](https://leetcode.com/problems/find-median-from-data-stream/)
    - [218. The Skyline Problem](https://leetcode.com/problems/the-skyline-problem/)


## Binary Search
  - Easy:
    - [69. Sqrt(x)](https://leetcode.com/problems/sqrtx/)
    - [704. Binary Search](https://leetcode.com/problems/binary-search/)
    - [35. Search Insert Position](https://leetcode.com/problems/search-insert-position/)
    - [349. Intersection of Two Arrays](https://leetcode.com/problems/intersection-of-two-arrays/)
    - [167. Two Sum II - Input Array Is Sorted](https://leetcode.com/problems/two-sum-ii-input-array-is-sorted/)
    - [278. First Bad Version](https://leetcode.com/problems/first-bad-version/)
  - Medium:
    - [300. Longest Increasing Subsequence](https://leetcode.com/problems/longest-increasing-subsequence/)
    - [74. Search a 2D Matrix](https://leetcode.com/problems/search-a-2d-matrix/)
    - [34. Find First and Last Position of Element in Sorted Array](https://leetcode.com/problems/find-first-and-last-position-of-element-in-sorted-array/)
    - [81. Search in Rotated Sorted Array II](https://leetcode.com/problems/search-in-rotated-sorted-array-ii/)
    - [33. Search in Rotated Sorted Array](https://leetcode.com/problems/search-in-rotated-sorted-array/)
    - [454. 4Sum II](https://leetcode.com/problems/4sum-ii/)
    - [240. Search a 2D Matrix II](https://leetcode.com/problems/search-a-2d-matrix-ii/)
    - [718. Maximum Length of Repeated Subarray](https://leetcode.com/problems/maximum-length-of-repeated-subarray/)
    - [50. Pow(x, n)](https://leetcode.com/problems/powx-n/)
    - [29. Divide Two Integers](https://leetcode.com/problems/divide-two-integers/)
    - [287. Find the Duplicate Number](https://leetcode.com/problems/find-the-duplicate-number/)
    - [209. Minimum Size Subarray Sum](https://leetcode.com/problems/minimum-size-subarray-sum/)
    - [153. Find Minimum in Rotated Sorted Array](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array/)
    - [162. Find Peak Element](https://leetcode.com/problems/find-peak-element/)
    - [378. Kth Smallest Element in a Sorted Matrix](https://leetcode.com/problems/kth-smallest-element-in-a-sorted-matrix/)
    - [230. Kth Smallest Element in a BST](https://leetcode.com/problems/kth-smallest-element-in-a-bst/)
  - Hard:
    - [4. Median of Two Sorted Arrays](https://leetcode.com/problems/median-of-two-sorted-arrays/)
    - [887.  Super Egg Drop](https://leetcode.com/problems/super-egg-drop/)
    - [410. Split Array Largest Sum](https://leetcode.com/problems/split-array-largest-sum/)
    - [154. Find Minimum in Rotated Sorted Array II](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array-ii/)

## Bitwise Operation
  - Easy:
    - [136. Single Number](https://leetcode.com/problems/single-number/)
    - [191. Number of 1 Bits](https://leetcode.com/problems/number-of-1-bits/)
    - [169. Majority Element](https://leetcode.com/problems/majority-element/)
    - [190. Reverse Bits](https://leetcode.com/problems/reverse-bits/)
    - [231. Power of Two](https://leetcode.com/problems/power-of-two/)
    - [389. Find the Difference](https://leetcode.com/problems/find-the-difference/)
    - [461. Hamming Distance](https://leetcode.com/problems/hamming-distance/)
    - [405. Convert a Number to Hexadecimal](https://leetcode.com/problems/convert-a-number-to-hexadecimal/)
    - [268. Missing Number](https://leetcode.com/problems/missing-number/)
  - Medium:
    - [78. Subsets](https://leetcode.com/problems/subsets/)
    - [338. Counting Bits](https://leetcode.com/problems/counting-bits/)
    - [1318. Minimum Flips to Make a OR b Equal to c](https://leetcode.com/problems/minimum-flips-to-make-a-or-b-equal-to-c/)
    - [89. Gray Code](https://leetcode.com/problems/gray-code/)
    - [260. Single Number III](https://leetcode.com/problems/single-number-iii/)
    - [371. Sum of Two Integers](https://leetcode.com/problems/sum-of-two-integers/)
    - [137. Single Number II](https://leetcode.com/problems/single-number-ii/)
    - [421. Maximum XOR of Two Numbers in an Array](https://leetcode.com/problems/maximum-xor-of-two-numbers-in-an-array/)

## Two-Pointer and Sliding Window
  - Easy:
    - [387.  First Unique Character in a String](https://leetcode.com/problems/first-unique-character-in-a-string/)
    - [349. Intersection of Two Arrays](https://leetcode.com/problems/intersection-of-two-arrays/)
    - [409. Longest Palindrome](https://leetcode.com/problems/longest-palindrome/)
    - [217. Contains Duplicate](https://leetcode.com/problems/contains-duplicate/)
    - [204. Count Primes](https://leetcode.com/problems/count-primes/)
    - [88. Merge Sorted Array](https://leetcode.com/problems/merge-sorted-array/)
    - [283. Move Zeroes](https://leetcode.com/problems/move-zeroes/)
    - [125. Valid Palindrome](https://leetcode.com/problems/valid-palindrome/)
    - [344. Reverse String](https://leetcode.com/problems/reverse-string/)
    - [27. Remove Element](https://leetcode.com/problems/remove-element/)
    - [977. Squares of a Sorted Array](https://leetcode.com/problems/squares-of-a-sorted-array/)
  - Medium:
    - [3. Longest Substring Without Repeating Characters](https://leetcode.com/problems/longest-substring-without-repeating-characters/)
    - [781. Rabbits in Forest](https://leetcode.com/problems/rabbits-in-forest/)
    - [49. Group Anagrams](https://leetcode.com/problems/group-anagrams/)
    - [18. 4Sum](https://leetcode.com/problems/4sum/)
    - [560. Subarray Sum Equals K](https://leetcode.com/problems/subarray-sum-equals-k/)
    - [454. 4Sum II](https://leetcode.com/problems/4sum-ii/)
    - [11. Container With Most Water](https://leetcode.com/problems/container-with-most-water/)
    - [16. 3Sum Closest](https://leetcode.com/problems/3sum-closest/)
    - [18. 4Sum](https://leetcode.com/problems/4sum/)
    - [424. Longest Repeating Character Replacement](https://leetcode.com/problems/longest-repeating-character-replacement/)
    - [713. Subarray Product Less Than K](https://leetcode.com/problems/subarray-product-less-than-k/)
  - Hard:
    - [76. Minimum Window Substring](https://leetcode.com/problems/minimum-window-substring/)
    - [992. Subarrays with K Different Integers](https://leetcode.com/problems/subarrays-with-k-different-integers/)

## Matrix
  - Easy:
    - [867. Transpose Matrix](https://leetcode.com/problems/transpose-matrix/)
    - [832. Flipping an Image](https://leetcode.com/problems/flipping-an-image/)
  - Medium:
    - [54. Spiral Matrix](https://leetcode.com/problems/spiral-matrix/)
    - [59. Spiral Matrix II](https://leetcode.com/problems/spiral-matrix-ii/)
    - [73. Set Matrix Zeroes](https://leetcode.com/problems/set-matrix-zeroes/)
    - [48. Rotate Image](https://leetcode.com/problems/rotate-image/)

## Dynamic Programming

- 1 Dimensional
  - Easy:
    - [70. Climbing Stairs](https://leetcode.com/problems/climbing-stairs/)
    - [53. Maximum Subarray](https://leetcode.com/problems/maximum-subarray/)
    - [121. Best Time to Buy and Sell Stock](https://leetcode.com/problems/best-time-to-buy-and-sell-stock/)
    - [746. Min Cost Climbing Stairs](https://leetcode.com/problems/min-cost-climbing-stairs/)
  - Medium:
    - [337. House Robber III](https://leetcode.com/problems/house-robber-iii/)
    - [322. Coin Change](https://leetcode.com/problems/coin-change/)
    - [300. Longest Increasing Subsequence](https://leetcode.com/problems/longest-increasing-subsequence/)
    - [139. Word Break](https://leetcode.com/problems/word-break/)
    - [152. Maximum Product Subarray](https://leetcode.com/problems/maximum-product-subarray/)
    - [338. Counting Bits](https://leetcode.com/problems/counting-bits/)
    - [309. Best Time to Buy and Sell Stock with Cooldown](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-with-cooldown/)
    - [264. Ugly Number II](https://leetcode.com/problems/ugly-number-ii/)
    - [279. Perfect Squares](https://leetcode.com/problems/perfect-squares/)
  - Hard:
    - [32. Longest Valid Parentheses](https://leetcode.com/problems/longest-valid-parentheses/)
    - [354. Russian Doll Envelopes](https://leetcode.com/problems/russian-doll-envelopes/)
    - [123. Best Time to Buy and Sell Stock III](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-iii/)

- 2 Dimensional
  - Medium:
    - [5. Longest Palindromic Substring](https://leetcode.com/problems/longest-palindromic-substring/)
    - [1143. Longest Common Subsequence](https://leetcode.com/problems/longest-common-subsequence/)
    - [131. Palindrome Partitioning](https://leetcode.com/problems/palindrome-partitioning/)
    - [62. Unique Paths](https://leetcode.com/problems/unique-paths/)
    - [64. Minimum Path Sum](https://leetcode.com/problems/minimum-path-sum/)
    - [221. Maximal Square](https://leetcode.com/problems/maximal-square/)
    - [416. Partition Equal Subset Sum](https://leetcode.com/problems/partition-equal-subset-sum/)
    - [718. Maximum Length of Repeated Subarray](https://leetcode.com/problems/maximum-length-of-repeated-subarray/)
    - [494. Target Sum](https://leetcode.com/problems/target-sum/)
  - Hard:
    - [10. Regular Expression Matching](https://leetcode.com/problems/regular-expression-matching/)
    - [72. Edit Distance](https://leetcode.com/problems/edit-distance/)
    - [887. Super Egg Drop](https://leetcode.com/problems/super-egg-drop/)
    - [132. Palindrome Partitioning II](https://leetcode.com/problems/palindrome-partitioning-ii/)
    - [44. Wildcard Matching](https://leetcode.com/problems/wildcard-matching/)
    - [410. Split Array Largest Sum](https://leetcode.com/problems/split-array-largest-sum/)

## Graph
- DFS
  - Medium:
    - [394. Decode String](https://leetcode.com/problems/decode-string/)
    - [721. Accounts Merge](https://leetcode.com/problems/accounts-merge/)
    - [547. Number of Provinces](https://leetcode.com/problems/number-of-provinces/)
    - [494. Target Sum](https://leetcode.com/problems/target-sum/)
    - [695. Max Area of Island](https://leetcode.com/problems/max-area-of-island/)
    - [130. Surrounded Regions](https://leetcode.com/problems/surrounded-regions/)
    - [1631. Path With Minimum Effort](https://leetcode.com/problems/path-with-minimum-effort/) 
    - [207. Course Schedule](https://leetcode.com/problems/course-schedule/)
    - [417. Pacific Atlantic Water Flow](https://leetcode.com/problems/pacific-atlantic-water-flow/)
  - Hard:
    - [679. 24 Game](https://leetcode.com/problems/24-game/)

- BFS
  - Easy:
    - [690. Employee Importance](https://leetcode.com/problems/employee-importance/)
  - Medium:
    - [279. Perfect Squares](https://leetcode.com/problems/perfect-squares/)
    - [130. Surrounded Regions](https://leetcode.com/problems/surrounded-regions/)
    - [1319. Number of Operations to Make Network Connected](https://leetcode.com/problems/number-of-operations-to-make-network-connected/)
    - [934. Shortest Bridge](https://leetcode.com/problems/shortest-bridge/)
    - [785. Is Graph Bipartite?](https://leetcode.com/problems/is-graph-bipartite/)
    - [994. Rotting Oranges](https://leetcode.com/problems/rotting-oranges/)
    - [752. Open the Lock](https://leetcode.com/problems/open-the-lock/)
    - [1162. As Far from Land as Possible](https://leetcode.com/problems/as-far-from-land-as-possible/)
    - [529. Minesweeper](https://leetcode.com/problems/minesweeper/)
  - Hard:
    - [815. Bus Routes](https://leetcode.com/problems/bus-routes/)
    - [127. Word Ladder](https://leetcode.com/problems/word-ladder/)
    - [1293. Shortest Path in a Grid with Obstacles Elimination](https://leetcode.com/problems/shortest-path-in-a-grid-with-obstacles-elimination/)
    - [773. Sliding Puzzle](https://leetcode.com/problems/sliding-puzzle/)
    - [827. Making A Large Island](https://leetcode.com/problems/making-a-large-island/)

- Dijkstra
  - Medium:
    - [787. Cheapest Flights Within K Stops](https://leetcode.com/problems/cheapest-flights-within-k-stops/)

- Topological Sort
  - Medium:
    - [207. Course Schedule](https://leetcode.com/problems/course-schedule/)
    - [210. Course Schedule II](https://leetcode.com/problems/course-schedule-ii/)
  - Hard:
    - [329. Longest Increasing Path in a Matrix](https://leetcode.com/problems/longest-increasing-path-in-a-matrix/)
    - [1203. Sort Items by Groups Respecting Dependencies](https://leetcode.com/problems/sort-items-by-groups-respecting-dependencies/)

## Disjoint Set
  - Medium:
    - [200. Number of Islands](https://leetcode.com/problems/number-of-islands/)
    - [721. Accounts Merge](https://leetcode.com/problems/accounts-merge/)
    - [547. Number of Provinces](https://leetcode.com/problems/number-of-provinces/)
    - [130. Surrounded Regions](https://leetcode.com/problems/surrounded-regions/)
    - [1631. Path With Minimum Effort](https://leetcode.com/problems/path-with-minimum-effort/)
    - [399. Evaluate Division](https://leetcode.com/problems/evaluate-division/)
    - [1319. Number of Operations to Make Network Connected](https://leetcode.com/problems/number-of-operations-to-make-network-connected/)
    - [684. Redundant Connection](https://leetcode.com/problems/redundant-connection/)
  - Hard:
    - [128. Longest Consecutive Sequence](https://leetcode.com/problems/longest-consecutive-sequence/)
    - [765. Couples Holding Hands](https://leetcode.com/problems/couples-holding-hands/)

## Design
  - Easy:
    - [1603. Design Parking System](https://leetcode.com/problems/design-parking-system/)
    - [705. Design HashSet](https://leetcode.com/problems/design-hashset/)
    - [706. Design HashMap](https://leetcode.com/problems/design-hashmap/)
    - [703. Kth Largest Element in a Stream](https://leetcode.com/problems/kth-largest-element-in-a-stream/)
  - Medium:
    - [146. LRU Cache](https://leetcode.com/problems/lru-cache/)
    - [341. Flatten Nested List Iterator](https://leetcode.com/problems/flatten-nested-list-iterator/)
    - [208. Implement Trie (Prefix Tree)](https://leetcode.com/problems/implement-trie-prefix-tree/)
    - [173. Binary Search Tree Iterator](https://leetcode.com/problems/binary-search-tree-iterator/)
    - [622. Design Circular Queue](https://leetcode.com/problems/design-circular-queue/)
    - [380. Insert Delete GetRandom O(1)](https://leetcode.com/problems/insert-delete-getrandom-o1/)
  - Hard:
    - [295. Find Median from Data Stream](https://leetcode.com/problems/find-median-from-data-stream/)
    - [460. LFU Cache](https://leetcode.com/problems/lfu-cache/)
  
## Greedy
- Medium:
  - [264. Ugly Number II](https://leetcode.com/problems/ugly-number-ii/)
  - [946. Validate Stack Sequences](https://leetcode.com/problems/validate-stack-sequences/)
  - [767. Reorganize String](https://leetcode.com/problems/reorganize-string/)
  - [373. Find K Pairs with Smallest Sums](https://leetcode.com/problems/find-k-pairs-with-smallest-sums/)
  - [313. Super Ugly Number](https://leetcode.com/problems/super-ugly-number/)


## Backtracking
  - Medium:
    - [46. Permutations](https://leetcode.com/problems/permutations/)
    - [22. Generate Parentheses](https://leetcode.com/problems/generate-parentheses/)
    - [93. Restore IP Addresses](https://leetcode.com/problems/restore-ip-addresses/)
    - [78. Subsets](https://leetcode.com/problems/subsets/)
    - [17. Letter Combinations of a Phone Number](https://leetcode.com/problems/letter-combinations-of-a-phone-number/)
    - [79. Word Search](https://leetcode.com/problems/word-search/)
    - [90. Subsets II](https://leetcode.com/problems/subsets-ii/)
    - [39. Combination Sum](https://leetcode.com/problems/combination-sum/)
    - [77. Combinations](https://leetcode.com/problems/combinations/)
    - [40. Combination Sum II](https://leetcode.com/problems/combination-sum-ii/)
    - [47. Permutations II](https://leetcode.com/problems/permutations-ii/)
    - [842. Split Array into Fibonacci Sequence](https://leetcode.com/problems/split-array-into-fibonacci-sequence/)
    - [216. Combination Sum III](https://leetcode.com/problems/combination-sum-iii/)
    - [89. Gray Code](https://leetcode.com/problems/gray-code/)
  - Hard:
    - [51. N-Queens](https://leetcode.com/problems/n-queens/)
    - [37. Sudoku Solver](https://leetcode.com/problems/sudoku-solver/)
    - [126. Word Ladder II](https://leetcode.com/problems/word-ladder-ii/)
    - [1659. Maximize Grid Happiness](https://leetcode.com/problems/maximize-grid-happiness/)

## Clone
- Medium:
  - [133. Clone Graph](https://leetcode.com/problems/clone-graph/)
  - [138. Copy List with Random Pointer](https://leetcode.com/problems/copy-list-with-random-pointer/)

## Math
  - Easy:
    - [204. Count Primes](https://leetcode.com/problems/count-primes/)
    - [628. Maximum Product of Three Numbers](https://leetcode.com/problems/maximum-product-of-three-numbers/)
    - [976. Largest Perimeter Triangle](https://leetcode.com/problems/largest-perimeter-triangle/)
    - [202. Happy Number](https://leetcode.com/problems/happy-number/)
    - [1232. Check If It Is a Straight Line](https://leetcode.com/problems/check-if-it-is-a-straight-line/)
  - Medium:
    - [29. Divide Two Integers](https://leetcode.com/problems/divide-two-integers/)
    - [343. Integer Break](https://leetcode.com/problems/integer-break/)
    - [166. Fraction to Recurring Decimal](https://leetcode.com/problems/fraction-to-recurring-decimal/)
  - Hard:
    - [149. Max Points on a Line](https://leetcode.com/problems/max-points-on-a-line/)


## Minimax
  - Easy:
    - [292. Nim Game](https://leetcode.com/problems/nim-game/)
  - Medium:
    - [375. Guess Number Higher or Lower II](https://leetcode.com/problems/guess-number-higher-or-lower-ii/)
    - [486. Predict the Winner](https://leetcode.com/problems/predict-the-winner/)
    - [464. Can I Win](https://leetcode.com/problems/can-i-win/)
    - [877. Stone Game](https://leetcode.com/problems/stone-game/)

## Geometry
  - Easy:
    - [1232. Check If It Is a Straight Line](https://leetcode.com/problems/check-if-it-is-a-straight-line/)
    - [1266. Minimum Time Visiting All Points](https://leetcode.com/problems/minimum-time-visiting-all-points/)
    - [892. Surface Area of 3D Shapes](https://leetcode.com/problems/surface-area-of-3d-shapes/)
  - Medium:
    - [1401. Circle and Rectangle Overlapping](https://leetcode.com/problems/circle-and-rectangle-overlapping/)
    - [963. Minimum Area Rectangle II](https://leetcode.com/problems/minimum-area-rectangle-ii/)
  - Hard:
    - [587. Erect the Fence](https://leetcode.com/problems/erect-the-fence/)
    - [1515. Best Position for a Service Centre](https://leetcode.com/problems/best-position-for-a-service-centre/)