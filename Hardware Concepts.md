### BIOS
- The code **in-built** into your hardware by manufacturer.
- Runs "automatically" when you start computer.
- keeps looking for a **Boot loader** to be loaded in RAM and to be executed.
### Boot Loader
- A program that exists on (typically sector-0 of) a secondary storage.
- Loaded by BIOS in RAM and passed over control to. 
- E.g. **GRUB**
- It's job is to locate the code of an OS kernel, load it in RAM and pass control over it.
### Kernel
- The code that is loaded and given control by BIOS initially when computer boots.
- Takes control of hardware.
- Creates an environment for **applications** to execute.
- Controls access to hardware by applications.

