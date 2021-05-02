## CourseHelpBot
This Discord bot was designed by a team of 4 for the 2021 RU Hacks competition. This project is submitted for the Discord Bot and Education hack categories.

## Inspiration
At the opening ceremony of RU Hacks, we were instantly hooked by the Discord bot category and decided to create a Discord bot that intends to solve a problem. Initially, we looked at creating something similar to Soccerguru, a bot that allows users to access different information regarding the sport of soccer.  We decided to create CourseHelpBot to help students be able to better prepare for final exams and achieve their desired final grade. 

## What it does
This bot is equipped with various commands that cover different courses at Ryerson University. Currently, the prototype only covers one course (ELE404: Electronic Circuits I). The bot has a series of commands that are mentioned below:

1. !help: This command will display the full list of all available commands.
2. !CourseCode + "calc" + lab mark,midterm mark: This command determines the final mark required to successfully pass the course.
3. !CourseCode + "weight": This command finds the weightage of every summative evaluation (tests/quizzes, labs, exams, etc.) for each course.
4. !CourseCode + “syllabus” +  “midterm/final”: This command finds the course material covered for the midterm or the final exam of the selected course. For example, if the user input is !ELE404 syllabus midterm, the bot displays all content that will be covered for the midterm exam.
5. !CourseCode +"calcgpa" + course1 grade, course2 grade, course3 grade, etc (Example: !ELE404 calcgpa 80,80,80): This command returns the cumulative GPA for the three courses and the achieved mark in each course.
6.  !CourseCode + "calcfinal" + lab mark,midterm mark, final mark (Example: !ELE404 calcfinal 80,80,80): This command returns the final grade in the course, taking all marks for each evaluation into the calculation.

## How we built it
This bot was built using the Javascript scripting language on Visual Studio Code and was imported to a Discord test server for testing purposes. 

## What we learned
We learned quite a bit about designing the various commands that can invoke a Discord bot to give a particular response. Specifically, we learned how to create and manage the bot after creating it, thanks to RU Hacks' workshops on Discord bots.

## What's next for CourseHelpBot - Discord Bot
As this project is currently in the prototype phase, we have only one course in the database for the bot. Within the next 2-3 months, we are planning to add more courses and improve the overall functionality of the Discord bot for better performance and usage.
