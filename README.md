# Recipe

An esoteric programming language designed to look like a culinary recipe.

The filename is `.rcp`

Written in Typescript.

# Example Program

The following code should produce a hangman game in the terminal:

```rcp
Hangman

Utensils
- 1 File reader
- 1 Input interface

Ingredients
- 1 List
- 1 Word
- 1 Correct
- 1 Incorrect
- 1 Show
- 1 Flour
- 1 Sugar
- 1 Guess

Method
1. Preheat.
2. Add file of 'words.txt' to list.
3. Separate list by line.
4. Remake list as flour.
5. Empty word.
6. Add any of flour to word.
7. Empty correct.
8. Empty incorrect.
9. Empty show.
10. Remake word as flour.
11. Empty sugar.
12. Add first of flour to sugar.
13. Add sugar to show if sugar is in correct.
14. Add '_' to show if sugar is not empty and sugar is not in correct.
15. Repeat from step 11 if size of show is less than size of word.
16. Skip to step 19 if show is not the same as word.
17. Shout wait, 'Win!' and wait.
18. Repeat from step 4.
19. Empty flour.
20. Add 6 to flour.
21. Take size of incorrect from flour.
22. Shout wait, show, wait, 'Chances: ', flour, wait, 'Correct: ', correct, wait, 'Incorrect: ', incorrect, and wait.
23. Bake until 'Guess: ' is guess.
24. Skip to step 27 if guess is not in word.
25. Add guess to correct if guess is not in correct.
26. Skip to step 28.
27. Add guess to incorrect if guess is not in incorrect.
28. Repeat from step 9 if size of incorrect is not more than 5.
29. Shout wait and 'Loss!'.
30. Repeat from step 4.
```

![Chef's hat (logo)](./image/icon.png)

Made by [darcy](https://github.com/darccyy)