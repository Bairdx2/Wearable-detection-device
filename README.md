# Wearable detection device

This is a highly portable and wearable device. The device will give an individual the ability to screen patients for Covid-19, lung infections, diabetes. The device will contain many sensors with the intention of providing information regarding environmental and user physiological conditions. The image below is of the first version of the device.

![alt text](https://i.imgur.com/qJBREET.png)

***Figure 1***: V1.0

## Table of Contents:
- Motivation
- Insight into working principle
- V1.0
- Future work
##

### Motivation:
The concept of the wrist sensor system came about because of apparent lacks Covid-19 testing. The polymerase chain reaction (PCR) test detects RNA associated with Covid-19 and is highly accurate but inconvenient due to the long wait turnaround times for results (1 day - 1 week). The antigen test (rapid test) detects proteins associated with Covid-19 and while not nearly as accurate as the PCR test, the turnaround times are remarkable slower (20 min - 1 day). The main driving force for this project was to make a device that could not only give a highly accurate prognosis in real time but also be highly portable and customizable.

##
### Insight into working principle:
The device is capable of detecting Covid-19 by measuring human breath with gas sensors. Since the initial spread of Covid-19 in the US, there has been a considerable amount of scientific research into specific biomarkers found in patients with Covid-19. Some of these biomarkers exist in very low quantities (ppm - ppb) in human breath and thus, highly sensitive gas sensors are required to measure them.

##
### V1.0:
Version 1 was designed from scratch and was mainly a learning excercise to gain practice with designing a wearable device consisting of two boards. One board contains all of the sensors and the other board supplies power.

**Board 1 sensors and capabilities:**
- gas sensor (Biomarker detection)
- Temperature sensor
- Wireless transmitter (Data tranmission)
- OLED screen (Data display)
- Microcontroller

**Board 2 capabilities:**
- Voltage boosting circuit
- Recharging circuit

##
### Future work:
While the focus of the device now is to be a prognosis tool for detecting diseases, the platform is highly modifiable and there are plans to use it for other interesting non-health related applications.
