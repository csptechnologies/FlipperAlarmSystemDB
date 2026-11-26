# 5800CO  (serial 0512711)

Carbon Monoxide Detector

Loops:
- L1 co: CO alarm (0x80)
- L2 eol: End of life (0x20)
- L4 tamper: Case tamper (0x40)

Files (event byte):
- 0512711 close.sub = 0x00
- 0512711 L1_co.sub = 0x80
- 0512711 L2_eol.sub = 0x20
- 0512711 L1_co_L2_eol.sub = 0xA0
- 0512711 L4_tamper.sub = 0x40

Contributed By:
- [Pyle49R](https://github.com/Pyle49R)