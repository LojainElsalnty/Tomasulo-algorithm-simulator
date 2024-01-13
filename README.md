# Description


• This simulator includes ALU ops (FP adds, subs, multiply, divide), (integer ADDI or SUBI needed for loops), loads and stores and branches (BNEZ is enough).


• The cache latency is 1 cycle with no cache misses and effective address is already calculated as such L.D F2,100 where 100 is the effective address directly. Address clashes are ignored.


• The user can input the latency of each type of instruction before we start simulating, EXCEPT ADDI and BNEZ, assume they take 1 cycle of execution each. No prediction is required.


• The user can select the size of all stations and buffers.


• Cache and Register file can be pre-loaded with some values or allow the user to load them.


• All instructions (integer and floating) enter the Tomasulo architecture, such as DADD and BNEZ, which can be considered add/sub instructions and hence they enter the add/sub reservation stations.

