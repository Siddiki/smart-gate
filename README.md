smart-gate
==========

Automate your home to protect your child

First at all, we will creat a google form, in which user can summit command: "on" for turn on the system, "off" for turn off the system. Since our project doesn't have too much data to send back and forth between spark core and the Internet, we try to make it simple as it only takes command to either turn on or turn off the system. It can be inplemented by connecting the power supply of sensor to the one of output pins of spark core.

Second, we wanna distinguish baby and adult, so we put two sensors at different height on the door: when a baby crosses the door, only the lower one triggers,but when an adult crosses, both trigger. If the baby walks through the door, then the spark core will send an alert to user.

However, writting an APP is way beyond the scope of this class; therefore they decide, perhaps we can use the google apps script as an alternative way. We may write some code in google apps script so that it'll receive data from spark core, once the condition is matched then it will send an email to user-- as user will get an "alert",assuming user has gmail on his phone. We think it is doable, because the apps script has feature of sending email to user.
