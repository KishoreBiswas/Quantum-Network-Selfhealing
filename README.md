# Quantum-Enhanced AI Self-Healing Network

## Project Overview
This repository contains the work for our thesis project on a Quantum-Enhanced AI Self-Healing Network.  
Phase 0 focuses on setting up the development environment.

## Team Members
- Kishore Biswas (Roll: 2263, Technical Writer)
- Shovon (Roll: 2243, Data Analyst/Tester)
- Topu (Roll: )


## Phase 0 Documentation
Full setup guide is available in [2263_Phase_0_-2.pdf](2263_Phase_0_-2.pdf).  
It covers:
- Prerequisites (Ubuntu 24.04 LTS, VirtualBox, Python 3.12)
- VM and Mininet setup (see 2243_Phase_0.pdf)
- Installing Python and virtualenv
- Installing packages via pip (requirements.txt)
- Installing simulators (Qiskit Aer, Cirq, Mininet)
- Verification steps

## How to Set Up Locally
1. Clone this repo:  
   `git clone https://github.com/YOUR_USERNAME/quantum-network-selfhealing.git`

2. Create virtual environment:  
   `python -m venv venv`

3. Activate it:  
   - Windows: `venv\Scripts\activate`  
   - Linux/macOS: `source venv/bin/activate`

4. Install dependencies:  
   `pip install -r requirements.txt`

5. Verify:  
   `python -c "import qiskit; print(qiskit.__version__)"`  
   (should show 1.2.0)

## Next Steps
Proceed to Phase 1 after verification.

For complete details, see the PDF file.