# EXPERIMENT NO. 5 – ZENER DIODE AS VOLTAGE REGULATOR

| **Name:** | | **Reg. No.:** | |
|---|---|---|---|
| **Date:** | | **Batch / Section:** | |

---

## AIM

To study the Zener diode as a voltage regulator and to obtain its line regulation and load regulation characteristics.

## APPARATUS REQUIRED

| S. No. | Name of the apparatus | Range | Quantity |
|:---:|:---:|:---:|:---:|
| 1 | Zener diode | 1N4735A | 1 |
| 2 | Resistors | 1 kΩ, 10 kΩ | 1 each |
| 3 | Regulated power supply | (0–30) V DC | 1 |
| 4 | Breadboard | — | 1 |
| 5 | Digital ammeter | (0–200) mA | 1 |
| 6 | Digital voltmeter | (0–20) V DC | 1 |
| 7 | Decade resistance box (load RL) | — | 1 |
| 8 | Connecting wires | — | As required |
| 9 | Simulation software | Proteus Design Suite | 1 |

## THEORY

A Zener diode is a heavily doped p-n junction diode, specially made to operate in the breakdown region. When reverse biased beyond a particular voltage, called the Zener breakdown voltage (Vz), it starts conducting heavily. Once it conducts, it maintains an almost constant voltage across its terminals whatever the current through it, i.e. it has a very low dynamic resistance. A series resistor Rs is connected to limit the current, since a high current can permanently damage the device.

In a Zener voltage regulator, the Zener diode is connected in reverse bias in parallel with the load, and the series resistor Rs is connected between the supply and the load. Any change in input voltage or load current changes the Zener current, while the output voltage across the load stays nearly constant at Vz.

**Line regulation:** the ability of the regulator to keep the output voltage constant when the input voltage varies, with the load kept constant.

**Load regulation:** the ability of the regulator to keep the output voltage constant when the load resistance (load current) varies, with the input voltage kept constant.

## PRECAUTIONS

1. While doing the experiment, do not exceed the ratings of the Zener diode; this may damage the diode.
2. Connect the voltmeter and ammeter in correct polarities as shown in the circuit diagram.
3. Do not switch ON the power supply unless the circuit connections have been checked as per the circuit diagram.

## PROCEDURE

### A. Line regulation

1. Connections are made as per the line regulation circuit diagram, with a fixed load resistance RL.
2. Vary the regulated power supply (input) voltage Vin in steps.
3. For each input voltage, note the output voltage Vo across the load and tabulate the readings.
4. Plot a graph of input voltage Vin (x-axis) versus output voltage Vo (y-axis).

### B. Load regulation

1. Connections are made as per the load regulation circuit diagram.
2. Set the input voltage Vin to a constant value above the Zener voltage.
3. Note the no-load output voltage VNL with the load disconnected.
4. Connect the load and vary the load resistance RL in steps; note the output voltage Vo for each value and tabulate the readings.
5. Plot a graph of load resistance RL (x-axis) versus output voltage Vo (y-axis).

## CIRCUIT DIAGRAM

### A. Line regulation

<img width="1177" height="617" alt="Screenshot 2026-11-25 222519" src="https://github.com/user-attachments/assets/cd03f9e4-bc76-4bb8-b0df-9bbb56cfe22e" />


### B. Load regulation

<img width="1085" height="575" alt="Screenshot 2026-11-25 223254" src="https://github.com/user-attachments/assets/875553a0-9524-4853-b499-9ad1cd14ea44" />


## SIMULATION USING PROTEUS

Build the Zener regulator circuit in Proteus using the 1N4735A, the series resistor and the load. Vary the input voltage (line regulation) and the load resistance (load regulation), and paste screenshots showing the meter readings.

### A. Line regulation – simulation

*[ Paste the Proteus line regulation simulation screenshot here ]*

**Figure 3:** Proteus simulation – line regulation

### B. Load regulation – simulation

*[ Paste the Proteus load regulation simulation screenshot here ]*

**Figure 4:** Proteus simulation – load regulation

## TABULATION
### A.Line Regulation Tabulation.
<img width="997" height="707" alt="Screenshot 2026-11-25 234926" src="https://github.com/user-attachments/assets/7231e114-c35e-46ab-8533-3b93a40ea5a6" />


### B.Load Regulation Tabulation

<img width="855" height="697" alt="Screenshot 2026-11-25 234912" src="https://github.com/user-attachments/assets/94344d49-c2d2-405b-8c44-558bea53907c" />




## FORMULAE

- **% Line regulation = (ΔVo / ΔVin) × 100**
- **% Load regulation = (VNL − VFL) / VFL × 100**
- **Series resistance Rs = (Vin − Vz) / (Iz + IL)**

ΔVo – change in output voltage; ΔVin – change in input voltage; VNL – no-load output voltage; VFL – full-load output voltage; Vz – Zener voltage; Iz – Zener current; IL – load current.

## MODEL GRAPH

### A. Line regulation (Vin vs Vo)

<img width="1386" height="700" alt="Screenshot 2026-11-25 234950" src="https://github.com/user-attachments/assets/2e24327c-afa4-47b8-b2ea-3078160550dd" />


### B. Load regulation (RL vs Vo)
<img width="1147" height="696" alt="Screenshot 2026-11-25 234940" src="https://github.com/user-attachments/assets/7d5c9f62-ce83-42f3-8b93-2cc8f110923d" />


## RESULT

Thus, the Zener diode was used as a voltage regulator, and its line regulation and load regulation characteristics were obtained.
