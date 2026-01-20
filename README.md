# Quantum-Enhanced AI Self-Healing Network

**Thesis Project** – Quantum-enhanced AI for autonomous network healing  
**Phase 0: Development Environment Setup** – 100% Complete (December 2025)

## Team Members (Phase 0)

- **Person 1** – Poritosh Dey (Lead Researcher)  
- **Person 2** – Kishore Biswas (Technical Writer)  
- **Person 3** – Shovon (Data Analyst/Tester)  


## Phase 0 Documentation (All Reports)

All team members successfully completed their assigned tasks.  
The development environment (Ubuntu VM, Mininet, Python 3.10+, virtualenv, simulators) is fully set up and documented.

| Person   | Name                  | Role                          | Document                                                                 | Main Focus                                      |
|----------|-----------------------|-------------------------------|--------------------------------------------------------------------------|-------------------------------------------------|
| Person 1 | Poritosh Dey          | Lead Researcher              | [docs/Poritosh Dey_Phase 0_Documentation-2.pdf](docs/Poritosh%20Dey_Phase%200_Documentation-2.pdf) | Ubuntu system config, essential tools, Python setup |
| Person 2 | Kishore Biswas (2263) | Technical Writer             | [docs/2263_Phase_0_-2.pdf](docs/2263_Phase_0_-2.pdf)                    | Full setup guide: virtualenv, pip, Qiskit Aer, Mininet, etc. |
| Person 3 | Shovon (Roll: 2243)   | Data Analyst/Tester          | [docs/2243_Phase_0-2.pdf](docs/2243_Phase_0-2.pdf)                      | VirtualBox VM creation, Mininet install & tests |

Click the links above to view the PDFs directly on GitHub.





# Quantum-Enhanced AI Self-Healing Network

Thesis Project – Quantum-enhanced AI for autonomous network self-healing

**Current Status (as of January 20, 2026)**  
- Phase 0: Development Environment Setup – 100% Complete (December 2025)  
- Phase 1: Failure Detection & Prediction – 100% Complete (January 2026)

## Phase 0: Development Environment Setup – 100% Complete

The team successfully set up the development environment (Ubuntu VM, Mininet, Python 3.10+, virtualenv, quantum simulators like Qiskit Aer, etc.).

### Team Members (Phase 0)
- **Person 1** – Poritosh Dey (Lead Researcher)  
- **Person 2** – Kishore Biswas (Roll: 2263, Technical Writer)  
- **Person 3** – Shovon (Roll: 2243, Data Analyst/Tester)


### Team Contributions

| Person | Name / Roll          | Role                        | Document Link                                                                                     | Main Focus                                                                 |
|--------|----------------------|-----------------------------|---------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------|
| 1      | Poritosh Dey (2274)  | Lead Researcher             | [docs/Phase1/2274_Poritosh_Dey_Phase1_Documentation.pdf](docs/Phase1/2274_Poritosh_Dey_Phase1_Documentation.pdf) | QML architecture design, quantum circuits & encoding, theoretical performance analysis |
| 2      | Kishore Biswas (2263)| Technical Writer            | [docs/Phase1/2263_Phase1_Documentation.pdf](docs/Phase1/2263_Phase1_Documentation.pdf)             | Full data pipeline documentation, preprocessing & feature engineering, QML specs + diagrams, methodology draft |
| 3      | Shovon Roll 2243            | Data Analyst / Tester       | [docs/Phase1/2243_Phase1_Implementation.pdf](docs/Phase1/2243_Phase1_Implementation.pdf)           | Network traffic simulation & failure injection, preprocessing pipeline, QML model training/evaluation (accuracy, F1, ROC), sandbox integration |

**Key Highlights from Phase 1**:
- Achieved high accuracy (up to 100% with classical models like Random Forest and SVM on synthetic data).
- Used Mininet for realistic network emulation on Ubuntu 24.04.3 LTS.
- Implemented hybrid quantum-classical pipeline (Qiskit / PennyLane for quantum models).
- Comprehensive evaluation of multiple models and metrics.

**Code & Dependencies** (if available):
- See `code/Phase1/` for any scripts/notebooks (QML models, Mininet simulations).
- Dependencies listed in `requirements.txt` (e.g., qiskit, pennylane, scikit-learn, pandas).

## Project Overview & Roadmap (Reference)

Modern networks face increasing complexity due to failures, security threats, and dynamic load conditions. The Quantum-Enhanced AI Self-Healing Network combines quantum-based predictive analytics, federated root cause analysis, autonomous healing, and robust security.

**Objectives**:
- Implement QML models for high-accuracy failure prediction.
- Diagnose causes using Quantum-Assisted Pattern Recognition (QAPR) and Federated Learning.
- Develop autonomous self-healing mechanisms.
- Ensure security via quantum intrusion detection, GAN anomaly detection, blockchain auditing.
- Integrate and demonstrate a fully functional self-healing system.

## How to Clone & Set Up Locally

```bash
git clone https://github.com/KishoreBiswas/Quantum-Network-Selfhealing.git
cd Quantum-Network-Selfhealing

# (Optional) Install Python dependencies if requirements.txt exists
pip install -r requirements.txt
