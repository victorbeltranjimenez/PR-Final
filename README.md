<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Voice authentication
*Víctor Beltrán*

*DATA ANALYTICS PT BCN sep 21*

## Content
- [Project Description](#project-description)
- [Hypotheses / Questions](#hypotheses-questions)
- [Dataset](#dataset)
- [Cleaning](#cleaning)
- [Analysis](#analysis)
- [Model Training and Evaluation](#model-training-and-evaluation)
- [Conclusion](#conclusion)
- [Future Work](#future-work)
- [Workflow](#workflow)
- [Organization](#organization)
- [Links](#links)

## Project Description
Analysis and creation of a model to verify the identity of a person through speech.

## Hypotheses / Questions
* Can you identify a person with speech accurately?
* Can this process improve the customer experience and relationship?
* What are the hypotheses you would like to test in order to answer your question?  
Frame your hypothesis with statistical/data languages (i.e. define Null and Alternative Hypothesis). You can use formulas if you want but that is not required.

## Dataset
Data from Github including 3000 .wav files including 6 speakers, saying the numbers 0 to 9 with 50 repetitions for each number. 
From each of the .wav files are extracted MFCC's with Librosa

![image](https://user-images.githubusercontent.com/87228449/159769837-b6283262-f674-475d-b37f-060747be3847.png)

[Dataset](https://github.com/Jakobovski/free-spoken-digit-dataset)

## Cleaning
The project did not require cleaning nor was it necessary to extract outliers. From the characteristics of the samples, the MFCC's were chosen as they were the most appropriate for this project. 

## Analysis
The steps I have followed are:
-extract features from each of the audios using Librosa.
-fitting and removal of data not needed for your feature study, keeping 20 samples of MFCC's per sample.
-using T-SNE, a dimension reduction to 3d has been performed.

<img src="https://user-images.githubusercontent.com/87228449/159778182-df9438d4-f82b-429c-9cb6-44278e93bb45.png" width="100"/>


  

## Model Training and Evaluation
*Include this section only if you chose to include ML in your project.*
* Describe how you trained your model, the results you obtained, and how you evaluated those results.
{% include 3d.html %}

## Conclusion
* Summarize your results. What do they mean?
* What can you say about your hypotheses?
* Interpret your findings in terms of the questions you try to answer.

## Future Work
Address any questions you were unable to answer, or any next steps or future extensions to your project.

## Workflow
Outline the workflow you used in your project. What were the steps?
How did you test the accuracy of your analysis and/or machine learning algorithm?

## Organization
How did you organize your work? Did you use any tools like a trello or kanban board?

What does your repository look like? Explain your folder and file structure.

## Links
Include links to your repository, slides and trello/kanban board. Feel free to include any other links associated with your project.


[Repository](https://github.com/victorbeltranjimenez/PR-Final)  
[Slides](https://1drv.ms/p/s!AtLmbOgMHZpjg9QHOGK5rBUIrGrf1A?e=Fr3agp)  
[3d]()
