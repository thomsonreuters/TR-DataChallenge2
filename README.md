# Competition III- Room Image Classification
## Introduction 

![alt text](https://github.com/katherine-shiqi/TR-DataChallenge2/blob/master/git_image/2.png)

Image recognition is a vital component in Artificial Intelligence. To seize new opportunities, Thomson Reuters has established a centralized Cognitive Computing Center and Labs as well as decentralized data science teams across each business units such as Financial & Risk,  Tax & Accounting, Legal and News. Image classification becomes a common topic at TR.

In this challenge, we will provide you with thousands of room images and expect you to label them into one of the three categories– Bedroom, Bathroom or Kitchen. Build your own cutting-edge deep learning model to win the competition!


## Description
Build a classification model to label images into one the three categories: bedroom, bathroom or kitchen
  

## Image Data, Training Data & Testing Data
Image Data: Please download images from our shared Dropbox with the link below.<br>
<a href="https://www.dropbox.com/s/4y0weojqr4yap1t/image.zip?dl=0">link to image dataset</a>


Training dataset:  5010  rows, 3 columns

ID      -    unique identifier for each image <br>
IMAGE   -    room image name<br>
ROOM    -    bedroom or bathroom or kitchen(our y label)<br>

Testing dataset:   885 rows, 3 columns

ID      -    unique identifier for each image <br>
IMAGE   -    room image name<br>
ROOM    -    your predicted result (bedroom or bathroom or kitchen) <br>

## Submission 

(I) You can use one of the five coding languages (Python, R, Java, C, C++) for this competition. <br>

(II) Zip your code and predicted result file in the following format and send it to thomsonreuters_GHC@thomsonreuters.com with a title of firstname-lastname-challenge3 (such as 'bill-smith-challenge3') <br>

<li> Fill out the ROOM column with your predicted result on test.csv. Name this result CSV file firstname-lastname-result.csv (such as bill-smith-result.csv). Only one predicted room category for each image is allowed. Example: bill-smith-result.csv</li>
<br>

| ID      | IMAGE             | ROOM          |
| ------- | ------------------| ------------- |
| 0       | 5947.JPG          | bathroom      |
| 1       | 8007.JPG          | bedroom       |
| ...     | ...               | ...           |
<br>
<li>put all your code into a folder named firstname-lastname-code</li>


## Evaluation and Score

Maximum score is 120.<br>
<li>You will get up to 100 points totally based on the accuracy rate of the submission CSV (firstname-lastname-result.csv). The formula is listed below:<br>
Accuracy rate =  (correctly predicted class / total testing class) × 100%</li>
<li>You will get up to 20 points totally based on code review determined by Thomson Reuters Review Board.<br>
We will review your code to check plagiarism. If we find a high similarity between your code and other participants' code or code published online such as on Github, Kaggle, etc, you will get 0 point in total. 


## Rules
<li>You agree not to transmit, duplicate, publish, redistribute or otherwise provide or make available the Competition Data to any party not participating in the Competition. </li>
<li>One person cannot participate with more than one user accounts.  You can’t resubmit and resend your result to our email. </li>
<li>Hand-labelling is not allowed on the testing dataset</li>
<li>Competition Timeline.  Start Date: Sep-17-2018.  End Date: Sep-21-2018 11:59 PM CST. </li>
<li>You agree to only use our provided training dataset for model building. Using other sources is prohibited.</li>
<li>Thomson Reuters reserves the right of final decision on the interpretation of these Terms and Conditions.</li>

