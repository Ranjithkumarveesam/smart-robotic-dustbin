# Smart Robotic Dustbin Block Diagram

![Block Diagram](diagrams/block_diagram.png)

- Smart Dustbin Lid Servo
- Ultrasonic/IR Sensors for waste detection
- Sorting Mechanism (servo-controlled chute)
- Waste bin partitions: Wet, Dry, Paper, Covers
- Microcontroller: Arduino/Raspberry Pi
- Speech Module: Text-to-Speech out
- Display: OLED/LCD matrix
- Sanitizer Pump (controlled via IR/proximate hand)
- Chocolate dispensation and seed wrapping automation motor
- Relays for actuators
- Power supply

## System Flow
1. **Detect waste placement:** Sensor triggers stomach door (servo).
2. **Sort waste:** Sort into correct partition (based on sensor).
3. **Eco Reward:** Dispense chocolate (servo motor), wrap seed in paper.
4. **Sanitizer:** Dispense sanitizer upon hand placement.
5. **Quotes and Expressions:** Display quote and emoji, speak quote.
6. **Interaction:** Friendly speech and expressive responses.

## Diagram
(Diagram will be updated with hand-drawn or software schematic soon.)
