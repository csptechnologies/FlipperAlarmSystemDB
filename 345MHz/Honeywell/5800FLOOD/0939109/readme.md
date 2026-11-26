# 5800FLOOD  (serial 0939109)

Flood / Temperature Sensor

Loops:
- L1 temp_low: Low temp (0x80)
- L2 temp_high: High temp (0x20)
- L3 flood: Flood (0x10)
- L4 tamper: Case tamper (0x40)

Files (event byte):
- 0939109 restore.sub = 0x00
- 0939109 L1_temp_low.sub = 0x80
- 0939109 L2_temp_high.sub = 0x20
- 0939109 L3_flood.sub = 0x10
- 0939109 L1_temp_low_L2_temp_high_L3_flood.sub = 0xB0
- 0939109 L4_tamper.sub = 0x40

Contributed By:
- [Pyle49R](https://github.com/Pyle49R)
- [AdaptaStation](https://adaptastation.dpdns.org)

AdaptaStation is my personal website.
