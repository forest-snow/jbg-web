
> Syllabus, Fall 2016
> Jordan Boyd-Graber
>
http://cs.colorado.edu/~jbg/teaching/CSCI_3022/

1. Course Number and Name
========================
CSCI 3022: Introduction to Data Science Algorithms

2. Credits and Contact Hours
========================
3 Credit Hours

3. Instructor's Name
========================
Professor: Jordan Boyd-Graber

4. Textbook
========================

Think Stats by Allen B. Downey (2014, 2nd Edition)
http://greenteapress.com/thinkstats2/

The book is available free online.  We'll supplement this book with
other readings from the web as described on course webpage.

5. Specific course information
========================

a. Description
----------

Computers have made it possible, even easy, to collect vast amounts of
data from a wide variety of sources. It is not always clear, however,
how to use those data and how to extract useful information from
data. This problem is faced in a tremendous range of scholarly,
government, business, medical, and scientific applications.  The goal
of this course is to review the principles of allowing machines to
make sense of these data in a mathematically rigorous way.

Introduces students to the tools, methods, and theory behind
extracting statistical insights from data using computer science
algorithms.  The course covers maximum likelihood algorithms, basic
regression, implementing statistical tests on large datasets, and
representing and manipulating data on a computer.

b. Prerequisites or co-requisites
------------

Prerequisites: CSCI 1300, MATH 2300

Mathematical maturity: We will work extensively with probabilities and
mathematical functions such as logarithms and differentiation.  You
should be comfortable manipulating these concepts algebraically.  You
should also be able to argue why mathematical statements are true
through a rigorous proof.  This will be a very mathematical course.
You can satisfy this requirement by taking a proof-based math course
(number theory, abstract algebra, etc.), discrete math, or a
theoretical (proof-based) algorithms course.

We will make extensive use of the Python 3 programming language.  It
is assumed that you know or will quickly learn how the program in
Python.  There will be no introduction to this skill-set.  You will
need to be able to understand object oriented programming in Python.
You can satisfy this requirement by completing a programming course
that uses Python and object-oriented techniques.

The computer-based aspects of this course will be oriented toward
Unix-like operating systems (Linux, OS X).  It may be possible to
complete the course using other operating systems, but you will be
responsible for troubleshooting any issues you encounter.

c. Status in curriculum
---

Fulfils Probability/Statistics Requirement 

6. Specific Goals
========================

By the end of this course, you’ll be able to take a problem and
analyze it to determine which data science techniques are appropriate
for solving the problem, how to prepare data to use that solution,
apply the solution, and to evaluate the results.  For the most common
data science techniques, you’ll also be able to implement solutions in
Python.


a. Specific Outcomes (Check course webpage for dates)
-------------------

* Probability basics
    * Recognize when a function is a valid probability distribution
    * Convert real-concepts to probability distributions
* Conditional probabilities
    * Manipulate conditional and marginal probability distributions
    * Apply Bayes rule to invert conditional probabilities
* Sampling from distributions
    * Describe distributions using standard parameterizations of 
    * Use a random number generator to sample from the distribution
* Maximum likelihood estimation
    * Given data and an objective function, derive the form of the maximum likelihood parameters
* Statistical tests
    * Identify statistical tests that correctly use data
    * Given a problem, identify which test is most appropriate
    * Given data, compute a test statistic
    * Given a test statistic, compute a p-value
* Linear Regression
* Logistic Regression
    * Given a parameterization of logistic regression classifiers, output a classification on an example
    * Given training examples, use stochastic gradient to update classifier parameters
* Feature engineering, feature combination
    * Given a regression or classification model, identify data representation failures
    * Correct problems of data representation to improve classification or regression
    * Design training / test data splits that allow effective evaluation of data science algorithms
* Clustering
    * Recognize when a problem can benefit from classification
    * Given a dataset, run k-means clustering or Gaussian mixture models
* SVMs
    * Evaluate a margin-based classifier given a dataset whether it's effective 
    * Distinguish when a margin-based classifier needs slack variables

b. ABET Student Outcomes
-

* (a) an ability to apply knowledge of mathematics, science, and engineering
* (b) an ability to design and conduct experiments, as well as to analyze and interpret data
* (c) an ability to design a system, component, or process to meet desired needs within realistic constraints such as economic, environmental, social, political, ethical, health and safety, manufacturability, and sustainability
* (e) an ability to identify, formulate, and solve engineering problems
* (f) an understanding of professional and ethical responsibility
* (g) an ability to communicate effectively


7. Brief list of topics to be covered
================

* What are data?  How do you represent them on a computer?
* Probability basics: independence, conditional distributions, marginalization, and Bayes’ rule 
* Distributions: equations to represent distributions, sampling from these distributions algorithmically
* Maximum likelihood estimation essentials, algorithmic implementation
* Algorithmically estimating parameters of a distribution given data 
* Hypothesis testing: z-tests, t-tests, chi-squared tests 
* Linear regression 
* Logistic regression 
* Clustering algorithms 

Approach
========================

Classes alternate between lectures and in-class exercises.  Students
are responsible for completing reading assignments before lectures and
actively asking questions during lectures.  In-class exercises are
organized around an in-depth, hands-on review of a concept introduced
in the previous lecture.  We will have quizzes over the material,
discuss the material, and use hands-on lab sessions in groups to walk
through algorithms to make sure everyone understands the techniques we
are discussing.

Halfway through the course, students will complete an in-class midterm
that will test high-level understanding of concepts.

Finally, it is required that you have regular access to a computer and
an Internet connection throughout this course. A laptop is
preferable. If you have a laptop, it would be useful to bring the
laptop to class, especially for the in-class exercises.


Homeworks
-

* Extracting semi-structured data and representing it on a computer
* Estimating discrete and continuous statistical parameters from data
* Statistical tests from data
* Continuous Regression
* Classification


Grading
-

Components of the final grade are as follows:

Percentage
* Homework 30%
* Midterm 25%
* Final 25%
* Quizzes 10%
* Participation 10%

It is possible to earn extra credit by going above and beyond the expectations of the assignment.

Assignments
=

Homework assignments due are in total 30% of your final grade. Assignments are designed to help you learn the material, so please use them for that! You are allowed to collaborate with others (as many people as you'd like), but you must turn in your own assignment. For example, you could work together in a group, but each person must write up their solutions individually.

Assignments are due on the class day indicated on the course web page (Thursday, 11:55 Mountain time). Late policy: each person has five free late days to be used, no questions asked, during the course (late days can only be used in increments of one day; if your assignment is three minutes or three hours late, that counts as one late day).  When turning in a late assignment, clearly mark at the top that you are using a late day.  After you use your late days, late assignments will get half credit.  Assignments more than two days late may not be graded.

Assignments are not worth the same number of points: some will be more difficult than others.

Assignments will be turned in through Moodle and graded on correctness and explanation.  Correctness will be graded automatically, so it is particularly important that your code follow the specifications outlined in each assignment.  Explanation will be graded by hand based on the clarity of how you describe your solution.

Asking Questions about Programming Problems
-

When you ask for help with programming, make sure to follow these guidelines:
* include a minimal (simple as possible) example that can replicate your problem; provide the inputs that replicate your problem (again, this should be as simple as possible; sending multi-megabyte files is usually not minimal);
* say exactly what you did (the exact command line / function call used);
* what you expected to see;
* what you got instead (include error messages and any output); and
* what versions of various resources you're using (python, numpy, scipy, repository version).

Midterm
=

There will be an in-class midterm. The midterm will cover material in the previous lectures and will be open notes (but closed book).

Final Exam
=

The final exam will be an exam similar to the midterm's structure but comprehensive over the entire course’s content.  The exam will he held at the time specified by the University.

Class Participation
=

Each class is critical to your learning experience, and I expect you to come to class prepared (having read all assigned readings, viewed the lecture, ready to engage). I also expect active participation, not passive reception of the material. Your energy in contributing to class discussions and hands-on exercises will make this class an enjoyable experience for all of us.

We will also be using the online learning platform Piazza.  You can get credit for participation by answering and asking useful questions on that platform.  Ideally you should be participating both online and in class, however.

Quizzes
=

Quizzes are designed to be easy and to reward doing the reading and attending class.  I will drop your lowest quiz scores.  Note that this syllabus does not mention the total number of quizzes or the number of scores that will be dropped.  You should not use information in Moodle or past iterations of the course as an attempt to guess what will happen with quizzes.  Students who have done this in the past have been sorely disappointed, as my goal is to make quizzes unpredictable.  Quizzes are also used as a proxy for attendance.  Thus, there is no opportunity for making up quizzes (and I don't have the ability to judge what is an excusable absence or not for a large class).  Have no fear, however, as I will drop the lowest quiz grades: as long as you do well on a majority of quizzes, you'll be fine.

Academic Integrity
=

All students of the University of Colorado at Boulder are responsible for knowing and adhering to the academic integrity policy of this institution. Violations of this policy may include: cheating, plagiarism, aid of academic dishonesty, fabrication, lying, bribery, and threatening behavior.  All incidents of academic misconduct shall be reported to the Honor Code Council (honor@colorado.edu; 303-735-2273). Students who are found to be in violation of the academic integrity policy will be subject to both academic sanctions from the faculty member and non-academic sanctions (including but not limited to university probation, suspension, or expulsion).

Other information on the Honor Code can be found at http://www.colorado.edu/policies/honor.html  and at http://www.colorado.edu/academics/honorcode/.

Course Policies
=

If you qualify for accommodations because of a disability, please submit to your professor a letter from Disability Services in a timely manner (for exam accommodations provide your letter at least one week prior to the exam) so that your needs can be addressed. Disability Services determines accommodations based on documented disabilities. Contact Disability Services at 303-492-8671 or by e-mail at dsinfo@colorado.edu. If you have a temporary medical condition or injury, see Temporary Injuries guidelines under the Quick Links at the Disability Services website and discuss your needs with your professor. Please inform the professor of any accommodations needed relative to disabilities at the start of the semester.

Campus policy regarding religious observances requires that faculty make every effort to deal reasonably and fairly with all students who, because of religious obligations, have conflicts with scheduled exams, assignments or required attendance. In this class, inform the professors of conflicts at the start of the semester.  See full details at http://www.colorado.edu/policies/fac_relig.html

Students and faculty each have responsibility for maintaining an appropriate learning environment. Those who fail to adhere to such behavioral standards may be subject to discipline. Professional courtesy and sensitivity are especially important with respect to individuals and topics dealing with differences of race, culture, religion, politics, sexual orientation, gender, gender variance, and nationalities.  Class rosters are provided to the instructor with the student's legal name. I will gladly honor your request to address you by an alternate name or gender pronoun. Please advise me of this preference early in the semester so that I may make appropriate changes to my records.  See policies at
http://www.colorado.edu/policies/classbehavior.html   and at
http://www.colorado.edu/studentaffairs/judicialaffairs/code.html#student_code.
