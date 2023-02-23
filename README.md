# CS350
<br>
<br>
<br><b>Summarize the project and what problem it was solving.</b>
<br> The goal of the project was to create a thermostat that was able to detect room temperatures every second as well as check the status of the buttons pressed to either increase or decrease the setpoint temperature (much like setting a default temperature on a thermostat at home). If the room temperature went above the setpoint then a message would be sent to our simulated server that the heat is on. If the room temperature dropped below the setpoint, though, then a light would turn on. The goal was to create this thermostat for a company that would eventually want the data sent over wi-fi to the cloud.
<br>
<br><b>What did you do particularly well?</b>
<br> The part where I feel I did particularly well was utilizing the UART peripheral to emulate sending data on a server. In the other artifact I attached (Milestone 2 - UART), I also worked on an assignment that involved sending actions done on the board to a server using the terminal in CCS. In both cases I struggled a good bit. However, I ultimately felt proud seeing UART essentially confirm that different functions were working correctly as I hoped.
<br>
<br> <b>Where could you improve?</b>
<br> I could have improved on creating a functioning loop that would continuously decrease or increase the setpoint temperature with one button press instead of having to repeatedly press button 0 or button 1. I struggled with this portion a lot. It made me realize that I really need to brush up on my C++ and recap on concepts I learned in the past so that it will not hinder me as I learn new things.
<br>
<br> <b>What tools and/or resources are you adding to your support network?</b>
<br>
<br> <b>What skills from this project will be particularly transferable to other projects and/or course work?</b>
<br>
<br> <b>How did you make this project maintainable, readable, and adaptable?</b>
<br>
