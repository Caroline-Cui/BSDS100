# BSDS 100: Intro to Data Science with R

## Abbie M. Popa

**Email**: apopa@usfca.edu

**Class Time**: TR, 2:40 - 4:25 PM in Harney 430

**Office Hours**: TR, 1:20 - 2:20 PM in Harney 107B (James Wilson's Office)

**Book**: [R for Data Science](http://r4ds.had.co.nz/index.html) by Hadley Wickham and Garret Grolemund

**Syllabus**: [Link](https://github.com/abbiepopa/BSDS100/blob/master/Syllabus/Fall_2018.pdf)

## Course Learning Outcomes

By the end of this course, you will be able to

- Proficiently wrangle, manipulate, and explore data using the R programming language
- Use contemporary R libraries including *ggplot2*, *tibble*, *tidyr*, *dplyr*, *knitr*, and *stringr*
- Visualize, present, and communicate trends in a variety of data types
- Communicate results using R markdown and R Shiny
- Formulate data-driven hypotheses using exploratory data analysis and introductory model building techniques

## Course Overview

### Assessment

The focus of this course will be to provide you with the basic techniques available for making informed, data-driven decisions using the R programming language. This is *not* a statistics course, but will provide you the intuition to make hypotheses about complex questions through visualization, wrangling, manipulation, and exploration of data. The course will be graded based on the following components:

- **Attendence** (20%): Attendance will be recorded and you will lose points for every class you miss.
- **Assignments** (40%): You will be assigned a computational assignment to be completed using RStudio and the package *knitr* regularly throughout class. 
- **Case Studies** (20%): You will be assigned applied case studies throughout the class that are to be completed using RStudio.
- **Final Project** (20%): The final project will be a computational case study that brings together the techniques learned throughout the semester. The description for this project will be provided towards the mid point of the semester.

<!---
### Data Science Links and News

- **Undergraduate Research in Statistics and Data Science**: [Article from Amstat News](http://magazine.amstat.org/blog/2017/09/01/undergraduateexpectations/)
--->

### Schedule

I will do my best to keep this schedule accurate and up to date. However, I reserve the right to change it as I deem necessary. Usually this will be due to the amount of material we are able to cover in class.

**Introduction**

| Topic | Reading | Assignment | Due Date | In Class Code |
 | :---  | :---:  | :---:  | :---:  | :---: |
 | [Introduction - History of Data Science](https://github.com/abbiepopa/BSDS100/blob/master/Lectures/Lecture%201%20Introduction.pdf) | [Ch. 1 What is Data Science?](https://www.safaribooksonline.com/library/view/doing-data-science/9781449363871/ch01.html)| [HW 1](https://github.com/abbiepopa/BSDS100/blob/master/Assignments/Assignment1.pdf) | Thursday, 8/23| [Installing R, RStudio, and LaTeX](https://github.com/abbiepopa/BSDS100/blob/master/class_code/R_Installation.pdf)|
 | [R and RStudio](https://github.com/abbiepopa/BSDS100/blob/master/Lectures/Lecture%202%20R%20and%20RStudio.pdf)| | [HW 2](https://github.com/abbiepopa/BSDS100/blob/master/Assignments/Assignment2.pdf) | Tuesday, 8/28| [In Class Code 2018-08-23](https://github.com/abbiepopa/BSDS100/blob/master/class_code/lecture2_livecode.R) |
 | [R Packages and RMarkdown](https://github.com/abbiepopa/BSDS100/blob/master/Lectures/Lecture%203%20R%20Markdown.pdf) | | [HW 3](https://github.com/abbiepopa/BSDS100/blob/master/Assignments/Assignment3.pdf) | Tuesday, 9/4 | [In Class Activity](https://github.com/abbiepopa/BSDS100/blob/master/class_code/lecture3_live_knit.pdf) <br> [In Class Activity Solution: Rmd Code](https://github.com/abbiepopa/BSDS100/blob/master/class_code/lecture3_live_knit_solutions.Rmd) <br> [In Class Activity Solution: PDF Output](https://github.com/abbiepopa/BSDS100/blob/master/class_code/lecture3_live_knit_solutions.pdf) <br> [Class Code - Packages](https://github.com/abbiepopa/BSDS100/blob/master/class_code/class_examples_packages.R) <br> [Class Code - R File to PDF](https://github.com/abbiepopa/BSDS100/blob/master/class_code/class_example_R_to_pdf.R) <br> [Class Output - R File to PDF](https://github.com/abbiepopa/BSDS100/blob/master/class_code/class_example_R_to_pdf.pdf) <br> [Class Code - Rmd File to PDF](https://github.com/abbiepopa/BSDS100/blob/master/class_code/class_example_Rmd_to_pdf.Rmd) <br> [Class Output - Rmd File to PDF](https://github.com/abbiepopa/BSDS100/blob/master/class_code/class_example_Rmd_to_pdf.pdf) <br> [Class Activity 2](https://github.com/abbiepopa/BSDS100/blob/master/class_code/More_Practice_Knitting.pdf)|

  
  
 **Data Structures in R**
  
 | Topic | Reading | Assignment | Due Date | In Class Code |
  | :---  | :---:  | :---:  | :---:  | :---: |
  | [Vectors, Matrices, and Arrays](https://github.com/abbiepopa/BSDS100/blob/master/Lectures/Lecture%204%20Data%20Structures%20I.pdf) | | [HW 4](https://github.com/abbiepopa/BSDS100/blob/master/Assignments/Assignment4.pdf)| Tuesday, 9/11 | [Class Code Aug 30, 2018](https://github.com/abbiepopa/BSDS100/blob/master/class_code/lecture4_180830.R) <br> [Class Code Sept 4, 2018](https://github.com/abbiepopa/BSDS100/blob/master/class_code/lecture4_180904.R)<br> [Coding Challenge](https://github.com/abbiepopa/BSDS100/blob/master/class_code/lecture4_coding_challenge_end_of_lecture.R)|
  | [Lists and Data Frames](https://github.com/abbiepopa/BSDS100/blob/master/Lectures/Lecture%205%20Data%20Structures%20II.pdf)| [Ch. 20 in R for Data Science](http://r4ds.had.co.nz/vectors.html)| | |  |
  | [Tibbles](https://github.com/abbiepopa/BSDS100/blob/master/Lectures/Lecture%205%20Data%20Structures%20III.pdf)| [Ch. 10 in R for Data Science](http://r4ds.had.co.nz/tibbles.html)| [HW 5](https://github.com/abbiepopa/BSDS100/blob/master/Assignments/Assignment5.pdf) | Tuesday, 9/18 (expected)| [Tibbles versus Data Frames Activity](https://github.com/abbiepopa/BSDS100/blob/master/class_code/The_Lack_of_Trouble_with_Tibbles.R) |
  | Strings and Factors | [Ch. 14.1 - 14.2 and 15 in R for Data Science](http://r4ds.had.co.nz/strings.html) | | | |


  
  
  **Data Wrangling and Plotting**
  
   | Topic | Reading | Assignment | Due Date | In Class Code |
   | :---  | :---:  | :---:  | :---:  | :---: |
   | Input and Output | | | | |  
   | Wrangling Data | | | |
   | Plotting in R | | HW 6 | Tuesday, 10/16 (expected)||
   | String Analysis|[Ch. 14.3 - 14.7 in R for Data Science](http://r4ds.had.co.nz/strings.html) | | | |
   | String Analysis 2|[Ch. 14.3 - 14.7 in R for Data Science](http://r4ds.had.co.nz/strings.html) | HW 7 | Tuesday, 11/6 (expected)|  |
 
 
 **Programming**
 
 | Topic | Reading | Assignment | Due Date | In Class Code |
 | :---  | :---:  | :---:  | :---:  | :---: |
 | Control Flow|[Ch. 19 in R for Data Science](http://r4ds.had.co.nz/vectors.html) | | | |
 | Writing Functions| [Ch. 19 in R for Data Science](http://r4ds.had.co.nz/vectors.html)| | | | 
 | Functionals| [Ch. 18 in R for Data Science](http://r4ds.had.co.nz/vectors.html)| | HW 8 | Tuesday 11/20 (expected) | 
 
 <!---
 
 **Statistical Modeling in R**
 
 | Topic | Reading | Assignment | Due Date | In Class Code |
 | :---  | :---:  | :---:  | :---:  | :---: |
 | [Intro to Statistical Modeling in R](https://github.com/abbiepopa/BSDS100/blob/master/Lectures/Lecture%2011%20Intro%20to%20Statistical%20Modeling.pdf) | [Ch. 23 and 24 in R for Data Science](http://r4ds.had.co.nz) | | | 
--->

### DS in the Wild
| Example |
|:--- |
| [Song Lyrics](https://github.com/abbiepopa/BSDS100/blob/master/class_code/DS_in_the_Wild_Example1.pdf)|

### Case Studies
| Case Study | Data | In-Class Date | Due Date |
|:--- | :---  | :---:  | :---: |
|CS 1|  | September 20th, 2018| October 2nd, 2018 |
|CS 2 | | October 23, 2018 | November 1, 2018 |

<!---

### Final Project
| Description | Due Date |
|:--- | :---  |
|[Project Signup](https://docs.google.com/spreadsheets/d/1pIAeZ1W5OENRyHbpfZgxKFzmGOtRNT2XkPkCQpjhzHI/edit?usp=sharing) | October 31st at 9:00 AM|
|[Final Project Description](https://github.com/abbiepopa/BSDS100/blob/master/Assignments/Final_Project_Fall_2017.pdf) | November 30th at 9:00 AM|

--->
### Important Dates

- Monday, August 27th - Last day to add the class
- Friday, September 7th - Census date. Last day to withdraw with tuition reversal
- Tuesday, October 16th - Fall break! (**no class**)
- Friday, November 2nd - Last day to withdraw
- Thursday, November 22nd - Thanksgiving Holiday (**no class**)
- Thursday, November 29 - Final Projects Due
- Tuesday, December 4th - Last day of class
