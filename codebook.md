<article class="markdown-body entry-content" itemprop="mainContentOfPage"><h1><a id="user-content-codebook" class="anchor" href="#codebook" aria-hidden="true"><span class="octicon octicon-link"></span></a>Codebook for Getting and Cleaning Data Project</h1>
<table><thead>
<tr>
<th>Variable name</th>
<th>Description</th>
</tr>
</thead><tbody>
<tr>
<td>subject</td>
<td>ID the subject who performed the activity for each window sample. Its range is from 1 to 30.</td>
</tr>
<tr>
<td>activity</td>
<td>Activity name</td>
</tr>
<tr>
<td>featDomain</td>
<td>Feature: Time domain signal or frequency domain signal (Time or Freq)</td>
</tr>
<tr>
<td>featInstrument</td>
<td>Feature: Measuring instrument (Accelerometer or Gyroscope)</td>
</tr>
<tr>
<td>featAcceleration</td>
<td>Feature: Acceleration signal (Body or Gravity)</td>
</tr>
<tr>
<td>featVariable</td>
<td>Feature: Variable (Mean or SD)</td>
</tr>
<tr>
<td>featJerk</td>
<td>Feature: Jerk signal</td>
</tr>
<tr>
<td>featMagnitude</td>
<td>Feature: Magnitude of the signals calculated using the Euclidean norm</td>
</tr>
<tr>
<td>featAxis</td>
<td>Feature: 3-axial signals in the X, Y and Z directions (X, Y, or Z)</td>
</tr>
<tr>
<td>featCount</td>
<td>Feature: Count of data points used to compute <code>average</code></td>
</tr>
<tr>
<td>featAverage</td>
<td>Feature: Average of each variable for each activity and each subject</td>
</tr>
</tbody></table>

#Dataset structure
Data2 is the Final Data table with the clean data:
str(Data2)
'data.frame':	180 obs. of  68 variables


#For additional details on the data set, Run the following script in R:
Data2 is the Final Data table with the clean data:
summary(Data2)

##Structure for Activity files
str(dataActivityTest)
str(dataActivityTrain)

##Structure for Subject files
str(dataSubjectTrain)
str(dataSubjectTest)

##Structure for Feature files
str(dataFeaturesTest)
str(dataFeaturesTrain)

