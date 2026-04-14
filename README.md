# Robust Lot-Sizing: Reference Implementations & Tutorials

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Python](https://img.shields.io/badge/python-3.7+-blue.svg)
![Gurobi](https://img.shields.io/badge/solver-Gurobi-green.svg)

Educational materials and tutorials for production planning optimisation under uncertainty.

## Contents

### Tutorials (tutorials/)

- **tutorial_deterministic_lot_sizing.ipynb** — Foundational lot-sizing problem with three formulations
- **tutorial_benders_decomposition.ipynb** — Benders decomposition for robust optimization (Bienstock & Özbay 2008)
- **tutorial_instance_generator.ipynb** — Generate synthetic test instances with configurable parameters

### Sample Data (data/)

- **base_case_T24.json** — Example instance for running tutorials (24-period horizon, 2 states)

## Quick Start

1. Install dependencies:
```bash
pip install -r requirements.txt
```

2. Run a tutorial:
```bash
jupyter notebook tutorials/tutorial_deterministic_lot_sizing.ipynb
```

3. Generate custom instances:
```bash
jupyter notebook tutorials/tutorial_instance_generator.ipynb
```

## Requirements

- Python 3.7+
- Gurobi Optimiser (with Python interface)
- See `requirements.txt` for Python package dependencies

## References

Bienstock, D., & Özbay, N. (2008). Computing robust basestock levels. 
*Discrete Optimization*, 5(2), 389–414. 
https://doi.org/10.1016/j.disopt.2006.12.002

## License

MIT License

## Contact

For questions about the thesis and full research, contact the author.
