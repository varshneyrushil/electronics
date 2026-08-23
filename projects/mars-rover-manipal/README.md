# Mars Rover Manipal — electronics source archive

This directory organizes surviving PCB and interface-board source from my Mars Rover Manipal work.

The rover was a multidisciplinary team system. These folders document electronics designs and interfaces I worked on; they do **not** imply sole authorship of the complete rover or of every third-party component model used by the CAD projects.

| Project | Surviving source | Notes |
|---|---|---|
| [STM32 subsystem/interface](stm32-subsystem-interface/) | Altium / SolidWorks PCB | Main STM32-based rover interface board |
| [Motor-driver interface](motor-driver-interface/) | KiCad + legacy Altium | Modular two-signal + ground motor-driver interface |
| [Robotic-arm 3-pin breakout](robotic-arm-interface-3pin/) | EAGLE + Gerbers | 10-pin to three 3-pin interface breakout |
| [Robotic-arm interface](robotic-arm-interface/) | Legacy RAR + Altium snapshot | Fuller/earlier arm-interface design |
| [Camera interface](camera-interface/) | Legacy RAR | EAGLE source + Gerbers inside archive |
| [Left-motor interface](left-motor-interface/) | Legacy RAR | EAGLE source + Gerbers inside archive |
| [Right-motor interface](right-motor-interface/) | Legacy RAR | EAGLE source + Gerbers inside archive |

The RAR-only projects are kept as original historical archives because the available analysis environment could enumerate, but not decompress, RAR v4 payloads. Their manifests are included so the contents remain transparent.
