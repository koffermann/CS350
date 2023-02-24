# CS350

<br><b>Summarize the project and what problem it was solving.</b>
<br><br> The goal of the project was to create a thermostat that was able to detect room temperatures every second as well as check the status of the buttons pressed to either increase or decrease the setpoint temperature (much like setting a default temperature on a thermostat at home). If the room temperature went above the setpoint then a message would be sent to our simulated server that the heat is on. If the room temperature dropped below the setpoint, though, then a light would turn on. The goal was to create this thermostat for a company that would eventually want the data sent over wi-fi to the cloud.
<br>
<br><b>What did you do particularly well?</b>
<br><br> The part where I feel I did particularly well was utilizing the UART peripheral to emulate sending data on a server. In the other artifact I attached (Milestone 2 - UART), I also worked on an assignment that involved sending actions done on the board to a server using the terminal in CCS. In both cases I struggled a good bit. However, I ultimately felt proud seeing UART essentially confirm that different functions were working correctly as I hoped.
<br>
<br> <b>Where could you improve?</b>
<br><br> I could have improved on creating a functioning loop that would continuously decrease or increase the setpoint temperature with one button press instead of having to repeatedly press button 0 or button 1. I struggled with this portion a lot. It made me realize that I really need to brush up on my C++ and recap on concepts I learned in the past so that it will not hinder me as I learn new things.
<br>
<br> <b>What tools and/or resources are you adding to your support network?</b>
<br><br> I mentioned this in a previous discussion post, but StackOverflow is a big part of my support network. It is a reliable way to not only learn from more experienced programmers, but to also connect with fellow programmers to learn what is new in the Computer Science world and stay knowledgeable about major changes in the field. I also regularly rely on YouTube tutorials in order to connect what I am learning with visuals that videos can provide. The comment section of YouTube can also function like StackOverflow at times since some comments provide useful insight on different things.
<br>
<br> <b>What skills from this project will be particularly transferable to other projects and/or course work?</b>
<br><br> This project--and, really, this entire course--is my first time connecting software with hardware. The skills I developed from putting the two together really put into perspective what programming can accomplish. I think working with a microcontroller really opened my eyes to other fields within computer science. I can definitely see myself getting into something like Raspberry Pi and gaining experience in fields that utilize hardware rather than avoid them because I primarily studied software in school.
<br>
<br> <b>How did you make this project maintainable, readable, and adaptable?</b>
<br><br> I made this project maintainable, readable, and adaptable by first doing my best to leave ample comments in the code. Especially after being away from the code for a long while, comments can serve as reminders. Comments are also lifesavers in group/team settings where code is constantly being passed around from person to person. It helps to know what each person had in mind when adding (or removing) code.
