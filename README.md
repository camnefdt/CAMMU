# CAMMU - V1

CAMMU is a universal multi material filament system, inspired by ERCF and Tradrack systems but designed to use no servo at all and keep components as accessible as possible.

A full custome controller and DIY controller is currently in the works and to be released soon. 2 stepper ports and 6 endstop connections are all that is needed if you build the 4 gate version.

Please feel free to contribute towards future projects and developments

![alt text][image]

[image]: https://github.com/camnefdt/CAMMU/blob/main/V1_Release/pics/IMG_20250531_124000.jpg
### Updates
- 13-12-2025:
    - Added ERCT axles of various lengths to help users whom are building more then 4 gates
- 06-08-2025:
    - Added CAMMU Gate Spacer to make the gate spacing a lot simpler
- 06-06-2025:
    - CAMMU Full release V1
    - Fixed folder structure and renamed old Beta to "CAMMU_Old"
    - Added modified ERCT-Cotton tail buffer files
    - **NOTE** The Cotton tail end cap with electronics was modified to fit BTT mmb V2 which is different size and mounting hole to MMB v1.
- 05-06-2025:
  - Added strengthened drive ends
  - Added slightly adjusted tension arm to align better on gate.
  - Added completed project photo.
- 01-04-2025:
  - Added modified top gate with thickened rear section for limit switch mount and enlarged screw holes for m3 screws.
- 12-03-2025:
  - Added build manual V1.
- 19-01-2025:
  - Added modified selector body to prevent premature wear of housing body.
  - Added slots to limit switch mounting on selector body.
  - Added strengthened selector drive end to limit unnecesary flex.
  - Moved extrude drive end idler pulley inward to make system more compact
  - Added more material on the bottom gate pivot ears to strengthen.
  - Modified to match new bottom gate ears as well as slotted limit switch mounting holes.
- 08-12-2024:
  - Added Build FAQ 
- 05-12-2024:
  - Add in basic instructions for assembly


### Build FAQ
- For the buffer, the ERCT (Cotton tail) buffer is a perfect fit. [***HERE***](https://github.com/Enraged-Rabbit-Community/ERCF_v2/tree/master/Recommended_Options/ERCT_Buffer)
- For the software control aspect of CAMMU, we decided to not reinvent the wheel and make use of the fantastic existing software called **Happy Hare** by moggieuk. You can find his github page [***HERE***](https://github.com/moggieuk)
  - You are requied to [***install Happy Hare***](https://github.com/moggieuk/Happy-Hare/wiki/Installation) on your existing klipper installation.
  - In due time we will compile a short guide on the installation and configuration of **Happy Hare**
- For the sensing aspect, not only do you require a filament sensor per gate, but also require a filament sensor on your toolhead
  - If you currently use the Sherpa range:
    - You can find a fantastic toolhead sensor for [***Sherpa Mini***](https://github.com/v6cl/MyDIYthings/tree/main/3Dprinters/AnnexEngineeringMOD/SherpaMini/SherpaMiniFilamentSensor).
      - This is a fantastic toolhead sensor and can easily be wired up to your existing toolhead board if you have one.
  - You also require a filament cutter on your toolhead as
    - The one we recommend and have tested can be found on Prusa Printables [***HERE***](https://www.printables.com/model/622289-filament-cutter-for-sherpa-and-sherpa-patterned-ex/files)


buy me a coffee
[***HERE***](https://www.buymeacoffee.com/camnefdt)
<a href="https://www.buymeacoffee.com/camnefdt"><img src="https://img.buymeacoffee.com/button-api/?text=Support CAMMU&emoji=&slug=camnefdt&button_colour=FFDD00&font_colour=000000&font_family=Cookie&outline_colour=000000&coffee_colour=ffffff" /></a>
