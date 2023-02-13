# Underground-Cable-Fault-Detector-over-IOT
Detects the exact location of faults in underground cables and transmits data over IOT
Underground transmission lines have lower visibility and less affected by weather, therefore,
they are more popular in urban area. However, the lower visibility of underground
transmission lines cause difficulty to maintain. Therefore, fault location for underground
transmission lines is a notable research topic. Power quality monitors serve as the voltage
and current sensors in an automatic fault location system. The system can detect and locate
both single-phase faults and multi-phase faults. Fault location in protective relays has been
available for over 20 years. These relays use impedance-based fault location algorithms,
typically from one terminal of the transmission line. The field case shows that the fault
location estimation is off by 475 feet in a 25Km composite line application. Impedance-
based algorithms are dependent on the system loading during the fault period, because one
of the required inputs is the load in each node of the system. Thus, due to the abnormal
behaviors of load variations it may be very difficult to estimate the correct load data to be
used in the algorithm. The data gathered in the specialized literature; the software PROTEUS
was used to simulate a single-phase circuit model subject to phase to earth failures. The
estimated fault distance is based on the measurements of voltage and current at the sending
and receiving ends, which are calculated by the software. The simulations are performed by
adopting the fault resistance value of Rf = 0.1ohm. This parameter, Rf, in principle, cannot
be measured, and therefore should not be regarded as an input parameter of the network,
although it influences the employment of techniques for fault location in the underground
system. Short Circuit Fault is when two conductors of a multi core cable come in critical
contact with each other due to insulation failure, it is so called as short circuit fault. The
concept of OHM’s law is used so fault can be easily detected and repaired. It’s a difficult
task to identify the faults in underground cables. By using Arduino controller, we can find
out exact the fault location. Once faults occur in the cable, the display unit displays the exact
fault location that displays which phase is affected in the cable. Regular conducting wire
along with resistors is used to represent the power cable. Four switches and the resistors have
been inserted at regular intervals on the wire. These switches are used to create faults. Power
supply of +5V is provided from one end of the cable and an LED.7805 voltage regulator
maintains the 5V DC supply. This voltage is used to handle the Arduino kit. Finally, the
information is uploaded to a website using the Wi-Fi module ESP8266.
