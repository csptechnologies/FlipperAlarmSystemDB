# 5821  (serial 0220037)

Temperature / Flood Sensor

Loops:
- L1 temp_low: Cold temp (0x80)
- L2 temp_high: Hot temp / freeze probe (0x20)
- L3 flood: Flood probe (0x10)
- L4 tamper: Case tamper (0x40)

Files (event byte):
- 0220037 restore.sub = 0x00
- 0220037 L1_temp_low.sub = 0x80
- 0220037 L2_temp_high.sub = 0x20
- 0220037 L3_flood.sub = 0x10
- 0220037 L1_temp_low_L2_temp_high_L3_flood.sub = 0xB0
- 0220037 L4_tamper.sub = 0x40

Contributed By:
- [Pyle49R](https://github.com/Pyle49R)
- [AdaptaStation](https://adaptastation.dpdns.org)

AdaptaStation is my personal website.
