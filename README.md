# First-Project
Building AI project

# Project Title - AI to predict if your relationship will last long

## Summary - 

The aim of the project is to monitor the behaviour between partners and to know exact traits/education/likes/dislikes/interests/cultural and moral thinking that brings two people closer to each other to bond for life and what makes them move away from each other at grim times.

## Background

The top fundamental factors that affect a relationship according to the researchers (published at PNAS) are commitment, appreciation, sexual satisfaction, happiness and conflict. The findings suggests that success of a relationshiop often relies in factoring in other person's feelings. People often break up as they are too self centered or no longer are tolerant of the other person over the course of time.

The following can be addressed -

* Work productivity can increase based on a healthy relationship 
* Quality of the relationship directly affects the parent-child well being
* Mental awareness now has become an important factor to consider with hybrid work culture
* Family bonding with relatives can increase with a successful realtionship


## How is it used?

A correlation can be defined between the relationship traits identified and public data set available. 

1) I am using a mock data with 5 arrays for each trait.
2) The columns taken as Name, Marital status , Commitment score, Happiness score, Appreciation score and Conflict score.
3) The input from above then can be bumped against set of relationship traits/ individual traits (published by Stanford University) to chart success rate and years in chart.

This AI can help individuals who are new to dating or have been in relationship for long , therapists, marraige counselars . Past relationship patterns can be used to predict events ahead much more efficiently and more accurately using this AI technology.

![Relationship traits]

<img src="https://github.com/Priyanka-Dcosta/First-Project/blob/main/31304986-8569947-image-a-14_1595972850088.jpg" width="600">


def main():

# Create table using string and numbers. (The scores are computed from the survey conducted on couples. The below data is mock)
   Names = ['Peter', 'Lily', 'Bianca', 'James', 'Greg']
   Marital_Status = ['Yes', 'No', 'Yes', 'Yes', 'No']
   Commit_Score = [6, 7, 8, 6, 6]   
   Appre_Score = [6, 8, 7, 7, 8]
   Happ_Score = [7, 8, 6, 6, 7]
   Conflict_Score = [4, 3, 5, 5, 3]
   
   totComit = sum(Commit_Score)
   totAppr = sum(Appre_Score)
   totHapp = sum(Happ_Score)
   totConf = sum(Conflict_Score)
   
   for i in range(len(Names)):
      print("%s %.2f%%" % (Names[i], 100.0))    # current just prints 100%
      
   main()
  
   ----
| Names       | Commit_Score| Appre_Score| Happ_Score |Conflict_Score |Marital_Status |
| ----------- | ------------|------------|------------|---------------|---------------|
| Peter       | 6           | 6          | 7          | 4             | Yes           |
| Lily        | 7           | 8          | 8          | 3             | No            |
| Bianca      | 8           | 7          | 6          | 5             | Yes           |
| James       | 6           | 7          | 6          | 5             | Yes           |
| Greg        | 6           | 8          | 7          | 3             | No            |
| Tot         |  41         | 36         | 34         | 20            |               |
       

![Relationship score]

<img src="https://github.com/Priyanka-Dcosta/First-Project/blob/main/Screen-Shot-2018-05-16-at-11.54.11-AM.png" width="600">


## Data sources and AI methods

[DataRobot API](https://www.datarobot.com/blog/preparing-the-data-for-relationships-by-datarobot/)

DataRobot team has used codes published by Stanford unviersity to  arrive at a relationship score which predicts how likely a couple will stay together for more than 2 years based on few datpoints collected by surveying them.In the image above, online data was gathered for Prince Harry and Megan Merkel. This kind of scoring system along with checking data between few variables suggests how relationship traits are correlated with each other and are essential to cauculate the likely success of a relationship.

[PNAS Data](https://www.pnas.org/doi/10.1073/pnas.1917036117#t02)

Below is an excerpt of 43 dataset collected by reseachers after surveying 11,000 couples based on how satisfied and committed they perceived their partners to be, and how appreciative they felt toward their partners. This can be used a training data set with data from Databorot team to make this analysis more accurate.

![image](https://user-images.githubusercontent.com/100334097/156302581-163b0a5b-82fb-4632-9a56-40c005f86e24.png)


## Challenges

Analysing realtionship & individual traits and developing a correlation between them may help to predict how a relationship should be perceived and how likely it can be successful based on the datapoints collected but these cannot be used to accurately suggest if a couple will make it or not as there are professionals like relationship experts, marriage counsellors,psychiatrists who can connect with individuals and take this call.

## What next?

I have  collected and exhibited the data and images from online but since I am new to python and machine learning , I would like help on actually understanding how machine learning is used to predict data. If we can bring in more training data set into the above equation from public domains, may be the project can provide scores precisely. 


## Acknowledgments

* https://www.pnas.org/content/117/32/19061#abstract-2 
* https://www.icpsr.umich.edu/web/ICPSR/studies/30103 - Michael J. Rosenfeld, Stanford University; Reuben J. Thomas, City College of New York; Maja Falcon, Stanford University
* 
* 
