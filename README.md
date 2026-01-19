# TLOA-Power-Adaptive-Algorithm-Based-on-Air-Ground-Joint-Interference
SHA:cda3d493e64998270cff20086f3b3fbbe45e59d2
This repository contains the experimental data and source code for the paper "TLOA Power Adaptive Algorithm Based on Air-Ground Joint Interference".  

## File Structure & Core Content
The compressed file includes two key experimental result sections:
- `3.2. Results and Analysis of the Comparative Experiment`: Comparative experiments under ideal CSI.
- `3.3. Results and Analysis of Experiments Under Non-Ideal Channel State Information`: Comparative experiments under non-ideal CSI (±2 dB power estimation error + channel attenuation disturbance).

## Environment Requirements
- Python IDE: PyCharm 2023.2.1 (Professional Edition)
- Runtime version: 17.0.8+7-b1000.8 amd64
- Dependencies: 
  - anaconda_depends_2023.09
  - PyTorch 1.13.1

## Quick Start
### 1. Scenario Visualization
Navigate to the `Scenario Plotting` folder (contains Scenario 1/2/3/4 drawing scripts):
- Run the script directly to generate scenario images (one-click execution).
- Modify the `number of runs` parameter at the end of the script to enable repeated execution.

### 2. Core Simulation Scripts
| Script Name                  | Function Description                                                                 |
|------------------------------|--------------------------------------------------------------------------------------|
| `generate_nodes.py`          | Simulates the initial power configuration of communication nodes.                     |
| `modify_communication_nodes.py` | Implements dynamic power adjustment for communication nodes.                       |
| `jammer_first_run.py`        | Jammer decision-making script (first decision based on TLOA strategy).               |
| `jammer_run.py`              | Jammer decision-making script (non-first decisions based on TLOA strategy).          |
| `test.py`                    | Detects jamming effectiveness in simulation scenarios.                               |

### 3. Data Statistics
Run the `Data Statistics` program to calculate and output the comparative experimental data presented in the paper (supports both ideal/non-ideal CSI scenario data).

## Key Algorithm Features
- TLOA algorithm supports continuous power control and adaptive jammer selection.
- Non-ideal CSI simulation: ±2 dB random error for power estimation + [-2,2] random disturbance for path loss models (LoS/two-ray propagation).
