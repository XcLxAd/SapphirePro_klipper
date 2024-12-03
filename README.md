# SapphirePro_klipper
Two Trees SapphirePro 3D printer settings for klipper.

Matherboard - MKS-Robin-Nano-V1.2


__Settings for OrcaSlicer:__
  
  - Start G-code:

    `START_PRINT EXTRUDER_TEMP=[first_layer_temperature] BED_TEMP=[first_layer_bed_temperature] Z_ADJUST=0.070`

    `PRIME_LINE F={initial_layer_speed}`
  
  - End G-code:

    `END_PRINT`

  - Start G-code filament:

    `SET_PRESSURE_ADVANCE ADVANCE=0.084`
