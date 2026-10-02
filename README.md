# Smart-Wave-Gesture-Switch
Touchless appliance-control circuit using IR sensing, LM358 comparator, CD4017 decade counter, and SPDT relay.

A touchless, gesture-controlled appliance switching system designed to toggle electrical loads without physical contact using infrared (IR) proximity sensing and sequential logic.

## 🛠️ Components & Hardware Stack
* **Sensor Module:** IR LED and Photodiode pair
* **Signal Conditioning:** LM358 Operational Amplifier (Comparator)
* **Sequential Logic:** CD4017 Decade Counter IC
* **Switching Stage:** Transistor interface and 5V SPDT Relay
* **Indicator:** LED status feedback

## 📋 Working Principle
1. **Proximity Detection:** The IR sensor detects hand gestures or motion within a configured range, altering the reflected infrared radiation.
2. **Signal Conditioning:** The LM358 comparator processes the analog sensor signals and converts them into clean digital triggers.
3. **State Switching:** The CD4017 decade counter acts as a sequential controller, toggling its output state on each valid motion trigger.
4. **Relay Activation:** The transistor stage drives the 5V SPDT relay to safely switch the connected appliance load on or off.


## 🎥 Project Demonstration

[▶ Watch Project Demonstration on Google Drive](https://drive.google.com/file/d/1jD3PgkqN8fh4GAVC00ui7RsuglN7NtiL/view?usp=sharing)
