# AdType Coding Challenges


1. Write a function called isUnique that returns whether a string has any repeated characters.

    E.g. "hello" would return false, since there are repeated characters, "monkey" would return true since all characters are  unique.

2. Given two strings, write a program that efficiently finds the longest common subsequence

3. In this exercise you have to analyze records of temperature to find the closest to zero. Implement the function closestToZero to return the temperature closer to zero which belongs to the array ts.

```javascript
function closestToZero(ts) {
    // Your code goes here
}
```

#### Input

* Temperatures are always expressed with floating point numbers ranging from -273 to 5526.
* ts is always a valid array and is never null


#### Output
* If ts is empty return 0 (zero)
* If two numbers are as close to zero, consider the positive number as the closest to zero (eg. if ts contains -5 and 5, return 5)

```javascript
// Update this test case to check your solution works 
// in all cases.
var ts = [7,-10,13,8,4,-7.2,-12,-3.7,3.5,-9.6,6.5,-1.7,-6.2,7];

var result = closestToZero(ts);

print(result); // -1.7
```
