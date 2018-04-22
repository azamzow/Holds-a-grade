# Holds A Grade Project

### Description

This project is used to learn inheritance, extentions, and parent and child classes in java. It calculates a exam score based on how many questions are on the test, the percentage they hold, and how many questions the user missed. It then calculates the users final exam grade after the curved percentage is given. 

- PassFailExamDemo program demonstrates the PassFailExam class, which inherits to PassFailActivity class. PassFailActivity also inherits GradedActivity class which demonstrates a passing or failing grade on the exam. 
- CurvedActivityDemo program demonstrates the CurvedActivity class, which inherits from the GradedActivity class. 

### To Run

Using terminal on Mac,

```
$ cd Holds-A-Grade
$ javac PassFailExamDemo.java
$ java PassFailExamDemo
--------------------Then-----------
$ javac CurvedActivityDemo.java
$ java CurvedActivityDemo
```

### Output

PassFailExamDemo.java 

	- This program first asks the user to input the number of questions on the test, along with how many they missed and the points for each question. It displays the exam score and if the student passed or failed. If the student passed, it displays 'P', if the student failed, it displays 'F'.



CurvedActivityDemo.java 

	- This program asks the user to enter their raw grade and the curved percentage. It then displays on the screen the score the student had before the curve, the final score the student has after the curve, and also the letter grade of the final score.