# aRtiLLeRY GENIUS <img align="right" width=200 src="/resources/icons/aRtiLLeRY GENIUS.png?raw=true" />

## Marlin 2.0.7.2 
Item|Modelo|Documentacion 
--------|------|-------------
Firmware|Marlin|[Version 2.0.7.2]()
Board|MKS GEN L V1.0|[Datasheet](https://github.com/omonge22/MKS-GEN_L)
Drivers|TMC2100|[Datasheet](https://github.com/omonge22/evoz3D/tree/main/resources/Datasheet/TMC2100)
Display|BTT TFT35| [Datasheet](https://github.com/omonge22/BIGTREETECH-TouchScreenHardware/tree/master/BTT%20TFT35%20V3.0) <br/> [Firmware](https://github.com/omonge22/BIGTREETECH-TouchScreenFirmware)
Extruder|Direct Titan Clone|[e3d assembly](https://e3d-online.dozuki.com/Guide/1.75mm+Direct+Titan+Assembly/19?lang=en) <br/> [Bracket Drawing](https://github.com/omonge22/evoz3D/blob/main/resources/Drawing/Titan%20Extruder/Bracket%20Printed.pdf) <br/> [Titan Drawing](https://github.com/omonge22/evoz3D/blob/main/resources/Drawing/Titan%20Extruder/Titan%20Assembly.pdf)
Hotend|Volcano Clone|[e3d assembly](https://e3d-online.dozuki.com/Guide/Building+a+new+Volcano/9?lang=en) <br/> [Volcano Nozzle Drawing](https://github.com/omonge22/evoz3D/blob/main/resources/Drawing/Volcano%20Nozzle/Volcano%20Nozzle.pdf) <br/> [Volcano Block Drawing](https://github.com/omonge22/evoz3D/blob/main/resources/Drawing/Volcano%20Nozzle/Volcano%20Block.pdf) <br/> [Volcano V6 Assembly](https://github.com/omonge22/evoz3D/blob/main/resources/Drawing/Volcano%20Nozzle/Volcano%20Nozzle%20Assembly.pdf)
Size|220x220x250|
Kinematics|Cartesian|
Steppers| X, Y, Z1, Z2, E0|Doble Z individualizado (G34 - Auto alineamiento Z)
Bed Leveling|BLTouch|[Manual](https://github.com/omonge22/evoz3D/blob/main/resources/Drawing/BLTouch/BLTouch%20Manual.pdf)
Bed|AC 120V|
Power|24V|

### Mods
En el archivo `pins_RAMPS.h` se cambia el pin 4 por el 2 para poder colocar el final de carrera en `XMAX endstop`
<br/> Ubicacion `Marlin\src\pins\ramps`
```
// RAMPS 1.4 DIO 4 on the servos connector
#ifndef FIL_RUNOUT_PIN
  #define FIL_RUNOUT_PIN  2
#endif
```

**Por defecto**
```
// define digital pin 4 for the filament runout sensor. Use the RAMPS 1.4 digital input 4 on the servos connector
#ifndef FIL_RUNOUT_PIN
  #define FIL_RUNOUT_PIN  4
#endif
````

> **Cables**
<br/> gris | blanco | negro |  De izquierda a derecha, viendo la conexion de pantalla hacia el Norte.



## Factory conf - Marlin 1.1.9
Item|Modelo|Documentacion
--------|------|-------------
Firmware|Marlin|[Version 1.1.9](https://github.com/omonge22/Marlin/tree/aRtiLLeRY-GENIUS_Factory-Marlin-1.1.9)
Board|MKS GEN L V1.0|[Datasheet](https://github.com/omonge22/MKS-GEN_L)
Drivers|TMC2100|[Datasheet](https://github.com/omonge22/evoz3D/tree/main/resources/Datasheet/TMC2100)
Display|MSKTFT28| [Firmware](https://github.com/omonge22/genius-tft-firmware)
Extruder|Direct Titan Clone|[e3d assembly](https://e3d-online.dozuki.com/Guide/1.75mm+Direct+Titan+Assembly/19?lang=en) <br/> [Bracket Drawing](https://github.com/omonge22/evoz3D/blob/main/resources/Drawing/Titan%20Extruder/Bracket%20Printed.pdf) <br/> [Titan Drawing](https://github.com/omonge22/evoz3D/blob/main/resources/Drawing/Titan%20Extruder/Titan%20Assembly.pdf)
Hotend|Volcano Clone|[e3d assembly](https://e3d-online.dozuki.com/Guide/Building+a+new+Volcano/9?lang=en) <br/> [Volcano Nozzle Drawing](https://github.com/omonge22/evoz3D/blob/main/resources/Drawing/Volcano%20Nozzle/Volcano%20Nozzle.pdf) <br/> [Volcano Block Drawing](https://github.com/omonge22/evoz3D/blob/main/resources/Drawing/Volcano%20Nozzle/Volcano%20Block.pdf) <br/> [Volcano V6 Assembly](https://github.com/omonge22/evoz3D/blob/main/resources/Drawing/Volcano%20Nozzle/Volcano%20Nozzle%20Assembly.pdf)
Size|220x220x250|
Kinematics|Cartesian|
Steppers| X, Y, Z1, Z2, E0|Sincronizacion Z por medio de faja
Bed Leveling|-|Previsto sistema BLTouch
Bed|AC 120V|
Power|24V|




