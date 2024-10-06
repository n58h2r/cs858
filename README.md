java c2024/10/3 17:19
Assignment 3: Hashtable
Assignment 3: Hashtable
Start Assignment
Due No Due Date Points 100
Submitting a file upload
Language: Java or Python or C++
Task Description: Complete the following task.
Task-1: Implement a Hash data structure from scratch. You can’t use built-in Hash or Dictionary APIs. You can use a built-in Array or List or your custom-built LinkedList. The Hash class must have the following functions and fields -
HashTable: A fixed-size array or list. Depending on your hash function, this array or list can be one-dimensional or two-dimensional.
hash(x): A hash function that converts a string x to an integer, i.e., index in the hashtable. You can implement any hash function described in the textbook. Your hash function must have a collision-resolution mechanism.
insert(x): Insert string x to the HashTable in the index returned by hash(x). size(): Returns the size of the elements, i.e., the number of keys.
Write sample test cases to validate your implementation.
Task-2: Read and parse each word from the file pride-and-prejudice.txt (https://canvas.eee.uci.edu/courses/68108/files/28223336?wrap=1) (https://canvas.eee.uci.edu/courses/68108/files/28223336/download?download_frd=1) . Note that this file is very large; therefore, reading the text at once will crash your program. You should read the text line by line. To split a line into words, you can consider anything other than alpha-numeric (i.e. [a-zA-Z0-9]) characters as delimiters, for example, ‘\n’, ‘\t’, ‘,’, ‘.’ etc.
An Anagram is a word or phrase formed by rearranging the letters of a different word or phrase, typically using all the original letters exactly once. For example, `mango` and `gonma` are anagrams containing the same characters. Write a function that would find out how many unique anagram-root words are there in the novel. An anagram-root word is a word that is derived by sorting the word by characters. For example, `mango`’s anagram root is `agmno`.
To find the number of unique anagram roots, do the following steps.
        https://canvas.eee.uci.edu/courses/68108/assignments/1469054?module_item_id=2923739 1/3

2024/10/3 17:19 Assignment代 写C++、python/Java
代做程序编程语言 3: Hashtable
Step-1: While you parse each word from the file, sort the words by character. You can use any built-in sorting API.
Step-2: Insert the sorted words in the hashtable you implemented above. If the word is already present in the hashtable, then skip it.
Step-3: Once all the words have been sorted and inserted (or skipped), call the size() function of the Hash class.
Note: You have to implement the classes from scratch. Please don’t engage in plagiarism in any manner. See UCI’s policy on academic integrity (https://aisc.uci.edu/students/academic- integrity/promote-integrity.php (https://aisc.uci.edu/students/academic-integrity/promote-integrity.php) ). Taking help from online materials is okay, but if you have taken any help online, please link the sources in the comment inside the code.
SWE-240P-Rubric
      https://canvas.eee.uci.edu/courses/68108/assignments/1469054?module_item_id=2923739 2/3

2024/10/3 17:19 Assignment 3: Hashtable
    Criteria Ratings Pts
   Code Quality and Structure
-- Does the code have meaningful variable/method names
-- Does the code contain comments where necessary? -- Is the code organized and structured?
-- Is the code properly formatted/indented?
 20 pts Excellent
  18 pts Good
16 pts Satisfactory
 0 pts No Marks
   20 pts
  Functionality and Correctness
-- Does the code run without any compilation errors -- Does the implementation handle edge cases?
-- Does the code pass sample test cases?
-- Does the code pass new test cases?
  30 pts Excellent
  27 pts Good
24 pts Satisfactory
 0 pts No Marks
   30 pts
  Presentation (Demo)
-- How well does the student explain the implemented approach?
-- How well does the student walk through the implementation?
-- How well does the student explain the trade-off (e.g., time, space complexity)?
-- How well does the student answer any relevant questions?
  50 pts Excellent
  45 pts Good
40 pts Satisfactory
 0 pts No Marks
  50 pts
    Total Points: 100
   https://canvas.eee.uci.edu/courses/68108/assignments/1469054?module_item_id=2923739
3/3


         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
