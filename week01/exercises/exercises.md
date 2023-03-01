# Exercise 1: Better Scores
_Goal: basic handling of JavaScript arrays_

Develop a small JavaScript program to manage the scores given to your user in a question-and-answer website (e.g., StackOverflow). You should:
 
- Define an array with all the scores you received in chronological order. For the moment:
  - Embed the scores directly in the source code.
  - Ignore the question, answer, and date that generated the score.
- Duplicate the array, but:
  - Eliminate the two lowest-ranking scores.
  - Add two new scores, in the end, equal to the (rounded) average of the existing scores.
- Print both arrays, comparing the scores before and after the "improvement," and showing the averages in both cases.

# Exercise 2: My Users' List
_Goal: basic handling of JavaScript strings_

Develop a small JS program to manage the list of users in a Q&A website.

- Define the names of users as a comma-separated list.
 - For instance: "Luigi De Russis, Luca Mannella, Fulvio Corno, Juan Pablo Saenz Moreno, Enrico Masala, Antonio Servetti, Eros Fani"
- Parse the string and create an array containing one name per array position.
 - Beware: no extra spaces should be present.
- Create a second array by computing the acronyms of the people as the initial letters of the name. Acronyms should be in all-capital letters.
 - For example, Luigi De Russis -> LDR.
- Print the resulting list of acronyms and the full names.
 - Extra: in alphabetical order of acronym.