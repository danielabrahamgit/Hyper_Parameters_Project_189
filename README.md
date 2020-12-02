# Hyper_Parameters_Project_189
This folder holds the 16ML course material pertaining to Hyper Parameters. Resources for both intructors and students are contained. These include course notes, a slide deck, quiz questions with answers, and a coding assignment with answers. This material is meant to be taught in the fifth week of class to develop an understanding of how a model architect settles on the learning parameters she will use. Students are 4 weeks into EE16B and CS61B.  This means that they are familiar with derivatives, which can be useful when talking about gradients.  In 61B they are getting into discussions about runtime with week, so this will be important to tie into when talking about grid search vs. random search. Notably, in the previous weeks of 16ML, the students have come across Ridge, Polynomial, and Logistic regularization.
___
## Usage
Instructors are encouraged to release the included notes to the students the day they give their lecture on Hyperparameters. This lecture should follow what is written in the slide deck. When teaching the students, we want to first make a connection to Ridge Regression and Ridge Weights, a hyperparameter they are already familiar with.  They should already understand the tradeoffs between high ridge weight and low ridge weight, so optimizing this hyperparameter should be a logical next step.  This same concept can then be extended to other hyperparameters.  When talking about grid and random search, make sure to slowly build up to the concept of runtime as this is something they are only just being introduced to.
<br>
After listening to the lecture and reading the notes, students are encouraged to take the provided quiz. These questions are not meant to be overly complicated, they are just testing whether or not students absorbed what they were supposed to from the lesson. Tell students to re-read the notes if they cannot pass the quiz. 
<br>
Release the coding assignment 24 hours after you give lecture. This will give students a chance to internalize the material and take the quiz before jumping into the more difficult work.  This assignment makes use of the MNIST data set and has the students finding optimal hyperparameters for different methods of classification.  We hope to reinforce the material the students have been learning in the past weeks by having them implement ridge regression, PCA, and logistic regression before tuning their hyperparameters.  Visual representations should give them a deeper understanding of the scale at which this tuning can help minimize loss.  The last part of the notebook should help them understand the tradeoffs when it comes to using grid search.
<br>
<br>
By the end of this week, students should understand the importance of tuning hyperparameters.  They should grasp tradeoffs associated with some of the more common hyperparameters, such as ridge weight and learning rate.  And they should be aware of the pros and cons of using grid search vs random search, especially as they relate to time complexity and optimal performance.
___
## Navigation
**Coding Assignments** <br>
The jupyter notebook coding assignments for the week are located in the Coding_Assignments folder.  This holds all relavent coding material for instructors and students.
* **Hyper_Intructor** - The Hyper Parameter Notebook with answers filled in and all cells run.  Intructors will use this as a reference when assisting students, note that this is not the only way to implement the solutions. Can also be provided to students as a solution manual.
* **Hyper_Student** - The Hyper Parameter Notebook with none of the answers filled in.  Provide this to students so that they can work on filling in the answers throughout the week.

**Lecture_Material**
The lecture material for this week can be found in the Lecture_Material folder. Within this folder you will find two subfolders named Notes and Slides.
* **Notes** - This folder holds the Note document for Hyperparameters as well as any related material.
  * **Hyper_Notes** - This is a pdf containig the hyperparameter notes for the week.  This file should be made accessible to the students so that they can review the material from lecture.
* **Slides** - This folder holds the lecture slides for this week
  * **Hyper_Slides** - This is a pdf containing the slide deck for a lecture on Hyperparameters

