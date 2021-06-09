---
layout: single
title: About Third Nurse Care Activity Recognition Challenge
permalink: /learn/
date: 2021-06-08T00:00:00+09:00
---

Human Activity Recognition (HAR) is the process of handling information from sensors and/or video capture devices under certain circumstances to correctly determine human activities. Traditionally, the HAR can be achieved by human observation through the visualization of video recording devices. However, it is time and labor consuming. Nowadays, this traditional way could be replaced by other simple and automatic methods based on sensors and Artificial Intelligence platforms. For instance, your smartphone or other smart wearable devices have the ability to recognize some of your movements such as walking or running based on the inside accelerometer sensor.

In addition, HAR has several remarkable applications in the real world, especially in the healthcare field. Besides the elderly/patient’s activity monitoring, the caregiver’s activity recognition plays an important role to improve the healthcare quality. Moreover, specifically in developed countries, the number of the elderly increases rapidly due to population aging, while the number of nurses can not satisfy. The greater the pressure on nurses, the more uncertain the healthcare quality is. Therefore, nurse care activity recognition is implemented to help the caregiver/nurse well manage and improve the quality of their work. In this challenge, based on the accelerometer data collected from the smartphone, the cheapest and easy-to-implement way, we aim to recognize the daily nurse care activities taking place at the nursing care facility.

## Challenge Goal
The goal of the Nurse Care Activity Recognition Challenge is to recognize the daily activities of a caregiver/nurse in a healthcare facility based on the accelerometer data collected from smartphones. Participants utilize accelerometer data and its activity labels in training files, propose the methods to extract features from these data, and then feed to their own model. Finally, each team needs to use their model to predict the activity based on the accelerometer data following by the timestamp in the test data. You can check out the basic [HAR tutorial here](/nurse2021/tutorial/tutorial.html).

- [To understand the dataset more clearly](/nurse2021/data/)
- [To download the dataset](https://ieee-dataport.org/competitions/third-nurse-care-activity-recognition-challenge)
- [Rules to participate in this challenge](/nurse2021/rules/)

The training and testing dataset contains accelerometer data of 12 users (2, 3, 4, 5, 6, 7, 9, 12, 17, 19, 21, and 22), which were collected on May and June, 2018. The training data is provided with the activities labels, which describe the users' activities before 18th June, 2018. The testing data was the accelerometer data acquired on 18th June and afterward. Participants are required to propose their pipelines, predict and submit the activity label for the testing dataset.

- Make a submission(Will be opened soon)


## Data use
All participants may use the data free of charge.

## Evaluation
Submissions will be evaluated by the AUC.
<!-- Submissions will be evaluated by the Accuracy using following formula:
![\Large Accuracy=\frac{Correctly predicted samples}{All samples}](https://latex.codecogs.com/gif.latex?Accuracy&space;=&space;\frac{Corectly&space;Predicted&space;Samples}{All&space;Samples}) -->

## Prizes
100,000 JPY for the winning team.

## Eligibility
Challenge is open to students, graduate students, researchers, professors, and data scientists. Members of Sozolab (“Organizers”) are not eligible to enter or win. To be eligible, participants need to register in the challenge, submit their results and a paper to HASCA Workshop. Only submissions with a submitted paper are eligible to win a prize.

## Workshop Participation
All participants are encouraged to participate in the Workshop to share details about their approach.

## Previously Organized Challenges
[Nurse Care Activity Recognition Challenge (2019)](https://hasc-nurse-challenge.github.io/)  
[Second Nurse Care Activity Recognition Challenge (2020)](https://abc-research.github.io/nurse2020/)  
[Cooking Activity Recognition Challenge (2020)](https://abc-research.github.io/cook2020/)  

## Contact Us
abc@sozolab.jp
