# BitUDCounter

Single bit up/down counter with one tri-state output gate.

This is a single bit counter with the ability to count up, count down, reset to zero, and load data from a data bus. This also contains a tri-state gate on the output, for incorporation on a data bus.

Each single bit also contains a carry count up and down for incorporation into multi-bit counters.

This U/D counter is appropriate for a stack pointer register, where we may wish to increment, decrement, load from a value, and write to the address lines. For a PC register, use a different up-only counter elsewhere.
