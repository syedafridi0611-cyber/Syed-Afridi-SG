# 🎯 Design of CMOS LNA for 2.4 GHz Radio Receiver

**A High-Performance Low-Noise Amplifier designed and simulated in Cadence Virtuoso for modern wireless applications.**

## 📋 Project Overview

This project presents the complete design and simulation of a **CMOS Low-Noise Amplifier (LNA)** operating at **2.4 GHz**, targeted for Wi-Fi, Bluetooth, and other 2.4 GHz ISM band radio receivers. 

The design achieves high gain (>15 dB), low noise figure (<2 dB), and optimized power consumption using a **cascode topology with inductive source degeneration** in 180nm CMOS technology. All simulations were performed using **Cadence Virtuoso** and **SpectreRF**.

**Key Achievements:**
- Gain: >15 dB
- Noise Figure: <2 dB
- Optimized for power efficiency and linearity
- Fully validated through S-parameter, noise, and stability analysis

---

## 🛠️ Tech Stack

- **EDA Tool:** Cadence Virtuoso (Schematic Editor, ADE L/XL)
- **Simulator:** SpectreRF
- **Technology Node:** 180nm CMOS
- **Analysis Types:** S-Parameter, Noise Figure, Harmonic Balance, Stability (K-factor)
- **Design Topology:** Cascode LNA with Inductive Degeneration
- **Supporting Tools:** MATLAB (post-processing), Excel (performance tracking)

---

## 📂 Core Project Components

- **Literature Review** – Comprehensive study of state-of-the-art CMOS LNAs (2023–2024 IEEE papers)
- **System Architecture** – Cascode topology with input/output matching networks
- **Schematic Design** – Transistor sizing and passive component optimization
- **Simulation & Validation** – DC, AC, S-parameter, NF, IIP3, and stability analysis
- **Layout Readiness** – Design prepared for physical implementation and parasitic extraction
- **Documentation** – Full project report and presentation

---

## 📊 What Was Done

1. **Problem Identification & Literature Survey** – Analyzed challenges in CMOS LNA design at RF frequencies
2. **Topology Selection** – Chose cascode with inductive degeneration for best noise-gain trade-off
3. **Component Sizing & Optimization** – Iteratively tuned W/L ratios, inductors, and capacitors
4. **Simulation & Validation** – Performed extensive simulations in Cadence Virtuoso
5. **Performance Analysis** – Achieved target specifications for gain, noise figure, and stability
6. **Documentation** – Prepared complete project report, presentation, and results

---

## 🗺️ Roadmap

- ✅ **Phase 1:** Literature review and topology selection
- ✅ **Phase 2:** Schematic design and optimization
- ✅ **Phase 3:** Comprehensive simulation and validation
- ⏳ **Phase 4:** Physical layout and post-layout simulation (Future)
- ⏳ **Phase 5:** Tape-out and measurement (Future)

---

## 🎯 Strategy Used

- **Cascode Topology** for improved isolation and gain
- **Inductive Source Degeneration** for simultaneous noise and input matching
- **Inductive Load** for high gain at 2.4 GHz
- **Iterative Optimization** using Cadence ADE for power-noise-linearity trade-off
- **Stability Analysis** (Rollett stability factor) to ensure unconditional stability

---

## 🚀 Future Enhancements

- Post-layout simulation with parasitic extraction
- Physical layout design using Cadence Layout Editor
- Integration with full RF receiver front-end
- Variable gain control implementation
- Fabrication and real-time measurement validation
- Extension to wideband or multi-band operation

---

## 📈 Results Highlights

- **Frequency:** 2.4 GHz
- **Technology:** 180nm CMOS
- **Gain (S21):** >15 dB
- **Noise Figure:** <2 dB
- **Power Consumption:** Optimized for low-power applications
- **Stability:** Unconditionally stable (K > 1)

---

## 🏁 Conclusion

This project successfully demonstrates the design and simulation of a high-performance CMOS LNA suitable for modern 2.4 GHz wireless receivers. The design meets all target specifications and provides a strong foundation for integration into complete RF front-end systems.

The work showcases proficiency in RFIC design, analog circuit optimization, and industry-standard EDA tools — valuable skills for roles in VLSI Design, RFIC Engineering, and Semiconductor R&D.

---

## 📚 References

- IEEE TCAS-II, IEEE TMTT, IEEE Solid-State Circuits Letters & JSSC papers (2023–2024)
- Standard RF CMOS design references and Cadence documentation

---

**Syed Afridi** | Team Member  
Department of Electronics and Communication Engineering  
KIT - Kalaignar Karunanidhi Institute of Technology

---

For enquiry and suggesions, Feel free to reach out - syedafridi0611@gmai.com
