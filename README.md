# Ohm's Law - LED Current Experiment

## 🎯 Objective

To understand Ohm's Law and experimentally observe how changing resistance affects current in an LED circuit while keeping the supply voltage constant.

## 💡 Concept

Ohm's Law describes the relationship between voltage, current, and resistance:

I = V / R

When voltage is constant:

- Increasing resistance decreases current.
- Decreasing resistance increases current.

## 🔧 Circuit

The circuit used was:

9V Supply → Resistor → Red LED → 9V Negative

Two resistor values were tested:

- 1kΩ
- Approximately 781Ω

## 🧮 Design Calculation

For a 9V supply and a red LED with an approximate forward voltage of 2V, the resistor required for approximately 9mA was estimated as:

R = (9V - 2V) / 0.009A

R ≈ 778Ω

A resistor of approximately 781Ω was then tested in the simulation.

## 🧪 Simulation Results

| Resistor | Measured Current |
|----------|------------------|
| 1kΩ      | 7.05mA           |
| ~781Ω    | 9.00mA           |

## 🔍 Comparison

When the resistance was reduced from 1kΩ to approximately 781Ω, the measured current increased from 7.05mA to 9.00mA.

This demonstrates that, at approximately constant voltage, reducing resistance increases current.

## 🧠 What I Learned

- Ohm's Law relates voltage, current, and resistance.
- At constant voltage, current decreases when resistance increases.
- At constant voltage, current increases when resistance decreases.
- Practical LED circuits do not always match the simple resistor-only calculation because an LED has its own voltage drop and nonlinear behavior.
- Calculations can be used to design a circuit, while simulation measurements help verify its actual behavior.

## 🏭 Engineering Lesson

Circuit design involves more than calculating a theoretical value.

A useful engineering process is:

**Calculate → Build → Measure → Compare → Understand**

## 🛠️ Tools Used

- Tinkercad Circuits
- Ohm's Law calculations
- LED
- Resistors
- 9V supply
