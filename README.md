
# 🕹️ Hackpad | osu!mania 4K keyboard

As the name suggest, this is a hackpad that is tuned for osu!mania (the keyboard rhythm game), and only has four keys!
<br><br>

*Note: following image is still just the PCB, will update soon once the CAD is complete.*

<img width="1025" height="498" alt="Pasted image" src="https://github.com/user-attachments/assets/a1c1cc63-68f7-4998-9c33-10b76efd7c68" />
<br<br>

For some background, this is technically not my first hackclub project.
I've circled the idea of following the Hackpad mission for some time now, and at the same time, I started playing the game [**osu!mania**](https://www.youtube.com/results?search_query=osu!mania) competitively, while using my laptop's keyboard. After one million taps on a single set of four keys, I finally decided to make one.
Additionally, while my ThinkPad's keyboard is awesome, the actuation force is actually quite heavy (60-70g), which heavily affected my endurance.
<br>

**In summary, this gives the benefit of:**
1) Preventing wear and tear on my keyboard
2) Keeping my hands from breaking apart
3) All the knowledge gained from a stardance hardware project.

<br><br><br>

## ⚙️ Features & Specifications
<br>

(Function diagram TBA)

**Dimensions: 100*42mm**
Made to maximize spacing between the left and right keys

**Peripherals: OLED Display, Rotary Encoder, 4x Standard Cherry MX switches**

**MCU: Seeeed Studio Xiao RP2040**

**Lighting: Per-key SK6812-MINI-E RGB LEDs**

**SMD footprint: 0805 Handsolder**
<br><br><br>

## 🛠️ Build your own

<br>

The assembly process follows a standard hackpad:
1) Order the PCB from JLCPCB (or another fab)
2) Solder all the parts (Although there were smd components, they're all in 0805 handsolder footprints)
3) 3D-print the case
4) Assemble the case, PCB, switches, and OLED display.
5) Upload the firmware.
<br>
All the necessary files are provided in this repository, so go take a look around before doing so.
<br>

### 📜 BOM
1) 1* Seeeed Studio XIAO RP2040
2) 1* EC11 Rotary Encoder (vertical)
3) 1* 128*32 0.91" OLED display
4) 4* Cherry MX-compatible switches
5) 4* SK6812-MINI-E Reverse mount ARGB LEDs
6) 4* 100nF 0805 Capacitors
7) 10* 10K 0805 Resistors
8) 1* 220R 0805 Resistors (optional, bridge R5 if not used)
9) 4* M3 Threaded inserts
10) 4* M3*16 screws
11) 3D printed case
12) 3D printed rotary encoder knob


