# Analog vs. Digital

We often hear that we live in a digital age. There are a variety of reasons that digital systems have become so prevalent in our lives. In order to understand these reasons, it is good to start with an understanding of what a digital system is and how it compares to its counterpart, the analog system.

The goal of this chapter is to provide an understanding of the basic principles of analog and digital systems.

<!-- omit in toc -->
## Index

- [1.1 Differences Between Analog and Digital Systems](#11-differences-between-analog-and-digital-systems)
- [1.2 Advantages of Digital Systems over Analog Systems](#12-advantages-of-digital-systems-over-analog-systems)

## 1.1 Differences Between Analog and Digital Systems

In electrical systems, signals represent information that is transmitted between devices using an electrical quantity (voltage or current).

An **analog** signal is defined as a continuous, time-varying quantity that corresponds directly to the information it represents. in the analog world the electrical signal represents the actual information that is being transmitted and is considered analog. Analog signals can be represented mathematically as a function with respect to time.

In digital signaling the electrical signal itself is not directly the information it represents; instead, the information is encoded. The most common type of encoding is binary (1’s and 0’s). Digital signals are not represented using traditional mathematical functions; instead, the digital values are typically held in tables of 1’s and 0’s.

Examples of Analog Signals and Systems:

- The human interface to a computer;
- the electrical signal representing sound that travels down the wire of a set of headphones;
- the actual sound coming out of headphones;
- electricity coming out of a wall outlet;
- the voltage from a battery or solar cell.

Examples of Digital Signals and Systems:

- Information stored on a computer;
- the computer hardware that processes information;
- devices such as computers, tablets, and smartphones are also considered digital systems because their hardware and information being processed are digital;
- the information being transmitted over the Internet and wireless networks is digital.

[↥ Back To Top](#index)

## 1.2 Advantages of Digital Systems over Analog Systems

There are a variety of reasons that digital systems are preferred over analog systems. First is **their ability to operate within the presence of noise**.

Another reason that **digital systems are preferred over analog ones is the simplicity of the circuitry**.

In order to produce a 1 and 0, you simply need an electrical switch. If the switch connects the output to a voltage below the threshold, then it produces a 0. If the switch connects the output to a voltage above the threshold, then it produces a 1.

*It is relatively simple to create such a switching circuit using modern transistors.*

Analog circuitry, however, needs to perform the conversion of the physical quantity it is representing (e.g., pressure, sound) into an electrical signal all the while maintaining a direct correspondence between the input and output.

Since analog circuits produce a direct, continuous representation of information, they require more complicated designs to achieve linearity in the presence of environmental variations (e.g., power supply, temperature, fabrication differences).

Since digital circuits only produce a discrete representation of the information, they can be implemented with simple switches that are only altered when information is produced or retrieved.

A final reason that **digital systems are being widely adopted is their reduced power consumption**.

With the advent of complementary metal oxide transistors (CMOS), electrical switches can be created that consume very little power to turn on or off and consume relatively negligible amounts of power to keep on or off. *This has allowed large-scale digital systems to be fabricated without excessive levels of
power consumption.*

Analog circuits, on the other hand, require continuous power to accurately convert and transmit the electrical signal representing the physical quantity. Also, the circuit techniques that are required to compensate for variances in power supply and fabrication processes in analog systems require additional power consumption.

While analog systems **will always be needed at the transition between the physical** (e.g., microphones, camera lenses, sensors, video displays) **and the electrical world**, it is anticipated that the push toward digitization of everything in between (e.g., processing, transmission, storage) will continue.

[↥ Back To Top](#index)
