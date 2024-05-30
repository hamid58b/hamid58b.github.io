---
title: "Characterizing Bugs in Python and R Data Analytics Programs"
collection: publications
permalink: /publication/2023-06-14-characterizing-bugs-python-r
excerpt: 'This paper presents a comprehensive study of bugs in Python and R data analytics tasks based on Stack Overflow posts, GitHub commits, and issues.'
date: 2023-06-14
venue: 'arXiv'
paperurl: 'https://arxiv.org/abs/2306.08632'
citation: 'Shibbir Ahmed, Mohammad Wardat, Hamid Bagheri, Breno Dantas Cruz, Hridesh Rajan, Characterizing Bugs in Python and R Data Analytics Programs, arXiv:2306.08632 [cs.SE], https://doi.org/10.48550/arXiv.2306.08632'
---

**Abstract**

R and Python are among the most popular languages used in many critical data analytics tasks. However, we still do not fully understand the capabilities of these two languages with respect to bugs encountered in data analytics tasks. What type of bugs are common? What are the main root causes? What is the relation between bugs and root causes? How to mitigate these bugs? We present a comprehensive study of 5,068 Stack Overflow posts, 1,800 bug fix commits from GitHub repositories, and several GitHub issues of the most used libraries to understand bugs in R and Python. Our key findings include: while both R and Python have bugs due to inexperience with data analysis, Python sees significantly larger data preprocessing bugs compared to R. Developers experience significantly more data flow bugs in R because intermediate results are often implicit. We also found changes and bugs in packages and libraries cause more bugs in R compared to Python while package or library misselection and conflicts cause more bugs in Python than R. While R has a slightly higher readability barrier for data analysts, the statistical power of R leads to fewer bad performance bugs. In terms of data visualization, R packages have significantly more bugs than Python libraries. We also identified a strong correlation between comparable packages in R and Python despite their linguistic and methodological differences. Lastly, we contribute a large dataset of manually verified R and Python bugs.

Subjects: Software Engineering (cs.SE)  
Cite as: arXiv:2306.08632 [cs.SE]  
https://doi.org/10.48550/arXiv.2306.08632
