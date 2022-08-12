# Noise Sensing Auto Recorder
I built a sound recorder that automatically records loud noises beyond a set threshold. The microphone detects the noise level of sounds and if it's greater than the set threshold it will save the recording.

![Project Image](Project image.HEIC)

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Timon Pinto | Irvington High School | Electrical Engineering | Incoming Junior

![Headstone Image](https://github.com/BlueStampEng/BSE_Template_Portfolio/blob/4655d8c4b2f1d0fa5912511d0b39542520b9f88e/branding/BlueStamp-Engineering-Logo-White.png)
  
# Final Milestone
My third and final milestone was modifiying the app code so that the sound recording saves to google drive instead of on the phone storage. I first created a google script so that a folder in my google drive could be accessed by my app. Then I used google API to link it to the app and I used the web feature on the MIT app inventor to set that folder, instead of the phone as the saving location. I did this by searching up tutorials on YouTube. A lot of them were outdated, but it worked.

[![Final Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1612573869/video_to_markdown/images/youtube--F7M7imOVGug-c05b58ac6eb4c4700831b2b3070cd403.jpg )](https://www.youtube.com/watch?v=F7M7imOVGug&feature=emb_logo "Final Milestone"){:target="_blank" rel="noopener"}

# Second Milestone
My second milestone was connecting all the parts and loading the app onto a phone. I used an Arduino nano, bluetooth HC 05, HIgh Sensitivity Arduino Microphone, a buzzer, and obviously wires. I was planning on using LEDS but decided not to. I connected all the components like in the schematic below. Then I downloaded the app I created with the MIT App Inventor onto an android phone. I connected it via bluetooth. Some challenges I faced were that some parts like the arduino nano and microphone weren't ordered on time so I had to wait and I had some problems with the arduino connectivity with ports, so i had to install new drivers.

<iframe width="690" height="388.125" src="https://www.youtube.com/embed/5jRdsDVFmwM" title="Timon P Milestone 2" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
# First Milestone
  

My first milestone was writing the code for the Arduino and creating an app to control everything. I got an Arduino and first set up initial values for the sensors and threshold. Then I setup bluetooth and the sensors to calulate average the sound level. As for the app, I used the MIT App Inventor to create one. The app works by connecting to the arduino via bluetooth. The microphone will detect noise level and if it crosses the set threshold, it will start recording. Once the sound level goes below the threshold, it stops recording and then is saved. You can also use it as a regular sound recorder, choosing when you want to record. One challenge I faced was that I at first didn't know how to use the bluetooth very well and also I had an error (confusion between integer type for the threshold). All I had to do was change the type and rename the label.

<iframe width="690" height="388.125" src="https://www.youtube.com/embed/bcs4oOWuk34" title="Timon P Milestone 1" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
