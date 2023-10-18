# The Is palindrome function is used to check if words when reversed will give you the same exact input that was used.

This program checks whether a given word is a palindrome or not.

## Description
 1. Check if the length of the word is 0 or 1. If true, return "is Palindrome".
2. Check if the first and last characters of the word are the same.
   - If true, create a new word without the first and last characters.
   - Recur with the new word (without the first and last characters) until there's 1 or 0 character left.
   - Return the result of the recursion.
3. If the first and last characters are not the same, return "is not Palindrome".
#### Input
- `Word: STRING` - The word to be checked for palindrome.

#### Output
- `STRING` - Returns "is Palindrome" if the input word is a palindrome; otherwise, returns "is not Palindrome".

## Usage

1. Define a word as a string.
2. Call the `IsPalindrome` function with the word as an argument.
3. Display the result.

### examples:
    IsPalindrome("pop")= "is Palindrome" 
    IsPalindrome("lol")= "is Palindrome" 
    IsPalindrome("play")= "is not Palindrome" 
    IsPalindrome("")= "is Palindrome" 
   #### In our work the for loop was used to move variable "word" into "new word" without the first and last characters.