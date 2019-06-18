# DA-compiler

## Introdution 
DA-compiler is a compiler that generates a simulation automaton from a description written in a domain specific language that is used to describe GUI components and interactions.

## Implementation
I implemented the AFComposer component that allows to compile the specification program to generate the automaton.

* The component takes as input a program written in an ".ihm" extension text file
* The component must generate a finite state automaton in the form of a transition table in a text file extension ".aef"
* A manipulated HMI component table coded in a ".gui" extension text file, the components are described in the specification program.

