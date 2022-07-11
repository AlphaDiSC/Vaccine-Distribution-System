# Vaccine-Distribution-System

An efficient program in which helps allotting slots for vaccination by considering many factors such as 
availability, age, RTPCR covid report, number of doses etc. 
The motive is to vaccinate all people in our dataset within a pre defined set of time (here 3 months). 
AVL tree has been used to achieve high efficieny and make the program scalable to handle large datasets. 

How Unique Ids are created:

UID 6-digit code that uniquely identifies each person

eg:-322998

First 3-digit code is V-C-A (Vaccine-Covid-Age)

Vaccine = {3,2,1} , 3 = no vaccination , 2 = 2 month vaccination, 1 = 1 month vaccination.
Covid = {3,2,1}, 3 = no Covid, 2 = 2 months before Covid, 1 = 1 months before Covid
Age = {9,8,7,6,5,4,3,2,1} , defines age group (9=90-100).

Last 3 digit determine the sequence of Registration, where 999 is given most
priority
