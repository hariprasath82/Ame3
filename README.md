# exp_5_study_and_characterization_of_h_plane_tee

# Experiment 5 — Study and Characterization of H-Plane Tee

---

## Aim

To study and measure the characteristics of an H-plane tee.

## Apparatus Used

Klystron power supply, klystron mount with tube, isolator, variable attenuator, frequency meter, slotted line section, H-plane tee, detector mount / crystal detector, matched terminations, VSWR meter, waveguide stands.

## Experimental Setup

<img width="746" height="446" alt="image" src="https://github.com/user-attachments/assets/5cc5ccb7-2004-4a24-8e14-044ebcef6cad" />

---

## Theory

In an H-plane tee an auxiliary waveguide arm is fastened perpendicular to the **narrow wall** of the main guide. It is a three-port device in which the axis of the auxiliary (side) arm is parallel to the planes of the magnetic field of the main guide, and the coupling from the main guide to the branch guide is by means of **magnetic fields** — hence the name H-plane tee.

The perpendicular arm is generally taken as the input and the other two arms are in **shunt** with it, so the junction is also called a **shunt tee**.

Because of the symmetry of the tee, when power enters the auxiliary arm and the two main arms 1 and 2 are terminated in identical loads, the power supplied to each load is **equal and in phase**. Conversely, if two signals of equal amplitude and the same phase are fed into the two main arms, they add together in the side arm. The H-plane tee therefore acts as an **adder**.

### Summary of behaviour

| Feed point | Result |
|---|---|
| Auxiliary (H) arm | Equal split into arms 1 and 2, in phase |
| Arms 1 and 2 (equal, in phase) | Signals add at the H-arm |
| Function | Adder, shunt tee |

---

## Procedure

1. Set up the microwave bench: klystron power supply → klystron mount → isolator → variable attenuator → frequency meter → slotted section → component under test (H-plane tee) → detector mount → VSWR meter.
2. Keep the control knobs of the klystron power supply at their initial settings (mode switch: AM; beam voltage knob: fully anti-clockwise; repeller voltage knob: fully clockwise; meter switch: beam current) and switch on the supply, the VSWR meter and the cooling fan.
3. Energise the klystron for maximum output at the desired frequency by adjusting the beam and repeller voltages; measure the operating frequency with the frequency meter and then detune it.
4. **Reference reading:** without the H-plane tee in the line, set the variable attenuator to obtain a convenient full-scale reference reading on the VSWR meter. Note the attenuator setting **A₁** dB.
5. **Insert the component:** connect the H-plane tee in the line, feeding the arm under test and terminating the remaining arms in matched loads.
6. Reduce the attenuation until the VSWR meter reads the same reference value. Note the attenuator setting **A₂** dB. The difference (A₁ − A₂) dB gives the coupling/isolation for that pair of ports.
7. **Power division:** feed the H-arm, terminate one collinear arm in a matched load and measure the power at the other collinear arm; repeat with the arms interchanged. The measured coupling should be about **3 dB** for each collinear arm.
8. **Isolation:** feed the H-arm and measure the power coupled to the isolated port, with all other ports match-terminated.
9. **VSWR of each port:** feed the port under test, terminate the remaining ports in matched loads, and measure the VSWR using the slotted line.
10. Repeat the measurements for each of the three ports.

---

## Observation

The characteristics of the H-plane tee were studied by measuring the power division, coupling, isolation and VSWR of the three ports.

### Observation Table

| S.No. | Measurement | Input Port | Output Port | Coupling / Isolation (dB) |
|---:|---|---|---|---:|
| 1 | Power division | H-arm | Arm 1 | 3.1 |
| 2 | Power division | H-arm | Arm 2 | 3.0 |
| 3 | Coupling | Arm 1 | H-arm | 3.2 |
| 4 | Coupling | Arm 2 | H-arm | 3.1 |
| 5 | Isolation | Arm 1 | Arm 2 | 31.5 |

### VSWR Observation

| S.No. | Port | VSWR |
|---:|---|---:|
| 1 | Arm 1 | 1.30 |
| 2 | Arm 2 | 1.28 |
| 3 | H-arm | 1.40 |

### Calculation

The coupling is calculated using:

$$
C = A_1 - A_2
$$

For Arm 1:

$$
C_1 = 3.1\text{ dB}
$$

For Arm 2:

$$
C_2 = 3.0\text{ dB}
$$

The average coupling is:

$$
C_{avg} = \frac{3.1+3.0}{2}
$$

$$
\boxed{C_{avg} = 3.05\text{ dB}}
$$

The measured isolation between the two collinear arms is:

$$
\boxed{I = 31.5\text{ dB}}
$$

### Inference

The H-plane tee divides the input power approximately equally between the two collinear arms. The coupling is approximately **3 dB** for each arm, and the signals at the two collinear arms are **equal in amplitude and in phase**.

Hence, the H-plane tee behaves as an **adder (summing junction)**.

> **Note:** The values given above are sample experimental readings. Replace them with your actual laboratory readings if required.


---

## Precautions

* Check all connections before switching on the kit.
* Keep all knobs at minimum before switching on the power supplies; the HT must be OFF while switching on the mains.
* Do not exceed a beam current of 30 mA, and keep the repeller voltage within the specified range.
* Terminate all unused ports in matched loads while taking readings.
* Do not look directly into an open waveguide

## Result

The characteristics of the H-plane tee were studied.
