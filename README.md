# Crack-LeetCode-With-Python
Use the native Python to crack the Leet Code. 

魔法击败魔法 雷霆击碎黑暗 -_-! 

## Arrays and Hashing

In order to count the elements from the array, list. We can use the Counter class or Default Dict class. 

For example:

242. Valid Anagram

We are given 2 strings and to decide if they are anagrams or not. By converting these 2 strings into Counter Objects, we can easily compare if they are the same or not. 

Link to LeetCode: [242 Valid Anagram](https://leetcode.com/problems/valid-anagram/description/)

Link to Counter in Python: [Counter](https://leetcode.com/problems/valid-anagram/description/)

217. Contains Duplicate (User Set or Counter)

Given an integer array nums, return true if any value appears at least twice in the array, and return false if every element is distinct.

We can use set() to check if the list size has been reduced or use the Counter() to count if there are duplicate elements.

Link to LeetCode: [217. Contains Duplicate](https://leetcode.com/problems/contains-duplicate/description/)

49. Group Anagrams (Use Tuple as the key of a dictionary and use dictionary comprehension)

Link to LeetCode: [49. Group Anagrams](https://leetcode.com/problems/group-anagrams/description/)

Link to Convert Python Key-Value Pair to Tuple [Convert key-value pair to typle](https://stackoverflow.com/questions/1600591/using-a-python-dictionary-as-a-key-non-nested)

Conclusion: For all the Anagram questions, we use sort or count to hack it! 

347. Top K Frequent Elements 老题新做

Link to LeetCode: (347. Top K Frequent)[https://leetcode.com/problems/top-k-frequent-elements/description/]

Use Counters and most_common API to hack it! 

Use max heap. 

Use bucket sort. -> Key is the number of appearances, and value is the number.

![image](https://github.com/ZehuaWang/Crack-LeetCode-With-Python/assets/40006814/9bbd6ebb-278d-415b-a04c-0de1fb14ae53)

238. Product of Array Except for Self

Link to LeetCode: (238. Product of Array Except for Self)[https://leetcode.com/problems/product-of-array-except-self/description/]

Use itertools to generate the pre-fix and post-fix array. 

![image](https://github.com/ZehuaWang/Crack-LeetCode-With-Python/assets/40006814/74195838-5fb0-4eaf-b8c1-e422cb14882b)



