# 5800PIR  (serial 0671393)

PIR Motion Detector

Loops:
- L1 motion: Motion (low sens / pet) (0x80)
- L2 motion: Motion (high sens) (0x20)
- L3 temp_low: Low temp (0x10)
- L4 tamper: Case tamper (0x40)

Files (event byte):
- 0671393 restore.sub = 0x00
- 0671393 L1_motion.sub = 0x80
- 0671393 L2_motion.sub = 0x20
- 0671393 L3_temp_low.sub = 0x10
- 0671393 L1_motion_L2_motion_L3_temp_low.sub = 0xB0
- 0671393 L4_tamper.sub = 0x40

Contributed By:
- [Pyle49R](https://github.com/Pyle49R)
- [AdaptaStation](https://adaptastation.dpdns.org)

AdaptaStation is my personal website.
