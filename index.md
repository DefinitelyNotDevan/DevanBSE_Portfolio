# Phone Controlled Robot Arm
My project is the Phone Controlled Robot Arm. This 3 joint arm uses servos to controll it and has a claw. It uses bluetooth to allow the phone to communicate with Arduino through an app.

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Devan G | Mark Day School | Electrical Engineering | Rising 8th Grader 

![Headstone Image](https://raw.githubusercontent.com/BlueStampEng/BSE_Template_Portfolio/de8633f62b5da2234992a0178a6a72fd6df7e7e1/branding/BlueStamp-Logo.svg)
  
# Final Milestone
My final milestone was my modification. I choose to make my app better so that the controls wouldn't be as jerky. I tried to approach this in many ways such as using a clock. This however did not work because it would just get stuck in a loop. My second way of making my app better was sliders. Originally, I was going to send the slider location and the character for the motor to rotate but it ended up not working because the arduino couldn't interpret it. I fixed this by rounding the thumb position and sending it in a 1 byte number along with rewiring the HC-06 bluetooth module and changing my arduino code.

<iframe width="690" height="388.125" src="https://www.youtube.com/embed/HeM0xD3lTdw" title="Devan G Milestone 3" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

# Second Milestone
My second milestone was controlling my arm with my app. One of the challenges I faced while completing this milestone was that the phone that I received has andriod 11 but the app that came with the kit was ment for Android 10. I ended up making my own app using MIT App Inventor which solved the errors that I encountered. It would send characters to the arduino which would then interpret them and initate the motor correspondingly. However this app was still in the testing mode so all of the controls are quite jerky. My next step is my modifications.

<iframe width="690" height="388.125" src="https://www.youtube.com/embed/o-gyQRcRt54" title="Devan G Milestone 2" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

# First Milestone
My first milestone was assembling my arm and connecting it to my Arduino. I recieved my pieces in the Lafvin 4DOF Smart Robot Mechanical Arm Kit and then built them using the guide that came with the kit. I had some trouble with screwing in screws into the servo flaps and screwing in lock nuts but I solved it by using a different screwdriver than what was in the box and also using a wrench to keep the lock nut in place while I screwed it in. Eventually I finished assembling my arm except that when I was getting the parts out of the kit, one of the parts broke so currently my claw is disconected from the rest of my arm. My next step is to connect my arm to bluetooth and then connect it to my phone.

<iframe width="690" height="388.125" src="https://www.youtube.com/embed/DGngI1tAAQ4" title="Devan G Milestone 1" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
