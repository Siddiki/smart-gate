https://cloud.githubusercontent.com/assets/8973982/5464240/ada211ee-8553-11e4-9445-3ec8bf3f10ce.JPG

smart-gate
==========

Introuducing the Smart Baby Guard! The device that watches your child for you while you can't.

WHY baby guard?
The Kansas State Department of Health and Education reports that 3,000,000 kids each year go the emergency room for household related injuries in the US alone. Of those 3,000,000, 2,096 children die, 80% of which are under the age of four. (http://www.kdheks.gov/news/web_archives/2012/01232012.htm) Clearly, current safety measures are not enough to protect all babies.

WHAT does our product do?
The Smart Baby Guard sends an alert to the parent any time a child leaves a predesignated safe zone.

HOW does our product work?
Our product is implemented by attaching two IR sensors to the door, one low enough that it can be tripped by the baby, and another high enough that it can only be tripped by an adult. If the child sensor is tripped (but not the adult sensor), then an alert will be sent to the parents' phone via internet. For development purposes, this will be achieved by using a spark core wifi microcontroller.

WHO will buy our product?
We aim to make our product affordable enough that all parents will be able to buy our device.

GITHUB CONTENTS

1. Midterm Presentation PPT - link to Mid term presentation presented at The Cooper Union on 10/23/14 

2. Midterm Presentation Skit - Script for presentation presented at The Cooper Union on 10/23/14

3. Truth Table - Truth Table and Logic expressions for Alert and Message

4. App Script Code - First of all, we will create a google form, in which the user can submit command: "on" to turn on the system, or "off" for turn off the system. Since our project doesn't have too much data to send back and forth between spark core and the Internet, we tried to make it simple as it only takes commands to either turn on or turn off the system. It can be implemented by connecting the power supply of the sensor to the one of output pins of the spark core.
However, writting an iOS or Android app is beyond the scope of this class; therefore we will use the google apps script as an alternative solution. We may write some code in google apps script so that it will receive data from spark core, once the condition is matched it will send an email to the user-- as user will get an "alert", assuming user has an email client on his phone. We think it is doable, because the apps script has feature of sending email to user.

5. Arduino Test - Arduino sketch written to test our code for Spark Core. The code sets up two pins as inputs (Sensor 1 and Sensor 2) and one as an output (connected to LED). This was just a very basic prototype that we made to test the circuit.

6. Spark Core Code - The code is supposed to read data from two sensors, if the higher sensor is low and lower sensor is high, then it means a baby is crossing the door, then the alert is assign "1", which will be sent the cloud.And user can get this from cloud. Furthermore, the app script code will read the data--"alert" from the cloud, and then send an "email alert" to user.

7. Component List - The list includes the components that we need for our first functional prototype. For each component, the estimated price, functionality, quantity and status are listed.

8. Arduino Test Code - The fully functional code on Arduino Micro.

Final Presentation Contents
========
1. Babyguard website - folder includes all of the documents used for the Babyguard.brace.io website. It includes all the .html, and .css files, along with any images we needed for the site. This website allowed us to communicate with potential customers online by acquiring their email through a fake beta, and then sending out mass emails. The website also includes a link to the survey.

2. Babyguard survey - link to the survey we sent out through our emailing list, as well as to other friends and family members. We wanted to gather data on the public opinion of our product. We asked if these people would like to see any additional functions on the product, to be able to better judge whether or not customers believe the product to be viable at the moment, or would there need to be something more. We asked them to estimate cost to be able to judge a price-range for the market.

3. Flyer Template - the link to one of the flyers that we put out on targetting location. All the flyers share the same template with only little modification.  

4. AutoCAD file for box - contains a link to the CAD file that we used to laser cut the acrylic box for the babyguard housing.

5. Final Presentation Slides - the link to the slides that was used in the final presentation on Dec. 16th 2014 


