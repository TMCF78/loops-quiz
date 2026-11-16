# Loop & Logic Quiz

An interactive Grade 7 coding quiz on **loops** and **conditionals (if / else)**.

**Play it here:** https://tmcf78.github.io/loops-quiz/

## What's inside

12 questions, shown in a new random order on every attempt:

- **Loops:** `repeat` blocks, nested loops, `for i in range(...)`, `while` loops, debugging a square-drawing script, and spotting a loop that never stops
- **Conditionals:** if/else, the `%` remainder for odd and even numbers, `and`, and `if/elif/else` grading
- **Robotics:** making a robot stop before a wall using a distance sensor

Code appears in two forms: **coding blocks** and **Python**.

Learners get instant feedback with an explanation after every answer. The results screen shows their score per topic and every question with the correct answer.

## Class scoreboard

Before starting, learners type their **first name** and **class**. When they finish, the quiz sends their result to the teacher's Google Form, which saves it to a Google Sheet that only the teacher can see.

| Column | Meaning |
|---|---|
| Name, Class | What the learner typed |
| Score | Correct answers out of 12 |
| Loops | Correct answers out of 8 loop questions |
| Conditionals | Correct answers out of 5 conditional questions |

The robot question counts in both Loops and Conditionals. Every attempt is saved as a new row with a timestamp.

To connect the quiz to a different form, change the `FORM` settings in `index.html`.

## How it works

The whole quiz is one file, `index.html`. It doesn't need any installation or a server. To edit the questions, change the `BANK` list near the bottom of the file.

It's hosted for free with **GitHub Pages**.
