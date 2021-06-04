# Course Planner

Term Project in Stanford CS 151, Logic Programming, by [Ayushi Tandel](https://github.com/ayushitandel),
[Andrew Lee](https://github.com/ndrewtl), and [Siah Yong Tan](https://github.com/siahyong).

Implementation of an interactive Program Sheet for the Stanford University Biocomputation major
and a general scheduler for Stanford courses.

## How to run

To use the Biocomputation Program sheet, open `BiocompProgramSheet.html` in your browser. Click a
course to add it to your planner. Each requirement begins red, and turns black when it is met.
Continue clicking courses until every requirement is black.

To use the course scheduler, open `solver.html`. Drag courses you want from the left column into a
planned quarter. When dragging, a course, quarters in which that course is offered will be
highlighted in yellow. A course will turn red if it is placed in quarter in which it is not
offered, or if it has a prerequisite course, and that course is not planned for a quarter before
it. When a quarter has between 12 and 20 units planned, it will turn green to indicate that a
valid number of courses have been scheduled.
