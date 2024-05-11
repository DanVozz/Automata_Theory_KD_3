# Automata_Theory_KD_3
Project #3

Universal Turing Machine project, developed as part of the Theory of Automata course at Texas Tech University, showcases a simulation of any Turing Machine using a specified encoding system. The core objective of this UTM is to interpret and execute encoded Turing Machine descriptions.

The UTM operates through three primary components: a syntax checker, a simulator, and a final state evaluator. The syntax checker validates the encoded Turing Machine format, ensuring it adheres to the defined encoding rules, such as starting states, transitions, and input symbols, while preparing the necessary tapes for simulation. The simulator component then processes each transition, comparing states and symbols, to execute the Turing Machine's logic. If the current state matches a final state as determined by the final state evaluator, the UTM accepts the input; otherwise, it rejects or continues processing.
