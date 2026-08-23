# Source map used to disambiguate the images

The uploaded reports and project files were used as context rather than silently guessing what an image represented. They are now also **copied into this master archive** under `reports/` and `pcb_files/`. Publication status is recorded separately because some files are team-owned, third-party/reference material or professional/private.

## Mars Rover Manipal / student hardware

### `IRDC MRM Report(1).pdf`
Useful for the rover electronics context: Jetson AGX Xavier and STM32F103 nodes, CAN architecture, motor controllers, power distribution, wiring choices, electronics-box context and the thermal-management concept. The report describes Jetson/STM32/CAN integration and the broader rover electrical architecture.

### `Molex and fuse holders.pdf`
Useful for connector/fuseholder selection and battery-monitoring context. It records work on high-current fuseholders, connector pitches/locking/current ratings, and the problem of insufficient STM32 ADC pins for monitoring all batteries.

### `Job Instruction Sheet_ Wire repair instructions.pdf`
Useful for the wiring/harness context. It covers soldered wire repair, mechanical joint quality, heat-shrink/insulation and crimp connector types including ferrules for screw/Wago/Phoenix-style terminals.

### `Job instruction sheet_ Battery Charging.pdf`
Useful for LiPo safety context and the damaged-connector photo. The instructions treat the battery as a high-current hazard and document safe charging practices.

### `ECD PROJECT.pdf`
Useful for the discrete motor-driver context. It explicitly describes a BJT H-bridge, PWM speed control, analog joystick control and a lab-control interface.

### `RUSHIL_VARSHNEY_20.pdf`
Useful for the Yagi-Uda context. It discusses Yagi-Uda directivity, spacing, gain and UHF operation before the physical antenna build.

### `RUSHIL_VARSHNEY_21.pdf`
Useful for embedded-C background. It contains Arduino-style GPIO, serial, timing, sensor and logic exercises. The differential-drive joystick code supplied later in chat is separate and should be added to the new repository when recovered/rewritten.

### PCB/source artifacts uploaded in this conversation
These are valuable migration targets for the new repository and should be matched to projects before publishing:

- `STM32F3DISCOVERY.PcbLib`
- `STM32F3DISCOVERY.SchLib`
- `Gerber_Rectifier_MD-pcb_2026-08-22.zip`
- `Gerber_optocoupler_optocoupler-lulu-land_2026-08-22.zip`
- `PCB_optocoupler-lulu-land_2026-08-22.pdf`
- `Schematic_optocoupler_2026-08-22.pdf`
- `PCB_ATmega16-breakout_2026-08-22.pdf`
- `Schematic_nano-breakout_2026-08-22.pdf`
- `Schematic_Motor-driver_2026-08-22.pdf`
- `Sheet1.SchDoc`, `Sheet2.SchDoc`
- `armmodified3pin.zip`
- `cytron.PrjPcb`
- `cytron test 1.zip`
- `BackupProjects_n00br0x_personal_0_20260822.zip`

These files should ultimately live beside per-project READMEs rather than being dumped into one `backup` repository.

## Professional/private material

### `Failure_analysis.pdf`
Used only to disambiguate the Flexible Optical flyback screenshots. It documents the repeated secondary-rectifier short, switching spikes, leakage/reverse-recovery mechanisms, clamp/snubber considerations, transformer variability and the tested 1200 V SiC diode corrective action.

**Do not include this report or the associated images in a public GitHub repository unless the employer has explicitly authorized publication.**

## Power-electronics reports not directly represented by these public images

The uploaded DC-DC/HVDC reports and final half-bridge simulation report are useful evidence for the CV/interview portfolio, but there is not yet a clean set of public-original images in this media archive that I would mix into the MRM repository automatically. They are better handled as a separate `power-electronics-study-and-simulation` project later.

## Archive inclusion status

The master archive now includes:

- all engineering/report PDFs supplied in this conversation other than the CV/resume PDFs;
- all PCB/schematic PDF exports supplied in this conversation;
- all surviving Altium libraries/project/schematic files supplied in this conversation;
- all Gerber/project ZIP archives supplied in this conversation;
- extracted copies of the ZIP contents for browsing/migration while retaining the original archives.

See `REPORT_INDEX.csv` and `PCB_FILE_INDEX.csv` for exact file-by-file mapping.
