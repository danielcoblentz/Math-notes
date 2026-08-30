# math-notes

Material from the math courses I took at Hood College between Fall 2023 and Fall 2025.
It is almost entirely PDF. There is nothing here to build or run.

## Courses

### MATH 207, Discrete Mathematics (Fall 2023)

Folder: `Discrete Math`. Taught by Nicholas Owad from the open textbook
*Discrete Mathematics: An Open Introduction*.
Logic and truth tables, quantifiers, sets, induction, counting, graphs and trees.
The folder holds the syllabus, a plain-text version of the week-by-week class
schedule, the homework sheets, some of the posted solution sets, and the oral
exam questions.

### MATH 213, Statistical Concepts and Methods (Spring 2025)

Folder: `Statistical Concepts and Methods`. Taught by Sara Malec from OpenIntro's
*Introduction to Modern Statistics*. All the computing was done in R on Posit Cloud.
Study design and sampling, describing variables, linear models, randomization
tests, sampling distributions, confidence intervals, the t distribution and the
central limit theorem, and inference for two groups.
This is the largest folder by a wide margin, mostly because of the Posit workspace
exports under `posit`.

### MATH 351, Probability (Fall 2025)

Folder: `probability`. Taught by James Parson from Durrett's
*Elementary Probability for Applications*.
Counting, sample spaces, the algebra of events, conditional probability and
independence, random variables and distributions, expectation, and the law of
large numbers.
Nearly all of this folder is his: the weekly notes he handed out, and his
written-out solutions to the homework, quizzes and midterms.

### MATH 339, Linear Algebra (Fall 2025)

Folder: `Linear Algebra`. Taught by Rachel Barber from Lay's
*Linear Algebra and Its Applications*, 6th edition.
Linear systems and row reduction, span and linear independence, linear
transformations, matrix inverses, determinants, eigenvalues and diagonalization.
Includes scans of my handwritten homework, the study checklists I wrote for the
second and third exams, and my group's final presentation on network flows.

## How it is organized

One folder per course, and inside each one, folders by kind of material. I set the
courses up at different times so the names are not identical, but the pattern is:

- Lecture material: `lecture slides` in 213, `topics and notes` in 351,
  `lecture materials` in 339. In 213 and 351 it is split by week.
- Assignments: `homework` in 207 and 213, `homework solutions` in 339 and 351.
  213 also has `assignments`, for the graded R write-ups, and `posit`, for the
  Posit Cloud workspaces those write-ups came out of.
- Exams and quizzes: `exams`, `exam content`, `exam solutions`, `quiz solutions`.
- The syllabus lives in a `syllabus` folder in 207 and at the top of the course
  folder in the other three.

`Statistical Concepts and Methods/SCM.MD` is a week-by-week index for 213 that
links into those folders.

Some notes on the filenames, which are mostly whatever the download gave me.
A `.pptx.pdf` ending means a PowerPoint deck exported to PDF. A ` - Tagged` ending
is an accessibility-tagged Word export and says nothing about the contents.
A `(1)` or `(2)` before the extension means I downloaded the file twice.
And `Solutions` in a name is not a reliable signal: in `Discrete Math` some of
those files are phone scans of my own handwritten work rather than the typeset
solution sets.

## Whose work this is

Most of what is here was written by my professors and handed out in class. It is
in this repository because it is what I studied from. It belongs to them.

Course-supplied:

- The syllabi, and the roughly 76 `.pptx.pdf` slide decks in 213.
- Almost all of `probability`, including 39 files of worked solutions to homework,
  quizzes and midterms.
- The handouts in `Linear Algebra/lecture materials` and the final project guidelines.
- The MATH 207 homework sheets and typeset solution sets.
- The `Homework N.docx` files in 213, which are the blank assignment prompts.
- Third-party work reproduced in the course packets: a BMJ research article, two
  JSTOR scans of a 1938 obituary of William Sealy Gosset, and a JAMA Network Open
  article.

Mine:

- The R write-ups in 213 under `assignments` and `quiz solutions`, a few of the
  homework PDFs, and the Posit Cloud exports under `posit`.
- The scanned homework and quiz work in `Linear Algebra/homework solutions` and
  `quiz solutions`, the checklists in `Linear Algebra/exam content`, and the
  presentation in `Linear Algebra/final project`.
- `Statistical Concepts and Methods/SCM.MD` and the Discrete Math schedule file.

If you taught one of these courses and would rather your material not sit in a
public repository, get in touch and I will take it down.
