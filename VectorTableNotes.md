# Vector Table Details for My MCU


1. What is a Vector Table?
   - Table of vectors
   - Table of addresses/pointers
2. What are Vectors?
   - direction (pointers or addresses)
4. Addresses of what?
   - Addresses of exception handlers. (system exceptions + interrupts)
   - Interrupts are external
   - 16 system exceptions + 82 interrupts
  
## Vector Table stuff
1. Another name for the position is IrQ number


Button Interrupt Notes 

the button is connected to PortC pin13. 

Some peripherals deliver their interrupts to the NVIC over the EXTI line. 
Some peripherals got the NVIC directly

