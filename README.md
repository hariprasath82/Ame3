# exp_3_vi_characteristics_of_gunn_oscillator

# Experiment 3 — V–I Characteristics of Gunn Oscillator

---

## Aim

To study the I–V characteristics of a Gunn diode and the depth of modulation of a PIN diode.

## Apparatus Used

Gunn power supply, Gunn oscillator, PIN modulator, isolator, frequency meter, variable attenuator, detector mount, slotted section, VSWR meter.

## Experimental Setup

<img width="2170" height="725" alt="image" src="https://github.com/user-attachments/assets/9572ed54-7f9f-413c-b568-c08d9049d680" />

---

## Theory

The Gunn oscillator is based on the **negative differential conductivity** effect in bulk semiconductors. The Gunn diode has two conduction bands separated by an energy gap larger than thermal agitation energies. When an electron is transferred to the satellite energy band it acquires negative differential mobility, producing the negative resistance required for oscillation.

In a Gunn oscillator the diode is placed in a resonant cavity, so the oscillation frequency is set by the cavity dimensions rather than by the diode itself.

Although a Gunn oscillator can be amplitude-modulated with the bias voltage, a separate **PIN modulator** is used in this experiment: a square-wave modulating signal is applied through the modulator onto the microwave carrier.

<img width="542" height="341" alt="image" src="https://github.com/user-attachments/assets/313e43ed-dd69-4b09-9a4f-7a7616faa805" />

---

## Procedure

1. Set up the components and equipment as shown in the figure above.
2. Initially set the variable attenuator for maximum attenuation.
3. Keep the control knobs of the Gunn power supply as follows:

   | Control | Setting |
   |---|---|
   | Meter switch | OFF |
   | Gunn bias knob | Fully anti-clockwise |
   | PIN bias knob / Mod amplifier | Mid position |
   | PIN mod frequency | Mid position |

4. Keep the control knobs of the VSWR meter as follows:

   | Control | Setting |
   |---|---|
   | Meter switch | Normal |
   | Input switch | Crystal low impedance / 200 K |
   | Range dB switch | 50 dB |
   | Gain control knob | Fully clockwise |

5. Set the micrometer of the Gunn oscillator between 5–7 mm for the required frequency of operation.
6. Switch ON the Gunn power supply, the VSWR meter and the cooling fan.
7. Keep the mode switch of the Gunn power supply at square wave / internal modulation.
8. Turn the meter knob to the voltage position and note that as the Gunn bias voltage is varied the current starts decreasing — this indicates the negative resistance characteristic of the Gunn diode. Apply a voltage that puts the device in the middle of the negative resistance region.
9. Connect the detector output to the SWR meter.
10. Adjust the square-wave modulation frequency to approximately 1 kHz.
11. Change the meter range if no deflection is observed.
12. Keep the slotted-line probe at the position where maximum deflection is observed on the meter.
13. Adjust the attenuator setting and the gain control knob of the VSWR meter and tune the detector plunger so the pointer indicates VSWR = 1.
14. Move the detector probe along the slotted line and note the position where the pointer reaches the extreme left — the first minimum. To locate the minimum exactly, note the positions of equal-response points on either side; their midpoint gives the position of the minimum. Note the next minimum position the same way.
15. Repeat the above procedure for different micrometer settings.

### Depth of Modulation of the PIN Diode

1. Apply the Gunn bias voltage slowly until the panel meter of the Gunn power supply reads 8 V.
2. Tune the PIN modulator bias voltage and frequency knobs for maximum output on the oscilloscope.
3. Align the bottom of the square wave on the oscilloscope with a reference level and note the micrometer reading of the variable attenuator.
4. Now, using the variable attenuator, align the top of the square wave with the same reference level and note the micrometer reading.
5. Connect the VSWR meter to the detector mount and note the dB reading for both micrometer settings of the variable attenuator.
6. The difference between the two dB readings gives the modulation depth of the PIN modulator.

> **Note:** After tuning the Gunn source, follow the same procedure for VSWR and impedance measurement as for the depth of modulation of the PIN modulator.

## Observation

### A. V–I Characteristics of Gunn Diode

The Gunn diode current was measured for different values of bias voltage.

| S.No. | Gunn Bias Voltage, V (V) | Gunn Current, I (mA) |
|---:|---:|---:|
| 1 | 0.0 | 0 |
| 2 | 1.0 | 4 |
| 3 | 2.0 | 9 |
| 4 | 3.0 | 15 |
| 5 | 4.0 | 22 |
| 6 | 5.0 | 28 |
| 7 | 6.0 | 31 |
| 8 | 7.0 | 29 |
| 9 | 8.0 | 26 |
| 10 | 9.0 | 24 |
| 11 | 10.0 | 22 |
| 12 | 11.0 | 23 |
| 13 | 12.0 | 25 |

The current initially increases with voltage and then decreases over a certain voltage range. This decreasing-current region represents the **negative differential resistance / negative differential conductivity region** of the Gunn diode.

### B. Depth of Modulation of PIN Diode

The modulation depth was measured by observing the change in the detected microwave power for the maximum and minimum levels of the modulated waveform.

| S.No. | Condition | Attenuator Reading (dB) |
|---:|---|---:|
| 1 | Minimum level | 18.0 |
| 2 | Maximum level | 8.0 |

---

## Calculation

### 1. Negative Differential Resistance Region

The differential resistance is given by:

$$
R_d = \frac{\Delta V}{\Delta I}
$$

Consider two points in the negative-resistance region:

$$
V_1 = 6.0\text{ V}, \qquad I_1 = 31\text{ mA}
$$

$$
V_2 = 10.0\text{ V}, \qquad I_2 = 22\text{ mA}
$$

Therefore,

$$
R_d = \frac{V_2-V_1}{I_2-I_1}
$$

$$
R_d = \frac{10-6}{22-31}
$$

$$
R_d = \frac{4}{-9}
$$

$$
\boxed{R_d \approx -0.44\text{ k}\Omega}
$$

The negative value confirms the negative differential resistance region of the Gunn diode.

### 2. Depth of Modulation of PIN Diode

The modulation depth in dB is calculated from the difference between the two measured power levels:

$$
M_{dB} = P_{\text{maximum}} - P_{\text{minimum}}
$$

Using the observed readings:

$$
M_{dB} = 18.0 - 8.0
$$

$$
\boxed{M_{dB} = 10\text{ dB}}
$$

Thus, the measured depth of modulation of the PIN modulator is approximately **10 dB**.

---




## Precautions

* Check the connections before switching on the kit.
* Make all connections properly.
* Take the observations carefully.

## Conclusion

The V–I characteristics of the Gunn diode were studied experimentally. The current initially increased with the applied bias voltage and then decreased over a certain voltage range, confirming the **negative differential resistance characteristic** required for Gunn oscillation.

The depth of modulation of the PIN diode was also measured using the microwave bench setup. For the sample readings, the modulation depth was found to be approximately **10 dB**.

Hence, the **V–I characteristics of the Gunn oscillator and the depth of modulation of the PIN diode were successfully studied**.


