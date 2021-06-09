# evoz3D <img align="right" width=300 src="/resources/icons/evoz3D_logo.png?raw=true" />



## Tabla de contenidos
  1. [Introducción](#Introducción)
  1. [Firmware ](#Firmware)
  1. [Perfiles de Laminado PrusaSlicer / SuperSlicer](#Perfiles-de-Laminado-PrusaSlicer-/-SuperSlicer)
  1. [Custom Buildplate](#Custom-Buildplate)
  1. [Apoya mi Trabajo](#Apoya-mi-Trabajo)
  1. [Gracias](#Gracias)



## Introducción
**evoz3D** es una empresa costarricense especializada en diseño e ingeniería que desarrolla y estimula la creatividad en productos y servicios 3D

El siguiente repositorio muestra las configuraciones para las impresoras utilizadas/desarrolladas/ajustadas por **evoz3D** en terminos de Firmware y relacionado, asi como las configuraciones de laminado para el software PrusaSlicer y SuperSlicer para dichas impresoras...

Adicional se encuentran los **_Custom Buildplate_** para cada uno de los equipos.



## Firmware 
[<img align="right" width=150 src="https://github.com/MarlinFirmware/Marlin/blob/2.0.x/buildroot/share/pixmaps/logo/marlin-250.png?raw=true" />](https://github.com/omonge22/Marlin)

 ### Impresoras

* #### aRtiLLeRY GENIUS [wiki](https://github.com/omonge22/evoz3D/blob/main/Wiki/aRtiLLeRY%20GENIUS/README.md)
  * Factory
  * > Recursos tomados del repositorio de [aRtiLLeRY 3D](https://github.com/artillery3d) 
    * [Marlin 1.1.9](https://github.com/omonge22/genius-firmware)
    * [TFT: mkstft28](https://github.com/omonge22/genius-tft-firmware) [<img align="right" width=150 src="https://avatars.githubusercontent.com/u/12979070?v=4" />](https://github.com/makerbase-mks)
    * [Contenido USB](https://drive.google.com/file/d/1ymOYUReszwrEQ4nJWugZOiGnmjrinvXf/view)
    * [Cura Profile](https://github.com/artillery3d/slicer_profiles)
    * [PDF Manual](https://drive.google.com/file/d/103mb-JaXS-LajUZ2fF9sH9GxXkMXWKK5/view)
  * [evoz3D Marlin Repository (1.1.9)](https://github.com/omonge22/Marlin/tree/aRtiLLeRY-GENIUS_Factory-Marlin-1.1.9) 
  * BLTouch / BTT TFT35
  * SKR1.4Turbo [_in process_](https://raw.githubusercontent.com/omonge22/evoz3D/main/resources/icons/web-pc.jpg)

* #### Prusa BEAR Custom [wiki](https://github.com/omonge22/evoz3D/blob/main/Wiki/Prusa%20BEAR/README.md) [<img align="right" width=150 src="https://avatars.githubusercontent.com/u/38851044?v=4" />](https://github.com/bigtreetech)
  * BMG Extruder [Marlin 2.???]
  * BEAR Extruder [_in process_](https://raw.githubusercontent.com/omonge22/evoz3D/main/resources/icons/web-pc.jpg)

* #### Prusa MINI FRANKENSTEIN
  * [Marlin 2.0.8.?](https://raw.githubusercontent.com/omonge22/evoz3D/main/resources/icons/web-pc.jpg)

* #### BLV-EVA
  * [Marlin 2.0.8.2](https://github.com/omonge22/Marlin/tree/_BLV-EVA)

* #### PORTU Prusa [wiki](https://github.com/omonge22/evoz3D/tree/main/Wiki/PORTU%20Prusa)
  * [_in process..._](https://raw.githubusercontent.com/omonge22/evoz3D/main/resources/icons/web-pc.jpg)

* #### Kingroom Kp3S
  * Factory
   * > Recursos tomados de [Kingroon.com](https://www.kingroon.com/downloads/)
     * Marlin (.bin)
       * [Firmware](https://github.com/omonge22/evoz3D/tree/main/resources/Kingroon%20Factory/KP3S-Firmware-201022)
       * [Firmware - BLTouch](https://github.com/omonge22/evoz3D/tree/main/resources/Kingroon%20Factory/KP3S-Firmware-3Dtouch)
     * [Contenido USB](https://drive.google.com/file/d/1L9fIGaFAllFT-b9qKtVpjevujm8QpJ2f/view)
     * [PDF Manual](https://github.com/omonge22/evoz3D/blob/main/resources/Kingroon%20Factory/KP3S-Manual.pdf) 



## Perfiles de Laminado PrusaSlicer / SuperSlicer
### Impresoras agregadas:
#### [Prusa Slicer](https://github.com/omonge22/evoz3D/tree/main/PrusaSlicer_config_bundle) <img align="right" width=150 src="https://raw.githubusercontent.com/prusa3d/PrusaSlicer/master/resources/icons/PrusaSlicer.png?raw=true" />

* aRtiLLeRY GENIUS
* Prusa BEAR Custom
* Prusa FRANKESTEIN MINI (_Proyecto abandonado_)
* BLV-EVA [_in process..._](https://raw.githubusercontent.com/omonge22/evoz3D/main/resources/icons/web-pc.jpg)
* PORTU Prusa [_in process..._](https://raw.githubusercontent.com/omonge22/evoz3D/main/resources/icons/web-pc.jpg)


#### [Super Slicer](https://github.com/omonge22/evoz3D/tree/main/SuperSlicer_config_bundle) <img align="right" width=125 src="https://github.com/supermerill/SuperSlicer/blob/master/resources/icons/SuperSlicer.png?raw=true" />
* aRtiLLeRY GENIUS
* Prusa BEAR Custom
* BLV-EVA [_in process..._](https://raw.githubusercontent.com/omonge22/evoz3D/main/resources/icons/web-pc.jpg)
* PORTU Prusa [_in process..._](https://raw.githubusercontent.com/omonge22/evoz3D/main/resources/icons/web-pc.jpg)



## Custom Buildplate
Las carpetas _Custom Buildplate_ permiten personalizar el entorno del laminador para mostrar una imagen similar a la cama física de la impresora.

Se adjuntan 3 archivos:
* **.stl** el cual muestra el modelado 3D de la superficie de impresión.
* **.png** el cual muestra los logos dibujados en la superficie de impresión.
* **.xcf** el cual es la extesión del programa **[_gimp_](http://www.gimp.org.es/)** para personalizar los logos/superfices. <img align="right" width=50 src="https://gitlab.gnome.org/uploads/-/system/project/avatar/1848/gimp-wilber.png?width=64?raw=true" />

### Impresoras
* [aRtiLLeRY GENIUS](https://github.com/omonge22/evoz3D-Config_Bundle/tree/main/Custom%20Buildplate/aRtiLLeRY%20GENIUS)
* [Prusa MINI FRANKENSTEIN](https://github.com/omonge22/evoz3D-Config_Bundle/tree/main/Custom%20Buildplate/Prusa%20MINI%20FRANKENSTEIN)
* BLV-EVA [_in process..._](https://raw.githubusercontent.com/omonge22/evoz3D/main/resources/icons/web-pc.jpg)



## Apoya mi Trabajo
[![paypal.me](resources/icons/paypal_50px.png)](https://www.paypal.me/omonge22)<br/>[paypal.me/omonge22](https://www.paypal.me/omonge22)
<br/><br/>
También podrías invitarme a un café en [Thingiverse](https://www.thingiverse.com/omonge22/designs) si asi lo prefieres.



## Gracias
A todas aquellas personas que permiten que **evoz3D** sea parte de sus proyectos...

