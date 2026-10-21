# Rama Wijaya — Executive Portfolio & Projects Archive

[![Live Portfolio](https://img.shields.io/badge/Live_Site-wijaya--rama.github.io-2563EB?style=for-the-badge&logo=githubpages&logoColor=white)](https://wijaya-rama.github.io)
[![Full Archive](https://img.shields.io/badge/Project_Archive-archive.html-0284C7?style=for-the-badge&logo=googlechrome&logoColor=white)](https://wijaya-rama.github.io/archive.html)
[![Tableau Public](https://img.shields.io/badge/Tableau_Public-Portfolio-E97627?style=for-the-badge&logo=tableau&logoColor=white)](https://public.tableau.com/app/profile/rama.wijaya8072/vizzes)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Rama_Wijaya-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ramawijaya1)
[![License: MIT](https://img.shields.io/badge/License-MIT-10B981?style=for-the-badge)](LICENSE)

> Executive personal portfolio and comprehensive data analytics archive of **Rama Wijaya** — Data Analyst specializing in Production Planning & Inventory Control (PPIC), Agribusiness Operations, Cloud Warehouses (BigQuery, Azure PostgreSQL), and Business Intelligence (Tableau, Power BI, Looker Studio).

---

## 🏛️ Design System & Architectural Highlights

This repository hosts a production-grade personal portfolio built with modern Apple & Google light-themed aesthetics and layout principles inspired by [Brittany Chiang](https://brittanychiang.com):

- **Dual-Pane Sticky Layout (Desktop)**: A fixed 40% left hero rail containing credentials, contact hubs, and a real-time reactive scrollspy navigation table-of-contents, paired with an independently scrollable 60% right rail featuring rich interactive project showcases.
- **Glassmorphism Mobile Navigation Dock**: A sticky bottom floating navigation capsule on mobile viewports (`< 1024px`) providing one-tap access to About, Projects, Experience, and Contact sections with zero horizontal drift or layout shifts.
- **Micro-Motions & Interactive Polish**:
  - Top 2.5px reading progress indicator mapped to real-time scroll depth.
  - Interactive cursor spotlight tracking on desktop.
  - Project mockup frames with hover lift and soft tech-blue glow.
  - Reactive macOS window mockups linking directly to live deployment stories.
- **Full Project Archive (`archive.html`)**: A data table and responsive card view listing all operational models, pipelines, and exploratory research across Rama's career with dynamic category filtering.
- **Zero-Dependency Static Delivery**: Built with semantic HTML5, utility-first Tailwind CSS (via CDN), and lightweight vanilla JavaScript. No node_modules, build steps, or bundle overhead — deploys instantly to GitHub Pages.

---

## 🚀 Flagship Operational Projects

| Project | Domain & Scale | Core Problem & Technical Focus | Live Demo |
| :--- | :--- | :--- | :--- |
| **Commercial Beef Feedlot Operations & Closeout Economics** | Agribusiness / Livestock<br/>`15,000 Head` • `90 Lots` | Closeout margin dynamics, carcass tonnage vs. quality grid arbitrage, winter thermal drag mitigation, and 30-day BRD treatment window economics. | [Live Story ↗](https://wijaya-rama.github.io/portfolio-feedlot-management/) |
| **Commercial Broiler Operations Hub & Yield Audit** | Poultry Integration<br/>`72 Flocks` • `1.78M Birds` | Closed House vs. Open House divergence, heat stress feed dissipation vs. growth, late-mortality timing, and European Performance Index (EPEF / IP). | [Live Story ↗](https://wijaya-rama.github.io/portfolio-smart-broiler/) |
| **Retail Workforce Productivity & Attrition Analysis** | People Analytics<br/>`2,000 Employees` • `24 Stores` | Labor cost optimization, scheduling efficiency across store formats, 9-Box talent grid attrition, and flight risk modeling. | [Live Story ↗](https://wijaya-rama.github.io/portfolio-retail-workforce/) |
| **Commercial Layer Operations & Egg Market Intelligence** | Commercial Layer<br/>`199,410 Pullets` • `60-Wk Cycle` | Hen-Day egg-laying persistence curves, wholesale egg price sensitivity, feed conversion efficiency (FCR), and tropical heat stress defect mitigation. | [Live Story ↗](https://wijaya-rama.github.io/portfolio-layer-poultry/) |

👉 *Explore the complete collection of 12+ projects, cloud architectures, and ML models on the [Full Project Archive](https://wijaya-rama.github.io/archive.html).*

---

## 🛠️ Ground-Level Problem Solving

### 1. Zero-to-One Cloud Warehouse & ERP Integration (PT Indo Prima Beef)
* **Challenge**: Livestock counts, feeding rations, and inventory receipts were fragmented across desktop spreadsheets without centralized validation.
* **Solution**: Standardized input templates, engineered automated ETL ingestion pipelines using Google Apps Script into **Google BigQuery**, and deployed automated daily **Looker Studio** executive monitoring alongside **Tally ERP**. Promoted twice within 12 months to Head of PPIC.

### 2. High-Volume Cloud Architecture & Enterprise D365 (PT Indonesia Livestock Operations)
* **Challenge**: Rapidly accumulating operational logs exceeded local spreadsheet limits and frequently crashed office hardware.
* **Solution**: Designed and deployed a cloud **Azure PostgreSQL** database to decouple operational data storage from front-end analysis. Connected clean **Excel** views and **Power BI** dashboards via **Power Automate** flows, while auditing opening balances during enterprise **Microsoft Dynamics 365** rollout.

### 3. Investment Due Diligence & Discrepancy Audits (AAMIG Consulting)
* Conducted structured transaction auditing and exploratory data checks using **Python (Pandas)** and **SQL** to support strategic capital allocation decisions.

---

## 📂 Repository Structure

```text
rama.wijaya.github.io/
├── index.html          # Main portfolio: dual-pane desktop + mobile floating dock
├── archive.html        # Comprehensive project archive with interactive category filtering
├── LICENSE             # MIT License
├── README.md           # Professional repository documentation
├── .gitignore          # Clean Git ignore rules (OS files, IDE configs, local archives)
└── images/             # Authentic project preview assets & photography
    ├── feedlot_thumb.png
    ├── broiler_thumb.png
    ├── retail_thumb.png
    ├── skincare_thumb.png
    ├── feedlot_full.png
    ├── broiler_full.png
    ├── retail_full.png
    ├── skincare_full.png
    └── rama-portrait.png
```

---

## 💻 Local Development & Preview

Because this project runs without build tools or external package managers, previewing it locally is as simple as running a lightweight static file server:

```bash
# Clone the repository
git clone https://github.com/wijaya-rama/rama.wijaya.github.io.git
cd rama.wijaya.github.io

# Start a local HTTP server using Python
python -m http.server 8000

# Open in browser:
# http://localhost:8000/          -> Main Portfolio
# http://localhost:8000/archive.html  -> Project Archive
```

---

## 📬 Contact & Channels

- **Website**: [wijaya-rama.github.io](https://wijaya-rama.github.io)
- **LinkedIn**: [linkedin.com/in/ramawijaya1](https://www.linkedin.com/in/ramawijaya1)
- **Tableau Public**: [Rama Wijaya's Visualizations](https://public.tableau.com/app/profile/rama.wijaya8072/vizzes)
- **Email**: [ramawijaya.business@gmail.com](mailto:ramawijaya.business@gmail.com)
- **WhatsApp**: [+62 857 8303 8095](https://wa.me/6285783038095)
- **Location**: Jepara, Central Java, Indonesia (Open to Remote & Relocation)

---

&copy; 2026 Rama Wijaya. Released under the [MIT License](LICENSE).
