<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Voice authentication
*Víctor Beltrán*

*DATA ANALYTICS PT BCN sep 21*

## Content
- [Project Description](#project-description)
- [Hypotheses / Questions](#Hypotheses-Questions)
- [Dataset](#dataset)
- [Cleaning](#cleaning)
- [Analysis](#analysis)
- [Model Training and Evaluation](#model-training-and-evaluation)
- [Conclusion](#conclusion)
- [Future Work](#future-work)
- [Links](#links)

## Project Description
Analysis and creation of a model to verify the identity of a person through speech.

## Hypotheses / Questions
* Can you identify a person with speech accurately?
* Can this process improve the customer experience and relationship?


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

<img src="https://user-images.githubusercontent.com/87228449/159778182-df9438d4-f82b-429c-9cb6-44278e93bb45.png" width="400"/>


  

## Model Training and Evaluation
*Include this section only if you chose to include ML in your project.*
I used Logistic Regression from Scikit-Learn in which I obtained 100% success rate results.

## Conclusion
the use of MFCC's in the field of voice biometrics authentication is a successful process.

## Future Work
adding voice recognition for double security using access codes.

## Links
Include links to your repository, slides and trello/kanban board. Feel free to include any other links associated with your project.


[Repository](https://github.com/victorbeltranjimenez/PR-Final)  
[Slides](https://1drv.ms/p/s!AtLmbOgMHZpjg9QHOGK5rBUIrGrf1A?e=Fr3agp)  

