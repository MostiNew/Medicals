# MEDFIT BRAVO · Prevention, Screening, Reha AI

**MEDFIT BRAVO** is a mobile‑first, clinical decision‑support tool that integrates point‑of‑care lab results and functional scores into the **WHO‑ICF framework**. It provides objective risk insights, tracks patient progress, and generates branded PDF reports for seamless documentation and multidisciplinary team communication.

---

## 🚀 Live Demo

👉 **[https://mostinew.github.io/Medicals/](https://mostinew.github.io/Medicals/)**

---

## ✨ Key Features

| Feature | Description |
|---------|-------------|
| **ICF‑Aligned** | Maps all inputs to WHO‑ICF categories (b280, b410, b420, b430, b440, b530, b540, b610, d230, d450, d920) |
| **Point‑of‑Care Ready** | Supports lab tests available as POCT: Glucose, HbA1c, Lipids, Creatinine/eGFR, Hb, Albumin, CRP, EF, BNP, FEV1/FVC |
| **Functionality Index** | Composite score (0–100) based on 9 objective markers – higher is better |
| **Risk Insights** | Evidence‑based, WHO‑aligned recommendations generated automatically |
| **Progress Tracking** | Trend chart and historical log to monitor patient outcomes over time |
| **Branded PDF Report** | One‑click generation of a professional report with your logo – ready for MDT meetings or patient records |
| **Multi‑Profile** | Acute Rehab, Preventive, and Palliative care – each with tailored fields |
| **Multi‑Language** | EN / DE / ES / AR – switch with one click |
| **Data Privacy** | All data stored locally in the browser – no cloud upload, no server |

---

## 🩺 Supported Lab Tests

| Category | ICF Code | Test | POCT Availability |
|----------|----------|------|-------------------|
| Pain | b280 | Pain (NRS 0‑10) | ✅ Subjective |
| Mobility | d450 | Mobility (0‑10) | ✅ Subjective |
| Fatigue | b130 | Fatigue (0‑10) | ✅ Subjective |
| Function | d230 | Global Function (0‑10) | ✅ Subjective |
| Cardiac | b410 | Heart Rate, SBP/DBP, EF, BNP | ✅ Clinic POCT |
| Haematological | b430 | Haemoglobin (Hb) | ✅ Clinic POCT |
| Respiration | b440 | FEV1, FVC | ✅ Home POCT |
| Nutrition | b530 | Albumin, BMI | ✅ Clinic POCT |
| Metabolism | b540 | Glucose, HbA1c, Lipids | ✅ Home POCT |
| Renal | b610 | Creatinine, eGFR | ✅ Clinic POCT |
| Inflammation | — | CRP | ✅ Clinic POCT |

---

## 🧠 How It Works

1. **Enter patient data & labs** – Fill in demographics, functional scores, and lab results.
2. **Save encounter** – Data is stored locally in your browser.
3. **View ICF recommendations & trends** – See risk insights, ICF domains, and a trend chart.
4. **Generate PDF Report** – One‑click download of a branded, shareable report.

---

## 📱 Mobile‑First Design

- Fully responsive – works on desktop, tablet, and mobile
- Scrollable form on small screens
- Touch‑friendly buttons and inputs
- Optimised for in‑clinic and home use

---

## 🔒 Data Privacy

- All data is stored in `localStorage` – **never** sent to any server
- No cookies, no tracking, no analytics
- Your data stays on your device – you control it

---

## 🛠️ Tech Stack

| Library | Purpose |
|---------|---------|
| Chart.js | Trend chart visualisation |
| html2pdf.js | PDF report generation |
| Font Awesome | Icons |

---

## 🚀 Deployment

To deploy your own instance:

1. **Clone or download** this `index.html` file.
2. **Upload to GitHub Pages**, Netlify, or any static hosting service.
3. **Open in a browser** – no build step, no dependencies to install.

### GitHub Pages Quick Start

1. Create a new public repository on GitHub.
2. Upload this `index.html` file.
3. Go to Settings → Pages → select `main` branch.
4. Your site will be live at `https://your-username.github.io/repo-name/`.

---

## 📄 PDF Report Preview

The PDF report includes:
- **Header** – Your "V" + "IRTUAL SOLUTIONS" logo (clickable to `virtualcaresolution.de`)
- **Patient Summary** – Gender, Age, BMI, Report Date, Profile
- **Current Check‑in** – All functional scores and lab results in a clean grid
- **Functionality Index** – Single score (0–100) with risk badge
- **ICF Domains** – Mapped categories with status
- **Care Tips** – Evidence‑based, WHO‑aligned recommendations
- **Trend Summary** – Last 5 encounters in a compact table
- **Footer** – "Powered by MEDFIT BRAVO · virtualcaresolution.de"

---

## 🏷️ About the "Care Aid" Positioning

In the German healthcare context, this tool is positioned as a **Pflegehilfsmittel (care aid)** – a supportive tool for home care, not a medical device.

**Key attributes:**
- Supports independence and self‑management at home
- Improves communication and coordination with care teams
- Aligns with WHO and ICF standards for functional assessment
- Does **not** make medical diagnoses or treatment recommendations

---

## 📞 Support & Contact

- **Brand**: virtualcaresolution.de
- **Footer**: Your IP is displayed for transparency – it is not tracked or stored.

---

## 📝 License

This tool is provided as‑is for clinical and care‑related use. Redistribution or commercial use requires permission from the brand owner.

---

**MEDFIT BRAVO** – *Prevention, Screening, Reha AI toolkit.*
