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

1. Midterm Presentation PPT - Mid term presentation presented at The Cooper Union on 10/23/14 [JERRY PLEASE UPLOAD]

2. Midterm Presentation Skit - Script for presentation presented at The Cooper Union on 10/23/14

3. Truth Table - Truth Table and Logic expressions for Alert and Message

4. App Script Code - First at all, we will creat a google form, in which user can summit command: "on" for turn on the system, "off" for turn off the system. Since our project doesn't have too much data to send back and forth between spark core and the Internet, we try to make it simple as it only takes command to either turn on or turn off the system. It can be inplemented by connecting the power supply of sensor to the one of output pins of spark core.
However, writting an APP is way beyond the scope of this class; therefore they decide, perhaps we can use the google apps script as an alternative way. We may write some code in google apps script so that it'll receive data from spark core, once the condition is matched then it will send an email to user-- as user will get an "alert",assuming user has gmail on his phone. We think it is doable, because the apps script has feature of sending email to user.

5. Arduino Test - Arduino sketch written to test our code for Spark Core

6. Spark Core Code - [JIALUN PLEASE EXPLAIN HERE]

