<div align="center">

# Kohei Sawada

- GitHub: [@Kohei-SAWADA](https://github.com/Kohei-SAWADA)
- LinkedIn: [Kohei Sawada](https://www.linkedin.com/in/kohei-sawada-498b30375/?skipRedirect=true)
- Projects: [VASPFlowForge](https://github.com/Kohei-SAWADA/VASPFlowForge), [usage_kun](https://github.com/Kohei-SAWADA/usage_kun)

## Featured Public Repositories

### [VASPFlowForge](https://github.com/Kohei-SAWADA/VASPFlowForge)

<p align="center">
  <a href="https://github.com/Kohei-SAWADA/VASPFlowForge">
    <img src="assets/vaspflowforge-thumbnail.png" alt="VASPFlowForge automated VASP workflow thumbnail" width="820">
  </a>
</p>

VASPFlowForge is a publishable automation toolkit for VASP workflows. It is
designed around a common research pattern:

```text
PBE structure relaxation -> HSE06 structure relaxation -> HSE06 DOS calculation
```

The project focuses on reliable stage-to-stage handoff, including automatic
promotion of converged structures into the next calculation stage. It also keeps
the public example safe by excluding licensed pseudopotential files such as
`POTCAR`, while documenting how users should provide them locally.

Key ideas:

- one-command batch workflow for multi-stage VASP jobs
- explicit convergence checks before using generated structures
- public STO example inputs without proprietary pseudopotentials
- English-first documentation with Japanese support
- designed for workstation-style Linux execution and adaptable HPC use

### [usage_kun](https://github.com/Kohei-SAWADA/usage_kun)

<p align="center">
  <a href="https://github.com/Kohei-SAWADA/usage_kun">
    <img src="assets/usage-kun-thumbnail.png" alt="usage_kun AI usage meter thumbnail" width="820">
  </a>
</p>

usage_kun is a privacy-first macOS menu bar app for keeping Claude Code and
Codex usage visible while working.

It is a small native utility rather than a dashboard. It shows 5-hour and
1-week usage windows, can optionally reuse local CLI sign-in state for official
usage numbers, and keeps sensitive data local.

Key ideas:

- compact macOS menu bar and pinned desktop usage meter
- Claude Code and Codex usage visibility while coding or writing
- local-first behavior with no telemetry
- read-only official sync when enabled
- packaged app workflow plus source-build instructions

## Toolbox

<p>
  <img alt="VASP" src="https://img.shields.io/badge/VASP-DFT-3b82f6?style=flat-square">
  <img alt="Gaussian 16" src="https://img.shields.io/badge/Gaussian%2016-quantum%20chemistry-6f42c1?style=flat-square">
  <img alt="Python" src="https://img.shields.io/badge/Python-research%20automation-3776AB?style=flat-square&logo=python&logoColor=white">
  <img alt="Bash" src="https://img.shields.io/badge/Bash-workflow%20control-4EAA25?style=flat-square&logo=gnubash&logoColor=white">
  <img alt="Shell Script" src="https://img.shields.io/badge/Shell%20Script-batch%20automation-121011?style=flat-square&logo=gnu-bash&logoColor=white">
  <img alt="Swift" src="https://img.shields.io/badge/Swift-macOS-F05138?style=flat-square&logo=swift&logoColor=white">
  <img alt="GitHub" src="https://img.shields.io/badge/GitHub-publication-181717?style=flat-square&logo=github&logoColor=white">
</p>
