# GBA-Logs
GBA-Logs for various test roms. 

These files were generated in NanoBoyAdvance by outputting register values in the following order as uint32_t before each instruction was executed. 

- r0
- r1
- r2
- r3
- r4
- r5
- r6
- r7
- r8
- r9
- r10
- r11
- r12
- r13
- r14
- r15
- CPSR
- SPSR (Same as CPSR for ARM modes without SPSR)

The data is tightly packed contiguously, and there is no header or other data between instructions.

The logs correspond to the following roms: 

| Log      | ROM | Notes | 
| ----------- | ----------- | ---- |
| arm-log.bin      | arm.gba       | https://github.com/jsmolka/gba-tests/tree/master/arm |
| armwrestler-log.bin      | armwrestler.gba       | Just the portion to get to the menu screen  |
| kirby-boot-log.bin      | Kirby Return to Dream Land ROM      | Captured up to the HAL logo being displayed  |
| redp-log.bin      | redp.gba       |   |
| thumb-gang-log.bin      | thumb-gang-log.gba       |   |


| Paragraph   | Text        |
