# Practical D: Conditional tests and loops.

## Practical Learning Outcomes

This practical looks at how to use conditional tests and loops in Python. This
is important to be able to make decisions about what to do in a program
and to be able to repeat operations. 

By the end of Practical D you will be able to:
* Use comparison operators to construct logical statements.
* Combine booleans with `and`, `or` and `not`.
* Use the control flow statements `if`, `elif`, `else` to make choices in programs.
* Use the `for` statement to loop through lists and strings.
* Understand how to use `enumerate` to loop through a list with an index.

## Preparation
To prepare for this practical you should first work through:

* First part of *Chapter 3 Logic, Control Flow and Filtering* 
  stopping before the video "Filtering Pandas DataFrame",
* First part of  *Chapter 4 Loops*
  stopping before the video "Looping Data Structures, part 1",

from the
[DataCamp](https://www.datacamp.com/)
online course: [Intermediate Python for Data Science
](https://www.datacamp.com/courses/intermediate-python-for-data-science). 
Note that you will need to use your DataCamp Academic Group account to access these chapters for free.

We will then exercise what you have learnt with bioinformatics-related examples.

## The practical
To use this practical you should *either*:

* If you are using Azure Notebooks import the practical as a library into your Azure Notebooks account,
  by clicking on (and then accepting default options):\
  [![Azure Notebooks](https://notebooks.azure.com/launch.png)
  ](https://notebooks.azure.com/import/gh/ARU-Bioinformatics/prac-D/)

* *Or* if you are using Google Colab then:
  * [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg) workbook_D.ipynb](
    https://colab.research.google.com/github/ARU-Bioinf-IBDS/prac-D/blob/master/workbook_D.ipynb) 
    then *COPY TO DRIVE*.
  * [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg) homework_D.ipynb](
    https://colab.research.google.com/github/ARU-Bioinf-IBDS/prac-D/blob/master/homework_D.ipynb) 
    then *COPY TO DRIVE*.  

* *Or* if you are using a local Jupyter Notebook installation, then 
  * download [workbook_D.ipynb](
    https://raw.githubusercontent.com/ARU-Bioinf-IBDS/prac-D/master/workbook_D.ipynb)
    by right clicking on the link and selecting *"Save Link As"*
  * download [homework_D.ipynb](
    https://raw.githubusercontent.com/ARU-Bioinf-IBDS/prac-D/master/homework_D.ipynb)
    by right clicking on the link and selecting *"Save Link As"*

  Once you have downloaded the notebooks move them to a directory where you are
  storing your work for this module (I would advise calling this `IBDS` and placing this in a
  folder that is automatically backed up to OneDrive, GoogleDrive or similar). 

If this unfamiliar, please go back and look at 
  [Practical A](https://github.com/ARU-Bioinf-IBDS/prac-A) 


Then in Azure Notebooks or Jupyter Notebook:
* open the workbook **workbook_D.ipynb** and work through it.
* once you have completed the workbook, then move onto the homework book **homework_D.ipynb**
* then go on to [Reflection on Practical D: Conditional tests and loops](
  https://canvas.anglia.ac.uk/courses/1490/discussion_topics/54062).

-------------------------

> This exercise is part of 
> [Introduction to Bioinformatics and Data Science, Practicals](https://github.com/ARU-Bioinf-IBDS/index/)
>
> Original author: [Oliver S. Smart](https://www.linkedin.com/in/osmart/),
> developed for [BSc (Hons) Bioinformatics Degree Apprenticeship](
  https://www.anglia.ac.uk/bioinformatician),
> [School of Life Sciences](https://www.anglia.ac.uk/science-and-engineering/life-sciences),
> Anglia Ruskin University
> Copyright (c) 2018-2019 Anglia Ruskin University

> <img src="https://aru-bioinf-ibds.github.io./images/DataCamp_Horizontal_RGB.svg" width="150"> 
>
> **A big thanks to [DataCamp](https://www.datacamp.com/) for supporting this class!**
