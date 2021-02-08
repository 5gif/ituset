# ituset
Set of configurations (ITU, 3GPP, Simulation) files for IMT-2020 Evalation 


# Cellular Simulation

The system simulation depends on mainly three input [configurations](#configurations)
- ITU-R M.2412 - IMT Parameters (Agnostic to technology)  [itucfg](#itucfg)
- System parameters - Specific to 3GPP Technology [nrcfg](#nrcfg)
- Simulation level paramters [simcfg](#simcfg)
- Master Config - Input, Output DIR to read and write files etc.,


# System Description

@todo Explain the system based on ITU parameters.

Current Environment :  \`${itucfg.ENV}\` Environment for **Config-${itucfg.CONFIG}** for the \`${itucfg.SCENARIO}\` Usage Scenario 

**Key Paramters** : ISD = ${itucfg.ISD}m, Frequency = ${nrcfg.FcGHz*1000}MHz

**Key 3GPP NR Parameters** :

Electrical Tilt : ${nrcfg.ElectricalTilt}degree   

BSAntennaConfig :  [${nrcfg.BSAntennaConfig.join(",")}]
