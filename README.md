# question-no-2942
Solution to the question no 2942 on leet code 

2942. Find Words Containing Character
You are given a 0-indexed array of strings words and a character x.

Return an array of indices representing the words that contain the character x.

Note that the returned array may be in any order.

Explanation:
It creates an empty list res to store the result.

Then, it loops through each word in the words array.

For each word, it checks if the character x exists using indexOf(x).

If x is found (i.e., indexOf(x) != -1), it adds the index i to the result list.

Finally, it returns the list of indices.
