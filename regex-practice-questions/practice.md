
### **Type 1: Explanation**  
1. What does the expression `"cat, bat, rat".match(/b\w+/)` do?  
```javascript
"cat, bat, rat".match(/b\w+/);
```
<span style="color:green">&nbsp;&nbsp;&nbsp;&nbsp;["bat"]</span> 

2. What will `"123-456-7890".match(/\d{3}/)` return?  
```javascript
"123-456-7890".match(/\d{3}/);
```
<span style="color:green">&nbsp;&nbsp;&nbsp;&nbsp;["123"]</span> 

3. What does `"hello\nworld".match(/.\n./)` return?  
```javascript
"hello\nworld".match(/.\n./);
```
<span style="color:green">&nbsp;&nbsp;&nbsp;&nbsp;["o\nw"]</span> 

4. What will `"name@example.com".match(/\w+@\w+\.\w+/)` return? 
<span style="color:red">#regex for standard valid email</span> 

```javascript
"name@example.com".match(/\w+@\w+\.\w+/) // Returns ["name@example.com"]
```
<span style="color:green">&nbsp;&nbsp;&nbsp;&nbsp;["name@example.com"]</span> 

5. What does `"file.txt".match(/\.txt/)` do?  
```javascript
"file.txt".match(/\.txt/); // Returns [".txt"]
```
<span style="color:green">&nbsp;&nbsp;&nbsp;&nbsp;[".txt"]</span> 

6. What does `"red green blue".match(/green/)` do?  
```javascript
"red green blue".match(/green/);
```
<span style="color:green">&nbsp;&nbsp;&nbsp;&nbsp;["green"]</span> 

7. What will `"abcdef".match(/[a-c]/)` return?  
```javascript
"abcdef".match(/[a-c]/);
```
<span style="color:green">&nbsp;&nbsp;&nbsp;&nbsp;["a"]</span> 

8. What does `"The quick brown fox".match(/q.+?k/)` return?  
```javascript
"The quick brown fox".match(/q.+?k/);
```
<span style="color:green">&nbsp;&nbsp;&nbsp;&nbsp;["quick"]</span> 

9.  What does `"apple".match(/a[a-z]+/)` return?  
```javascript
"apple".match(/a[a-z]+/);
```
<span style="color:green">&nbsp;&nbsp;&nbsp;&nbsp;["apple"]</span> 

10. What will `"a1b2c3".match(/\d+/)` return?  
```javascript
"a1b2c3".match(/\d+/)
```
<span style="color:green">&nbsp;&nbsp;&nbsp;&nbsp;["1"]</span> 

11. What does `"good food mood".match(/o+o/)` do?  
```javascript
"good food mood".match(/o+o/);
```
<span style="color:green">&nbsp;&nbsp;&nbsp;&nbsp;[""]</span> 

12. What does `"@username".match(/@\w+/)` return?  
```javascript
"@username".match(/@\w+/);
```
<span style="color:green">&nbsp;&nbsp;&nbsp;&nbsp;[""]</span> 

1.  What does `"path/to/file".match(/\/to\//)` do?  
```javascript

```
<span style="color:green">&nbsp;&nbsp;&nbsp;&nbsp;[""]</span> 

14. What does `"1.23".match(/\d\.\d+/)` return?  
```javascript

```
<span style="color:green">&nbsp;&nbsp;&nbsp;&nbsp;[""]</span> 

15. What will `"AB123CD".match(/[A-Z]+\d+/)` return?  
```javascript

```
<span style="color:green">&nbsp;&nbsp;&nbsp;&nbsp;[""]</span> 

16. What does `"hello_world".match(/\w+_\w+/)` return? 
```javascript

```
<span style="color:green">&nbsp;&nbsp;&nbsp;&nbsp;[""]</span> 

17. What does `"123abc456".match(/\d{3}/)` return?  
```javascript

```
<span style="color:green">&nbsp;&nbsp;&nbsp;&nbsp;[""]</span> 

18. What does `"My name is John".match(/name\s\w+/)` return? 
```javascript

```
<span style="color:green">&nbsp;&nbsp;&nbsp;&nbsp;[""]</span> 

19. What will `"https://example.com".match(/https?:\/\/\w+\.\w+/)` return? 
```javascript

```
<span style="color:green">&nbsp;&nbsp;&nbsp;&nbsp;[""]</span> 

20. What does `"abcdEFGH".match(/[A-Z]+/)` return?  
```javascript

```
<span style="color:green">&nbsp;&nbsp;&nbsp;&nbsp;[""]</span> 

21. What does `"abc123".match(/(\w)(\d)/)` return?  
```javascript

```
<span style="color:green">&nbsp;&nbsp;&nbsp;&nbsp;[""]</span> 

22. What will `"hello world".match(/(\w+)\s(\w+)/)` 
```javascript

```
<span style="color:green">&nbsp;&nbsp;&nbsp;&nbsp;[""]</span> 

23. What does `"1234".match(/\d{2,3}/)` 
```javascript

```
<span style="color:green">&nbsp;&nbsp;&nbsp;&nbsp;[""]</span> 

24. What will `"aaaabbb".match(/a{2,}/)` 
```javascript

```
<span style="color:green">&nbsp;&nbsp;&nbsp;&nbsp;[""]</span> 

25. What does `"hello".match(/[aeiou]{2}/)` 
```javascript

```
<span style="color:green">&nbsp;&nbsp;&nbsp;&nbsp;[""]</span> 

26. What does `"ABCD1234".match(/[A-Z]+\d+/)` 
```javascript

```
<span style="color:green">&nbsp;&nbsp;&nbsp;&nbsp;[""]</span> 

27. What does `"file_name.ext".match(/(\w+)\.(\w+)/)` 
```javascript

```
<span style="color:green">&nbsp;&nbsp;&nbsp;&nbsp;[""]</span> 

28. What does `"Mississippi".match(/s{2,}/)` 
```javascript

```
<span style="color:green">&nbsp;&nbsp;&nbsp;&nbsp;[""]</span> 

29. What will `"hello world".match(/(\w)(?=\s\w)/)` 
```javascript

```
<span style="color:green">&nbsp;&nbsp;&nbsp;&nbsp;[""]</span> 

30. What does `"2025-01-01".match(/\d{4}-(\d{2})-(\d{2})/)[2]` 
```javascript

```
<span style="color:green">&nbsp;&nbsp;&nbsp;&nbsp;[""]</span> 

31. What does `"abc123".match(/(\d+)(\w+)/)` 
```javascript

```
<span style="color:green">&nbsp;&nbsp;&nbsp;&nbsp;[""]</span> 

32. What does `"hello123".match(/\D+/)` 
```javascript

```
<span style="color:green">&nbsp;&nbsp;&nbsp;&nbsp;[""]</span> 

33. What will `"yes no maybe".match(/(\w+)\s(\w+)\s(\w+)/)` 
```javascript

```
<span style="color:green">&nbsp;&nbsp;&nbsp;&nbsp;[""]</span> 

34. What does `"color: #123456".match(/#[0-9a-fA-F]{6}/)` 
```javascript

```
<span style="color:green">&nbsp;&nbsp;&nbsp;&nbsp;[""]</span> 

35. What does `"aaa111bbb222".match(/([a-z]+)(\d+)/)` 
```javascript

```
<span style="color:green">&nbsp;&nbsp;&nbsp;&nbsp;[""]</span> 

36. What will `"1,234.56".match(/\d{1,3}(,\d{3})*\.\d{2}/)` 
```javascript

```
<span style="color:green">&nbsp;&nbsp;&nbsp;&nbsp;[""]</span> 

37. What does `"aabbcc".match(/a(b{2})c/)` 
```javascript

```
<span style="color:green">&nbsp;&nbsp;&nbsp;&nbsp;[""]</span> 

38. What does `"xyzz".match(/x(y(z))/)` 
```javascript

```
<span style="color:green">&nbsp;&nbsp;&nbsp;&nbsp;[""]</span> 

39. What does `"abab".match(/(ab)\1/)` 
```javascript

```
<span style="color:green">&nbsp;&nbsp;&nbsp;&nbsp;[""]</span> 

40. What will `"abc123abc".match(/(abc)\d+\1/)` 
```javascript

```
<span style="color:green">&nbsp;&nbsp;&nbsp;&nbsp;[""]</span> 


---

### **Type 2: Task**  
1. Match any string that contains a number.  
2. Find all lowercase letters in a string.  
3. Match a string that ends with "ed".  
4. Match the word "yes" in a string.  
5. Find any two consecutive vowels in a string.  
6. Match any string containing the word "hello".  
7. Find a string that contains exactly two spaces.  
8. Find a string that starts with "abc".  
9. Match any string that contains the digit `7`.  
10. Find all occurrences of the letter `e`.  
11. Match a string that has at least one uppercase letter.  
12. Find a string with a period (`.`) in it.  
13. Match a string that contains a single space.  
14. Match all words that start with the letter `c`.  
15. Match a string that contains the sequence "123".  
16. Match a string that contains a forward slash (`/`).  
17. Find all strings that contain "and".  
18. Match a string that starts and ends with the same letter.  
19. Match all lowercase letters except "x" and "y".  
20. Find all words in a string that are exactly 5 letters long.  
21. Match all words starting with a vowel.  
22. Find all sequences of two or more consecutive digits.  
23. Match all words that contain exactly three letters.  
24. Find all occurrences of the word "cat" or "dog".  
25. Capture the first and last name from a string like `"John Doe"`.  
26. Match strings with repeating characters (e.g., `"aa"`, `"bb"`).  
27. Extract all the hashtags from a tweet.  
28. Validate a 24-hour time format like `"23:59"`.  
29. Capture the area code and phone number from `(123) 456-7890`.  
30. Find sequences of whitespace followed by a word.  
31. Match strings containing at least one uppercase and one digit.  
32. Find all non-alphanumeric characters in a string.  
33. Match email addresses.  
34. Validate dates in the format `YYYY-MM-DD`.  
35. Extract the filename and extension from a path like `/path/to/file.txt`.  
36. Find all duplicate words in a sentence.  
37. Match words that do not contain the letter "e".  
38. Extract the domain name from a URL like `https://www.example.com`.  
39. Match strings containing three consecutive vowels.  
40. Find all 4-letter palindromes in a string.  
