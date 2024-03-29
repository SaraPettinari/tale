# TALE

The tag-based multi-perspective methodology (TALE) aims to support the robotic developer in the automatic extraction of multi-perspective event logs from the execution of a robotic system and analyze them through process mining.

The TALE methodology has been designed to foster the application of process mining and the development of techniques suitable for robotic systems.
It allows the system designer to specify tags in the source code and transform them into events to be inserted into the log. The generated event logs are enriched with multi-perspective information (such as space, communication, and resource occupancy), thus defining a multi-perspective event log, suitable for the application of process mining techniques.

Please refer to the methodology description for more details: [website](https://pros.unicam.it/tale/) and [paper](https://link.springer.com/chapter/10.1007/978-3-031-46587-1_7).

## Submodules
- **tale_analysis**: contains the tool enabling multi-perspective analysis of robotic data via DFG discovery and enhancement.

- **ekg_multi_query**: : contains the tool enabling multi-perspective analysis of robotic data via EKG discovery and enhancement.
