# Comfort40

Comfort40 is a compact 40-key mechanical keyboard designed to ditch all the bloat and keep only what matters. It’s got the vibe of minimalism with just enough muscle to handle your everyday typing, coding, shortcut-spamming, and layer-fu. Built for chill, built for speed, built for the desk setups that scream “I know what I’m doing.”

---

## What Even Is This

Comfort40 is a DIY keyboard project for anyone who’s ever looked at a full-size keyboard and thought “nah.” It’s a 40% board, ortholinear (so all the keys line up like a grid), and completely open source. You can build it however you like solder or hotswap, RGB or no RGB, loud clicky switches or silent stealthy ones. It’s your call.

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

## Images

### Fully Assembled Render  
| Image | Description |
|-------|-------------|
| <img width="1125" alt="fully assembled render" src="https://github.com/user-attachments/assets/b25a1f96-3e9b-4d84-83ee-15db85797ef3" /> | A render straight outta Fusion 360. You’re looking at the full Comfort40 in all its glory, keycaps and all. |

### PCB  
| Image | Description |
|-------|-------------|
| <img width="988" alt="pcb" src="https://github.com/user-attachments/assets/e28a2817-680a-41ed-a237-d80aa2330bfe" /> | KiCad PCB layout. Shows the switch footprint grid, MCU spot, USB traces, and that crispy clean diode matrix. |

### Schematic  
| Image | Description |
|-------|-------------|
| ![schematic](https://github.com/user-attachments/assets/093c0030-422a-466b-8b7a-45d711813bf6) | The full wiring brain. Every connection from switch to controller. Diodes, resistors, reset, and the rest. |

### KiCad 3D View  
| Image | Description |
|-------|-------------|
| ![3dview](https://github.com/user-attachments/assets/26f2c8da-9cd6-488c-902c-eda8ac0b64d1) | The raw KiCad 3D preview. Check that switch layout and component placement. No case here, just vibes. |

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

## License

MIT. Remix it. Fork it. Sell it to your friends. Just don’t be a jerk.

---

made for comfort not clutter  
zero bloat  
just keys
