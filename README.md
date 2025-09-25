# BANZAI-SV08
Modifications, Configs and Orca Slicer Profiles for the Sovol SV08 3D Printer
<br>
<br>
Model: Sovol SV08 - https://www.sovol3d.com/products/sovol-sv08-3d-printer
<br>
Firmware: Klipper - Mainline - https://github.com/Rappetor/Sovol-SV08-Mainline
<br>
Probe - EddyDuo running eddy-ng - https://github.com/vvuk/eddy-ng/wiki
<br>
KlipperExpander - https://github.com/VoronDesign/Voron-Hardware/tree/master/Klipper_Expander
<br>
Toolhead Cover - https://www.printables.com/model/1167115-sv08-fan-shroud-atomic-remix-v2
<br>
Tophat - https://www.printables.com/model/1392873-sv08-top-hat-double-top-hat-enclosed-for-mmus
<br>
Feet/Risers - https://www.printables.com/model/1041899-sovol-sv08-feet-v4
<br>
Door Stop - https://www.printables.com/model/1003732-sv08-door-stop
<br>
Spool Holder Relocation - https://www.printables.com/model/928589-sovol-sv08-side-mount-spool-holder-remix
<br>
Extruder Gear Pin Fix - https://www.printables.com/model/1020013-sv08-fix
<br>
SV08 Gantry Belt Fix - https://www.printables.com/model/1154812-sovol-sv08-side-slide-carriage-make-parallel-to-th
<br>
<br>
Custom SV08 Configs Description -
<br>
eddy-ng.cfg - working config for eddy-ng with updated homing and QGL.
<br>
heatsoak.cfg - variable heatsoak macro
<br>
klipperExpander.cfg - expander board config for Chamber Thermistor
<br>
led-control.cfg - controls toolhead neopixel LED
<br>
printer.cfg - main printer config - use as a reference
<br>
sovol-macros.cfg - updated mainline SV08 Macros
<br>
sovol-stock-purge.cfg - only the purge line macro from the stock sovol setup instead of using KAMP.
<br>
<br>
Custom BANZAI Mods - 
<br>
BANZAI MCU Fan Adapter - Replaces the stock metal sheet cover with a small footprint fan holder. Requres 2 or 4x M3x5mm Heatset Inserts.
<br>
![IMG_4851](https://github.com/user-attachments/assets/993e125c-ad2f-437e-ad16-c6e2f98fe5f3)
<br>
<br>
BANZAI Bed Plate Mod - Replaces the stock plastic bed plate for use with the SV08 Taco Bed Mod without needing to glue any washers: https://github.com/Wrath669/SV08BedTension/blob/main/README.md. Requires 9 M4x8mm Heatset Inserts.
<br>
<img width="1427" height="964" alt="Screen Shot 2025-09-20 at 9 58 08 AM" src="https://github.com/user-attachments/assets/8152761d-db5a-4573-8b67-f2bd35ddbdeb" />
<br>
<img width="1875" height="901" alt="Screen Shot 2025-09-20 at 9 50 53 AM" src="https://github.com/user-attachments/assets/4f1c07da-08e7-4a01-8428-49ba757e1d15" />
<br>
<br>
Calibration STLs - 
<br>
Calibration Cube + Key Measuerments Guide - Cube with holes and angled features to measure dimensional accuracy
<br>
Firebolt Calibration - 2A Feature calibration cube "IYKYK"
<br>
Flow Calibration - Filament flow calibration square for 0.4MM Nozzles. Print with filament flow ratio at 1.00 to start then measure the walls of the print with calipers. Use the equation 1.20/(Measured Value)*(Flow Rate) to find the desired rate. Repeat steps with new settings applied and remeasure. If walls are > or < 1.20mm redo the equation and rerun the test until you are in the 1.19-1.21mm wall range. 
<br>
<br>
Orca Slicer 2.3.1 Settings -
<br>
<br>
Printer Settings
<br>
<img width="943" height="1128" alt="SV08-I" src="https://github.com/user-attachments/assets/42a4da72-6131-4da2-a8c0-0b13b4f9f6da" />
<br>
<img width="889" height="1003" alt="SV08-M" src="https://github.com/user-attachments/assets/34541b09-0057-4f02-8221-2f966c71b123" />
<br>
<img width="898" height="1016" alt="SV08-E" src="https://github.com/user-attachments/assets/be4e5796-d588-485f-83f3-b8dd01714249" />
<br>
<img width="948" height="1137" alt="SV08-MO" src="https://github.com/user-attachments/assets/6ef49d37-6ec5-43d5-b254-83f7b2b457fd" />
<br>
<br>
Process Settings
<br>
Quality - 
<br>
<img width="478" height="1139" alt="Q1" src="https://github.com/user-attachments/assets/1c07f271-fe8a-4deb-97e2-7df5bcf330ce" />
<br>
<img width="477" height="710" alt="Q2" src="https://github.com/user-attachments/assets/af349a74-9647-42a6-8372-865d4a93a4db" />
<br>
<img width="476" height="821" alt="Q3" src="https://github.com/user-attachments/assets/56ad2b2e-e53c-471a-9495-15c1ac2a6a37" />
<br>
Strength - 
<br>
<img width="480" height="912" alt="ST1" src="https://github.com/user-attachments/assets/9a5c3a64-f8b5-43b3-a04f-402a1a57c99c" />
<br>
<img width="475" height="283" alt="ST2" src="https://github.com/user-attachments/assets/a2156328-6abf-4257-91cd-032b600e7252" />
<br>
Speed - 
<br>
<img width="485" height="924" alt="SP1" src="https://github.com/user-attachments/assets/d22d7ccb-33fd-4e5a-b200-2308040b841b" />
<br>
<img width="466" height="751" alt="SP2" src="https://github.com/user-attachments/assets/88fd8512-bd2e-4748-adce-c1dd0a1f2958" />
<br>
Support - 
<br>
<img width="487" height="616" alt="SU1" src="https://github.com/user-attachments/assets/df8e5793-444a-4381-a633-6bc6cf7d27b0" />
<br>
<img width="487" height="754" alt="SU2" src="https://github.com/user-attachments/assets/ee6b5d71-e2bb-47a7-a6a1-e338aafdaa98" />
<br>
Other - 
<br>
<img width="475" height="759" alt="O1" src="https://github.com/user-attachments/assets/bfdd31cf-50bc-4764-82ee-e6bb945d9315" />
<br>
<img width="485" height="656" alt="O2" src="https://github.com/user-attachments/assets/99709d91-7c12-453b-9d34-a68cb06593ca" />
<br>
<br>
Generic PLA Start Point - Tune Temperature, Flow, Adaptive Pressure Advance for specific filament being used
<br>
<img width="1027" height="1294" alt="PLA1" src="https://github.com/user-attachments/assets/1c8ff3b6-63a1-4882-a395-d89115a22545" />
<br>
<img width="1030" height="1294" alt="PLA2" src="https://github.com/user-attachments/assets/d5e9acbd-827b-408d-8f32-507fc281a94c" />
<br>
<img width="1031" height="1292" alt="PLA3" src="https://github.com/user-attachments/assets/3fea30de-bb4a-4e7f-8db0-c592bfd0f84f" />
<br>

