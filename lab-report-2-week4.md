# Lab Report Week 4

## Code Change 1 (Missing a ")" at end of link)
Screenshot of Code change:
![Image](codechanges.png)

Link to failure inducing input 1: [Here](https://github.com/khottinger/markdown-parse/commit/49ff87ac817fb5e9f07909e61cb209abef258ac6)

Symptom vs Expected Result:
![Image](symptom1.png)

**Lets Discuss** :
Our first file we used to break our program was edited by removing a closed Parenthesis, this ended up being a failure-inducing input
because it caused a bug to execute. Our program ran perfectly fine before we removed a parenthesis. When that edit was made the symptom
showed up and we saw our program was including a part of the link it shouldn't. As a lab group we worked together and added lots of if-then 
conditions to ensure our program was only collecting the information we needed that was in parenthesis. By examining the wrong output we recieved(symptom), 
we saw that we needed to alter our program to handle the bug without changing our test file. After lots of attempts... we got the correct output!



## Code Change 2 (Blank line followed by random text)
Screenshot of Code change:
![Image](codechange3.png)

Link to failure inducing input 2: [Here](https://github.com/khottinger/markdown-parse/blob/main/test-file2.md)

Symptom vs Expected Result:
![Image](symptom2.png)

**Lets Discuss**



## Code Change 3 (Blank line followed by empty () and then random text)
Screenshot of Code change(edits made @ same time as code change 1:
![Image](codechanges.png)

Link to failure inducing input 3: [Here](https://github.com/khottinger/markdown-parse/blob/main/test-file3.md)

Symptom vs Expected Result:
![Image](symptom3.png)

**Lets Discuss**

