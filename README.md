# Project 2: RADAR BSW Module Testing for MRR (Medium Range Radar)

## Project Overview
This project focuses on testing the **RADAR Base Software (BSW) modules** of the **Medium Range Radar (MRR)** system, covering:
- Customer Diagnostics (CD)
- Communication Manager (COM)
- Fault Management (FM)

The goal is to ensure **performance, reliability, and compliance** of radar functionalities in real-time automotive applications.

---

## Roles & Responsibilities

- Requirement analysis for CD, COM, FM modules
- Test case design & review
- Test execution & defect tracking
- Collaboration with developers for issue resolution
- Ensuring compliance with quality standards

---

##  Tools & Technologies Used
- **CANalyzer / CANoe** (Rest Bus Simulation & Testing)
- **CAPL Scripting** (Communication Access Programming Language)
- **CAPL / Python (Automation scripts)Excel / JIRA / RQM** (for test automation & analysis)
- **Excel / JIRA / RQM** (Defect & Test Management)

---

## 📂 Folder Structure
```
RADAR_BSW_MRR_Testing/
│── README.md                # Project Overview
│── LICENSE                  # License file
│── .gitignore               # Git ignore rules
│
├── documents/               # Requirements
│   ├── ACC_requirements.xlsx
│
├── testcases_and_execution/ # Test cases and execution results
│   ├── ACC_test_cases_with_results.xlsx
│
├── scripts/                 # Automation scripts
│   ├── capl_script.can
│
├── assets/                  # Supporting diagrams and logos
│   ├── architecture_diagram.png
│   └── logo_placeholder.png
│
└── screenshots/             # Execution results/screenshots
    └── sample_execution.png
```
---

##  How to Run/Test the Project
1. Open `/documents/BSW_requirement.xlsx` for requirements reference.
2. Select test cases from `/testcases_and_execution/`.
3. Run automation scripts from `/scripts/`:
   ```bash
   python example_script.py
   or load CAPL scripts in CANoe.  
4. Capture and save execution results in /screenshots/.

---

## Example Test Case Format

| Test Case ID | Requirement ID | Pre-Condition       | Steps                  | Expected Result                       | Status |
| ------------ | -------------- | ------------------- | ---------------------- | ------------------------------------- | ------ |
| TC\_COM\_01  | R-3141         | ECU in normal state | Send ECU reset command | ECU should reset and enter INIT state | Pass   |

---

📜 License

This project is licensed under the MIT License – see the LICENSE file for details.
