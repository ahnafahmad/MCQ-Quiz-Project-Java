# Quiz project on MCQ Exam Java JSON Project

## Language
- Java

## Data Format
- JSON

## Project Scenerio
- This is a java quiz game created by integrating json-simple in java using JSON manipulation techniques. <br>
- Admin can create a **Question Bank** by adding mcq type questions and add relevant question options.  <br />
- A random user can attend the **Quiz Exam** by answering the maximum 5 questions from that **Question Bank** which is generate randomly.

## Program output:
 ```
1. Add Quiz
2. Start Quiz

 ```
 ### What can the Project look like 
 - Here the Admin's part,
 if user select option 1, then system will tell user to input a question, 4 options and correct ans to save data in a quiz bank. The quiz bank will be a json file. 
 For  an example,
  ```
System>Please add a ques here:

User>Which testing is done by developer?
System>Input options.

Option a:
Admin> Unit Testing

Option b:
Admin> Integration Testing

Option c:
Admin> Sanity Testing

Option d:
Admin> Regression Testing

System> Please input the correct ans
Admin> a

System: Quiz saved at the database. Do you want to add more? (y/n)
if user press y, then the previous scenario will happen again otherwise the program will be closed.

 ```
 
 - Here the User's part
   If user select option 2,  then,
 ```
System> You will be asked 5 questions, each questions has 1 marks
1. Which testing is done by developer?
a. Unit Testing
b. Integration Testing
c. Sanity Testing
d. Regression Testing
User> a
System> Correct!
else not correct,
System: Not correct

 ```
 
 ## Data Format Sample
- Finally 5 different random questions will appear from your question database. At least add 15 questions from any category from testing.
 ```
Result: You got [correct_marks] out of 5

 ```
 - JSON Format 
 ```
[
{
"Question":"Which testing is done by developer?",
"option a":"Unit Testing",
"Option b":"Integration Testing",
"Sanity Testing":"Sanity Testing",
"Option d":"Regression Testing",
"answer":"a"
},
{
"Question":"Which is functional testing?",
"option a":"Load Testing",
"Option b":"Security Testing",
"Sanity Testing":"Gorilla Testing",
"Option d":"Benchmark Testing",
"answer":"c"
}
]

 ```

