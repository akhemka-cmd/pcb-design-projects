# PCB Design Projects

A portfolio of my PCB designs — automotive LiDAR hardware (Georgia Tech VIP) and an industrial automation controller (SMARK).

| Project | Description | Tool | Status |
|---|---|---|---|
| [`smark-aem-150dc8-eth`](smark-aem-150dc8-eth/) | STM32-based industrial automation controller with Ethernet, isolated ADC front-end, 8× analog + 8× digital inputs | KiCad | Rev 1 |
| [`automotive-lidar/rev1-sprite-hardware`](automotive-lidar/rev1-sprite-hardware/) | "Project Sprite" automotive LiDAR hardware — interface board, motion platform, power supply, scanning mechanism | KiCad | Rev 1 |
| [`automotive-lidar/rev2-vip-spring25`](automotive-lidar/rev2-vip-spring25/) | Automotive LiDAR redesign — 5-ch receiver, IMU, USB hub, interface & power boards | Altium Designer | Rev 2 |

## Opening the projects

- **KiCad projects** (`smark-aem-150dc8-eth`, `rev1-sprite-hardware`): open the `.kicad_pro` file in KiCad 7/8. Symbol/footprint libraries are referenced via the included `sym-lib-table` / `fp-lib-table` (Rev 1 LiDAR) or KiCad's stock libraries (SMARK).
- **Altium project** (`rev2-vip-spring25`): open `AutoLidar_VIP_Spring25.PrjPcb` in Altium Designer.

## Author

Arnav Khemka — Georgia Institute of Technology
