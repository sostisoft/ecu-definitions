# ECU Definitions Library

Open-source collection of ECU definition files (XDF + RomRaider XML) organized by vehicle brand and model. These files describe the memory maps, tables, and parameters inside engine control units, enabling firmware analysis and tuning.

Compatible with [TunerPro RT](https://www.tunerpro.net/), [RomRaider](https://www.romraider.com/), and [EcuForge](https://github.com/sostisoft/eku).

## Library Stats

| | Count |
|--|-------|
| XDF definition files | **352** |
| RomRaider XML definitions | **671** |
| Vehicle brands | 15 |
| ECU families covered | 50+ |

## Supported Vehicles

### BMW (217 XDFs)
| Folder | ECU | Vehicles |
|--------|-----|----------|
| `BMW/B58_Gen1` | Bosch MG1CS003 | F30 340i, G30 540i, F22 M240i |
| `BMW/B58_Gen2` | Bosch MG1CS201 | G20 M340i, G29 Z4 M40i |
| `BMW/Classic_Vintage` | Bosch/Siemens various | E30, E36, E34, E32 (80s-90s models) |
| `BMW/E36_M3` | Siemens DME | E30 M3 S14, E36 M3 |
| `BMW/E39_M5_MSS52` | Siemens MSS52 | E39 M5 S62 |
| `BMW/E46_M3_MSS54` | Siemens MSS54/MSS54HP | E46 M3 S54 |
| `BMW/E46_M3_SMG_II` | Siemens SMG II | E46 M3 SMG transmission |
| `BMW/E60_M5_MSS70_S85` | Siemens MSS70 | E60 M5 S85 V10 |
| `BMW/GS20_TCU` | Siemens GS20 | Automatic transmission control |
| `BMW/ME5.2_M62_E39` | Bosch ME5.2 | E39 540i M62 (non-turbo) |
| `BMW/ME7.2_M62TU_V8` | Bosch ME7.2 | E39 540i, E53 X5 4.4 V8 M62TU |
| `BMW/ME9_Valvetronic` | Bosch ME9 | E46, E60, E63 Valvetronic engines |
| `BMW/MS41` | Siemens MS41 | E36/E39 M52 |
| `BMW/MS42_M52TU` | Siemens MS42 | E46/E39 M52TU |
| `BMW/MS43_M54` | Siemens MS43 | E46/E39 M54 |
| `BMW/MS45_M54_E46` | Siemens MS45.0/45.1 | E46 M54, ZHP |
| `BMW/MSV70_N52` | Siemens MSV70 | E90/E60 N52 |
| `BMW/N54_MSD80` | Siemens MSD80 | 135i, 335i, 535i (+ FlexFuel) |
| `BMW/N55_E-Series` | Bosch MEVD17.2 | E82 1M, E9x 335is |
| `BMW/N55_S55_N13_F-Series` | Bosch MEVD17.2 | F30 335i, F80 M3, F20 M135i |
| `BMW/S58_M3_M4` | Bosch MG1CS201 | G80 M3, G82 M4 |
| `BMW/S63_M5_M6` | Bosch MEVD17.2 | F10 M5, F06/F12/F13 M6 |

### Ford (33 XDFs)
| Folder | ECU | Vehicles |
|--------|-----|----------|
| `Ford/EEC-IV_Foxbody` | Ford EEC-IV | 1987-1993 Mustang 5.0, T-Bird SC, Trucks |
| `Ford/EEC-V_Mustang` | Ford EEC-V | 1994-2004 Mustang V6/GT/Cobra |
| `Ford/EEC-V_F150_Lightning` | Ford EEC-V | 1999-2004 F-150 Lightning, Expedition |
| `Ford/EEC-V_Trucks` | Ford EEC-V | Mid-90s F-Series 302/351w |
| `Ford/EEC-V_Other` | Ford EEC-V | Focus, Ranger, T-Bird SC |
| `Ford/Ford_AU_Falcon` | Ford | AU/EF Falcon (Australia) |
| `Ford/Ford_EU_Cosworth` | Marelli IAW | Sierra/Sapphire/Escort Cosworth |

### GM (45 XDFs)
| Folder | ECU | Vehicles |
|--------|-----|----------|
| `GM/P01_512Kb_LS1_LS6` | GM P01 | Corvette, Camaro, GTO, Silverado (LS1/LS6) |
| `GM/P59_1Mb_LS2_LS3` | GM P59 | C6 Corvette, G8, CTS-V (LS2/LS3/LS7) |

### Subaru (671 RomRaider XMLs)
| Folder | Format | Vehicles |
|--------|--------|----------|
| `Subaru/RomRaider_XML/ECUFlash/` | ECUFlash XML | WRX, STI, Legacy GT, Forester XT, Outback, BRZ, Tribeca |
| `Subaru/RomRaider_XML/RomRaider/` | RomRaider XML | All Subaru with Denso ECU (metric + standard units) |

### VAG — Volkswagen/Audi (8 XDFs)
| Folder | ECU | Vehicles |
|--------|-----|----------|
| `VAG/Audi_S4_B5_ME7.1` | Bosch ME7.1 | B5 S4 2.7T |
| `VAG/VW_Golf7_Audi_A3_SIMOS18` | Continental SIMOS 18.1 | Golf 7 GTI/R, Audi A3/S3 |
| `VAG/VW_Golf_VR6` | Bosch | Golf VR6 |

### Other Brands
| Folder | XDFs | Vehicles |
|--------|------|----------|
| `Alfa_Romeo/Bosch_Motronic` | 29 | Various Alfa Romeo with Bosch Motronic |
| `Volvo/960_V90_S90_M44` | 2 | 960, V90, S90 with Motronic M4.4 |
| `Motos/` | 4 | Buell, Ducati, Moto Guzzi, Suzuki (Denso) |
| `Opel/` | 2 | Generic Opel |
| `Other/` | 8 | Lada, Daewoo Lanos, misc |
| `Acura/NSX_Legend` | 1 | NSX / Legend |
| `Mazda/Miata_BPL9` | 1 | Miata |
| `Nissan/S13_240SX` | 1 | S13 240SX |
| `Peugeot/205_Turbo` | 1 | 205 Turbo |

## File Formats

- **`.xdf`** — TunerPro RT definition format (XML-based or binary). Contains table addresses, sizes, scaling formulas, and axis definitions.
- **`.xml`** — RomRaider/ECUFlash definition format. Same information, different XML schema. Primarily used for Subaru.
- **`.adx`** — TunerPro datalogging/acquisition definition (companion to XDF).

## Usage

Clone and browse:
```bash
git clone https://github.com/sostisoft/ecu-definitions.git
```

Use with EcuForge — definitions are loaded automatically or via File > Import Definition.

## Sources & Credits

These definitions were collected from publicly available open-source repositories and community resources:

- [dmacpro91/BMW-XDFs](https://github.com/dmacpro91/BMW-XDFs) — BMW N54, N55, S55, B58, S63, S58
- [zarboz/BMW-XDFs](https://github.com/zarboz/BMW-XDFs) — BMW ME5.2, ME7.2, ME9, MS41, MS45, Classic
- [EcuTune/MSS54-XDFs](https://github.com/EcuTune/MSS54-XDFs) — BMW E46 M3 MSS54
- [Shambiomern/Engine-Tune-Repository](https://github.com/Shambiomern/Engine-Tune-Repository) — Alfa Romeo, GM, multi-brand
- [LS_Based_Engine_Repository](https://github.com/jmccord/LS_Based_Engine_Repository) — GM LS engines
- [ms4x.net](https://www.ms4x.net/) — BMW MS42, MS43, MS45, MSV70, MSS70, ME7.2, GS20, SMG II
- [EFIDynoTuning](https://forum.efidynotuning.com/) — Ford EEC-IV/V (by Decipha/Michael Ponthieux)
- [TunerPro.net](https://www.tunerpro.net/downloadBinDefs.htm) — Various Ford EEC definitions
- [SubaruDefs](https://github.com/RomRaider/SubaruDefs) — Subaru RomRaider/ECUFlash definitions
- [SimosDefinitions](https://github.com/bri3d/SimosDefinitions) — VW/Audi SIMOS 18.1
- [Volvo-B3604-Tuning-Files](https://github.com/Shambiomern/Volvo-B3604-Tuning-Files-Tunerpro-XDF-Motronic) — Volvo 960/V90

## Contributing

If you have XDF or RomRaider XML definitions to share, please open a PR following the folder structure: `Brand/Model_ECU/filename.xdf`

## License

Individual definition files retain their original licenses from their respective sources. This repository aggregates publicly available community definitions for educational and tuning purposes.
