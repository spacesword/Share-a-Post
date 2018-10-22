title: Skinput Technology The Future
author: Amit
tags:
  - Technology
categories:
  - Tech News
  - Future Technology
date: 2018-02-09 15:43:00
---

### Skinput Technology
![](https://upload.wikimedia.org/wikipedia/en/a/ae/Skinput_arm_buttons.JPG)
     
#### Introduction
    

Skinput is a technology, which uses the surface of the skin as an input device. Microsoft Company has developed Skinput, a technology that appropriates the human body for acoustic transmission, allowing the skin to be used as an input surface. In particular, we resolve the location of finger taps on the arm and hand by analyzing mechanical vibrations that propagate through the body. To capture this acoustic information, they developed a wearable armband that is non-invasive and easily removable. It was developed by Chris Harrison, Densely Tan, and Dan Morris of the Microsoft Research's Computational User Experiences Group (MRCUEG). 

Skinput allows the user to simply tap their skin in order to control audio devices, play games, make phone calls.
Skinput technology combines the highly developed machine learning and simple bio-acoustic sensors to make people avail their forearms and fingers as touch pads.
Its first public appearance was at Microsoft's Tech Fest 2010.
<style>
@media (max-width: 767px) {
  .temp{
    width: 300px;
    height:500px;
  }
}

@media (min-width:px) {
  .temp{
   width: 300px;
    height:500px;
  }
}
</style>
<iframe  src="https://www.youtube.com/embed/Pz17lbjOFn8" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen class="temp" style="margin-left:2%"></iframe>

#### Principle

It listens to vibrations in your body and also responds to the various hand gestures.
The arm itself acts as an instrument.
It works on the principle of bio-acoustic.
The arm band detects the acoustic signals and converts them into electronic signals.



Skinput, the system is a combination of two technologies:
    a. The ability to detect the ultra low frequency sound.
    b. The ‘Pico’ projectors.
Pico projectors apply the use of projector in a handheld device.
An acoustic detector detects the ultra low frequency.


#### What Makes It Work?

__Bio-Acoustics and Sensors__: It’s the armband sensing element that captures the various sort of the vibrations once users faucet their fingers at the skin surface. 

__Bluetooth__: It’s used to connect the Bio-Acoustic sensing element for mobile in order so that information will be transferred to many being controlled devices like mobile, iPod or laptop. 
Pico-Projector: Pico-Projector is employed as Output device that show menu. It’s employed in mobile and camera to show the project.



__Pico projectors__ are tiny battery powered projectors - as small as a mobile phone - or even smaller: these projectors can even be embedded inside phones or digital cameras. Pico-projectors are small, but they can show large displays (sometimes up to 100").
![](https://images.adsttc.com/media/images/59f7/9cf0/b22e/3853/dd00/002a/slideshow/Technology-for-architects-in-2017-.jpg?1509399789)

When a finger taps the skin, several distinct forms of acoustic energy are produced. Some energy is radiated into the air as sound waves; this energy is not captured by the Skinput system. Among the acoustic energy transmitted through the arm, the most readily visible are transverse waves, created by the displacement of the skin from a finger impact. When shot with a high-speed camera, these appear as ripples, which propagate outward from the point of contact.

#### Wave Propagations
 ![](https://image.slidesharecdn.com/yamskin-150317102602-conversion-gate01/95/skinput-technology-10-638.jpg?cb=1426588032)

We highlight these two separate forms of conduction – transverse waves moving directly along the arm surface, and longitudinal waves moving into and out of the bone through soft tissues – because these mechanisms carry energy at different frequencies and over different distances.


#### Bio-Acoustic Sensor
  ![](http://wrtassoc.com/wp-content/uploads/2010/05/Armband.jpg)

It is a low-cost cantilever-type vibration sensor loaded by a mass to offer high sensitivity at low frequencies. The pins are designed for easy installation and are solder able.

 
Inside the Skinput armband is a pair of sensor arrays, each consisting of five sensors. When the armband is wrapped around your arm, one array sits on top of your arm and the other below it, giving the sensors the widest range of useful data.

#### How It Works?


In Skinput, a keyboard, menu, or other graphics are beamed onto a user's palm and forearm from a pico projector embedded in an armband.
An acoustic detector in the armband then determines which part of the display is activated by the user's touch.
Their software matches sound frequencies to specific skin locations, allowing the system to determine which “skin button” the user pressed.



#### Processing : Model

An audio interface is captured from sensors and is converted to digital signal form. In the skinput prototype system, we employ an audio interface to digitally capture the information from the sensor arrays in the armband. This audio interface was connected through a Firewire to the computer. In the computer there is a thin client composed in C interfaced with the gadget utilizing the Audio Stream Input/Output that is ASIO protocol. The sampling rate for each channel was set to 5.5kHz range. This diminished sampling rate makes the skinput approach easily convenient to embedded proces­sors. Data is transferred through a local socket to our essential application, which is composed in java. Mainly three functions are performed by this java programs. The first one, it produces a live visualization of the signal or data from the sensor arrays. In second, the inputs from data stream are segmented in to independent taps or instances. The classification of these input instances is carried out in the third section. Real-time classification is done using SVM.
Corresponding action is implemented to system.

#### Support Vector Machines (SVM) are used for this purpose.

In order to classify among different fingertips and different locations on the skin, SVM is employed.
The software needs to be trained with different skin locations as different input vectors to the software.
Once it is trained, the action is performed on the skin itself.

![](https://www.google.co.in/url?sa=i&rct=j&q=&esrc=s&source=images&cd=&cad=rja&uact=8&ved=2ahUKEwjUooiCm5nZAhUGSY8KHWDHAywQjRx6BAgAEAY&url=https%3A%2F%2Fwww.researchgate.net%2Ffigure%2FHyperplane-blue-line-representation-in-SVM-Red-and-blue-circles-represent-data-points_268232391&psig=AOvVaw0WMB-Qk4tuPHN06UV_aF-w&ust=1518278686355747)

A Support Vector Machine (SVM) is a supervised machine learning algorithm that can be employed for both classification and regression purposes. SVMs are more commonly used in classification problems.
SVMs are based on the idea of finding a hyperplane that best divides a dataset into two classes.

Support vectors are the data points nearest to the hyperplane, the points of a data set that, if removed, would alter the position of the dividing hyperplane.
Because of this, they can be considered the critical elements of a data set.

<img src="https://github.com/Sdev0245/Images/blob/master/t1.png?raw=true" >

For a classification task with only two features, you can think of a hyperplane as a line that linearly separates and classifies a set of data.
The further from the hyperplane our data points lie, the more confident we are that they have been correctly classified, therefore we want our data points to be as far away from the hyperplane as possible, while still being on the correct side of it.
So when new testing data is added, whatever side of the hyperplane it lands will decide the class that we assign to it.

The distance between the hyperplane and the nearest data point from either set is known as the margin. 
The goal is to choose a hyperplane with the greatest possible margin between the hyperplane and any point within the training set, giving a greater chance of new data being classified correctly.
But what happens when there is no clear hyperplane?
This is where it can get tricky. Data is rarely ever as clean as our simple example above. A dataset will often look more like the jumbled balls below which represent a linearly non separable dataset.


 
In order to classify a dataset like the one above it’s necessary to move away from a 2d view of the data to a 3d view. Explaining this is easiest with another simplified example. Imagine that our two sets of colored balls above are sitting on a sheet and this sheet is lifted suddenly, launching the balls into the air. While the balls are up in the air, you use the sheet to separate them. This ‘lifting’ of the balls represents the mapping of data into a higher dimension. This is known as kernelling.
![](https://66.media.tumblr.com/9bffea56372d28d2a30f80557451e824/tumblr_inline_o9aabehtqP1u37g00_540.png)
 
Because we are now in three dimensions, our hyperplane can no longer be a line. It must now be a plane as shown in the example above. The idea is that the data will continue to be mapped into higher and higher dimensions until a hyperplane can be formed to segregate it.



#### Implementation

If a person is paralyzed or physically disable, we can implement this technology. It provides a projected graphical interface on the skin, so the person who is paralyzed or physically disable, they can use it easily like making a call, playing game, control music player application etc.
Through the help of Skinput technology, we can implement it in education system like we can use calculator or browsing through a mobile phone etc.
We can turn our arm into a cellphone.
It will be possible to make calls by just typing numbers that flash on your forearm.
All other functions can also be performed using Skinput. 
We can also increase or decrease the volume or change the track of our music players like the i-Pod without actually touching the gadget.

#### Advantages

No need to interact with the gadget directly.
The projector interface can appear much larger than it ever could on a device’s screen.
Arm can be brought closer to face (or vice-versa) to see the display close up.
People with larger fingers get trouble in navigating tiny buttons and keypads on mobile phones. With skinput, this problem disappears.

#### Disadvantages

Though the band seems easy enough to slip on, many people would not wear a very big band around their arm for the day.
Not enough research has been conducted on this product to test the possible skin diseases or types of cancer; one can get from using this product.
This technology might start up at very high cost which will not be affordable for the common man.

####  Conclusion

The most profound achievement of Skinput is proving that the human body can be used as a sensor.
A person might walk toward their home, tap their palm to unlock the door and then tap some virtual buttons on their arms to turn on the TV and start flipping through channels.
Extensive Research is going on currently on Skinput to:
       
  a). make the armband more smaller.
       
  b). Incorporate More Devices with This System.
       
  c). Extend accuracy level.