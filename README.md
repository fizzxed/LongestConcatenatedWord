# LongestConcatenatedWord
The challenge:
Write a program that reads a file containing a alphabetically sorted list of words (one word per line, no spaces, all lower case) and:
1. Find the longest word in the file that can be constructed concatenating copies of shorter words also found in the file.
2. Also report the second longest word found
3. Also give the words that can be concatenated together to create the larger word
4. Also report the total count of words that can be constructed of other words in the file.

For example, if the input file is: 
```
cat
cats
catsdogcats
catxdogcatsrat
dog
dogcatsdog
hippopotamuses
rat
ratcat
ratcatdog
ratcatdogcat
```
We should get:
```
Longest compound word found is: 	"ratcatdogcat"
Concatenated from 4 words: ['rat', 'cat', 'dog', 'cat']
Second Longest compound word found is: 	"catsdogcats"
Concatenated from 3 words: ['cats', 'dog', 'cats']
Number of compound words is 5
```
___
## Running the code
To run the code you must supply an input file. There are two input files provided.
```
python concatwords.py words.txt
```
Output:
```
Longest compound word found is: 	"ethylenediaminetetraacetates"
Concatenated from 6 words: ['ethylene', 'diamine', 'tetra', 'ace', 'tat', 'es']
Second Longest compound word found is: 	"electroencephalographically"
Concatenated from 7 words: ['electro', 'en', 'cep', 'ha', 'lo', 'graphic', 'ally']
Number of compound words is 97107
```
Credits:

words.txt taken from here: [Here](https://github.com/davidkbainbridge/compound-words)

Problem description parts and some code inspiration taken from [Here](https://medium.com/@jessgreb01/longest-concatenated-word-algorithm-34934b864e3e#.apofgxqn9) and [There](http://www.ardendertat.com/2012/06/15/programming-interview-questions-28-longest-compound-word/)


