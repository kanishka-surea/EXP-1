## EXPERIMENT NO. 1 – VERIFICATION OF KIRCHHOFF'S LAWS

| **Name:** | Kanishka S | **Reg. No.:** | 26017655 |
|---|---|---|---|
| **Date:** |25/11/2026 | **Batch / Section:** | 26ODJ102 |

---

## AIM

a. To verify Kirchhoff's Voltage Law (KVL) for the given circuit.

b. To verify Kirchhoff's Current Law (KCL) for the given circuit.

## APPARATUS REQUIRED

| S. No. | Component | Range / Rating | Quantity |
|:---:|:---:|:---:|:---:|
| 1 | Resistor | 1 kΩ | 3 |
| 2 | DC Voltmeter | 0–30 V | 3 |
| 3 | DC Ammeter | 0–0.2 A | 3 |
| 4 | Breadboard | — | 1 |
| 5 | Regulated Power Supply (RPS) | 0–30 V | 1 |
| 6 | Connecting wires | As required | As required |
| 7 | Simulation software | Proteus Design Suite | 1 |

## THEORY

**Kirchhoff's Voltage Law (KVL):** The algebraic sum of all voltage rises and voltage drops around any closed loop in an electrical circuit is zero.

**Kirchhoff's Current Law (KCL):** The algebraic sum of currents at any node is zero. In other words, the total current entering a node is equal to the total current leaving the node.

## PROCEDURE

### A. Verification of KVL

1. Connect the circuit as shown in the KVL circuit diagram.
2. Ensure that the RPS output is set to zero volts before switching it on.
3. Check that all meters are correctly connected and set to their zero positions.
4. Switch on the RPS and gradually set the required input voltage within the specified range.
5. Measure and record the voltage across each resistor using the voltmeters.
6. Repeat the measurements for different input-voltage values and tabulate the readings.

### B. Verification of KCL

7. Connect the circuit as shown in the KCL circuit diagram.
8. Ensure that the RPS output is set to zero volts before switching it on.
9. Check that all meters are correctly connected and set to their zero positions.
10. Switch on the RPS and gradually set the required input voltage within the specified range.
11. Measure and record the current in each branch using the ammeters.
12. Repeat the measurements for different input-voltage values and tabulate the readings.

## CIRCUIT DIAGRAMS

### A. KVL circuit diagram


<img width="787" height="511" alt="WhatsApp Image 2026-11-24 at 13 38 55" src="https://github.com/user-attachments/assets/803d6a39-bf20-45c0-8953-2a8335f035f9" />

**Figure 1:** KVL verification circuit

### B. KCL circuit diagram


<img width="689" height="627" alt="WhatsApp Image 2026-11-24 at 13 52 51" src="https://github.com/user-attachments/assets/462bfcb7-a46b-4416-8c1f-fb53c866e326" />

**Figure 2:** KCL verification circuit

## SIMULATION USING PROTEUS

Build the KVL and KCL circuits in Proteus using the same resistor values and supply voltage as the hardware circuit. Place DC voltmeters and DC ammeters from the Virtual Instruments mode, run the simulation, and paste a screenshot showing the meter readings for each circuit.

### A. KVL simulation


<img width="1080" height="545" alt="WhatsApp Image 2026-11-24 at 13 54 13" src="https://github.com/user-attachments/assets/5464ec7d-631e-4a71-a7ab-db504609b14f" />

**Figure 3:** Proteus simulation of KVL circuit

### B. KCL simulation


<img width="1080" height="804" alt="WhatsApp Image 2026-11-24 at 13 55 07" src="https://github.com/user-attachments/assets/4f48e33c-555e-485d-9a40-59bce7ea906f" />

**Figure 4:** Proteus simulation of KCL circuit

## OBSERVATION AND TABULATION

### A. KVL – Voltage measurements

| S. No. | Supply voltage Vs (V) | VR1 (V) | VR2 (V) | VR3 (V) | VR1 + VR2 + VR3 (V) |
|:---:|:---:|:---:|:---:|:---:|:---:|
| Theoritical | 100  | 1668V  | 27.8V  | 55.6V | 100.05|
| Practical | 100| 16.7V | 27.8V|55.6V |100.1 |

### B. KCL – Current measurements

| S. No. | I1 (A) | I2 (A) | I3 (A) | Va |
|:---:|:---:|:---:|:---:|:---:|
| Theoritical |  -1.48A | 1.85A |0.56A  | 52.63V | 
| Practical | 1.58A | 1.05A | 0.53A |52.6V | 

## CALCULATIONS

### A. KVL

According to KVL, **Vs = VR1 + VR2 + VR3**.

Substitute the observed values and verify that the algebraic sum of the voltage drops is approximately equal to the supply voltage.


<img width="1593" height="1600" alt="WhatsApp Image 2026-11-24 at 14 03 37" src="https://github.com/user-attachments/assets/f9a5b98f-0da2-4109-b625-caa8b122e783" />

**Figure 5:** KVL calculation

### B. KCL

According to KCL, **It = I1 + I2 + I3**.

Substitute the observed values and verify that the total current entering the node is approximately equal to the sum of the branch currents.

*[ Paste the KCL calculation screenshot here ]*
<img width="1470" height="1600" alt="WhatsApp Image 2026-11-24 at 14 03 54" src="https://github.com/user-attachments/assets/37e7a786-0a10-46a7-9e72-1cd6ea535b0d" />

**Figure 6:** KCL calculation

## RESULT

Thus, Kirchhoff's Voltage Law (KVL) and Kirchhoff's Current Law (KCL) were verified experimentally and through Proteus simulation for the given circuits.
