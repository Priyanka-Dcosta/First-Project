# First-Project
Building AI project

# Project Title - AI to predict if your relationship will last long

## Summary - 

The aim of the project is to monitor the behaviour between partners and to know exact traits/education/likes/dislikes/interests/cultural and moral thinking that brings two people closer to each other to bond for life and what makes them move away from each other at grim times.

## Background

The top fundamental factors that affect a relationship according to the researchers at Stanforn University (published at PNAS) are commitment, appreciation, sexual satisfaction, happiness and conflict. The findings suggests that success of a relationshiop often relies in factoring in other person's feelings. People often break up as they are too self centered or no longer are tolerant of the other person over the course of time.

The following can be addressed -

* Work productivity can increase based on a healthy relationship 
* Quality of the relationship directly affects the parent-child well being
* Mental awareness now has become an important factor to consider with hybrid work culture
* Family bonding with relatives can increase with a successful realtionship


## How is it used?

A correlation can be defined between the relationship traits identified and public data set available. 

1) I am using a mock data with 5 arrays for each trait.
2) The columns taken as Name, Marital status , Commitment score, Happiness score, Appreciation score and Conflict score.
3) The input from above then can be bumped against set of relationship traits/ individual traits (published by PNAS) to chart success rate and years in chart.

This AI can help individuals who are new to dating or have been in relationship for long , therapists, marraige counselars . Past relationship patterns can be used to predict events ahead much more efficiently and more accurately using this AI technology.

![Relationship traits]

<img src="https://github.com/Priyanka-Dcosta/First-Project/blob/main/31304986-8569947-image-a-14_1595972850088.jpg" width="600">


def main():

   Names = ['Peter', 'Lily', 'Bianca', 'James', 'Greg']
   Marital_Status = ['Yes', 'Yes', 'Yes', 'No', 'No']
   Commitment_Score = [6.7, 7.2, 8.4, 6.5, 4.6]   
   Happiness_Score = [7, 8, 9, 6, 4]
   Appreciation = [7, 8, 9, 6, 4]
   Conflict = [2,4, 2.1, 3.4, 4.5, 4.8]
   
   totComit = sum(Commitment_Score)
   totHapp = sum(Happiness_Score)
   totAppre = sum(Appreciation)
   totConf = sum(Conflict)
   
   # write your solution here

   for i in range(len(Names)):
      print("%s %.2f%%" % (Names[i], 'Peter'))    # current just prints 100%

main()
```


## Data sources and AI methods
Where does your data come from? Do you collect it yourself or do you use data collected by someone else?
If you need to use links, here's an example:
[Twitter API](https://developer.twitter.com/en/docs)

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

## Challenges

What does your project _not_ solve? Which limitations and ethical considerations should be taken into account when deploying a solution like this?

## What next?

How could your project grow and become something even more? What kind of skills, what kind of assistance would you  need to move on? 


## Acknowledgments

* https://www.pnas.org/content/117/32/19061#abstract-2 
* https://www.icpsr.umich.edu/web/ICPSR/studies/30103 - Michael J. Rosenfeld, Stanford University; Reuben J. Thomas, City College of New York; Maja Falcon, Stanford University
* 
* do not use code, images, data etc. from others without permission
* when you have permission to use other people's materials, always mention the original creator and the open source / Creative Commons licence they've used
  <br>For example: [Sleeping Cat on Her Back by Umberto Salvagnin](https://commons.wikimedia.org/wiki/File:Sleeping_cat_on_her_back.jpg#filelinks) / [CC BY 2.0](https://creativecommons.org/licenses/by/2.0)
* etc
