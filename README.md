# Electronics Hardware Portfolio

Hands-on electronics and systems work spanning **PCB design, embedded control, robotics, power electronics, wiring/harness integration, test engineering, and hardware prototyping**.

Most public material here comes from student engineering projects, Mars Rover Manipal, and university work from roughly 2019–2021. I have kept original source and project evidence where useful while adding context so that historical prototypes are not mistaken for current production designs.

> **Professional/confidential work is intentionally not published here.**

---

## Selected hardware

| Rover electronics & integration | STM32 / subsystem PCB design |
|---|---|
| ![Rover electronics box](images/rover/01_rover_electronics_box_open_chassis_integration.png) | ![STM32 rover interface PCB](images/pcb/01_stm32_rover_subsystem_interface_pcb_layout.png) |
| System-level rover electronics integration, power distribution, wiring and subsystem packaging. | STM32-based rover subsystem/interface PCB developed to consolidate distributed interfaces and wiring. |

| Motor-driver interface | Indoor integration test mule |
|---|---|
| ![Motor-driver interface](images/pcb/04_modular_motor_driver_interface_pcb_layout.png) | ![Integration test mule](images/rover/02_indoor_jetson_stm32_integration_test_mule.png) |
| Recovered modular interface PCB carrying two motor-control signals plus ground between rover wiring and the motor-driver module. | Indoor Jetson/STM32 test platform used to test software, networking and video functionality without repeatedly deploying the full rover. |

| Battery characterization | Yagi-Uda antenna |
|---|---|
| ![Battery discharge curve](images/battery/05_battery_constant_current_discharge_voltage_curve.png) | ![Yagi-Uda antenna](images/antenna/02_yagi_uda_antenna_completed.png) |
| Constant-current discharge testing used to obtain experimental battery voltage-vs-time behaviour. | Student-built directional antenna prototype based on Yagi-Uda element-spacing and length calculations. |

---

## Browse the actual source

### Mars Rover Manipal

- [STM32 subsystem/interface PCB](projects/mars-rover-manipal/stm32-subsystem-interface/)
- [Modular motor-driver interface](projects/mars-rover-manipal/motor-driver-interface/)
- [Robotic-arm 3-pin breakout](projects/mars-rover-manipal/robotic-arm-interface-3pin/)
- [Robotic-arm interface archive](projects/mars-rover-manipal/robotic-arm-interface/)
- [Camera interface archive](projects/mars-rover-manipal/camera-interface/)
- [Left-motor interface archive](projects/mars-rover-manipal/left-motor-interface/)
- [Right-motor interface archive](projects/mars-rover-manipal/right-motor-interface/)

### Other electronics projects

- [Discrete BJT H-bridge motor driver](projects/personal/discrete-motor-driver/)
- [ATmega16 breakout](projects/personal/atmega16-breakout/)
- [Optocoupler/interface board](projects/personal/optocoupler-interface/)
- [Reverse-polarity protection](projects/personal/reverse-polarity-protection/)

See the [project index](projects/) for source-format and provenance notes.

---

## Rover electronics & system integration

My Mars Rover Manipal work included electronics design and maintenance across:

- custom PCBs and subsystem interfaces;
- STM32-based control hardware;
- Jetson/MCU integration;
- power distribution and high-current wiring;
- embedded/data interfaces;
- motor-controller integration;
- harness fabrication and connector selection;
- electronics-box integration and troubleshooting;
- test fixtures and an indoor subsystem test mule.

The rover was a multidisciplinary team project. Images of the complete rover/electronics box represent the team system; the project READMEs describe the electronics work and surviving source rather than claiming sole authorship of the full machine.

---

## Motor control & prototyping

Early electronics work included transistor-level motor-control design and build iterations:

- discrete BJT H-bridge simulations;
- breadboard prototypes;
- hand-built perfboard implementations and rework;
- joystick-based differential-drive experiments;
- instrumented Proteus simulation;
- PCB/manufacturing outputs.

The [discrete motor-driver project](projects/personal/discrete-motor-driver/) includes an explicit authorship note because the surviving schematic was drawn within a shared student project.

---

## Battery test hardware & analogue instrumentation

I built an adjustable electronic load originally to characterize battery discharge behaviour. Surviving material documents:

- a low-resistance current shunt;
- separate voltage-sense wiring across the shunt;
- analogue gain calibration;
- an adjustable power stage;
- logged battery voltage measurements;
- the resulting voltage-vs-time discharge curve.

The exact final circuit revision no longer survives, so repository descriptions intentionally separate documented evidence from later reconstruction.

---

## Wiring, harnesses & repair

Rover integration also involved practical electrical assembly:

- high-current battery wiring;
- ferrule and connector crimping;
- Anderson-style power contacts;
- soldered XT-series connectors;
- ribbon/FRC wiring;
- Ethernet/LAN termination;
- screw-terminal and Wago-style connections;
- wire repair and field rework.

See [`images/harness/`](images/harness/) and the public job-instruction reports.

---

## Reports and documentation

[`reports_public/`](reports_public/) contains historical reports and engineering notes that I can share publicly, including:

- electronics/motor/battery training reports;
- antenna comparison and Yagi-Uda work;
- communication-protocol and embedded-C exercises;
- connector/fuseholder/battery-monitoring notes;
- wire-repair and battery-charging job instructions;
- a discrete motor-driver academic project;
- an HVDC research report.

These are retained primarily as **evidence of the engineering work and learning process at the time**, not as current design standards.

Larger team reports, internship documents and professional employer material are deliberately not included in this public-ready repository unless publication rights are clear.

---

## Context and provenance

For file-by-file context:

- [`CAPTIONS.md`](CAPTIONS.md)
- [`IMAGE_INDEX.csv`](IMAGE_INDEX.csv)
- [`REPORT_INDEX.csv`](REPORT_INDEX.csv)
- [`SOURCE_MAP.md`](SOURCE_MAP.md)
- [`NOTICE.md`](NOTICE.md)

---

## Main engineering areas represented

`Electronics` · `PCB Design` · `Embedded Systems` · `Motor Control` · `Power Electronics` · `Hardware Test` · `Harnessing & Interconnects` · `Robotics` · `MATLAB/Simulink` · `Proteus`

---

## About me

I am an electronics / systems engineer currently completing an MSc in Systems & Control at TU Delft. My professional experience includes regulated medical-device electronics and hardware verification, alongside power-electronics failure analysis and hands-on electronics development.

This repository focuses on public project material rather than confidential professional work.
