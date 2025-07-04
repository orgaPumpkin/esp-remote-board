# esp-remote-board
This is a custom board for my [esp-remote](https://github.com/orgaPumpkin/esp-remote-project) project (check it out).

It is a Hat for the esp8266, which contains an IR receiver, an IR emitter, and two buttons to send set messages.

I made this board in order to make this project more accessible, as putting the esp8266 into the Hat is way easier than connecting the components to a breadboard.

Additionally, a Hat is way more compact and clean than a breadboard and gives the project the feeling of a final product.

![3D render](pictures/3d.png)
![pcb](pictures/hat_pcb.png)
![schematic](pictures/hat_schematic.png)

| Component             | Designator                        | LCSC Part Number | Link                                                  | Est Price |
|-----------------------|-----------------------------------|------------------|-------------------------------------------------------|-----------|
| TSOP34838             | U2                                | C44620           | https://www.aliexpress.com/item/1005005744020934.html | 2.2$      |
| PTS810                | SW3, SW4                          | C221895          | https://www.aliexpress.com/item/1005004443276452.html | 2.2$      |
| 470 Ohm 0402 resistor | R15, R16, R17, R18, R19, R20, R21 | C23179           | https://www.aliexpress.com/item/1005003721873929.html | 1.2$      |
| SS8050                | Q1                                | C2150            | https://www.aliexpress.com/item/1005008666448511.html | 0.9$      |
| 1x15 2.54 Socket      | J1, J2                            | C7499333         | https://www.aliexpress.com/item/4001198421663.html    | 1.5$      |
| 3.0mm THT IR LED      | D4, D5, D6, D7                    | C7470790         | https://www.aliexpress.com/item/1005003946239993.html | 2.1$      |
| 0603 red LED          | D3                                | C2286            | https://www.aliexpress.com/item/1005005226854182.html | 1.2$      |
| ESP8266 NodeMcu v2    |                                   | C503597          | https://www.aliexpress.com/item/32656401198.html      | 3.8$      |
|                       |                                   |                  |                                                       |           |
| AliExpress shipping   |                                   |                  |                                                       | 3$        |
| JLCPCB with shipping  |                                   |                  |                                                       | 28.2$     |
| Total ~               |                                   |                  |                                                       | 46.3$     |
