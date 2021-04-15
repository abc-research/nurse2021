---
layout: single
title: Data Description
permalink: /data/
date: 2020-01-08T00:00:00+09:00
---
The dataset consists of care activities that nurses do in the Care facility. The activities can be categorized in 3 principle types:
<ul>
  <li>Help in Mobility</li>
  <li>Assistance in Transfer</li>
  <li>Position change</li>
</ul>
<p float="left">
  <img src="/nurse2021/assets/11.png" width="500" />
</p>
This activities further divided into several categories as shown in the table below:
![activity list](/nurse2021/assets/actList.PNG)
The data was collected in an experiment lab and in the real field. The lab data was collected in the Smart Life Care Unit of the Kyushu Institute of Technology in Japan. In this experiment, 7 subjects participated who are professional nurses. To collect the data accelerometer sensor in Mobile phone and motion capture was used. But we are opening only the mobile phone accelerometer data for this challenge. For the real field data, it was collected in a Care Facility in Japan. Data collection was done using mobile phone accelerometer and 42 subjects participated in this experiment. We are opening data of 6 nurses for training and 3 nurses for testing in this challenge. 
<ul>
  <li><b>Position of the Mobile phone:</b> Attached in right arm using armband</li>
  <li><b>Sampling rate:</b> 60 Hz</li>
  <li><b>Preprocessing:</b> No preprocessing method is applied on this data</li>
  <li><b>Training and Testing data:</b> <a href = "https://ieee-dataport.org/open-access/nurse-care-activities-datasets-laboratory-and-real-field">Download the training and testing data</a></li>
</ul>

## Data structure
Training
<ul>
  <li>Field accelerometer data (6 subjects)</li>
  <li>Lab  accelerometer data (2 subjects)</li>
  <li>labels of field data</li>
  <li>labels of lab data</li>
</ul>
Testing
<ul>
  <li>Field accelerometer data (3 subjects) </li>
</ul>

