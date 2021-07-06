# Analog Questions

A large portion of these questions are based off of the 18-220 Analog course from Carnegie Mellon.
You can find the course notes for the class [here](https://github.com/mikinty/CMU-Notes/blob/master/18-220/18220_exam_review.pdf).

## Basics

- How do you find the equivalent resistance of a circuit?
- How do you find the equivalent capacitance of a circuit?
- What a Thevenin and Norton equivalents, why do we use them?
- How does a capacitor work?
- How does an inductor work?

## Transistors

* A diode is made from a P and N type, explain how these two regions build a diode
* How does a transistor work and why would you use one in a circuit?
* What is the difference between a BJT and a MOSFET?
  * Why are MOSFETs more common in modern circuits?
* Explain the 3 main parts of a MOSFET, the gate, source and drain.
* What does it mean for a MOSFET to be on?
* What do we say a MOSFET behaves like a VCCS (voltage-controlled current source) in saturation?
* Design the following digital gates with MOSFETS:
  * NOT
  * OR
  * AND
  * XOR
* Explain why a CMOS is advantageous to a MOSFET.
* What are some applications of a MOSFET?

## Power, Capacitance and Inductance

* What is an RC circuit, and how do you solve it? What are some applications for it?
* What is an RL circuit, and how do you solve it? What are some applications for it?
* Why would you use an RC vs an RL circuit?
* What is a full-wave rectifier?
* What is a way to regulate current, why do we need to do this in certain circuits?
* What is a way to regulate voltage, and why do we need to do this in certain circuits?
* What is parasitic capacitance/inductance?
* What is a transformer, and why are they useful?
  * What is an ideal transformer, and what are the assumptions for it?
  * What are non-ideal transformer properties?
* Know the following switching power converters:
  * Buck Converter
  * Boost Converter
  * Flyback (Buck-Boost) Converter
* Draw an LC oscillator -- how does it behave?
* Draw an overdamped, critically damped, and underdamped time response for an RLC circuit.

## Op-Amps

* What are op-amps and why do we use them?
  * What is a transfer function in the context of an op-amp?
  * What is an ideal op-amp? Explain what it means for a non-ideal op-amp:
    * Nonzero input current
    * Finite input resistance
    * Finite output impedance
* Draw an inverting and noninverting op-amp
* Draw a differential op-amp
* What are the assumptions for an ideal op-amp?

## Signal Processing

* How does RFID technology work?
  * Draw the circuit for an RFID scanner and tag
* Draw a LPF (Low Pass Filter)
* Draw a High Pass Filter
* What is a Bode plot and what can it tell us?
  * Be able to take a transfer function and draw the Bode plot for it
* What is the Shannon-Nyquist sampling theorem?
* What is aliasing?

## Designing circuits

* Explain what parasitic capacitance is and how to handle it. Also understand it in the context of:
  * Where it might occur
  * Why we can't always increase clock speed
* Design a circuit that allows an Arduino to control a 12V RGB LED strip