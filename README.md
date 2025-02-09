# FSM-Finite-State-Machine---Finite-State-Machines

ALL DRAWINGS AND DIAGRAMS IN POLISH IN FILE AUTOMATY
AND SOLUTION IN FILE 1

FSM (Finite State Machine) - Finite State Machines

Real sequential circuits operate according to a finite number of states, generating repeating sequences of characters at their outputs, which is why they are often called Finite State Machines (FSM).
FSM is a tool for modeling the behavior of sequential systems.
FSM is defined by a list of its states, its initial state and the conditions for each transition.
There are two types of FSM - Moore and Mealy machines.
Both types of machines meet the basic assumptions of a state machine, differing only in the way of the initial state.

Moore machine
A Moore machine is an FSM whose output state depends only on the current state of the machine

State diagram

Example: Design a 110 sequence detector that acts as a Moore machine

Transition table

Coded transition table

Hardware implementation of the detector

Check the operation of the circuit for different bit sequences. Place the results in a report.

1. Mealy machine
A Mealy machine is an FSM that defines the output data from the current state and from the input states.

State diagram

Example: Design a 110 sequence detector that acts as a Mealy machine

Transition table

Coded transition table

Hardware implementation of the detector

Check the operation of the circuit for different bit sequences. Place the results in a report. Also provide any observed differences in the operation of this machine compared to the previous one.

Comparison of Moore and Mealy Machines

Moore and Mealy FSMs are functionally equivalent

A Mealy FSM has a richer description and usually requires fewer states
(smaller area)
A Mealy FSM changes its output asynchronously to a clock as fast as
the input changes, which usually means that a Mealy FSM responds
one clock cycle earlier than the corresponding Moore FSM
A Moore FSM changes its output state synchronously to a clock
A Moore FSM has no connecting circuit between the input and the output
A counter is a Moore FSM

The computer is a powerful FSM

a. Prepare a report on all the steps in this lab

Each report should be given the following heading and include:
a detailed description of all the steps in the lab, along with your own conclusions about the work done
