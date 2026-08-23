# Image captions and context

This file is the human-readable companion to `IMAGE_INDEX.csv`. Captions preserve the context supplied in chat and are deliberately careful about uncertain or team-owned details.

## PCB & electronics design

### `images/pcb/01_stm32_rover_subsystem_interface_pcb_layout.png`

**Short caption:** STM32 rover subsystem/interface PCB layout

Two-layer STM32-based rover subsystem/interface PCB layout with labelled interfaces for motors/actuators, ADC, camera, Jetson/UART and other rover subsystems. User reports the 20-pin FRC interface was deliberately mapped so a reversed connector would not short power to ground, making field faults safer and easier to diagnose.

**Publication status:** `PUBLIC_CANDIDATE`  
**Naming confidence:** `high`  
**Related source material:** IRDC MRM Report(1).pdf; PCB project folders in n00br0x/pcbs (exact project to match during migration)  
**Recommended use:** Hero image for PCB/system-integration section

### `images/pcb/02_mrm_custom_pcb_family_and_components.png`

**Short caption:** Fabricated Mars Rover Manipal PCB family and components

Collection of fabricated custom rover PCBs, development boards and electronic components from the student-project hardware workflow. Useful as evidence that designs progressed beyond CAD into ordered, assembled and integrated hardware.

**Publication status:** `PUBLIC_CANDIDATE`  
**Naming confidence:** `high`  
**Related source material:** Gerber/PCB/Schematic files uploaded in this conversation; n00br0x/pcbs  
**Recommended use:** Portfolio overview image

### `images/pcb/03_discrete_motor_driver_pcb_layout_render.png`

**Short caption:** Discrete motor-driver PCB layout render

PCB render of the discrete BJT motor-driver design, showing the board layout produced after schematic/prototyping work. The wider project included transistor-level H-bridge simulation, breadboard/perfboard prototypes, embedded/joystick control and later PCB implementation.

**Publication status:** `PUBLIC_CANDIDATE`  
**Naming confidence:** `high`  
**Related source material:** Schematic_Motor-driver_2026-08-22.pdf; Gerber_Rectifier_MD-pcb_2026-08-22.zip; ECD PROJECT.pdf  
**Recommended use:** Supporting image for motor-driver project

## Rover system integration

### `images/rover/01_rover_electronics_box_open_chassis_integration.png`

**Short caption:** Rover electronics box during integration and maintenance

Open rover electronics-box/chassis view during hardware integration and maintenance, showing the practical wiring, controllers, power electronics and service access involved in keeping the prototype operational.

**Publication status:** `PUBLIC_CANDIDATE`  
**Naming confidence:** `high`  
**Related source material:** IRDC MRM Report(1).pdf; Job Instruction Sheet_ Wire repair instructions.pdf  
**Recommended use:** Strong system-integration image

### `images/rover/02_indoor_jetson_stm32_integration_test_mule.png`

**Short caption:** Indoor Jetson/STM32 integration test mule

Small indoor hardware test mule built so the team could test the Jetson, STM32, or both together without repeatedly deploying the roughly 50 kg rover. User reports it was used for controller integration, networking and video-encoding tests and was especially useful during heavy Manipal rains.

**Publication status:** `PUBLIC_CANDIDATE`  
**Naming confidence:** `high`  
**Related source material:** IRDC MRM Report(1).pdf (Jetson/STM32/CAN architecture); user-supplied project context  
**Recommended use:** Hero image for design-for-test / engineering infrastructure

### `images/rover/03_rover_electronics_top_view_power_distribution_and_subsystems.png`

**Short caption:** Rover electronics and power-distribution top view

Top view of the rover electronics installation showing distribution hardware, wiring, controllers and subsystem packaging in the chassis. Good visual context for the system-level electrical integration described in the IRDC report.

**Publication status:** `PUBLIC_CANDIDATE`  
**Naming confidence:** `high`  
**Related source material:** IRDC MRM Report(1).pdf  
**Recommended use:** System architecture/supporting image

## Harness, connectors & field repair

### `images/harness/01_charred_power_connectors_after_momentary_lipo_short.png`

**Short caption:** Power connectors damaged by a momentary LiPo short

Two power connectors after a momentary LiPo short. User supplied this as a safety/lessons-learned example from working with high-current rover batteries. The team battery instructions explicitly treated short-circuit current as a serious hazard.

**Publication status:** `PUBLIC_CANDIDATE`  
**Naming confidence:** `high`  
**Related source material:** Job instruction sheet_ Battery Charging.pdf  
**Recommended use:** Lessons-learned / safety image; not a hero image

### `images/harness/02_improvised_power_data_splitter_adapter.png`

**Short caption:** Improvised splitter/adapter cable

Example of the improvised adapters and connectors used to keep rover development moving when dedicated harness hardware was unavailable. Keep the caption focused on prototyping/test use rather than production workmanship.

**Publication status:** `PUBLIC_CANDIDATE`  
**Naming confidence:** `high`  
**Related source material:** Job Instruction Sheet_ Wire repair instructions.pdf; user-supplied context on XT60/XT90, Anderson, Molex, ferrules and Wago work  
**Recommended use:** Supporting image for hands-on hardware section

### `images/harness/03_prototype_power_harness_with_dc_dc_module.png`

**Short caption:** Prototype power harness with DC-DC module

Prototype power wiring/harness assembly with an inline DC-DC module and hand-made terminations. Representative of the team's frequent custom harness, connector and power-distribution work.

**Publication status:** `PUBLIC_CANDIDATE`  
**Naming confidence:** `high`  
**Related source material:** Job Instruction Sheet_ Wire repair instructions.pdf; Molex and fuse holders.pdf  
**Recommended use:** Supporting image

### `images/harness/04_cytron_md13s_motor_controller_field_hardware_closeup.png`

**Short caption:** Cytron MD13S motor-controller field hardware close-up

Close-up of a Cytron MD13S motor controller used in rover hardware. The image is useful as field-hardware context rather than as evidence of a custom PCB design.

**Publication status:** `PUBLIC_CANDIDATE`  
**Naming confidence:** `high`  
**Related source material:** cytron.PrjPcb; cytron test 1.zip; user-supplied rover context  
**Recommended use:** Supporting field-hardware image

## Motor control & prototyping

### `images/motor/01_arduino_joystick_hbridge_motor_control_proteus_simulation.png`

**Short caption:** Arduino/joystick H-bridge motor-control simulation

Proteus simulation combining a discrete BJT H-bridge, direction/switching logic and Arduino/joystick control. User later described simplifying the differential-drive mixing mathematically to left=y+x and right=y-x, with deadband, sign-based direction and normalized PWM magnitude.

**Publication status:** `PUBLIC_CANDIDATE`  
**Naming confidence:** `high`  
**Related source material:** ECD PROJECT.pdf; user-supplied embedded motor-control code  
**Recommended use:** Good bridge between hardware and embedded-control sections

### `images/motor/02_discrete_motor_driver_perfboards_top_side.png`

**Short caption:** Discrete motor-driver perfboard prototypes — component side

Two hand-built perfboard implementations of the discrete motor-driver circuit. Shows transistor/IC-level assembly before the later PCB implementation.

**Publication status:** `PUBLIC_CANDIDATE`  
**Naming confidence:** `high`  
**Related source material:** ECD PROJECT.pdf; Schematic_Motor-driver_2026-08-22.pdf  
**Recommended use:** Strong hands-on prototyping image

### `images/motor/03_discrete_motor_driver_perfboard_bottom_rework.png`

**Short caption:** Discrete motor-driver perfboard — underside and rework

Underside of a heavily reworked motor-driver perfboard. User reports repeated solder rework lifted/damaged pads, after which component/resistor leads were used as replacement conductors to recover the prototype. Useful evidence of prototype recovery and continuity/debug work; not intended as a production-quality layout example.

**Publication status:** `PUBLIC_CANDIDATE`  
**Naming confidence:** `high`  
**Related source material:** ECD PROJECT.pdf; user-supplied build history  
**Recommended use:** Hands-on/rework evidence; contextual caption essential

### `images/motor/04_discrete_motor_driver_breadboard_prototype.png`

**Short caption:** Discrete motor-driver breadboard prototype

Breadboard-stage prototype of the motor-driver circuit with discrete transistors and bench instrumentation/power hardware before soldered/perfboard and PCB versions.

**Publication status:** `PUBLIC_CANDIDATE`  
**Naming confidence:** `high`  
**Related source material:** ECD PROJECT.pdf  
**Recommended use:** Development-progression image

### `images/motor/05_discrete_hbridge_instrumented_proteus_simulation.png`

**Short caption:** Instrumented discrete H-bridge Proteus simulation

Earlier/alternate Proteus H-bridge simulation heavily instrumented with voltage/current probes to inspect device and motor behavior. Good evidence of a measure-every-node approach during early circuit learning and debugging.

**Publication status:** `PUBLIC_CANDIDATE`  
**Naming confidence:** `high`  
**Related source material:** ECD PROJECT.pdf  
**Recommended use:** Supporting simulation image

## Digital logic hardware

### `images/logic/01_multipurpose_combinational_logic_perfboard_bottom.png`

**Short caption:** Hand-soldered multi-function combinational-logic perfboard — underside

Underside of a directly soldered multi-function digital-logic perfboard built from logic ICs. User describes implementing several logic/code-conversion/arithmetic functions via switch-selectable hardware and spending extensive time debugging/reworking the direct-soldered interconnects.

**Publication status:** `PUBLIC_CANDIDATE`  
**Naming confidence:** `high`  
**Related source material:** User-supplied handwritten logic notes and Proteus simulation images in this folder  
**Recommended use:** Hands-on digital-logic image

### `images/logic/02_combinational_logic_proteus_simulation.png`

**Short caption:** Combinational-logic Proteus simulation

Proteus logic-gate simulation associated with the hand-derived combinational-logic exercises and the later direct-soldered hardware implementation.

**Publication status:** `PUBLIC_CANDIDATE`  
**Naming confidence:** `high`  
**Related source material:** Handwritten binary-code-conversion logic images in this folder  
**Recommended use:** Simulation/supporting image

### `images/logic/03_binary_to_excess3_hand_derived_logic.png`

**Short caption:** Hand-derived binary-to-Excess-3 logic

Hand-drawn combinational logic for a binary-to-Excess-3 conversion block, used as part of the discrete logic design work.

**Publication status:** `PUBLIC_CANDIDATE`  
**Naming confidence:** `high`  
**Related source material:** Combinational-logic simulation and perfboard images  
**Recommended use:** Supporting derivation image

### `images/logic/04_binary_to_2421_hand_derived_logic.png`

**Short caption:** Hand-derived binary-to-2421 logic

Hand-drawn combinational logic for conversion from binary to 2421 code.

**Publication status:** `PUBLIC_CANDIDATE`  
**Naming confidence:** `high`  
**Related source material:** Combinational-logic simulation and perfboard images  
**Recommended use:** Supporting derivation image

### `images/logic/05_binary_to_gray_hand_derived_logic.png`

**Short caption:** Hand-derived binary-to-Gray-code logic

Hand-drawn binary-to-Gray conversion using XOR relationships between adjacent bits.

**Publication status:** `PUBLIC_CANDIDATE`  
**Naming confidence:** `high`  
**Related source material:** Combinational-logic simulation and perfboard images  
**Recommended use:** Supporting derivation image

### `images/logic/06_digital_logic_handwritten_design_notes.png`

**Short caption:** Handwritten digital-logic design/test notes

Additional handwritten notes from the same digital-logic build. The image is low-resolution/partly rotated, so keep its public caption generic rather than claiming specific equations that cannot be read confidently.

**Publication status:** `PUBLIC_CANDIDATE`  
**Naming confidence:** `medium`  
**Related source material:** Other digital-logic images in this folder  
**Recommended use:** Archive/supporting image; probably omit from README

## Battery test & analog instrumentation

### `images/battery/01_battery_monitor_external_adc_breakout_prototype.png`

**Short caption:** Battery-monitor external-ADC/breakout prototype

Perfboard/external-ADC style prototype associated with rover battery-monitoring work. The MRM task report notes that battery monitoring was being developed and that available STM32 ADC pins were insufficient for all batteries, motivating external/expanded acquisition approaches.

**Publication status:** `PUBLIC_CANDIDATE`  
**Naming confidence:** `medium`  
**Related source material:** Molex and fuse holders.pdf  
**Recommended use:** Supporting battery-monitoring image

### `images/battery/02_constant_current_battery_load_early_breadboard_prototype.png`

**Short caption:** Early constant-current battery-load breadboard prototype

Early breadboard/power-stage prototype associated with the homemade constant-current battery discharge load. User recalls a low-resistance copper-wire shunt, analog feedback, a BJT/P-channel MOSFET power stage and a separate low-voltage control supply. Exact component values and final topology are not fully recovered.

**Publication status:** `PUBLIC_CANDIDATE`  
**Naming confidence:** `medium`  
**Related source material:** User-supplied calibration notebook and discharge-curve images; RUSHIL_VARSHNEY_13.pdf for battery terminology/background  
**Recommended use:** Supporting build image

### `images/battery/03_constant_current_load_pmos_bjt_hand_schematic.png`

**Short caption:** Hand sketch of P-channel MOSFET/BJT current-load stage

Hand-drawn reconstruction/working sketch showing a P-channel MOSFET power device driven via an NPN BJT, consistent with the user's recollection of separating the low-voltage precision/control electronics from the dissipative power device.

**Publication status:** `PUBLIC_CANDIDATE`  
**Naming confidence:** `high`  
**Related source material:** User-supplied constant-current-load context  
**Recommended use:** Useful explanatory image

### `images/battery/04_shunt_signal_gain_calibration_notebook.png`

**Short caption:** Shunt/amplifier calibration notebook

Handwritten calibration data for the analog sensing chain. The page records millivolt-level inputs and volt-level outputs and notes an approximate gain of 67.5, consistent with amplifying a low-voltage shunt signal for the feedback/measurement circuit.

**Publication status:** `PUBLIC_CANDIDATE`  
**Naming confidence:** `high`  
**Related source material:** Constant-current battery-load prototype; user-supplied four-wire shunt context  
**Recommended use:** Strong instrumentation/calibration evidence

### `images/battery/05_battery_constant_current_discharge_voltage_curve.png`

**Short caption:** Measured battery voltage-versus-time discharge curve

Spreadsheet plot from the battery-characterization experiment. The constant-current load was built specifically to obtain a repeatable battery discharge curve; the recorded voltage falls from about 3.8 V toward the end-of-discharge knee near 3.0 V.

**Publication status:** `PUBLIC_CANDIDATE`  
**Naming confidence:** `high`  
**Related source material:** Constant-current load images; RUSHIL_VARSHNEY_13.pdf  
**Recommended use:** Hero result image for battery-test project

## RF & antenna

### `images/antenna/01_yagi_uda_antenna_build_in_progress.png`

**Short caption:** Yagi-Uda antenna build in progress

Physical Yagi-Uda antenna fabrication in progress, with elements positioned along a simple boom. The associated report studied Yagi-Uda spacing, gain/directivity and UHF operation before the antenna was built.

**Publication status:** `PUBLIC_CANDIDATE`  
**Naming confidence:** `high`  
**Related source material:** RUSHIL_VARSHNEY_20.pdf  
**Recommended use:** Build-process image

### `images/antenna/02_yagi_uda_antenna_completed.png`

**Short caption:** Completed Yagi-Uda antenna prototype

Completed physical Yagi-Uda antenna prototype. Use as evidence of basic practical antenna fabrication rather than advanced RF characterization; no VNA/S-parameter measurements have been provided.

**Publication status:** `PUBLIC_CANDIDATE`  
**Naming confidence:** `high`  
**Related source material:** RUSHIL_VARSHNEY_20.pdf  
**Recommended use:** Hero image for antenna project

## Professional flyback failure analysis

### `private/flexible_optical/01_measured_switching_waveforms_scope.png`

**Short caption:** Measured flyback switching waveforms

Scope capture from the Flexible Optical internship investigation, showing MOSFET drain, secondary current and MOSFET gate traces. User clarified that this belongs to the professional flyback failure-analysis work, not the earlier student half-bridge DC-DC project.

**Publication status:** `PRIVATE_PROFESSIONAL_DO_NOT_PUBLISH`  
**Naming confidence:** `high`  
**Related source material:** Failure_analysis.pdf  
**Recommended use:** Private interview evidence only unless employer explicitly authorizes publication

### `private/flexible_optical/02_original_flyback_supply_schematic.png`

**Short caption:** Flyback power-supply schematic used for failure analysis

Full flyback supply schematic discussed during the internship failure analysis. User identified repeated D2 secondary-rectifier shorts; C15 and D5 were intentionally not populated in the actual configuration, while some boards had separate assembly defects such as missing R10.

**Publication status:** `PRIVATE_PROFESSIONAL_DO_NOT_PUBLISH`  
**Naming confidence:** `high`  
**Related source material:** Failure_analysis.pdf  
**Recommended use:** Private only

### `private/flexible_optical/03_flyback_clamp_rectifier_schematic_detail.png`

**Short caption:** Flyback clamp / transformer / rectifier schematic detail

Schematic detail around the primary clamp network, transformer and upper secondary rectifier D2. Included to preserve context for the failure mechanism discussion and component-population decisions.

**Publication status:** `PRIVATE_PROFESSIONAL_DO_NOT_PUBLISH`  
**Naming confidence:** `high`  
**Related source material:** Failure_analysis.pdf  
**Recommended use:** Private only

### `private/flexible_optical/04_primary_switch_and_transformer_schematic_detail.png`

**Short caption:** Primary MOSFET / transformer schematic detail

Schematic detail around the primary MOSFET, transformer and current-control area used when discussing units that received gate drive but did not show normal drain switching.

**Publication status:** `PRIVATE_PROFESSIONAL_DO_NOT_PUBLISH`  
**Naming confidence:** `high`  
**Related source material:** Failure_analysis.pdf  
**Recommended use:** Private only

### `private/flexible_optical/05_simulink_flyback_power_stage_behavioral_control_model.png`

**Short caption:** MATLAB/Simulink flyback power-stage model with behavioral controller

Simulink reconstruction of the flyback power stage. Because the original controller SPICE model was unavailable, the controller behavior was reconstructed from the datasheet using simple control blocks; the model was then used to reproduce the observed switching transient and peak behavior.

**Publication status:** `PRIVATE_PROFESSIONAL_DO_NOT_PUBLISH`  
**Naming confidence:** `high`  
**Related source material:** Failure_analysis.pdf  
**Recommended use:** Private only

## Third-party reference

### `reference_only/01_third_party_constant_current_load_reference_diagram.png`

**Short caption:** Third-party analog constant-current-load reference diagram

Reference image supplied in chat to discuss likely topology. This is not presented as the user's original artwork and should not be uploaded to a public portfolio. Recreate the circuit as an original diagram if a GitHub explanation needs one.

**Publication status:** `REFERENCE_ONLY_DO_NOT_PUBLISH`  
**Naming confidence:** `high`  
**Related source material:** User discussion only  
**Recommended use:** Reference only

### `reference_only/02_third_party_kelvin_four_wire_sensing_reference.png`

**Short caption:** Third-party Kelvin/four-wire sensing reference screenshot

Screenshot supplied in chat to confirm the four-wire/Kelvin measurement concept. User clarified that the voltage-sense wires were connected inside the high-current connection points across the wire shunt. Do not publish this screenshot; redraw the concept if needed.

**Publication status:** `REFERENCE_ONLY_DO_NOT_PUBLISH`  
**Naming confidence:** `high`  
**Related source material:** User discussion only  
**Recommended use:** Reference only

## `images/pcb/04_modular_motor_driver_interface_pcb_layout.png`

**Short caption:** Modular rover motor-driver interface PCB layout

Recovered PCB layout for a modular rover motor-driver interface. The surviving source routes two motor-control signals plus ground between a 10-position rover-side connector, two duplicate 3-pin headers and the motor-driver module footprint. This specific revision is documented as a PWM/direction signal-routing interface; an I²C-addressed architecture is not claimed for this file set.

**Related source:** `projects/mars-rover-manipal/motor-driver-interface/`
