# Sasquatch


## Big Picture:
<img height=400, width=275 src="https://github.com/ItsZeusBro/Sasquatch/blob/ae69abf834ebac22c671279b0f20d12f85d308fb/sasquatch.jpeg">

In general any function can be solved with the following:
1. Vectorize an input, and its corresponding expected output
2. run simulations until a solution is found.
3. check simulation that works (basically a simulation works if it produces the answer for a given simulation and a corresponding rules set and terminating generation) against other inputs for the function that serves the same purpose
4. The more times you pass new tests with the given simulation, the more perfect the function. 
5. Eventually we want to find a function for a contiguous set of inputs to greatly optimize the functions performance in a hardware simulation environment

In general we can solve any problem including the most general function of "deduction". So all deductions can be achieved with a single simulation, rule set, and generation, by piping the output of the simulation back into the simulation to find the next deduction.


## Future Optimization:
One day we can actually run sasquatch to find a high level equivalent of sasquatch. This will greatly optimize Sasquatch for faster run times! 
On another note, we can have sasquatch learn to generalize simulations into functions, by using existing functions to produce tests and having sasquatch produce functions that pass the tests.

Functions that are found and enshrined can be infused into the simulation engine on the way to solving unknown problems. This is only a good idea if they are truly optimal, otherwise dependant solutions become outdated and sub-optimal if they dont keep up with the more optimal function. In otherwords, if A depends on B and B gets replaced with B' then A is still dependent on B and B' has no bearing on the impact of A and all the compute time spent on finding A with B gets wasted if A is to improve.

## A good reason for Arbitrary Deterministic Encoding
Arbitrary symbols that are reused to represent any characther (as opposed to one to one encoding of literals) means we can get lucky overtime if inputs and outputs across literals share the same input output solution relativity. 

So if abc as input uses 123 for its translation and def uses 123 for its translation, they both share the same relativity for all function inputs and outputs, and if the problem is associated with this relativity, (like problems involving mathematical induction), then we can probably have the same simulation and generation output correspond to multiple inputs and outputs for different functions. This might find higher order functions that serve more than one purpose! This could converge on the physics of calculation (a general purpose simulation)!

## More Applications:
We can eventually encode assembly language instructions and run them in a virtual machine to make middle tier functions for the near term future. We want to focus on Sasquatch itself, slowly replacing all of its core functionality to scale its performance.

Finally, we want to use sasquatch to find an equation that can compute any simulation (any generation of a simulation) in one step

## Design Goals
We would like to calculate the computational cost of each generation for any nxn matrix a priori, and gather experimental data to see bang for buck performance of real solutions over-time, then fork the code-base and optimize simulations for a single matrix type that give us the most efficiency. (we can do more than one to diversify overtime)

## Different Modes
1. Nnary
- This means that a set of the input symbols are translated to a ordered variable set that is arbitrary
- rules are calculated based on this configuration which is dynamicly related to the number of codes used for translation.
- Therefore the input is substituted for variables which are positionally related to one another in a relativity that
- is deterministic
2. Binary
- This is traditional cellular autmoata which is translated using the binary code of the underlying input unicode code point
3. Hexary
- This uses 16 or 32 modes for each cell in any size or dimension matrix representation. This means that we have a literal and
- not a symbolic translation of the underlying input

## Moon Shot:
This is basically a new hypothesis for how truth and existentialism works

It relies on the truth properties of "giberish". Automata produce simulations between two propositions where each proposition follows the same translation encoding rules. If the second proposition follows from the first proposition, then we say that so long as this simulation is not proved inconsistent in the future with two other propositions, then the first simulation creates a valid proof for the connection between the first two propositions.

We call this impercievable simulated automata which is the logical stuff between propositions in the form of a simulated environment "giberish", even though we presume it to have meaning.

The reason we presume it to have meaning is because of the following argument:
1. All logic comes down to three types of inferences: Invalid, valid, tautological
2. If something is valid or tautological, it means there is no contradiction. On the flipside, if something is invalid it means there is contradiction
3. All propositions are either positive, or negative in their meaning. If something is negative we can replace the entire proposition with another proposition with a single negation.
4. We can carry a single bit in an automata simulation that creates a positive or negative translation.
5. Therefore if there is no contradiction in the simulation and the second proposition follows from the first then we have a valid existential proof


<img width=500 height=500 src='https://github.com/ItsZeusBro/JudgementDay/blob/b0cc7e0ed4a5b1a41346d8fcc34126ef1651002e/Automata.png'>

## Interpretation:

There is a problem to merely conclude that one proposition follows from the other, simply by looking at this example. However, if this simulation and its rules worked for a bunch of propositions without ever contradicting itself in the simulation, then it is very likely that the simulation approaches real logic that is valid.

To build a robust logical simulation one should focus on a dictionary of propositions that never contradict anything else in the dictionary. If you can prove all propositions in the dictionary using a simulation, then you have a good logical simulation that approaches real universal logic

we also have to make sure that there is no possibility in the translation unit for any negation to exist outside of the negation cell. Or at the very least translate out any negations in the translation into another proposition with the negation cell!

As a part of the rule system, any proposition in the current state of the simulation that spells out a negation outside of the negation cell, should be translated to an equivalent statement. This does not violate the arbitrary rule principle. Rules can be arbitrarily selected without violating the existentialism of the system, so long as they are consistent.

Overtime many simulations develop that are not invalidated by any contradiction. These can be statistically studied overtime to find how they relate to one another, and where they converge overtime becomes stronger and stronger. This can lead to a general purpose intelligence if you have math, physics, and natural language converge upon a Universal Logic. It should even be able to tell the future and the past with greater accuracy starting from some tautological truth! We even stand a good chance of being able to study the Multi-Verse with greater accuracy, black holes, etc... Time will tell...

