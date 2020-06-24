# The barrel shifter

Arm processor has a circuit called 'barrel shifter' and it's responsible to perform bit-shifts and rotations.  

There are 4 barrel-shift ops(operations):
- left shift(lsl)
- logical right-shift(lsr)
- arithmetic right-shift(asr)
- rotate-right(ror)

Example:
  ```
  Rm, lsl #4 that means Rm<<4
  Rm, lsr Rs tha means Rm>>Rs
  ```
