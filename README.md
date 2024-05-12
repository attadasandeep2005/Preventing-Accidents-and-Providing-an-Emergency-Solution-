<h1># Preventing-Accidents-and-Providing-an-Emergency-Solution</h1>
Arduino Code for integration of GSM module, GPS module, and various sensor to  preventing accidents and providing an emergency solution <br>

<p>In India, traffic accidents have become a major worry. The main causes of traffic accidents are careless and fast-moving drivers. Road accidents have increased as a result of greater traffic disorder brought on by increased automobile use. Some people can't get to the hospital in time after an accident because of traffic congestion, an ambulance, or not having the right information. This is an automated accident prevention, detection, and emergency response system based on the Internet of Things (IoT).In the event of an accident, the system is intended to transmit signals to the closest hospital. It determines whether or not a driver has had alcohol. The automobile will automatically stop until the alcohol odor is eliminated if the sensor detects it. Additionally, it recognizes when the driver is dozing off as a result of the ride and activates the buzzer. The automobile will stop when it senses an object that is closer than thirty centimeters away. In the event of an accident, the system will send an SMS with the accident location to the closest hospital.</p>

## Feature

:heavy_check_mark: Accident Detection
:heavy_check_mark: Accident Prevention
:heavy_check_mark: Emergency Solution

## How Does It Works

* Accident Prevention


      *To prevent accidents, we have implemented four sensors:
      *Ultrasonic: This sensor will stop the car when it detects an object within 30 cm of the vehicle.
      *PIR: Used to monitor the driver's motion, instantly stopping the car if the driver moves out of its range.
      *MQ3: Determines whether the driver is under the influence of alcohol.
      *Buzzer: When the PIR sensor detects that the driver is falling asleep, it will sound an alarm.
  
* Accident Identification
  
    One sensor was all we needed to detect an accident.

    * Vibrator sensor: This will emit a signal in the event of an auto accident. We implement an emergency solution based on the signal. 
* Emergency Resolution 
    We employed a server and a few modules in the emergency solution.
    * GPS NEO 6M: Find the latitude and longitude of your car right now.
    * SIM 800L: Send an SMS to the phone number that responds to your post-request using your latitude and longitude.
    * Server: The server determines the shortest route between hospitals and the scene of the accident, then provides hospital information in response.

##  Circuit Diagram

![circuit_diagram](https://github.com/attadasandeep2005/Preventing-Accidents-and-Providing-an-Emergency-Solution-/assets/145467099/f7d9443b-871f-4a7c-85c3-18db3e800bf3)
