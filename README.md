
# Workshop: Twitter Text Analytics for R

## Sponsored by 
* [Project Mosaic](https://projectmosaic.uncc.edu/)

## July 27, 2016
 
## Instructor

* Ryan Wesslen

Original materials are by [Pablo Barber&aacute;](http://pablobarbera.com/), sponsored by [Quantitative Methods Working Group, European University Institute](https://sites.google.com/site/qmwgroup/). Please see the forked original workshop materials. Thanks to Pablo for allowing us to use his materials!

Additional content (via Pablo Barber&aacute;) were based on materials prepared by [Dan Cervone](http://dcervone.com/), [Alex Hanna](http://alex-hanna.com), [Ken Benoit](http://www.kenbenoit.net/), [Paul Nulty](https://github.com/pnulty), [Kevin Munger](https://github.com/kmunger), and [Justin Grimmer](http://www.justingrimmer.org/).)

For Project Mosaic's workshop, I've created new challenges for each module using Charlotte Twitter datasets. 

All of the material below is from the original workshop, except the schedule that reflects the Project Mosaic workshop materials.

## Description

The popularity of text as data is increasing rapidly within the social sciences. “Scholars have long recognized this, but the massive costs of analyzing even moderately sized collections of texts have hindered their use in political science research” (Grimmer and Stewart 2013) and elsewhere in the social sciences. This situation has changed with increasing computing power and more capable computing tools. In the coming years, the relevance of text data will further increase as more and more human communication is recorded online.

This workshop provides an introduction to text analysis using R. We will cover methods to conduct quantitative analysis of textual and web data, with an emphasis on social media data, applied to the study of social science questions. The workshop is made up of three "modules", each consisting of an introduction to a topic followed by examples and applications using R. The first module will cover how to format and input source texts, how to prepare the data for analysis, and how to extract descriptive statistics. The second module will discuss automated classification of text sources into categories using dictionary methods and supervised learning. Finally, the third module will discuss unsupervised classification of text into categories using topic modeling.


## Setup and Preparation

You will need to bring a laptop to all sessions of the workshop. You will need [R](https://cran.r-project.org/) and [RStudio](https://www.rstudio.com/) installed. [Follow the instructions here to install both](https://github.com/pablobarbera/eui-text-workshop/blob/master/installing_RStudio.pdf).

### Instructions for using course materials on GitHub ###

You have three options for downloading the course material found on this page:  

1.  You can download the materials by clicking on each link.  

2.  You can "clone" repository, using the buttons found to the right side of your browser window as you view this repository.  This is the button labelled "Clone in Desktop".  If you do not have a git client installed on your system, you will need to [get one here](https://git-scm.com/download/gui) and also to make sure that [git is installed](https://git-scm.com/downloads).  This is preferred, since you can refresh your clone as new content gets pushed to the course repository.  (And new material will get actively pushed to the course repository while this course takes place.)

3.  Most simply, you can choose the button on the right marked "Download zip" which will download the entire repository as a zip file.

You can also subscribe to the repository if you have [a GitHub account](https://github.com), which will send you updates each time new changes are pushed to the repository.

## Schedule for July 27 Project Mosaic Workshop


| Time         | Topic                                                     |
| ------------ | ---------------------------------------                   |
| 10:00-10:30  | Introduction to Twitter              | 
| 10:30-11:00  | [Descriptive analysis, regular expressions](01-intro/02-descriptive.Rmd)              | 
| 11:00-11:15  | [Dictionary methods](01-intro/03-dictionaries.Rmd)              | 
| 11:15-12:00  | [Challenge I](01-intro/04-challenge1-solutions.Rmd)              | 
| 12:00- 1:00  | Lunch Break |
|  1:00- 2:00  | [Supervised methods](02-supervised/01-supervised.Rmd)                  | 
|  2:00- 2:30  | [Challenge II](02-supervised/02-challenge2-solutions.Rmd)    |
|  2:30- 3:00  | Coffee Break |
|  3:00- 3:30  | [Unsupervised methods](03-unsupervised/01-topic-models.Rmd)                  | 
|  3:30- 4:00  | [Challenge III](03-unsupervised/02-challenge3-solutions.Rmd)    |
|  4:00- 5:00  | Data (e.g. Public API) and Research Ideas    |

