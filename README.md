# Comfort40

Comfort40 is a compact 40-key mechanical keyboard designed to ditch all the bloat and keep only what matters. It’s got the vibe of minimalism with just enough muscle to handle your everyday typing, coding, shortcut-spamming, and layer-fu. Built for chill, built for speed, built for the desk setups that scream “I know what I’m doing.”

![image](https://github.com/user-attachments/assets/1e82e9fc-8fce-48a1-beae-bce962e7a07d)


---

## What Even Is This

Comfort40 is a DIY keyboard project for anyone who’s ever looked at a full-size keyboard and thought “nah.” It’s a 40% board, ortholinear (so all the keys line up like a grid), and completely open source. You can build it however you like solder or hotswap, loud clicky switches or silent stealthy ones. It’s your call.

This board runs QMK and VIA, so you can customize literally every key. Layer keys? Macro madness? Tap dance? Yeah, it’s all here. Want a numpad? Put it on a layer. Arrows? You bet. The layout may be tiny but the power is unhinged.

---

## The Vibe

Comfort40 is designed in KiCad, modeled in Fusion 360, and 100% meant to be hacked on. The case is 3D printable, the plate is laser cuttable.
---

## Build Stats

layout → 4x10 grid  
switches → MX-style 
controller → RP2040  
port → USB-C  
pcb → hotswap  
NO RGB THO  
case → printable 
firmware → QMK + VIA

---
| Component                  | Description                                      | Qty | Estimated Price (USD) | Notes |
|---------------------------|--------------------------------------------------|-----|------------------------|-------|
| **PCB**                   | Custom Comfort40 PCB                             | 1   | $30.00(after coupon)   | From JLCPCB or similar |
| **Microcontroller**       | RP2040                                           | 1   | $2.00                  | USB-C |
| **Switches**              | MX-compatible mechanical switches                | 40  | $20.00                 | Gateron|
| **Keycaps**               | 40-key ortholinear set                           | 1   | $23.00                 | XDA/DSA works well |
| **Diodes**                | 1N4148                                           | 40  | $3.00                  | Through-hole or SMD |
| **Reset Switch**          | Tactile momentary switch                         | 1   | $0.50                  | Used for flashing |
| **Hotswap Sockets**       | Kailh MX hotswap sockets                         | 40  | $8.00                  | Why not |
| **Plate**                 | Laser-cut acrylic or FR4                         | 1   | $6.00                  | DXF included |
| **Case (Top + Bottom)**   | 3D printed or resin enclosure                    | 1   | $18.00                 | Print or outsource |
| **Screws/Standoffs**      | M3 hardware                                      | 1 set | $2.00                | For mounting everything |
| **USB Cable**             | USB-C to USB-A cable                             | 1   | $4.00                  | Any decent one |
| **Rotary Encoder**        | EC11 vertical rotary encoder                     | 1   | $2.00                  | Includes push button switch |
| **Knob Cap**              | Aluminum or plastic vertical knob                | 1   | $1.50                  | Press-fit or set screw type |
| **Foam/Dampening**        | EVA foam or PE sheet                             | 1   | ALREADY HAVE IT AT HOME| Optional silencing mod |

---
## Estimated Total: **$120.00 USD**


## Images

## Fully Assembled Render  
| Image | Description |
|-------|-------------|
| <img width="1125" alt="fully assembled render" src="https://github.com/user-attachments/assets/b25a1f96-3e9b-4d84-83ee-15db85797ef3" /> | A render straight outta Fusion 360. You’re looking at the full Comfort40 in all its glory, keycaps and all. |

## PCB  
| Image | Description |
|-------|-------------|
| <img width="988" alt="pcb" src="https://github.com/user-attachments/assets/e28a2817-680a-41ed-a237-d80aa2330bfe" /> | KiCad PCB layout. Shows the switch footprint grid, MCU spot, USB traces, and that crispy clean diode matrix. |

## Schematic  
| Image | Description |
|-------|-------------|
| ![schematic](https://github.com/user-attachments/assets/093c0030-422a-466b-8b7a-45d711813bf6) | The full wiring brain. Every connection from switch to controller. Diodes, resistors, reset, and the rest. |

## KiCad 3D View  
| Image | Description |
|-------|-------------|
| ![3dview](https://github.com/user-attachments/assets/26f2c8da-9cd6-488c-902c-eda8ac0b64d1) | The raw KiCad 3D preview. Check that switch layout and component placement. No case here, just vibes. |

## Hot swappable
| Image | Description |
|-------|-------------|
| <img width="618" alt="image" src="https://github.com/user-attachments/assets/43e7f192-4b49-4cfb-8506-24b7866044d7" /> | KLE Layout |

---

## Flashing the Brain

QMK is the default brain of Comfort40. Flash it with QMK Toolbox or VIA Configurator

---

## Who It’s For

- people who like small keyboards  
- people who like building stuff  
- people who hate reaching for arrow keys  
- people who want full power in a tiny square of plastic  
- also people who just want a reason to use their soldering iron again

---

## Licence

MIT

made for comfort not clutter  
zero bloat  
just keys
