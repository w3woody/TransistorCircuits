# Flags

This board contains a bunch of miscellaneous logic in order to get the Flags register working correctly.

Our flags register consists of three bits: Z (Zero), C (Carry) and N (Negative). This board handles the logic of determining which values for carry, negative and zero are fed to the F register boards (either the results form the ALU or from the bus), as well as determining which signal is used for the ALU's carry/reverse-carry lines. The board also contains logic for determining if the output of the ALU is zero.

Because this board controls so much logic, it has hooks throughout the ALU and the flag registers. The control lines are also used to determine which signals are sent to the flag register for storage.

Unlike our other boards, this is sort of a mess of logic necessary to tie the other components together. And unlike our other boards we only need one of these to tie our Accumulator, Flag and ALU boards together.
