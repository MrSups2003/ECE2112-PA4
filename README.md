# EXPERIMENT 4 DATA WRANGLING AND DATA VISUALIZATION

- Name: Supnet Joshua
- Section: 2ECE-D
- Date Submitted: September 19, 2024

# ECE BOARD EXAM PROBLEM: 
Using data wrangling and data visualization technique with
storytelling, analyze the data and present different (i) data frames; and (ii) visuals using the dataset given.
1. Create the following data frames based on the format provided:
Example: Vis = [“Name”, “Gender”, “Track”, “Math<70”]; hometown is constant as Visayas
Output:
Name Gender Track Math
S4 Male Instrumentation 65
S11 Female Communication 48
S22 Female Communication 64
a. Filename: Instru = [“Name”, “GEAS”, “Electronics >70”]; where track is constant as Instrumentation and hometown Luzon
- For this part, I used df.loc with conditions as students 'Hometown' is Luzon and the 'Track' they take is Instrumentation. However, I also added another condition that the "Name", "GEAS" grade, and "Electronics" grades that are greater than 70, should be only displayed as my data frame named "Instru"
- The variable "Instru" should display the data frames of students from Luzon, having a track as "Instrumentation," their grade in GEAS, and their electronics grade that is over 70.

b. Filename: Mindy = [ “Name”, “Track”, “Electronics”, “Average >=55”]; where hometown is constant as Mindanao and gender Female
- For this problem, I created another column called average; the average will be the student's grade from Math, GEAS, Electronics, and Communication, divided by 4. For the data frame, we will consider those who are only from Mindanao, are female, and have an average equal to or greater than 55. I also added that the display of the data frame will only be the "Name", "Track", "Electronics" grade, and "Average" score that is equal to or greater than 55.

# 2. Create a visualization that shows how the different features contributes to average grade
- So for this, I made a bar graph of students on the x-axis as the "Track," "Hometown," and "Gender," with the y-axis as the "Average."

Does chosen track in college, gender, or hometown contributes to a higher average score?
- I think that place, track, or gender doesn't affect the ability to get a 'higher average score.' It is based on the ability, resiliency, tenacity, and will to achieve high average grades.
