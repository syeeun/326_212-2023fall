# 326.212 Statistical Computing and Labs @ SNU

This is the course website for 326.212: "Statistical Computing and Labs" at Seoul National University in Fall 2023. Assignments, lecture notes, and open-source code will all be available on this website.

## Announcements/comments

* 2023-09-05: First day of fall semester classes at 28-103

## Course Information

**Instructor**: 신예은 shin.y at snu dot ac dot kr

**Class Time**: Tuesdays & Thursdays 13:00 - 14:50 (강의 at 28-103, 실습 at 25-203 & 204)

**Office Hours**: TBD <!-- Fridays 13:00 ~ 16:00 at 25-216 or by appointment-->

**TA**
­김승우 kimsw1526 at snu dot ac dot kr;
김태연 ktyppp38 at snu dot ac dot kr;
­박지성 jsp1362 at snu dot ac dot kr;
이종진 ga0408 at snu dot ac dot kr;

**Textbook**: [R for Data Science](http://r4ds.had.co.nz/index.html) by Hadley Wickham and Garret Grolemund

**References**: [Advanced R](http://adv-r.had.co.nz/) ([Korean translation](http://jpub.tistory.com/792)); 
    [The Art of R Programming](https://nostarch.com/artofr.htm) ([Korean translation](http://www.acornpub.co.kr/book/r-programming))

<!-- **Syllabus**: [Link, in Korean](./syllabus2022.pdf) -->

## Course Objectives

By the end of this course, you will be able to

- acquire basic programming skills using the [R programming language](https://www.r-project.org);
- proficiently wrangle, manipulate, and explore data using R;
- utilize contemporary R packages, especially the [tidyverse](https://www.tidyverse.org);
- visualize, present, and communicate trends in a variety of data types;
- formulate data-driven hypotheses using exploratory data analysis and introductory model building techniques.

## Course Overview

### Assessment

The course will be graded based on the following components:

- **Attendance** (10%): Includes both the lecture and the lab sessions.
- **Assignments** (30%): You will be assigned a computational assignment to be completed using RStudio and the package *knitr* regularly throughout class. 
- **Quizzes** (20%): Unscheduled quizzes will be frequently given throughout the class during the lab sessions.
- **Final project** (40%): The project will be a computational case study that brings together the techniques learned throughout the semester. The description of the project will be provided towards the midpoint of the semester.

### Schedule

| Week | Date  | Type    | Topic                                          | Date  | Type    | Topic                            | Assignment (DUE)           |
|------|-------|-----------|------------------------------------------------|-------|-----------|----------------------------------|----------------------------|
| 1    | 9/5   | 강의 1  | Introduction                                   | 9/7   | 강의 2  | Data Visualization               |                       |
| 2    | 9/12  | 실습 1  | Git; Github                                    | 9/14  | 강의 3  | Data Transformation              |                       |
| 3    | 9/19  | 강의 4  | Data Transformation; EDA                       | 9/21  | 강의 5  | Exploratory Data Analysis        |                       |
| 4    | 9/26  | 실습 2  | R workflow; R Markdown                         | 9/28  | 추석    |                                  |                       |
| 5    | 10/3  | 개천절  |                                                | 10/5  | 강의 6  | Import and Tidy Data             | Homework 1 (10/4)     |
| 6    | 10/10 | 강의 7  | Import and Tidy Data; Relational Data          | 10/12 | 강의 8  | Strings                          |                       |
| 7    | 10/17 | 실습 3  | Data Visualization                             | 10/19 | 강의 9  | Factors, Date and Times          | Homework 2 (10/20)    |
| 8    | 10/24 | 강의 10 | Pipes; Functions                               | 10/26 | 강의 11 | Functions                        |                       |
| 9    | 11/31 | 실습 4  | (Quiz)                                         | 11/2  | 강의 12 | Vectors                          | Homework 3 (11/3)     |
| 10   | 11/7  | 실습 5  | Data Transformation                            | 11/9  | 강의 13 | Iteration                       | Final Project (12/17) |
| 11   | 11/14 | 실습 6  | Exploratory Data Analysis                      | 11/16 | 강의 14 | Model Basics                     |                       |
| 12   | 11/21 | 실습 7  | Import and Tidy data; Relational Data; Strings | 11/23 | 강의 15 | Model Building                   | Homework 4 (12/4)     |
| 13   | 11/28 | 실습 8  | (Quiz)                                         | 11/30 | 실습 10 | Factors, Date and Times, Vectors |                       |
| 14   | 12/5  | 실습 9  | Functions; Pipes; Iterations                   | 12/7  | 실습 11 | (Q&A)                            |                       |
| 15   | 12/12 | 실습 12 | (Quiz)                                         | 12/14 | 실습 13 | (Q&A)                            |                       |

<!-- Overall, this course will be split into two main parts: (1) lecture sessions on the basics of how to code in R and (2) lab sessions for performing hands-on data analysis on real case studies and examples using R.

The following schedule is tentative and is subject to change over the course.-->

<!--
| Week | Topic | Reading | Assignment | Due Date |
|---| --- | --- | --- | --- |
| 1 (9/1)      | [Introduction](./lectures/01-intro) | Ch. 1 | [Homework 1](./hw/hw1.html)  | 2022-09-21 |
| 2 (9/6, 9/8)     | [Data Visualization I, II](./lectures/02-visualization), Workflows, R Markdown | Chs. 2, 3, 28, 4, 6, 8, 27 | |   |
| 3 (9/13, 9/15)    | [Data Transformation I, II](./lectures/03-transformation) | Ch. 5 |  |  |
| 4 (9/20, 9/22)    | [Data Transformation III](./lectures/03-transformation), [Exploratory Data Analysis I](./lectures/04-EDA) | Chs. 5, 7 | [Homework 2](./hw/hw2-updated.html) | 2022-10-16  |
| 5 (9/27, 9/29)    | [Exploratory Data Analysis II, III](./lectures/04-EDA) | Ch. 7 |  |  |
| 6 (10/4, 10/6)    | [Import and Tidy Data I, II](./lectures/05-tidy) | Chs. 10, 11, 12 |  |  |
| 7 (10/11, 10/13)  | [Import and Tidy Data III](./lectures/05-tidy), [Relational Data](./lectures/06-relational) | Chs. 10, 11, 12, 13 | [Final Project](./project/Project2022.html)  | 2022-12-17 |
| 8 (10/18, 10/20)  | [Strings I, II](./lectures/07-string) | Ch. 14 | [Homework 3](./hw/hw3.html) | 2022-11-09 |
| 9 (10/25, 10/27)  | [Factors, Date and Times I, II](./lectures/08-factors)  | Chs. 15, 16 |  |  |
| 10 (11/1, 11/3)   | [Pipes](./lectures/09-pipe), [Functions I](./lectures/10-functions) | Chs. 18, 19 |  |  |
| 11 (11/8, 11/10) | [Functions II](./lectures/10-functions), [Vectors I](./lectures/11-vectors) | Chs. 19, 20 | [Homework 4](./hw/hw4.html) | 2022-11-30  |
| 12 (11/15, 11/17) | [Vectors II](./lectures/11-vectors), [Iteration I](./lectures/12-iteration) | Chs. 20, 21 |  |  |
| 13 (11/22, 11/24) | [Iteration II](./lectures/12-iteration), [Model Basics I](./lectures/13-model_basics) | Chs. 21, 22, 23  |  |  |
| 14 (11/29, 12/1)   | [Model Basics II](./lectures/13-model_basics), [Model Building I](./lectures/14-model_building) | Chs. 23, 24 |  |  |
| 15 (12/6, 12/8)  | [Model Building II](./lectures/14-model_building), Final Project | Chs. 24, 25 | | |
| 16 (12/13)  | Final Project | | | |
-->

<!--
| Week | Topic | Reading | Assignment | Due Date |
|---| --- | --- | --- | --- |
| 1 (9/1)      | [Introduction](./lectures/01-intro) | Ch. 1 | [Homework 1](./hw/hw1.html)  | 2022-09-21 |
| 2 (9/6, 9/8)     | [Data Visualization I, II](./lectures/02-visualization), Workflows, R Markdown | Chs. 2, 3, 28, 4, 6, 8, 27 | |   |
| 3 (9/13, 9/15)    | [Data Transformation I, II](./lectures/03-transformation) | Ch. 5 |  |  |
| 4 (9/20, 9/22)    | [Data Transformation III](./lectures/03-transformation), [Exploratory Data Analysis I](./lectures/04-EDA) | Chs. 5, 7 | [Homework 2](./hw/hw2-updated.html) | 2022-10-16  |
| 5 (9/27, 9/29)    | [Exploratory Data Analysis II, III](./lectures/04-EDA) | Ch. 7 |  |  |
| 6 (10/4, 10/6)    | [Import and Tidy Data I, II](./lectures/05-tidy) | Chs. 10, 11, 12 |  |  |
| 7 (10/11, 10/13)  | [Import and Tidy Data III](./lectures/05-tidy), [Relational Data](./lectures/06-relational) | Chs. 10, 11, 12, 13 | [Final Project](./project/project.md) [[Rmd](./project/project.Rmd)]  | 2022-12-10 |
| 8 (10/18, 10/20)  | [Strings I, II](./lectures/07-string) | Ch. 14 | [Homework 3](./hw/hw3.html) | 2022-11-09 |
| 9 (10/25, 10/27)  | [Factors, Date and Times I, II](./lectures/08-factors)  | Chs. 15, 16 |  |  |
| 10 (11/1, 11/3)   | [Pipes](./lectures/09-pipe), [Functions I](./lectures/10-functions) | Chs. 18, 19 |  |  |
| 11 (11/8, 11/10) | [Functions II](./lectures/10-functions), [Vectors I](./lectures/11-vectors) | Chs. 19, 20 | [Homework 4](./hw/hw4.html) | 2022-11-30  |
| 12 (11/15, 11/17) | [Vectors II](./lectures/11-vectors), [Iteration I](./lectures/12-iteration) | Chs. 20, 21 |  |  |
| 13 (11/22, 11/24) | [Iteration II](./lectures/12-iteration), [Model Basics I](./lectures/13-model_basics) | Chs. 21, 22, 23  |  |  |
| 14 (11/29, 12/1)   | [Model Basics II](./lectures/13-model_basics), [Model Building I](./lectures/14-model_building) | Chs. 23, 24 |  |  |
| 15 (12/6, 12/8)  | [Model Building II](./lectures/14-model_building), Final Project | Chs. 24, 25 | | |
| 16 (12/13)  | Final Project | | | |
-->

## Acknowledgment
Lecture notes for this course were arranged from the source code of the textbook available at <https://github.com/hadley/r4ds>.
