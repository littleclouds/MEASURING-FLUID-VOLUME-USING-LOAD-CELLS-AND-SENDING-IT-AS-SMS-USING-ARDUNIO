# MEASURING-FLUID-VOLUME-USING-LOAD-CELLS-AND-SENDING-IT-AS-SMS-USING-ARDUNIO UNO

## INTRODUCTION

The operation of an electronic weighing scale can be split into two parts for understanding. The first
being the sensing part and the second, the processing part. The sensing part essentially contains a
collection of sensors which measure the weight and convert it into electrical form for processing.
The processing part then takes this signal and displays it on the LCD for a readout. The sensors
used for measurement are known as load-cells.

A load cell is basically a transducer (a device which converts one form of energy into other form)
that converts a force (the weight in this case) into an electrical signal. The load-cell consists of a set
of strain gauges which get deformed upon application of a pressure (strain) on them. This
deformation is measured as an electrical signal so that it is suitable for processing.
Because of the fact that the applied strain changes the electrical resistance of the wire, a load cell
normally consists of 4 strain gauges that are connected as a wheatstone bridge.

A collective output of the 4 strain gauges is obtained that is in a order of a few millivolts. The
arrangement in a weighing scale is such that, the object that is placed on the platform exerts the
force onto carefully placed load-cells beneath it. These transducers generate an electrical signal
which is then amplified by the use of a high quality signal amplifier for it to be suitable in the
subsequent sections of electronics in the device.

This signal after amplification is taken by the processing part which converts the analog voltage
into a digital form with the help of a precision analog to digital converter which is then displayed on
to the digital read out.

The displayed weight can be relayed by the GSM module interfaced with the arduino uno as an
SMS to the phone no. of person
This part of the processing and the digital read out is handled by the use of a Micro processor
Control Unit (MCU) which can perform other necessary operations based upon the design necessity.
These operations can be maintenance of some statistical data, zero adjustment, interface to a PC
system etc.

Care is taken to calibrate these devices before they are used. This is done because of the uniqueness
of the components that are used in them. This is an important step without which the device
provides a wrong reading


## Required Components:
• Arduino Uno
• Load cell (40kg)
• HX711 Load cell Amplifier Module
• 16x2 LCD
• Connecting wires
• USB cable
• Breadboard
• Nut bolts, Frame and base
