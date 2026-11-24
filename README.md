# 💼 EXPENOMICS — Global Project Cost Estimation & Expense Tracker

**EXPENOMICS** is an interactive, zero-dependency, client-side web application built for software agencies, freelancers, consultants, and project managers worldwide to estimate project budgets, model team resource costs, track categorized expenses, apply multi-regional tax rules, and generate executive PDF quotations.

---

## ✨ Key Features

* **🌍 Global Country, Currency & Tax Mapping:** Built-in dataset supporting **200+ countries** with automatic ISO currency formatting (`Intl.NumberFormat`), phone country codes, and regional tax presets.
* **🇮🇳 Automated India GST Engine:** Dynamically detects intra-state vs. inter-state supply to split GST into **CGST (9%) + SGST (9%)** or **IGST (18%)**.
* **🔐 Client-Side Security:** User registration and session authentication powered by the **Web Crypto API (`SHA-256`)** with real-time password complexity enforcement.
* **👥 Team & Resource Costing:** Allocate Project Manager fees and manage dynamic team rosters across seniority tiers (*Junior, Mid, Senior, Lead*) with automated hourly and fixed-fee calculations.
* **📊 Categorized Expense Ledger:** Track non-labor project expenditures across *Development, Marketing, and Operations* with real-time *Paid / Pending* status flags.
* **🛡️ Real-Time Input Sanitization:** Regex-based live input filtering for alphabetic names, numeric phone numbers, and 2-decimal monetary values.
* **📄 Multi-Archetype PDF Reports:** Instant browser print-to-PDF generation formatted for A4 paper with 4 specialized report views (*Detailed, Summary, Client Proposal, and Internal Audit*).
* **🎨 Modern Tactile 3D UI:** Pure CSS 3D rotating showcase cube, tactile 3D push buttons, responsive sidebar navigation, and instant **Light / Dark Mode** toggle.
* **🔒 100% Offline & Private:** Runs entirely in the browser using `sessionStorage` with zero external servers, databases, or third-party dependencies.

---

## 🛠️ Tech Stack

* **Structure:** HTML5 (Semantic Forms, Tables, Print Layouts)
* **Styling & Animations:** CSS3 (Custom Properties/Variables, Grid/Flexbox, 3D Transforms, `@media print`)
* **Logic & Browser APIs:** Vanilla JavaScript (ES6+), Web Crypto API (`crypto.subtle`), Web Storage API (`sessionStorage`), `Intl.NumberFormat`

---

## 🚀 How to Run Locally

Because EXPENOMICS follows a zero-dependency architecture, no build tools, servers, or package installations are required:

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/](https://github.com/)<your-username>/Expenomics.git
