# Anagram-list
Anagrams are have same charachters with the same length in different forms.In python program from given list to form groups of each anagram words after eliminate duplicate words from the given list we can print by using function, in that function join method and sorted method also used.this code is efficient and simple.
## Usage:
* Anagram grouping can be useful in various scenarios,including:Wordgames,Cryptography,Dictionary Organisation.....etc.
## Quetion:
Write a function that takes tha list of words as input and returns a list of sets,where each set contains words that are anagrams of each other.
## input:
* A list of string,where each string represents a word.
* The lenght of the list is n(1<=n<=10^4),and the maximum length of each word is m(1<=m<=100)
## output:
A list of sets,where each set contains words that are anagrams of each other.
## Note:
* The order of the sets and the order of words within each set do not matter.
* The input list may contain duplicate words,but the output should only contain distinct sets of anagrams.
[Python code](https://youtu.be/r0ID3LGpOUs)
## Example1 :
```python
length of list("n"):5
words("str"):
cat
dog
tac
god
act
Output:
[["cat","tac","act"],["dog","god"]]
```
## Example 2:
```python
length of list:6
words("str"):
cat
dog
cat
tac
god
act
Output:
[["cat","tac","act"],["dog","god"]]
```
