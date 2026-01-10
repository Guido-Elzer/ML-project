#ML Project
This repository contains a machine learning project developed on the Snellius HPC cluster.
The project uses Python, Matplotlib, and PyTorch with CUDA support installed via a virtual
environment combined with environment modules.

---

Environment setup (Snellius)
Snellius uses environment modules instead of global software installations.
Before working on this project, load the required module stack:

```bash
module purge
module load 2025
module load Python/3.13.1-GCCcore-14.2.0
module load matplotlib/3.10.3-gfbf-2025a
