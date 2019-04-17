## String Chains
Given an array of words representing your dictionary, you test each word to see
if it can be made into another word in the dictionary.
This will be done by removing characters one at a time.

Each word represents its own first element of its string chain, so start with a chain length of 1.
Each time you remove a character, increment your string chain by 1.

In order to remove a character, the resulting word must be in your original dictionary.
Your goal is to determine the longest string chain achievable for a given dictionary.

For example, dictionary: [a, and, an, bear]. The word 'and' could be reduced to 'an' and then to 'a'.
The single character 'a' cannot be reduced any further as the null string is not in the dictionary.

This will be the longest string chain, having a length 3.

Complete the 'longestChain' function below.

The function is expected to return an integer.  
The function accepts string_array words as parameter.

```
public static int longestChain(List<String> words){
  // write your code here
}
```
