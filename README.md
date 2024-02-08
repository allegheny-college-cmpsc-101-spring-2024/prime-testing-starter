# Primality Testing Engineering Effort

[![build](../../actions/workflows/build.yml/badge.svg)](../../actions/)
![Platforms: Linux, MacOS, Windows](https://img.shields.io/badge/Platform-Linux%20%7C%20MacOS%20%7C%20Windows-blue.svg)
[![Language: Python](https://img.shields.io/badge/Language-Python-blue.svg)](https://www.python.org/)
[![Code Style: Black](https://img.shields.io/badge/Code%20Style-Black-blue.svg)](https://github.com/psf/black)
[![Commits: Conventional](https://img.shields.io/badge/Commits-Conventional-blue.svg)](https://www.conventionalcommits.org/en/v1.0.0/)
[![Discord](https://img.shields.io/discord/872320492936257537?logo=discord)](https://discord.gg/kjah8MFYbR)

## Introduction

- Due date: Check Discord or the
[Course Materials Schedule](https://github.com/allegheny-college-cmpsc-101-spring-2024/course-materials/blob/main/Schedule.md)
- This assignment is graded. Half is determined by gatorgrade score. See full 
description in the syllabus section for
[Assignment Evaluation](https://github.com/allegheny-college-cmpsc-101-spring-2024/course-materials?tab=readme-ov-file#assignment-evaluation)
- Submit this assignment on GitHub following the expectations in the syllabus on
[Assignment Submission](https://github.com/allegheny-college-cmpsc-101-spring-2024/course-materials#assignment-submission).
- To begin, read this `README` and the Proactive Programmers' project
[instructions](https://proactiveprogrammers.com/data-abstraction/engineering-efforts/primality-testing/)
- This project has been adapted from Proactive Programmers' material,
thus discrepancies are possible.
- Post to the #data-structures Discord channel for questions and clarifications.
- For reference, check the
[starter repo](https://github.com/allegheny-college-cmpsc-101-spring-2024/prime-testing-starter)

## Learning Objectives

This assignment is about remembering and understanding
programming language constructs by running programs,
observing output, and describing steps.
The learning objectives of this assignment are to:

1. Use Git and GitHub to manage source code file changes
2. Study type annotation in function declarations, floating point
arithmetic, and modulus operations
3. Use profiler for empirical assessment of algorithms.
4. Write clearly about the programming concepts in this assignment.

## Seeking Assistance

Please review the course expectations on the syllabus about
[Seeking Assistance](https://github.com/allegheny-college-cmpsc-101-spring-2024/course-materials#seeking-assistance).
Students are reminded to uphold the Honor Code. Cloning the assignment
repository is a commitment to the latter.

For this assignment, you may use class materials, textbooks, notes, and the
internet. Ensure that your writing is original and based on your own understanding
of the concepts. Examples of plagiarism include:

- verbatim copying without citation
- copying with single word modifications
- paraphrasing sections or notes from a source without citation

To claim that work is your own, it is essential to craft the logic and the
writing together without copying or using the logical structure of another
source. The honor code holds everyone to this standard.

## Project Overview

After cloning this repository to your computer, please take the following
steps:

- Follow the 
  [instructions on the Proactive Programmers web site](https://proactiveprogrammers.com/data-abstraction/engineering-efforts/primality-testing/)
  for this project to take all of the needed steps and to complete all of 
  the required deliverables.
- Use the `cd` command to change into the directory for this repository.
- Specifically, you can change into the program directory by typing `cd primality`.
- Install the dependencies for the project by typing `poetry install`.
- Run the program in the following fashion by typing:
  - `poetry run primality --number 49979687 --approach efficient`
  - `poetry run primality --number 49979687 --approach efficient --profile`
  - Please note that the program will not work unless you add the required
    source code.
  - Please refer to the `writing/reflection.md` file for all ways to run the
    program.
  - Again, please note that there are multiple ways to run this project and you
    should try them all!
- Confirm that the program is producing the expected output by looking in the
  appropriate section of the project description on the Proactive Programmers
  web site.
- If you have already installed the
  [GatorGrade](https://github.com/GatorEducator/gatorgrade) program that runs
  the automated grading checks provided by
  [GatorGrader](https://github.com/GatorEducator/gatorgrader) you can, from the
  repository's base directory, run the automated grading checks by typing
  `gatorgrade --config config/gatorgrade.yml`. If a specific part of a
  `gatorgrade` check does not work on your laptop, please refer to GitHub
  Actions to see if it passed when run on the continuous integration server.
- Again, you may always review the output from running GatorGrader in GitHub
  Actions.
- Don't forget to provide all of the required responses to the technical writing
  prompts in the `writing/reflection.md` file.
- Please make sure that you completely delete the `TODO` markers and their
  labels from all of the provided source code. This means that instead of only
  deleting the `TODO` marker from the code you should delete the `TODO` marker
  and the entire prompt and then add your own comments to demonstrate that you
  understand all of the source code in this project.
- Please make sure that you also completely delete the `TODO` markers and their
  labels from every line of the `writing/reflection.md` file. This means that
  you should not simply delete the `TODO` marker but instead delete the entire
  prompt so that your reflection is a document that contains polished technical
  writing that is suitable for publication on your professional web site.
