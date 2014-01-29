generating-electricity-from-electromagnetic-wave-in-the-atmosphere
==================================================================


       With Portable electronic devices becoming a basic part of life, powering of these devices has
always been a problem. Although many new technologies made possible the appearance of very
low power wireless electronic devices, the problem still exists with these devices making them
not to be wireless completely due to power requirements. As a solution, almost all of these
devices are currently powered by batteries. However, batteries have got some limitations of
which the major one is the need to recharge them periodically using power outlets. This limits
the use of the electronic devices in areas where power outlets are not easily accessible.


      The main focus of this project is to design a system that can capture EM energy from the air and
convert it into DC power to charge low power portable electronic devices. The source of the
electromagnetic energy may be a GSM/CDMA base station, Wi-Fi access point, Bluetooth
transmitter or any other source within the operating frequency range of the system. Due to the
diversified nature of these sources and since no means of measuring the signal strength from
them was available while conducting this thesis; it is focused on designing a system that can
optimally work in most of these cases rather than assuming a single type of source.


purpose


  It can be used in non-electrified rural areas of our country for recharging cell phones by
integrating a power pump in each GSM/WCDMA/CDMA base station.
 The charger can be used with a local transmitter (Bluetooth, Wi-Fi …) to recharge many
electronic devices simultaneously and without the need to be near or in the same room
to the power outlet.
 The wireless charger can be integrated with cell phones and continuously recharge the
battery and hence no plug in charge pod at all.
 It can also integrated in nodes of a wireless sensor networks enabling the nodes will
exist for ever.
 For academic purpose it will demonstrate wireless transmission of power, which is a big
area of research these days. It also tests the achievability of harvesting enough free
energy from ambient sources of EM energy to charge low power electronic devices.




                                System Design and Analysis
                                
  At the top level, wireless charging system proposed in this thesis comprises of an antenna to
collect electromagnetic energy and a circuit for conditioning the power received from the
antenna.

  The antenna is a multiband rectangular patch antenna capable of capturing EM energy from
various sources over a large spectrum. The power conditioning circuit consists of a
multiplier/rectifier circuit which converts AC signal to DC and performs a DC- DC conversion
followed by a voltage regulator to supply the electronic device with a constant voltage. The
energy storage is the battery already being used in the electronic device

  Basics of Charge Pump
Charge pump is a rectifier/multiplier circuit that when given an input in AC is able to output a
DC voltage typically greater than a simple rectifier can generate. In other words it is an AC to DC
converter that both rectifies the AC signal and elevates the DC level. This circuit is a base of
power converters such as the ones that are used for many electronic devices today, though these
circuits are more complex than the charge pumps used in this thesis.
Charge pump circuits consist of repetitive components that progressively increase the output
voltage in a DC form. Theoretically, by increasing the number of stages of the pump it is possible
to deliver any required output voltage, but at the cost of decreasing the current, since the circuit
must obey Ohm’s law. In their construction, voltage these circuits consist chiefly of rectifiers and
capacitors. The rectifiers used may be half wave full wave rectifiers.
The simplest and the basic building block of these circuits is a voltage doubler circuit, which
gives a DC out that is twice(double) of the magnitude of the input AC signal.


Charge Pump Design


     From the very nature of the system, the power conditioning circuit for the wireless charging
system should meet the following requirements.
• It should be able to operate at low power level as the power that could be collected from
EM energy sources is expected to be low. Hence, all active components that are used in
the design should be turned on with low signal level.
• It should consume very low power as the total power transferred in the circuit to the
electronic device is low. This requires simple electronic circuit with the minimum
possible number of active and passive components. In addition, the power dissipation of
these components should be low.
• The power/voltage regulator should be able to provide a stable output to the electronic
device under varying input conditions. But at the same time it should be simple enough
so that it will not consume high power.
• Frequency dependent components should have their best performance in the frequency
band in which the system is designed to operate.
Power converter circuits in many electronic devices have a lot of protective circuitry along with
circuitry to reduce noise. They also use a transformer to isolate the input from the output to
prevent overload of the circuit and user injury by isolating the components from any spikes on
Wireless charging system
BDU (IoT), SCEE Page 15
the input line. However, in the system designed in this thesis such a low power level is being
used that a circuit this complex would require more power than is available, and it would
therefore be very inefficient and possibly not function. Therefore, it is necessary to use a simple
design.
In this thesis, a charge pump circuit that meets the above requirements is designed.



                       If you are interested in this work, please contact me via my email brookyaleg@gmail.com so that I can provide you the full research paper and images of the prototype.
