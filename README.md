# ASIC-RAG-HEALTH: Hardware-Accelerated Healthcare Intelligence

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![Healthcare AI](https://img.shields.io/badge/Domain-Healthcare%20AI-red.svg)](https://github.com/Agnuxo1)
[![ASIC-RAG](https://img.shields.io/badge/Hardware-ASIC%20LV06-green.svg)](https://github.com/Agnuxo1)
[![Blockchain](https://img.shields.io/badge/Security-Blockchain-blue.svg)](https://github.com/Agnuxo1)

> **Hardware-Accelerated Retrieval-Augmented Generation for Scalable Healthcare Blockchain in Resource-Constrained Environments**

## Overview

ASIC-RAG-HEALTH validates the **Lucky Miner LV06** ASIC as a low-power replacement for GPU-based inference in rural and resource-constrained healthcare settings. The system combines a Retrieval-Augmented Generation (RAG) pipeline with ASIC-generated cryptographic attestations to create a privacy-preserving, energy-efficient medical AI platform.

The project demonstrates that repurposed Bitcoin mining hardware can power clinical AI workloads at a fraction of the energy cost of traditional GPU deployments — enabling healthcare blockchain nodes in areas without reliable power infrastructure.

## Key Contributions

- **ASIC as Healthcare Compute** — LV06 SHA-256 ASIC provides deterministic, low-power inference assistance
- **Phase 2 Clinic Node Validation** — Rigorous benchmark of LV06 as a standalone clinic node
- **Head-to-Head Benchmarks** — ASIC vs GPU power/performance comparison for healthcare workloads
- **Ultimate Benchmark Suite** — Multi-scenario validation across clinic power, daily workload, and paper-grade testing
- **Cryptographic Data Sovereignty** — Patient data integrity via ASIC-generated hash attestations

## Experimental Results

| Experiment | Description | Status |
|-----------|-------------|--------|
| Phase 2 Clinic Power | LV06 as primary clinic compute node | Validated |
| Daily Workload | Sustained 8-hour clinical operation | Validated |
| Paper Head-to-Head | Peer-review-grade ASIC vs GPU benchmark | Validated |
| Ultimate Benchmark | Full multi-scenario validation suite | Complete |

## Repository Structure

```
ASIC-RAG-HEALTH/
├── demo_full_medical_workflow.py       # Full pipeline demonstration
├── exp_phase2_01_clinic_power.py       # Clinic power validation
├── exp_phase2_02_daily_workload.py     # Daily workload experiment
├── exp_phase2_04_paper_head_to_head.py # ASIC vs GPU comparison
├── exp_phase2_ULTIMATE_BENCHMARK.py    # Complete benchmark suite
├── medical_bridge.py                   # ASIC-medical interface layer
├── health_config.py                    # Configuration
├── ultimate_benchmark_results.json     # Benchmark results
├── GPU_VS_ASIC_COMPARISON.md          # Performance analysis
├── ASIC-RAG-HEALTH Validation.md      # Full validation report
├── README_PHASE_2.md                  # Phase 2 documentation
├── PHASE_2_FIELD_REPORT.md            # Field deployment report
├── Experiment_v10/                    # Version 10 experiments
└── papers/
    └── ASIC_RAG_Healthcare_LLM_Paper.html  # Research paper
```

## Installation

```bash
git clone https://github.com/Agnuxo1/ASIC-RAG-HEALTH-Hardware-Accelerated-Healthcare-Intelligence
cd ASIC-RAG-HEALTH-Hardware-Accelerated-Healthcare-Intelligence

pip install -r requirements.txt  # or: pip install numpy requests flask
```

## Hardware Setup

```bash
# Phase 2: Connect Lucky Miner LV06 to your network
# Edit health_config.py with your device IP
LV06_IP = "192.168.0.15"  # Change to your LV06 IP
```

## Usage

```bash
# Run full medical workflow demo
python demo_full_medical_workflow.py

# Run Phase 2 clinic power validation
python exp_phase2_01_clinic_power.py

# Run ultimate benchmark
python exp_phase2_ULTIMATE_BENCHMARK.py

# GPU vs ASIC head-to-head comparison
python exp_phase2_04_paper_head_to_head.py
```

## Scientific Context

This work builds upon the ASIC-RAG-CHIMERA framework for holistic medical anomaly detection and extends it with:

1. **Phase 2 validation** proving sustained clinic-level operation
2. **Energy efficiency analysis** comparing ASIC vs GPU power consumption
3. **Scalability projections** for rural healthcare blockchain deployment
4. **Cryptographic data sovereignty** using ASIC hash attestations

## Related Work

- [ASIC-RAG Hardware-Accelerated Medical Anomaly Detection](https://github.com/Agnuxo1/ASIC-RAG-Hardware-Accelerated-Medical-Anomaly-Detection-and-Cryptographic-Data-Sovereignty)
- [ASIC Anomaly Detection Complete System](https://github.com/Agnuxo1/ASIC-Anomaly-Detection-Complete-System)

## Citation

```bibtex
@article{angulo2025asicraghealth,
  title={ASIC-RAG-HEALTH: Hardware-Accelerated Retrieval-Augmented Generation
         for Scalable Healthcare Blockchain in Resource-Constrained Environments},
  author={Angulo de Lafuente, Francisco},
  year={2025},
  url={https://github.com/Agnuxo1/ASIC-RAG-HEALTH-Hardware-Accelerated-Healthcare-Intelligence}
}
```

## Author

**Francisco Angulo de Lafuente**
- GitHub: [Agnuxo1](https://github.com/Agnuxo1)
- ResearchGate: [Francisco Angulo de Lafuente](https://www.researchgate.net/profile/Francisco-Angulo-Lafuente-3)
- Email: agnuxo1@gmail.com

## License

MIT License — See [LICENSE](LICENSE) for details.
