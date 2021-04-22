---
layout: single
title: Data Description
permalink: /data/
date: 2021-04-21T00:00:00+09:00
---
The accelerometer data has been collected using one smartphone carried by subjects, which are caregivers and nurses, when they were conducting daily works at a healthcare facility. The smartphone was carried in an arbitrary position such as a pocket. There are a total of 27 activities divided into 4 groups. All the activities are listed in the below table.

<table>
  <tr>
    <th colspan=3 style="text-align: center"><h3>Activities of direct care</h3></th>
  </tr>
  <tr>
    <td>1: Vital</td>
    <td>7: Morning gathering/ exercises</td>
    <td>13: Family/guest response</td>
  </tr>
  <tr>
    <td>2: Meal/medication</td>
    <td>8: Rehabilitation / recreation</td>
    <td>14: Outing response</td>
  </tr>
  <tr>
    <td>3: Oral care</td>
    <td>9: Morning care</td>
    <td>19: Get up assistance</td>
  </tr>
  <tr>
    <td>4: Excretion</td>
    <td>10: Daytime user response</td>
    <td>20: Change dressing assistance</td>
  </tr>
  <tr>
    <td>5: Bathing/wiping</td>
    <td>11: Night care</td>
    <td>21: Washing assistance</td>
  </tr>
  <tr>
    <td>6: Treatment</td>
    <td>12: Nighttime user response</td>
    <td>27: Emergency response such as accident</td>
  </tr>
</table>


<table>
  <tr>
    <th colspan=3 style="text-align: center"><h3>Activities of residence cleaning</h3></th>
  </tr>
  <tr>
    <td>15: Linen exchange</td>
    <td>23: Preparation and checking of goods</td>
    <td>24: Organization of medications</td>
  </tr>
  <tr>
    <td>16: Cleaning</td>
    <td></td>
    <td></td>
  </tr>
</table>
<table>
  <tr>
    <th colspan=3 style="text-align: center"><h3>Documentation/Communication activities</h3></th>
  </tr>
  <tr>
    <td>17: Handwriting recording</td>
    <td>22: Doctor visit correspondence</td>
    <td>25: Family/doctor contact</td>
  </tr>
  <tr>
    <td>18: Delegating/meeting</td>
    <td></td>
    <td></td>
  </tr>
</table>
<table>
  <tr>
    <th colspan=3 style="text-align: center"><h3>Other activities</h3></th>
  </tr>
  <tr>
    <td>26: Break　　　　　</td>
    <td>28: Special remarks/notes　　　　　</td>
    <td>　　　　　　　　　　　　　　　</td>
  </tr>
</table>


## Data structure
In this challenge, participants are provided training data and test data. Training data contains data from ?? subjects and the activity labels file. Test data contains the data of ?? subject.

The training data folder contains the “files” folder, which contains all accelerometer data of all training subjects, and the “activities.csv” file contains the activity labels of the training data.

![fiels](/nurse2021/assets/files.png)

In the data file of each subject, we have 5 columns: subject_id, datetime, and 3 coordinates of the accelerometer data.
![data-acc](/nurse2021/assets/data-acc.png)

In the label file (“activities.csv”), we have 8 columns: id (label id), user_id, activity_type_id, activity_type (name), target_id (patients), activity2user_id, start and finish timestamp of the activity.
![data-record](/nurse2021/assets/data-record.png)

