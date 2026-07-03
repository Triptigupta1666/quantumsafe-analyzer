# Quantum Safe Analyzer
Enterprise quantum-risk assessment and PQC migration framework — risk scoring, architecture design, key lifecycle management, and phased migration roadmap.

### Post-Quantum Cryptographic Risk Assessment and Migration Framework

## Overview

QuantumSafe Analyzer is a Python-based cybersecurity project that helps organizations assess their exposure to quantum computing threats and prepare for migration to Post-Quantum Cryptography (PQC).

The project simulates an enterprise environment by analyzing a cryptographic inventory, identifying vulnerable algorithms, designing a hybrid PQC architecture, implementing key management strategies, and generating a phased migration roadmap aligned with NIST recommendations.

---

## Objectives

- Identify cryptographic assets using vulnerable algorithms such as RSA and ECC.
- Assess quantum computing risks, including "Harvest Now, Decrypt Later" threats.
- Design a hybrid Post-Quantum Cryptographic architecture.
- Implement secure key lifecycle management.
- Develop a governance-driven migration strategy for enterprise adoption of PQC.

---

## Technologies Used

- Python 3.x
- Pandas
- Matplotlib
- ReportLab
- NetworkX (optional, for diagrams)
- Jupyter Notebook

---

## Project Structure

```
QuantumSafeAnalyzer/
│
├── assets.csv
│
├── risk_engine.py
├── charts.py
├── report.py
├── architecture.py
├── architecture_diagram.py
├── key_management.py
├── migration.py
│
├── reports/
│   ├── risk_report.csv
│   ├── QuantumSafe_Report.pdf
│   ├── pqc_architecture.csv
│   ├── key_management_report.csv
│   └── migration_strategy.csv
│
├── diagrams/
│   └── pqc_architecture_enterprise.png
│
├── charts/
│   ├── algorithm_distribution.png
│   ├── risk_distribution.png
│   ├── department_risk.png
│   └── high_risk_assets.png
│
└── README.md
```

---

## Features

### Task 1 – Cryptographic Risk Assessment

- Reads enterprise cryptographic inventory
- Identifies RSA and ECC usage
- Calculates risk scores
- Detects Harvest Now, Decrypt Later risks
- Generates risk reports and visualizations

Output:

- `risk_report.csv`
- `QuantumSafe_Report.pdf`
- Risk charts

---

### Task 2 – Post-Quantum Architecture Design

- Recommends PQC algorithms
- Designs hybrid cryptographic deployment
- Maps enterprise cryptographic architecture
- Generates architecture diagrams

Output:

- `pqc_architecture.csv`
- Enterprise architecture diagram

---

### Task 3 – Key Management

Implements:

- Key generation
- Secure storage
- Key rotation
- Key backup
- Key revocation
- PQC readiness assessment
- TLS migration strategy

Output:

- `key_management_report.csv`

---

### Task 4 – Migration Strategy

Develops:

- Risk-based migration priorities
- Phased migration roadmap
- Hybrid deployment approach
- NIST-aligned recommendations
- KPIs and success metrics

Output:

- `migration_strategy.csv`

---

## Workflow

```
assets.csv
      │
      ▼
risk_engine.py
      │
      ▼
risk_report.csv
      │
      ├────────► charts.py
      │               │
      │               ▼
      │        Charts (.png)
      │
      ├────────► report.py
      │               │
      │               ▼
      │         PDF Report
      │
      ├────────► architecture.py
      │               │
      │               ▼
      │      PQC Architecture
      │
      ├────────► architecture_diagram.py
      │               │
      │               ▼
      │      Enterprise Diagram
      │
      ├────────► key_management.py
      │               │
      │               ▼
      │      Key Management Report
      │
      └────────► migration.py
                      │
                      ▼
             Migration Strategy
```

---

## How to Run

### Step 1

Clone or download the project.

### Step 2

Install dependencies.

```bash
pip install pandas matplotlib reportlab networkx
```

### Step 3

Run the modules in the following order:

```bash
python risk_engine.py
```

```bash
python charts.py
```

```bash
python report.py
```

```bash
python architecture.py
```

```bash
python architecture_diagram.py
```

```bash
python key_management.py
```

```bash
python migration.py
```

---

## Sample Outputs

The project generates:

- Risk Assessment Report
- PDF Executive Report
- Enterprise Architecture Diagram
- Algorithm Distribution Chart
- Risk Distribution Chart
- Department Risk Analysis
- Key Management Report
- Migration Roadmap

---

## NIST Alignment

The migration strategy follows the principles recommended by NIST for Post-Quantum Cryptography:

- Cryptographic inventory
- Algorithm agility
- Hybrid cryptographic deployment
- Secure key management
- Governance
- Continuous monitoring

---

## Future Enhancements

- Interactive dashboard using Streamlit
- Live cryptographic asset discovery
- Integration with enterprise Key Management Systems (KMS)
- Cloud deployment support
- Automated compliance reporting
- Real-time quantum risk monitoring

---

## Author

Tripti Gupta

Delhi Technological University

Project: QuantumSafe Analyzer

2026


---

## Project Highlights

- Developed an end-to-end **Post-Quantum Cryptography (PQC)** assessment framework using Python.
- Simulated an enterprise cryptographic inventory to identify **RSA**, **ECC**, and other quantum-vulnerable cryptographic assets.
- Performed **cryptographic risk assessment** by analyzing algorithms, key management practices, and long-term data exposure ("Harvest Now, Decrypt Later").
- Designed a **hybrid cryptographic architecture** integrating classical cryptography with NIST-recommended PQC algorithms such as **ML-KEM** and **ML-DSA**.
- Created a professional **enterprise architecture diagram** illustrating secure communication workflows, HSM integration, cloud services, and hybrid TLS deployment.
- Implemented a **key lifecycle management framework** covering key generation, storage, rotation, backup, revocation, and destruction.
- Evaluated enterprise readiness for PQC adoption by recommending secure key storage using **Hardware Security Modules (HSMs)** and **Cloud Key Management Services (KMS)**.
- Developed a **phased migration roadmap** aligned with NIST guidance, including migration priorities, hybrid deployment strategies, implementation timelines, and measurable KPIs.
- Automated the generation of:
  - Cryptographic risk assessment reports
  - Executive PDF reports
  - Risk analysis charts
  - PQC architecture recommendations
  - Key management reports
  - Migration strategy reports
- Built the project using **Python**, **Pandas**, **Matplotlib**, and **ReportLab**, demonstrating practical application of cybersecurity and post-quantum cryptography concepts.

---
## Skills Demonstrated

- Post-Quantum Cryptography (PQC)
- Cryptographic Risk Assessment
- Hybrid Cryptographic Migration
- Enterprise Security Architecture
- Key Management Lifecycle
- NIST PQC Migration Planning
- Risk Analysis and Reporting
- Data Visualization
- Python Programming
- Pandas
- Matplotlib
- ReportLab
- Cybersecurity Documentation
