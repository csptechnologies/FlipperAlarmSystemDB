# 5800COMBO-S1  (serial 0407721)

Smoke/Heat/CO Combo (serial 1)

Loops:
- L1 smoke: Smoke / heat (0x80)
- L2 maintenance: Maintenance (0x20)
- L3 temp_low: Cold < 41F (0x10)
- L4 tamper: Case tamper (0x40)

Files (event byte):
- 0407721 restore.sub = 0x00
- 0407721 L1_smoke.sub = 0x80
- 0407721 L2_cleanme.sub = 0x20
- 0407721 L3_temp_low.sub = 0x10
- 0407721 L1_smoke_L2_cleanme_L3_temp_low.sub = 0xB0
- 0407721 L4_tamper.sub = 0x40

Contributed By:
- [Pyle49R](https://github.com/Pyle49R)
- [AdaptaStation](https://adaptastation.dpdns.org)

AdaptaStation is my personal website.
