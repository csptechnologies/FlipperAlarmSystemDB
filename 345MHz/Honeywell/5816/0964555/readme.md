# 5816  (serial 0964555)

Door/Window Transmitter

Loops:
- L1 contact: Wired terminals (NC) (0x80)
- L2 reed: Reed switch (0x20)
- L4 tamper: Case tamper (0x40)

Files (event byte):
- 0964555 Close.sub = 0x00
- 0964555 L1 Open.sub = 0x80
- 0964555 L2 Open.sub = 0x20
- 0964555 L1 L2 Open.sub = 0xA0
- 0964555 tamper.sub = 0x40

Contributed By:
- [Pyle49R](https://github.com/Pyle49R)