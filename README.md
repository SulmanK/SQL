---
title: 'SQL: Table of Contents'
author: "Sulman Khan"
date: "`r format(Sys.time(), '%d %B, %Y')`"
output: 
  html_document:
    css: C:/Users/sulma/OneDrive/Desktop/Data Science/Machine Learning/gf_small_touches.css
    highlight: tango
    mathjax: default
    theme: cerulean
---

```{r setup, cache = FALSE, echo = FALSE, message = FALSE, warning = FALSE, tidy = FALSE}
require(knitr)
options(width = 160, scipen = 5)
options(dplyr.print_max = 200)
# options(width = 100, digits = 7)
opts_chunk$set(message = FALSE, error = FALSE, warning = FALSE, 
               collapse = TRUE, tidy = FALSE,
               cache = TRUE, cache.path = '.cache/', 
               fig.align = 'left', dpi = 100, fig.path = 'figures/NBA/')
# opts_chunk$set(dev="png", 
#                dev.args=list(type="cairo"),
#                dpi=96)
```
# SQL
Udemy - Course on PostgreSQL published under my [RPubs repository](https://rpubs.com/SulmanKhan/444167) and [GitHub repository](https://github.com/SulmanK/SQL)

Includes lecture notes and exercises using SQL commands.




## Lecture Notes
 * SQL: Statement Fundamentals
      + [SELECT](https://rpubs.com/SulmanKhan/446183) 
      + [SELECT DISTINCT](https://rpubs.com/SulmanKhan/446184)
      + [SELECT WHERE](https://rpubs.com/SulmanKhan/446185)
      + [COUNT](https://rpubs.com/SulmanKhan/446186)
      + [LIMIT](https://rpubs.com/SulmanKhan/446187)
      + [ORDER BY](https://rpubs.com/SulmanKhan/446188)
      + [BETWEEN](https://rpubs.com/SulmanKhan/446189)
      + [IN](https://rpubs.com/SulmanKhan/446190)
      + [LIKE](https://rpubs.com/SulmanKhan/446191)
 * SQL: GROUP BY Statements
      + [MIN MAX SUM and AVG](https://rpubs.com/SulmanKhan/446201)
      + [GROUP BY](https://rpubs.com/SulmanKhan/446211)
      + [HAVING](https://rpubs.com/SulmanKhan/446220)
 * SQL: JOINS
      + [AS](https://rpubs.com/SulmanKhan/446240)
      + [INNER JOIN](https://rpubs.com/SulmanKhan/446251)
      + [OUTER JOIN](https://rpubs.com/SulmanKhan/446263)
      + [UNION](https://rpubs.com/SulmanKhan/446267)
 * SQL: Advanced SQL Commands
      + [Timestamps and Extract](https://rpubs.com/SulmanKhan/446273)
      + [Mathematical Functions](https://rpubs.com/SulmanKhan/446278)
      + [String Function and Operators](https://rpubs.com/SulmanKhan/446286)
      + [SubQuery](https://rpubs.com/SulmanKhan/446843)
      + [Self-Join](https://rpubs.com/SulmanKhan/446864)
 * SQL: Creating Database and Tables
      + [Data Types](https://rpubs.com/SulmanKhan/446887)
      + [Primary Keys and Foreign Keys](https://rpubs.com/SulmanKhan/446893)
      + [Create Table](https://rpubs.com/SulmanKhan/446912)
      + [Insert](https://rpubs.com/SulmanKhan/446924)
      + [Update](https://rpubs.com/SulmanKhan/446927)
      + [Delete](https://rpubs.com/SulmanKhan/446931)
      + [Alter Table](https://rpubs.com/SulmanKhan/446942)
      + [Drop Table](https://rpubs.com/SulmanKhan/446951)
      + [CHECK Constraint](https://rpubs.com/SulmanKhan/446968)
      + [NOT NULL Constraint](https://rpubs.com/SulmanKhan/446982)
      + [UNIQUE Constraint](https://rpubs.com/SulmanKhan/446989)
 * SQL: Bonus Lectures
      + [Views](https://rpubs.com/SulmanKhan/447035)
      + [PostGreSQL with Python](https://github.com/SulmanK/SQL/blob/master/Lecture%20Notes/Extra/PostGreSQL%20with%20Python.txt)
    
## UDEMY: Exercises
 * [SQL: Statement Fundamentals - General Challenges](https://rpubs.com/SulmanKhan/446192)
 * [SQL: Assessment Test 1 - GROUP BY Statements](https://rpubs.com/SulmanKhan/446225)
 * [SQL: Assessment Test 2 - JOINS and Advanced SQL Commands](https://rpubs.com/SulmanKhan/446873)
 * [SQL: Assessment Test 3 - Creating Databases and Tables](https://rpubs.com/SulmanKhan/447015)
 

## Stanford Lagunita: Exercises
 * [SQL: Stanford Exercises - Movie Rating -  PART I](https://rpubs.com/SulmanKhan/449883)
 * [SQL: Stanford Exercises - Movie Rating - PART II](https://rpubs.com/SulmanKhan/449884)
 * [SQL: Stanford Exercises - Movie Rating - PART III](https://rpubs.com/SulmanKhan/449885)
 * [SQL: Stanford Exercises - Social Network -  PART I](https://rpubs.com/SulmanKhan/449911)
 * [SQL: Stanford Exercises - Social Network - PART II](https://rpubs.com/SulmanKhan/449913)
 * [SQL: Stanford Exercises - Social Network - PART III](https://rpubs.com/SulmanKhan/449914)






-Sulman Khan
