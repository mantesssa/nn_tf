# Overhead Plane Detector > raw images
https://universe.roboflow.com/skybot-cam/overhead-plane-detector

Provided by a Roboflow user
License: CC BY 4.0

# SkyBot

This is the dataset powering http://skybot.cam, an app that captures planes flying over top of my house.

![Skycam Tweet](https://i.imgur.com/DhxlR8J.png)

Upon the project gaining popularity on [Hacker News](https://news.ycombinator.com/item?id=30039597) from the above [tweet](https://twitter.com/LukeBerndt/status/1484916000139194375), I thought I'd share the dataset and an example model to make it easier for others to build a plane spotting app, too.

## About this Project
I built a system to take photos of all of the airplanes that fly over my house. Most of these planes are passing by at more than 30,000 feet! It uses ADS-B to track where the aircraft are relative to the camera, points the camera in the right direction and snaps a photo. I then run a few serverless functions that are running to detect where the aircraft is in the image and make a thumbnail. Much of the services are hosted on Azure. There's more details on the overall project here! http://skybot.cam/about. The project is [open source](https://github.com/IQTLabs/SkyScan/tree/main/ml-model/scripts) as a part of my work from IQT as well.


![Skybot Infrastructure](https://i.imgur.com/Lrv71Aq.png)


## About the Dataset
The dataset is of airfract that was captured as they flew overhead. It includes a mix of large and small passenger jets and an assortment of business jets. There are also a images with buildings and contrails, where there is not aircraft present.

### Use Cases

This dataset should allow for a plane dectector model to be built like for plane spotting and plane detection. 

## About Me
I'm Luke Berndt, I work on Azure products at Microsoft. You can learn more about me here: http://lukeberndt.com/