#LPG-Leakage-Detector-without-using-Microcontroller
Developed an LPG leakage detector using dual comparator, LM7805 regulator, TIP122 transistor, and MQ6 sensor. The system triggers an alert when gas exceeds a threshold, providing a low-cost, reliable safety solution adaptable for households to prevent potential hazards.

🛑 Problem Statement

LPG (Liquefied Petroleum Gas) is commonly used in households for cooking and heating. However, accidental gas leakage can lead to serious hazards such as fire, explosion, and health issues.
Many existing detectors rely on microcontrollers, which increase cost, complexity, and require programming knowledge. A low-cost, standalone, and reliable system is needed to detect LPG leakage instantly and trigger an alert to prevent accidents.

🎯 Strategies

Sensor Selection

Use MQ6 gas sensor which has high sensitivity to LPG.

Signal Conditioning

Apply dual comparator circuit to compare sensor voltage with a predefined threshold.

Power Regulation

Implement LM7805 voltage regulator for stable 5V supply to the circuit.

Alert Mechanism

Use TIP122 transistor as a driver to activate buzzer/alarm when gas level crosses the limit.

Low-Cost & Simplicity

Avoid microcontroller to keep design simple, reliable, and inexpensive.

✅ Solution

A hardware circuit was designed using MQ6 sensor, dual comparator, LM7805 regulator, and TIP122 transistor.

When gas concentration is below the threshold, the system remains inactive.

When concentration exceeds the safe limit, the comparator output triggers the transistor, activating a buzzer/alarm.

This provides an immediate warning system that is:

Low-cost

Reliable

Easy to implement in households

Requires no programming or microcontroller

## 🔄 Project Flowchart  

   Start
    !
Initial Power Supply
     !
Is Sensor Output 
greater than
 threshold?
    !
Activate Buzzer
    !
Gas Detection

## ⚡ Circuit Diagram  

![Circuit Diagram](images/circuit.png)  

![Untitled](https://github.com/user-attachments/assets/0b2987a0-c202-4cb8-b0d6-1baef35a1a39)




