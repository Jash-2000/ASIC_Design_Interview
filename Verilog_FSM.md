# Important Concepts to revise

1. Latch Inferring -- The previous value of a signal is retained if the update condition is not met. Fix: Provide "Default" values to all wires/regs.
2. Block vs Non-Blocking Assignments -- Keyword "assign" can only be used for wires. Block "always" can have both comb and seq statements (Specifics use "always_ff" and "always_comb")
3. Module I/Os -- The input of a module can never be a "reg" similarly, when instancing a module the output must be connected to "wire".
4. MetaStability and CDC -- The use of 2 flop synchronizer and/or using Async, Fifo and/or Using Handshake Mechanism. Study Reset Synchronization.
5. Reduing RTL Area -- Reusing Multipliers, Optimizing Reg/Wire Width, Using shift registers instead of mul/div for 2^n operations.
6. 

# Common Coding Problems 

1. Clock Divide Algorithms -- Using Counters with clog2(N)-1 reg array to store the counter and toggle the clock everytime the counter reaches N-1. Preferable to use enable signal instead of dividing the clock.
2. 
