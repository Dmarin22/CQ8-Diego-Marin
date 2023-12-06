# CQ8-Diego-Marin

Staircase

Time Complexity:

There are two nested for loops each running up to n times because of this the time complexity is O(n^2)

Space Complexity:

The space complexity is O(1) because the solutions uses constant time no matter the input size since it only uses one variable


Alternating Characters

Recursion:

Base Case: If the string s has a length of 1 or less, the function returns 0. This is because no characters need to be removed to make it alternating.

Recursive Calls:

If the first two characters of s are the same, it increments the count (adds 1) and makes a recursive call with the substring starting from the second character.
If they are different, it makes a recursive call without incrementing the count, again with the substring starting from the second character.


Time Complexity:

The function processes each character of the string once making it O(n)

Space Complexity:

O(n) This is due to the space used by the call stack for each recursive call. In the worst case, there could be as many recursive calls as there are characters in the string.
