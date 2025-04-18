# 🚦 Tiva C TM4C123G: LED Toggle Using Push Button

This project demonstrates how to cycle through different LED colors (Red, Green, Blue, Off) on a Tiva C Series TM4C123G LaunchPad using a single push button.

## 🎯 Project Objective

- Use **SW1 (PF4)** button to toggle LEDs in the following order:
  - 🔴 RED
  - 🟢 GREEN
  - 🔵 BLUE
  - ⚫ OFF
- On each button press, the LED changes.

## 🛠️ Hardware Used

- TM4C123GXL LaunchPad
- Onboard RGB LED (connected to PF1, PF2, PF3)
- Onboard Push Button SW1 (connected to PF4)

## 🧪 Working Principle

- The button is configured with a **pull-up resistor** (active-low logic).
- The system keeps track of the state (`0 - 3`) and cycles through:
0 -> RED ON
1 -> GREEN ON
2 -> BLUE ON
3 -> ALL OFF
  ## ▶️ How to Run

1. Flash the code to your TM4C123G using Keil uVision.
2. Press SW1 button repeatedly.
3. Watch the RGB LED change colors in sequence.

## 🧑‍💻 Author

**Muhindhar**  
KIOT - Department of ECE  
