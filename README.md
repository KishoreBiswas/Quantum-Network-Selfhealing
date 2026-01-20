# Quantum-Enhanced AI Self-Healing Network

Thesis Project – Quantum-enhanced AI for autonomous network healing

**Current Status (as of January 20, 2026)**  
- Phase 0: Development Environment Setup – 100% Complete (December 2025)  
- Phase 1: Failure Detection & Prediction – 100% Complete (January 2026)

## Phase 0: Development Environment Setup – 100% Complete

The team successfully set up the development environment (Ubuntu VM, Mininet, Python 3.10+, virtualenv, simulators like Qiskit Aer).

### Team Members (Phase 0)
- **Person 1** – Poritosh Dey (Lead Researcher)  
- **Person 2** – Kishore Biswas (2263, Technical Writer)  
- **Person 3** – Shovon (2243, Data Analyst/Tester)

### Phase 0 Documentation (All Reports)
Click the links to view the PDFs directly on GitHub.

| Person | Name / Roll          | Role                        | Document Link                                                                 | Main Focus                                      |
|--------|----------------------|-----------------------------|-------------------------------------------------------------------------------|-------------------------------------------------|
| 1      | Poritosh Dey         | Lead Researcher             | [docs/Poritosh Dey_Phase 0_Documentation-2.pdf](docs/Poritosh Dey_Phase 0_Documentation-2.pdf) | Ubuntu system config, essential tools, Python setup |
| 2      | Kishore Biswas (2263)| Technical Writer            | [docs/2263_Phase_0_-2.pdf](docs/2263_Phase_0_-2.pdf)                          | Full setup guide: virtualenv, pip, Qiskit Aer, Mininet |
| 3      | Shovon (2243)        | Data Analyst / Tester       | [docs/2243_Phase_0-2.pdf](docs/2243_Phase_0-2.pdf)                            | VirtualBox VM creation, Mininet install & tests |

**Status**: Phase 0 is fully documented and complete – ready for Phase 1!

## Phase 1: Failure Detection & Prediction – 100% Complete (January 2026)

Phase 1 implements Quantum Machine Learning (QML) for detecting and predicting network failures. It includes Mininet simulations, data pipelines, model training (classical + quantum), and evaluations (e.g., 100% accuracy with Random Forest/SVM in some cases).

### Team Contributions

| Person | Name / Roll          | Role                        | Document Link                                                                                     | Main Focus                                                                 |
|--------|----------------------|-----------------------------|---------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------|
| 1      | Poritosh Dey (2274)  | Lead Researcher             | [docs/2274_Poritosh_Dey_Phase1_Documentation.pdf](docs/2274_Poritosh_Dey_Phase1_Documentation.pdf) | QML architecture design, quantum circuits, theoretical analysis           |
| 2      | Kishore Biswas (2263)| Technical Writer            | [docs/2263_Phase1_Documentation.pdf](docs/2263_Phase1_Documentation.pdf)                           | Data pipeline documentation, preprocessing, QML specs, methodology draft  |
| 3      | Roll 2243            | Data Analyst / Tester       | [docs/2243_Phase1_Implementation.pdf](docs/2243_Phase1_Implementation.pdf)                         | Network simulations, QML implementation/training, metrics evaluation       |
**Key Highlights**:
- High accuracy achieved (up to 100% with classical models on synthetic data).
- Used Mininet for traffic simulation & failure injection.
- Qiskit / Pennylane for quantum models.

**Code & Dependencies** (if available):
- See `code/Phase1/` for scripts/notebooks (QML models, simulations).
- Dependencies listed in `requirements.txt` (e.g., qiskit, pennylane, scikit-learn).

## How to Clone & Set Up Locally
```bash
git clone https://github.com/KishoreBiswas/Quantum-Network-Selfhealing.git
cd Quantum-Network-Selfhealing
# Install dependencies (if requirements.txt exists)
pip install -r requirements.txt
