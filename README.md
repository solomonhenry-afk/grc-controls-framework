# 🧩 GRC Controls Implementation Framework  
[![GRC Validate & Report](https://github.com/solomonhenry-afk/grc-controls-framework/actions/workflows/kri_metrics.yml/badge.svg)](https://github.com/solomonhenry-afk/grc-controls-framework/actions/workflows/kri_metrics.yml)

A professional-grade framework demonstrating how Lighthouse Technology maps **NIST CSF, ISO 27001, and COBIT** controls to technical and governance implementations.  

---

## 📊 Key Features
- Comprehensive **control-to-regulation mapping**
- Risk scoring and residual risk calculation
- Automated weekly metric updates (GitHub Action)
- Excel-based dashboards with KRI indicators

---

## 🧱 Folder Structure

grc-controls-framework/
│
├── templates/ → Excel templates & starter CSVs
├── reports/ → Generated KRI logs
├── automation/ → Python automation scripts
├── docs/ → Control implementation documentation
└── .github/workflows/ → CI/CD for metrics updates


---

## 🚀 How It Works
1. Update your Excel workbook (Control_Mapping, Risk_Assessment, KRI_Dashboard)  
2. Commit changes to `templates/`  
3. GitHub Action triggers `automation/run_metrics.py`  
4. A new entry is added to `reports/kri_metrics_log.csv`

---

## 🧠 Example Metric Log
| Date | Status | Compliance | Residual Risk |
|------|---------|-------------|---------------|
| 2025-10-03 | ✅ Metrics recalculated | 95% | 2.7 |

---

## 🏗️ Future Add-ons
- Link PowerShell scripts to real AD audit evidence  
- Connect dashboard to PowerBI for real-time visualization  
- Integrate with SIEM or Splunk for compliance monitoring  

---

## 👨‍💻 Author
**Bassey Solomon Henry**  
Cybersecurity & GRC Engineer | Cloud Security | DevSecOps  
🔗 [LinkedIn](https://www.linkedin.com/in/bassey-solomon-henry)  
🌐 [Portfolio](https://lighthouse-technology.vercel.app)

