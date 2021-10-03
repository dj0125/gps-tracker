# gps-tracker
How to make a GPS tracker using NpodeMCU

Story

Nowadays one of the popular services of online taxi booking services like Uber, Taxi for Sure, Zoom Car and many more have opened the world of real time location tracking. GPS plays a vital role both in allowing the user and also the service provider to track the taxi.
In this tutorial you will be making an Internet of Things(IOT) based GPS tracker that will track the position of the device in real time. In this project you can use security and transportation service.

Application:
    Tracking Car/Bike/almost anything.
    Can be used by School, in their school buses to track it and also parents will know the where about of the bus.
    In Spying someone.

Components Required:
    NodeMCU
    GPS Module
    Jumper Wires
    Battery/Power Supply ( 5v-9v)

Okay lets go step by step.

Step 1

First you have to need create a project on Blynk app. Click on New Project. Select Name And Device:
![WhatsApp Image 2021-10-03 at 1 34 28 PM](https://user-images.githubusercontent.com/91609293/135745394-ee654bff-1079-4bf9-b476-f7cef8b21aa3.jpeg)

Here I select Name GPS Tracker and Board NodeMCU then click Create:
![WhatsApp Image 2021-10-03 at 1 34 29 PM](https://user-images.githubusercontent.com/91609293/135745413-69df3f10-f735-476f-b9fc-e65f26d3c0fc.jpeg)

This is a very important step a auth Token is sent to your mail address:
![WhatsApp Image 2021-10-03 at 1 33 32 PM](https://user-images.githubusercontent.com/91609293/135745427-b7744a46-ad2e-43e8-ac9a-0a56c9873c04.jpeg)


Now show this interface and click on Plus sign.Now select Map:
![WhatsApp Image 2021-10-03 at 1 34 30 PM](https://user-images.githubusercontent.com/91609293/135745458-67d1c037-8d5a-48de-bb5b-80149473721a.jpeg)

After selecting map show like this interface
Go to map setting  select virtual pin VO
![WhatsApp Image 2021-10-03 at 1 34 32 PM](https://user-images.githubusercontent.com/91609293/135745481-8931de43-5305-4cf1-9d29-a04ffe6b53be.jpeg)
![WhatsApp Image 2021-10-03 at 1 34 32 PM (1)](https://user-images.githubusercontent.com/91609293/135745478-6ff49194-c9cf-40b7-9ef7-0157129b48d1.jpeg)
![WhatsApp Image 2021-10-03 at 1 34 31 PM](https://user-images.githubusercontent.com/91609293/135745480-5f30e1db-d098-40cd-8601-10fc716a8571.jpeg)


Complete your app setting now you have to need Arduino setting. Now go to your mail copy auth and past on arduino char auth[] this position

Ok now almost finished only set your wi-fi name and password then upload code on NodeMCU and set on your device like circuit

NodeMcu to GPS connection. If all are ok then final show:

GPS Taker final interface. Download Arduino firmware and library Click Here.
Schematics
-nodemcu-gps-tracker.

