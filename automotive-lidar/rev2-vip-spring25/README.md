# Automotive LiDAR — VIP Spring 2025 (Rev 2)

Rev 2 of the Georgia Tech VIP Automotive LiDAR hardware — a complete Altium Designer redesign of the [Rev 1 KiCad hardware](../rev1-sprite-hardware/).

## Boards & subsystems

| File | Contents |
|---|---|
| `altium/AutoLidar_VIP_Spring25.PrjPcb` | Altium project — open this |
| `altium/Root.SchDoc` | Top-level schematic |
| `altium/5ch Receiver.SchDoc` | 5-channel LiDAR receiver front-end |
| `altium/5V Regulator.SchDoc` | 5V power regulation |
| `altium/BNO055.SchDoc` / `altium/BNO055 (IMU).SchDoc` | BNO055 9-axis IMU |
| `altium/InterfaceBoard.SchDoc` | System interface board |
| `altium/Manual Override.SchDoc` | Manual override controls |
| `altium/USB HUB.SchDoc` | USB hub |
| `altium/Scanning Mechanism.SchDoc` | Scanning mechanism interface |
| `altium/Power Supply.SchDoc` | Power supply |
| `altium/MSub.SchDoc`, `altium/L Subsys.SchDoc` | Motor / laser subsystems |
| `altium/PCB1.PcbDoc`, `altium/PCB2.PcbDoc` | Board layouts |
| `altium/draft2.PcbDoc`, `altium/smallerBoardDR1.PcbDoc` | Layout iterations |
| `altium/AutoLidar_VIP_Spring25.IntLib` | Integrated component library |

## Design notes

- Full hierarchical Altium project: schematic libraries (`.SchLib`), PCB libraries (`.PcbLib`), and an integrated library (`.IntLib`) are included so the project opens without missing components.
- Rev 2 consolidates the Rev 1 (KiCad) architecture into the Altium flow with dedicated receiver, IMU, and interface boards.
