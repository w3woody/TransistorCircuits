# BitUCounter

Single bit up-only counter.

This is a single bit counter with the ability to count up, reset to zero, and load data from a data bus. This also contains two separate tri-state gate on the output, for incorporation on a data bus and separate address bus.

This counter is appropriate for a PC register that increments only, but may need to write to a separate data bus (for pushing the contents of the PC register on the stack) and a separate address bus.
