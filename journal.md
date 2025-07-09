# comfort40 journal  
a log of everything from brain fog to actual progress  

---

## July 1  
**Task**: Starting the schematic  
Sat down and opened KiCad for the first time on this project  
Added footprints for diodes and switches  
Googled “how to do schematic layout properly” more than once  
Started basic matrix planning but got distracted halfway  

**Time Spent**: 0.8 hrs  

| Image | Description |
|-------|-------------|
| ![image](https://github.com/user-attachments/assets/d1996188-5212-48e2-af35-a0dfc16e0273) | Initial schematic work in KiCad |

---

## July 2  
**Task**: Schematic cleanup and adding components  
Realized the diode directions were all over the place  
Fixed them and added reset button and rotary encoder footprints  
Spent more time figuring out encoder wiring than expected  

**Time Spent**: 1.2 hrs  

| Image | Description |
|-------|-------------|
| ![image](https://github.com/user-attachments/assets/537d3a9a-4b7b-4d4d-bcd2-40fde0db1bfc) | Updated schematic with rotary encoder |

---

## July 3  
**Task**: PCB routing  
Did almost all the routing in one session  
Tried using the autorouter then gave up and went manual  
Double-checked spacing for Kailh sockets and encoder clearance  

**Time Spent**: 2.0 hrs  

| Image | Description |
|-------|-------------|
| <img width="729" alt="image" src="https://github.com/user-attachments/assets/cadf813a-3665-4bd1-b0d2-c84b20b54bde" /> | Final routed board in PCB editor |

---

## July 4  
**Task**: Part selection  
Browsed through parts for like three hours  
Shortlisted switches and keycaps  
Tested encoder sizes against the board  
Made a spreadsheet for the BOM  

**Time Spent**: 1.5 hrs  

| Image | Description |
|-------|-------------|
| ![image](https://github.com/user-attachments/assets/51310cb2-f3d4-4664-88f8-8be9e9805b44) | BOM draft and part selection progress |

---

## July 5  
**Task**: MCU and firmware planning  
Decided on rp2040 for compact form factor  
Verified that the encoder and matrix pin assignments were valid  
Sketched out rough layout plan for QMK config  

**Time Spent**: 1.0 hrs  

| Image | Description |
|-------|-------------|
| ![image](https://github.com/user-attachments/assets/ede32f65-d854-4e25-99e2-60068acd711f)  | Pinout notes and QMK planning sketch |

---

## July 6  
**Task**: Starting the 3D model  
Imported plate from KiCad into Fusion  
Started blocking out the top shell  
Tried 3 different plate mounting ideas  
Settled on using standoffs and snap fit  

**Time Spent**: 2.0 hrs  

| Image | Description |
|-------|-------------|
|   <img width="968" alt="3drender" src="https://github.com/user-attachments/assets/180e6d76-1b8b-42e4-a49d-ba128c1201dd" /> | Fusion model of top case beginning |

---

## July 7  
**Task**: Modeling the bottom shell  
Finished standoffs and modeled cutout for encoder  
Totally forgot to leave space for the USB port  
Fixed wall thickness and made the case printable  

**Time Spent**: 2.0 hrs  

| Image | Description |
|-------|-------------|
|    ![image](https://github.com/user-attachments/assets/c4fe4806-2d12-4d22-af69-cb92cc8c9cc1) | Bottom case in Fusion with encoder slot |

---

## July 8  
**Task**: Detailing the model  
Refined corner radius and added fillets  
Did a dry run to align the plate with the case  
Added inner ledge for plate support  
Rendered a high-res preview for the log  

**Time Spent**: 2.5 hrs  

| Image | Description |
|-------|-------------|
|    ![image](https://github.com/user-attachments/assets/04cc2af3-99bf-4a66-9ee1-e16c87924aa6) | Final case design and render preview |

---

## July 9  
**Task**: File exports and measurements  
Exported STL files for both case halves  
Did a full clearance check on encoder and switch positions  
Made sure screw holes lined up with standoffs  

**Time Spent**: 1.5 hrs  

---

## July 10  
**Task**: Final checks and summary  
Went through schematic PCB and model once more  
Tested the VIA layout and generated JSON  
Saved everything to repo and backed it up  

**Time Spent**: 1.0 hrs  

---

## Total Time Logged  
**~14.5 hours**  
