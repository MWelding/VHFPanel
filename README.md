# 📡 VHF Panel
A simple and efficient **VHF Panel** designed for use on the **VATSIM Network** with an **Arduino Mega** and **Mobilfight**. It utilizes common, easily accessible components and is wired with **Dupont connectors** for straightforward assembly.

![VHF Panel Image](images/main.jpeg)

## ⚙️ Features  
- **Displays standby frequency on an 8-digit 7-segment display**
- **Single rotary encoder knob:** (Supports both single and double encoders)
  - Integrated button allows switching between large and small frequency increments
- **Generic KD22 push button:** Can be assigned to any custom function
- **Frequency toggle button:** Quickly switch between active COM1 and standby frequencies
- **Side-mounted digital encoder:** Designed for use as a trim control

---

## 🛠️ Materials Used

- **Arduino Mega R3 (25 Euro)**  
  [Available on Amazon](https://www.amazon.de/-/en/dp/B09F9VJBZX?_encoding=UTF8&psc=1)

- **7-Segment Display 3-Pack (10 Euro)**  
  [Available on Amazon](https://www.amazon.de/-/en/AZDelivery-MAX7219-TM1637-Compatible-Raspberry/dp/B07Z7RHD2J)

- **Rotary Encoders 5-Pack (10 Euro)**  
  [Available on Amazon](https://www.amazon.de/-/en/KY-040-Encoder-Automotive-Electronics-Multimedia/dp/B09726Y8RB)

- **Push Button 30-Pack (10 Euro)**  
  [Available on Amazon](https://www.amazon.de/-/en/RUNCCI-YUN-Pieces-Momentary-Button-Railway/dp/B08P4DD2BP)

- **KD-22 Illuminated Non-Locking Switches 10-Pack (12 Euro)**  
  [Available on Amazon](https://www.amazon.com/Locking-Button-Switch-19x19mm-Illuminated/dp/B07CXN14QV?th=1)

- **8 Pieces M3 Bolts (+-8 mm)**
- **220 Ohm Resistor**
- **M3 Washers:** May not be necessary depending on M3 screw size
- **3D Printed Parts**

**Total Project Cost (Essential Components Only): 34 Euro**  
**Total Project Cost (Full Build): 67 Euro**


## 🖨️ 3D Printed Housing
The enclosure is thoughtfully designed for easy 3D printing on an **Ender 3** printer. The **STL folder** includes three essential files:
- **Main enclosure**
- **Top panel**
- **Optional rotary encoder knob**

<div style="display: flex; justify-content: center;">
  <img src="images/Enclosure.png" alt="Enclosure" width="300" height="300">
  <img src="images/Top panel.png" alt="Top Panel" width="300" height="300">
  <img src="images/knob.png" alt="Rotary Knob" width="300" height="300">
</div>

Achieving the perfect fit for the rotary encoder might require some fine-tuning. We recommend adjusting the **print size by 1-2%** up or down and testing multiple versions to ensure an optimal fit.



## ⚡ Electronics
Most components, such as the **7-segment display** and **rotary encoders**, can be directly connected using their respective PCB pins. However, the **KD-22 switch** and **momentary switch** will require some soldering to function properly.

Below is a user-friendly wiring diagram showing the components laid out as if viewed from behind (inside the case).

### 📌 Notes:
- The connections to the **KD-22 switch** are exposed; ensure you use **heat-shrink tubing** or **electrical tape** to insulate them.
- The **Arduino Mega** (at least the model used here) doesn't have enough **VCC** or **GND** pins for every component. Daisy chaining with Dupont connectors isn't ideal. A simple solution is to create **Y-splitters** for better connectivity.



## ⚙️ Mobiflight Setup
*This section is currently under development. Stay tuned for updates!*




