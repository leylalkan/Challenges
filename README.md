# Challenges
## Equivalent Keypresses:
Write a function that takes an array containing two strings where each string represents keypresses separated by commas. For this problem, a keypress can be either a printable character or a backspace (represented by -B). Your function should determine if the two strings of keypresses are equivalent. You can produce a printable string from such a string of keypresses by having backspaces erase one preceding character. 
Consider two strings of keypresses equivalent if they produce the same printable string. For example:  
```
checkEquivalentKeypresses(["a,b,c,d", "a,b,c,c,-B,d"]) // true  
checkEquivalentKeypresses(["-B,-B,-B,c,c", "c,c"]) // true  
checkEquivalentKeypresses(["", "a,-B,-B,a,-B,a,b,c,c,c,d"]) // false
```

## Different Cases:
Have the function DifferentCases(str) take the str parameter being passed and return it in upper camel case format where the first letter of each word is capitalized. The string will only contain letters and some combination of delimiter punctuation characters separating each word. 
For example: if str is `“Daniel LikeS-coding”` then your program should return the string `DanielLikesCoding`.
