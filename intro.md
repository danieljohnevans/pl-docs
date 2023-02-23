# A Gentle Introduction to PrairieLearn in 30 Minutes or Less

This guide is meant to introduce potential instructors to the PrarieLearn system. It will discuss the background and motivation behind PrarieLearn, its advantages, and guide readers through a basic tutorial. This entire guide is meant to be read and worked through in 30 minutes-or-less in order to give potential instructors a sense of PrarieLearn and if would be a good fit for their classroom.


## What is PrarieLearn?

[PrairieLearn](https://www.prairielearn.com/) is an online problem-driven learning management system for creating homework and exams. PrarieLearn was created at the University of Illinois, Urbana-Champain to administer homework and exams to an increasingly growing student population. It is meant to ease the burden on instructors and teaching assistants while allowing them to retain pedagogic and creative control over assessment strategies. Its flexible, extensible question-asking platform scales without sacrificing student learning or assessment quality.

The features enable instructors to easily create questions that can randomize and autograde themselves. Instructors can draw from a number of client- and server-side libraries to handle such tasks as graphical drawing, symbolic algebra, or student code compilation and execution. While PrarlieLearn can be written using arbitrary HTML, JavaScript, and Python, it also has a vibrant community of current users who actively contribute open-source materials to the wider community.

## Background and Motivation

PrarieLearn is inspired by a mastery learning philosophy that seeks to inspire students with the motivation to self-assess and re-test their skills until optimal understanding is achieved. To this end, it grants instructors immense autonomy and flexibilty in determining how best to achieve these assessment strategies. It's unique grading system ensures that students are given immediate feedback throughout the assessment process, thereby allowing them to check their answers and re-assess themselves based on learning outcomes. PrarieLearn's unique autograding feature ensures that students can get a new variant of particular problem each time they are assessed. Student can therefore keep getting instances until they master the type of question. 

PrarieLearn was designed in conjunction with the [Computer-Based Testing Facility](https://cbtf.illinois.edu/) to allow for asynchronous testing. New and current users are welcome to a weekly CBTF/PrairieLearn "Office Hours" where faculty users come together to work on test items in an open-office-hour format. Contact [Dave Mussulman (Engineering)](), [Mariana Silva (Engineering](), or [Julie Baker (LAS)]() for more information.

<!-- Need some language about background. Do we want to include language about CBTF? 
Do we have literature I can cite about testing motivation? 
Also get emails! -->


### Advantages of PrarieLearn

While embracing a philosophy of learning mastery, the Prarielearn team has built as an open-source learning management system that encourages collaboration. The PrarieLearn Platform has two distinct advantages over other Learning Management Systems:

    1. Autograding not limited to specific grading or question formats (e.g., multiple choice). Throughout its history, many instructors have contributed pre-made “elements” for building common kinds of STEM questions. In this way, it is extensible. PrarieLearn is built in such a way that the instructor is limited only by web browser in creating questions.

    2. There is excellent community and staff support for writing “question generators.” Rather than write specific questions, instructors are encouraged and taught how-to write a little code to parameterize questions. These parameterized questions can then be re-used semester after semester, or on varying homeworks or exams in the same semester.
 

## Features of PrarieLearn

Unlike other Learning Management Systems, PrarieLearn supports three kinds of assessments. These should be taken as suggestions and are generally understood to be fluid. However, they should give a sense of what sort of assessment is possible in PrarieLearn:

    1. Homework: This is a place for students to practice concepts in an active learning enviroment. Students can attempt questions until they are correct. This assessment generator supports repeating question generation with “streak bonus” 

    2. Exams: These are summative evaluations. Students receive a specific set of questions and are given be given multiple attempts to answer those questions. Each subsequent attempt rewards them with partial credit. These exams can be customized through question "pools" for further “personalization” of exams (for security)

    3. Practice exams: These signal exam structure, and help guide studying. They can be identical to exams, except students can generate instances on demand.

PrarieLearn also has strong visualization and analysis tools for instructors:

    - Instructors can interactively monitor (aggregate) student progress on homework/exams
    - They can inspect individual question and item performance. Thereby changing difficulty or removing
    - They can review assessment received by a particular student
    - They can also provide support for students reporting bugs in questions

### Basic Setup

The following section will take you through the basics of setting up a PrarieLearn instance in the browser. It will take you through question creation and insert those questions into an assessment. It will then show you how to view that assessment as both an instructor and as a student. 

<!-- This section will draw from https://prairielearn.readthedocs.io/en/latest/getStarted/, https://prairielearn.readthedocs.io/en/latest/getStarted/#creating-questions-from-the-example-course, https://prairielearn.readthedocs.io/en/latest/getStarted/#creating-a-new-assessment 

Each element of this section will provide a clear roadmap of what is being performed and use numbers rather than bullet points. 

 -->

## Next Steps

Now that we have a understanding of PrarieLearn and a basic portal created. The next section will design a mock course. It is intended for an instructor or a TA looking to scaffold their first course through PrarieLearn and will highlight many of the most common quesion types and features of the learning management system.  

## Tips

    - Remember that PrarieLearn can be one piece of your assessment solution
    - Start from existing (pencil-and-paper/textbook) homework/exams questions
    - Frequent, smaller assessments (can reduce stress, achieve better learning)
    - For homework, include an automatic partial credit late period (e.g. 2-day 70% window)

Contact [Dave Mussulman (Engineering)](), [Mariana Silva (Engineering](), or [Julie Baker (LAS)]() for more information about office hours and reach out for assistance.

### Other useful Resources

    - Getting info from other systems into Prairie Learn
    - [Frequently Asked Questions](https://prairielearn.readthedocs.io/en/latest/faq/)

