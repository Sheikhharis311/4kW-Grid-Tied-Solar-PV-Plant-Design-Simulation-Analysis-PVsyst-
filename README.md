# ⚡ 4kW Grid-Tied Solar PV Plant – Design, Simulation & Analysis (PVsyst)

📘 **Internship Simulation Project**  
👨‍🎓 **Submitted by:** Haris Sheikh  
🎓 **Discipline:** Electrical Engineering Student  
🏢 **Internship Organization:** Solar Complete Firm  
📍 **Project Simulation Location:** Krishna Nagar, Kanpur (Software Modeled)  
🏠 **Originally From:** Nagpur, Maharashtra  
🗓️ **Internship Duration:** 1 Month  
🧰 **Tools Used:** PVsyst, Manual Calculations, MNRE Guidelines

---

## 📌 Project Overview

This is a simulation-based solar PV system design project completed during my internship. The project involved modeling a **4kW residential grid-tied solar plant** using **PVsyst software**, along with manual electrical calculations. The aim was to understand the core concepts of **solar PV system design**, energy yield simulation, loss analysis, net metering, and technical documentation as per MNRE standards.

> ⚠️ **Note:** This project was simulated in software only and not physically installed on-site. However, all design steps reflect real-world engineering practices.

---

## ⚙️ System Specifications

| Component              | Specification                                   |
|------------------------|--------------------------------------------------|
| Solar Panel            | Bifacial 450 Wp, Mono PERC, 144 half-cut cells |
| Panel Brand            | LONGi Solar (Model: LR4-72 HBD 450 M G2)       |
| Total Panels           | 8                                               |
| Simulated System Size  | 3.6 kW (STC)                                    |
| Inverter               | 5.5 kVA, 1Ø, Grid-Tied (Model: EHC-S55MP3B-PNJ) |
| Tilt Angle             | 15°                                             |
| Azimuth Angle          | 0° (South-facing)                               |

> 🔄 540 Wp panels were unavailable in PVsyst, so equivalent 450 Wp panels were used as simulation proxy.

---

## 📈 Task 1: PVsyst Simulation

### 🎯 Objective:
Simulate system performance and predict annual generation.

**Simulation Inputs:**
- Location: Krishna Nagar, Kanpur (software input)
- Tilt: 15°, Azimuth: 0°
- Inverter: 5.5 kVA Havells
- Capacity: 3.6 kW

**🔍 Simulation Results:**
- 🔋 Annual Energy Output: `5.31 MWh/year`
- ⚙️ Performance Ratio: `75.57%`
- 🔧 Specific Yield: `1633 kWh/kWp/year`
- 🧹 Soiling Loss: `2.00%`

📎 Full simulation data available in `PVsyst_Report.pdf`

---

## 📐 Task 2: Cable Sizing Calculations

- ✅ Calculated manually using IS 732 standard
- ✅ Considered real-world voltage drop <1%

**Results:**
- **DC Side:** 4 mm² copper cable  
- **AC Side:** 6 mm² copper cable

---

## 📘 Task 3: Technical Specifications (Based on Standards)

| Component  | Details |
|------------|---------|
| Panels     | LONGi 450 Wp, bifacial, 21.3% efficiency, 25-year warranty |
| Inverter   | MPPT-enabled, 5-year warranty, anti-islanding compliant |
| Cables     | UV-resistant copper (DC: 4 mm², AC: 6 mm²) |
| Earthing   | 3-pipe earthings + lightning arrestor (IS 3043 standard) |
| Structure  | Galvanized MS, fixed tilt |

✅ Specifications aligned with MNRE & CEA technical guidelines.

---

## 📄 Task 4: Net Metering Study

This project included a simulation of the **net metering policy** applicable in Uttar Pradesh:

- ✅ DISCOM: UPPCL / KESA
- ✅ Up to 10kW allowed for residential LT connection
- ✅ Bi-directional energy meter used
- ✅ Billing simulation example included

---

## 📂 Task 5: Documentation Checklist

| Document                          | Status |
|----------------------------------|--------|
| PVsyst Simulation Report         | ✅     |
| Cable Sizing Sheet               | ✅     |
| Technical Datasheets             | ✅     |
| Net Metering Example Sheet       | ✅     |
| System Layout (SLD)              | ✅     |

---

## ✅ Conclusion

Although this system was **not installed in real-world**, it was **designed and analyzed in complete technical depth** using industry-grade tools and standards. This internship project helped me build practical confidence in solar system design, especially using PVsyst and engineering calculation methods.

---

## 🙋‍♂️ About Me

I am **Haris Sheikh**, a passionate electrical engineering student from **Nagpur**, interested in **renewable energy systems**, smart power solutions, and simulation-based design.

---

## 📄 License

This project is shared under the [MIT License](LICENSE) for learning and reference purposes only.
