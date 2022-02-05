---
content_type: page
title: Course Text
uid: a1ae82bd-baca-7740-562c-d1f0ae24300c
---

The key ingredient in this course - and what differentiates it from many other related courses - is the uncertainty that is encountered whenever a built system is actually installed in the field. We may find uncertainty in the operating environment, whether it is a windy airspace, a bumpy road, or an obstacle-strewn factory floor. We also find uncertainty in the parameters that define a system, for example, masses and stiffnesses and dampings, torque constants, and physical size. Finally, since complex electromechanical systems involve sensors and actuators, we have to acknowledge uncertainty in measurement and feedback control. Ultimately, such systems are meant to accomplish specific objectives, and the designer's task is to achieve robustness, performance, and cost-effectiveness in the presence of uncertainty.

The notes given here are terse but intended to be self-contained. The goal is to provide fundamental relations useful for modeling and creating systems that have to operate with uncertainty. As a motivation, we focus a lot of attention on ocean waves as a prototypical random environment, and carry out simplified, linear motion and force analysis for marine structures and vehicles. Individual chapters are listed in the table below, or the entire text may be downloaded as one file. A separate compilation of solved homework problems is also available on the [assignments]({{< baseurl >}}/pages/assignments) page.

Hover, Franz S., and Michael S. Triantafyllou. _System Design for Uncertainty_. Cambridge, MA: MIT Center for Ocean Engineering, 2010. ([PDF - 1.3MB]({{< baseurl >}}/resources/mit2_017jf09_coursetext)) (Courtesy of Michael S. Triantafyllou. Used with permission.)

{{< tableopen >}}
{{< theadopen >}}
{{< tropen >}}
{{< thopen >}}
TOPICS
{{< thclose >}}
{{< thopen >}}
FILES
{{< thclose >}}

{{< trclose >}}

{{< theadclose >}}
{{< tropen >}}
{{< tdopen >}}
Chapter 1: Introduction
{{< tdclose >}}
{{< tdopen >}}
([PDF]({{< baseurl >}}/resources/mit2_017jf09_ch01))
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}


Chapter 2: Linear Systems

2.1 Definition of a system

2.2 Time-invariant systems

2.3 Linear systems

2.4 The impulse response and convolution

2.5 Causal systems

2.6 An example of finding the impulse response

2.7 Complex numbers

2.8 Fourier transform

2.9 The angle of a transfer function

2.10 The Laplace transform


{{< tdclose >}}
{{< tdopen >}}
([PDF]({{< baseurl >}}/resources/mit2_017jf09_ch02))
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}


Chapter 3: Probability Events

3.1 Events

3.2 Conditional probability

3.3 Bayes' rule

3.4 Random variables

3.5 Continuous random variables and the probability density function

3.6 The Gaussian PDF

3.7 The cumulative probability function

3.8 Central limit theorem


{{< tdclose >}}
{{< tdopen >}}
([PDF]({{< baseurl >}}/resources/mit2_017jf09_ch03))
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}


Chapter 4: Random Processes

4.1 Time averages

4.2 Ensemble averages

4.3 Stationarity

4.4 The spectrum: definition

4.5 Wiener-Khinchine Relation

4.6 Spectrum interpretation


{{< tdclose >}}
{{< tdopen >}}
([PDF]({{< baseurl >}}/resources/mit2_017jf09_ch04))
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}


Chapter 5: Short Term Statistics

5.1 Central role of the Gaussian and Rayleigh distributions

5.2 Frequency of upcrossings

5.3 Maxima at and above a given level

5.4 1/N'th highest maxima

5.5 1/N'th average value

5.6 The 100-year wave: estimate from short-term statistics


{{< tdclose >}}
{{< tdopen >}}
([PDF]({{< baseurl >}}/resources/mit2_017jf09_ch05))
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}


Chapter 6: Water Waves

6.1 Constitutive and governing relations

6.2 Rotation and viscous effects

6.3 Velocity potential

6.4 Linear waves

6.5 Deepwater waves

6.6 Wave loading of stationary and moving bodies

6.7 Limits of the linear theory

6.8 Characteristics of real ocean waves


{{< tdclose >}}
{{< tdopen >}}
([PDF]({{< baseurl >}}/resources/mit2_017jf09_ch06))
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}


Chapter 7: Optimization

7.1 Single-dimension continuous optimization

7.2 Multi-dimensional continuous optimization

7.3 Linear programming

7.4 Integer linear programming

7.5 Min-max optimization for discrete choices

7.6 Dynamic programming

7.7 Solving dynamic programming on a computer


{{< tdclose >}}
{{< tdopen >}}
([PDF]({{< baseurl >}}/resources/mit2_017jf09_ch07))
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}


Chapter 8: Stochastic Simulation

8.1 Monte Carlo simulation

8.2 Making random numbers

8.3 Grid-based techniques

8.4 Issues of cost and accuracy


{{< tdclose >}}
{{< tdopen >}}
([PDF]({{< baseurl >}}/resources/mit2_017jf09_ch08))
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}


Chapter 9: Kinematics of Moving Frames

9.1 Rotation of reference frames

9.2 Differential rotations

9.3 Rate of change of Euler angles

9.4 A practical example: dead reckoning


{{< tdclose >}}
{{< tdopen >}}
([PDF]({{< baseurl >}}/resources/mit2_017jf09_ch09))
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}


Chapter 10: Vehicle Internal Dynamics

10.1 Momentum of a particle

10.2 Linear momentum in a moving frame

10.3 Example: mass on a string

10.4 Angular momentum

10.5 Example: spinning book

10.6 Parallel axis theorem

10.7 Basis for simulation

10.8 What does an inertial measurement unit measure?


{{< tdclose >}}
{{< tdopen >}}
([PDF]({{< baseurl >}}/resources/mit2_017jf09_ch10))
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}


Chapter 11: Control Fundamentals

11.1 Introduction

11.2 Partial fractions

11.3 Stability in linear systems

11.4 Stability ↔ Poles in LHP

11.5 General stability

11.6 Representing linear systems

11.7 Block diagrams and transfer functions of feedback systems

11.8 PID controllers

11.9 Example: PID control

11.10 Heuristic tuning


{{< tdclose >}}
{{< tdopen >}}
([PDF]({{< baseurl >}}/resources/mit2_017jf09_ch11))
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}


Chapter 12: Control Systems — Loop Shaping

12.1 Introduction

12.2 Roots of stability — Nyquist criterion

12.3 Design for nominal performance

12.4 Design for robustness

12.5 Robust performance

12.6 Implications of Bode's integral

12.7 The recipe for loopshaping


{{< tdclose >}}
{{< tdopen >}}
([PDF]({{< baseurl >}}/resources/mit2_017jf09_ch12))
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}


Chapter 13: Math Facts

13.1 Vectors

13.2 Matrices


{{< tdclose >}}
{{< tdopen >}}
([PDF]({{< baseurl >}}/resources/mit2_017jf09_ch13))
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}