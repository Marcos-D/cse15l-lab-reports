## Week 8 Lab Report
---
### [Link to my Markdown Repository](https://github.com/Marcos-D/CSE15L-Platypus)

### Code Snippet 1  
1. Test:    
    ![my_snip2Test](/pictures4/my_snip1Test.PNG)
2. Output:
    ![my_snip2Out](/pictures4/my_snip1Out.PNG)
3. Can it be fixed in > 10 lines?
    - Most likely, especially because Java really doesn't care about white space. Matter is we could condense the entire class into one very very ugly one line. In all seriousness, a couple conditionals to check for these edge cases could work.

### Code Snippet 2
1. Test:
    ![my_snip2Test](/pictures4/my_snip2Test.PNG)
2. Output:
    ![my_snip2Out](/pictures4/my_snip2Out.PNG)
3. Can it be fixed in > 10 lines?
    - Definitely! We could write a loop to check that our () are always matched. 

### Code Snippet 3
1. Test:
    ![my_snip1Test](/pictures4/my_snip3Test.PNG)
2. Output:
    ![my_snip1Out](/pictures4/my_snip3Out.PNG)
3. Can it be fixed in > 10 lines?
    - This one is a bit harder to fix than just a couple conditionals, I think the smartest approach for this one would be to check if a closing ) comes before a valid url extension (.com, .org, etc.)

---
### [Link to Reviewed Markdown Repository](https://github.com/Marcos-D/CSE15L-Platypus)

### Code Snippet 1
1. Test:
    ![my_snip1Test](/pictures4/my_snip1Test.PNG)
2. Output:
    ![reviewed_snip1Out](/pictures4/reviewed_snip1Out.PNG)
3. Can it be fixed in > 10 lines?
    - A couple conditionals should do the trick. This test was designed for very weird edge cases the reviewed may not cover.

### Code Snippet 2
1. Test:
    ![my_snip1Test](/pictures4/my_snip2Test.PNG)
2. Output:
    ![reviewed_snip1Out](/pictures4/reviewed_snip2Out.PNG)
3. Can it be fixed in > 10 lines?
    This one performed as expected! Yay!

### Code Snippet 3
1. Test:
    ![my_snip1Test](/pictures4/my_snip3Test.PNG)
2. Output:
    ![reviewed_snip1Out](/pictures4/reviewed_snip3Out.PNG)
3. Can it be fixed in > 10 lines?
    - Don't see why it can't be fixed in under 10 lines! But the issue arrises from an out of bounds error, most likely something in the code is extending to far out from an opening character.