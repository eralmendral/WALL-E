<img width="480px" src="https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/50f9d7d2-7d1b-4b61-b959-5d02102ba501/dbz5el3-0f738887-71cc-4566-8455-38d5332ea875.png?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOjdlMGQxODg5ODIyNjQzNzNhNWYwZDQxNWVhMGQyNmUwIiwiaXNzIjoidXJuOmFwcDo3ZTBkMTg4OTgyMjY0MzczYTVmMGQ0MTVlYTBkMjZlMCIsIm9iaiI6W1t7InBhdGgiOiJcL2ZcLzUwZjlkN2QyLTdkMWItNGI2MS1iOTU5LTVkMDIxMDJiYTUwMVwvZGJ6NWVsMy0wZjczODg4Ny03MWNjLTQ1NjYtODQ1NS0zOGQ1MzMyZWE4NzUucG5nIn1dXSwiYXVkIjpbInVybjpzZXJ2aWNlOmZpbGUuZG93bmxvYWQiXX0.C-OA5kX5Vk0Zwn3_TjCECzsJsmzTQVMbhgWxAjqcdOE"></img>

## Microprocessors and Microcontrollers


### Microprocessors
    - came before microcontroller
    - piece of machine
    - can perform set of instructions
    - mathematical operations
    - Includes
      - Control Unit
        - arithmetic logic unit
        - registers
        - program counter
        - flags
      - External Interface
        - ROM
        - RAM
        - I/O
      - Buses
        - Data Bus
        - Control Bus
        - Address Bus

    - Does not have RAM/ROM/IO built into it
    - System on a chip has
    - Modern Microprocessors has caches, so they have RAM built into it.


### How do things boot up?
- Inside microprocessors it has startup system that will go out in the
   address buses. To go fetch data.
- There are jump instructions to some place else
- And that jumped instructions which is code, loads more code and starts executing.
- Program in kind of non-volatile memory.
- When processor power up, it will do one specific thing at a time.
  - Go to specific memory location and start executing code.
- To do that we have to program in Assembly language, create machine code or use a compiler to create some assembly language machine code and convert that to binary file.
- That binary file is loaded in flash memory or ROM memory inside the system so that the processor can boot and go to that memory location.

