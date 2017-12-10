# AikidoPi

>Aikido is a Japanese Martial Art ... performed by blending with the motion of the attacker and redirecting the force of the attack rather than opposing it head-on. 
[*Aikikai Foundation*](http://www.aikikai.or.jp)

I've found myself in situations where it'd be very useful to have a tool which could redirect and manipulate data from various formats agnostic to the input or output transporting the data. For example, read a serial byte stream to a file, or drop random bytes from a UDP stream and redirect the output on another port.

From this I had an idea to define a set of interfaces for inputs, manipulations, and outputs that could be put together to easily accomplish this in a generic way. Once these interfaces are defined and a platform created around them, new implementations could be added as plugins as needed. By having this on a small portable computer such as a raspberry pi, the device could be taken into a lab or the field as needed and reconfigured easily to perform tests on the fly.
