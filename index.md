# Noise Sensing Auto Recorder
I built a sound recorder that automatically records loud noises beyond a set threshold. The microphone detects the noise level of sounds and if it's greater than the set threshold it will save the recording.

<img src="https://github.com/timonpinto/timonpinto/blob/main/Project%20image.png?raw=true" width="400" height="200" />


| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Timon P | Irvington High School | Electrical Engineering | Incoming Junior

<p align="center">
<img src="https://github.com/timonpinto/timonpinto/blob/main/Headstone.png?raw=true" width="403" height="302" />
</p>
  
# Final Milestone
My third and final milestone was modifiying the app code so that the sound recording saves to google drive instead of on the phone storage. I first created a google script so that a folder in my google drive could be accessed by my app. Then I used google API to link it to the app and I used the web feature on the MIT app inventor to set that folder, instead of the phone as the saving location. I did this by searching up tutorials on YouTube. A lot of them were outdated, but it worked.

<iframe width="690" height="388.125" src="https://www.youtube.com/embed/7h4n2luKAAU?color=white&rel=0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

# Second Milestone
My second milestone was connecting all the parts and loading the app onto a phone. I used an Arduino nano, bluetooth HC 05, HIgh Sensitivity Arduino Microphone, a buzzer, and obviously wires. I was planning on using LEDS but decided not to. I connected all the components just like in the schematic below. Then I downloaded the app I created with the MIT App Inventor onto an android phone. I connected it via bluetooth. Some challenges I faced were that some parts like the arduino nano and microphone weren't ordered on time so I had to wait and I had some problems with the arduino connectivity with ports, so i had to install new drivers.

<iframe width="690" height="388.125" src="https://www.youtube.com/embed/5jRdsDVFmwM?rel=0&modestbranding=1" title="Timon P Milestone 2" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<p align="center">
<img src="https://github.com/timonpinto/timonpinto/blob/main/schematic.png?raw=true" width="403" height:="359" />
</p>

# First Milestone
  

My first milestone was writing the code for the Arduino and creating an app to control everything. I got an Arduino and first set up initial values for the sensors and threshold. Then I setup bluetooth and the sensors to calulate average the sound level. As for the app, I used the MIT App Inventor to create one. The app works by connecting to the arduino via bluetooth. The microphone will detect noise level and if it crosses the set threshold, it will start recording. Once the sound level goes below the threshold, it stops recording and then is saved. You can also use it as a regular sound recorder, choosing when you want to record. One challenge I faced was that I at first didn't know how to use the bluetooth very well and also I had an error (confusion between integer type for the threshold). All I had to do was change the type and rename the label.

<iframe width="690" height="388.125" src="https://www.youtube.com/embed/bcs4oOWuk34?rel=0&modestbranding=1" title="Timon P Milestone 1" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
