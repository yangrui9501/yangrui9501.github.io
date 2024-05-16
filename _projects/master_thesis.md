---
title: "Robust Second-Order Sliding Mode Control Law Design and Realization for Nonlinear Mechanical Systems"
collection: projects
type: "Master Thesis"
# permalink: /projects_test/2014-spring-teaching-1
venue: "National Cheng Kung University (NCKU), Master Thesis (Instructor: Chao-Chung Peng)"
date: 2021-01-15
location: "Tainan, Taiwan"
paperurl: 'https://thesis.lib.ncku.edu.tw/thesis/detail/1bedc1f055d88d5fba37764b81eb6d6a/?seq=1'
---

The master thesis focuses on the robust control law design for the nonlinear mechanical systems. Including the motion control of the DC motor systems, single-axis reaction wheel positioning, and spacecraft attitude control via multiple reaction wheels. My master thesis can be found in [here](https://thesis.lib.ncku.edu.tw/thesis/detail/1bedc1f055d88d5fba37764b81eb6d6a/?seq=1).

## DC Motor Positioning Control

The following videos demo the positioning control of a DC motor using the proportional-integral-derivative (PID) control and the super-twisting control (STC). It can be found that both controllers can track the desired trajectory well.

### PID Controller

<iframe width="560" height="315" src="https://www.youtube.com/embed/OSMh8fcpw88" title="Positioning Control of Servo Motor: PID Controller" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

### STC Controller

<iframe width="560" height="315" src="https://www.youtube.com/embed/1G4lbZZYg68" title="Positioning Control of Servo Motor: Super-Twisting Controller" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- <iframe width="560" height="315" src="https://www.youtube.com/embed/WVu-fAEO4OE" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> -->

## DC Motor Positioning Control with External Disturbance Input

However, when the system is subjected to unknown external disturbances, the PID controller cannot perfectly track the desired command, whereas the STC can. In the following demo, the exogenous PWM signal is imposed as the disturbance source. The experiment results reveal that the STC has superior robust performance compared to PID.

### PID Controller

<iframe width="560" height="315" src="https://www.youtube.com/embed/E_wRcExUixA" title="Positioning Control of Servo Motor: PID Controller (with exogenous disturbance)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

### STC Controller

<iframe width="560" height="315" src="https://www.youtube.com/embed/WVu-fAEO4OE" title="Positioning Control of Servo Motor: Super-Twisting Controller (with exogenous disturbance)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>


## Single-Axis Reaction Wheel Positioning Control

This video demonstrates the positioning control of the single-axis reaction wheel platform via the super-twisting controller.

<iframe width="910" height="520" src="https://www.youtube.com/embed/CLiuZAgAwfM" title="Positioning Control of Reaction Wheel Module: Super-Twisting Controller" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>