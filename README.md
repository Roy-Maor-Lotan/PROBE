# How Efficient Is Your Agent? Online Predictive Bounds under Budget Constraints
 
[![arXiv](https://img.shields.io/badge/arXiv-2611.11279-b31b1b.svg)](https://arxiv.org/abs/2611.11279)
 
Roy Maor Lotan, Shai Feldman, Yaniv Romano
 
> 🚧 **Code will be available soon.**
 
## Overview
 
How many interactions will an AI agent need to solve a task? This work studies that question in an online setting: tasks arrive one at a time, and before each run we issue an upper bound on the number of interactions the agent will need to succeed. Because evaluation budgets are limited, some runs must be stopped early. Their completion time then goes unobserved, so the bound cannot always be checked.
 
We introduce **PROBE**, a method that constructs calibrated upper bounds online. It reweights the observed feedback using inverse-probability weighting and adaptively allocates the budget across tasks to reduce the expected coverage shortfall. PROBE provably maintains coverage over any finite horizon while respecting the budget. On software engineering, retrieval-augmented generation, and instruction-following tasks, PROBE achieves coverage closer to the target level than a calibrated baseline, with tighter bounds.
 
## Citation
 
If you find this work useful, please cite:
 
```bibtex
@misc{lotan2026efficientagentonlinepredictive,
      title={How Efficient Is Your Agent? Online Predictive Bounds under Budget Constraints},
      author={Roy Maor Lotan and Shai Feldman and Yaniv Romano},
      year={2026},
      eprint={2611.11279},
      archivePrefix={arXiv},
      primaryClass={cs.LG},
      url={https://arxiv.org/abs/2611.11279},
}
```
 
