# csharp-first-project
## My solution to a challenge project in C# course of freeCodeCamp and Microsoft

The Starter code project for this module is a C# console application that implements the following code features:

* Uses arrays to store student names and assignment scores.

* Uses a foreach statement to iterate through the student names as an outer program loop.

* Uses an if statement within the outer loop to identify the current student's name and access that student's assignment scores.

* Uses a foreach statement within the outer loop to iterate through the assignment scores array and sum the values.

* Uses an algorithm within the outer loop to calculate the average exam score for each student.

* Use an if-elseif-else construct within the outer loop to evaluate the average exam score and assign a letter grade automatically.

* Integrates extra credit scores when calculating the student's final score and letter grade as follows:
	* Detects extra credit assignments based on the number of elements in the student's scores array.
	* Applies a 10% weighting factor to extra credit assignments before adding extra credit scores to the sum of exam scores.

Your goal in this challenge is to implement the coding updates required to produce the teacher's requested score report.

The current score report lists the student's name followed by the calculated overall grade and letter grade. Here is the existing report format:

| Student | Grade | Letter Grade |
| Sophia | 95.6 | A |
| Andrew | 91.6 | A- |
| Emma | 89.2 | B+ |
| Logan | 93 | A |
