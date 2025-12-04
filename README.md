# IMI – Inversion Modelling for Methane Emissions

This repository contains code, configuration files and experiment logs on inverse modelling of methane (CH₄) emissions using the IMI framework. 

## Repository structure

The project is organised to keep configurations, runs and outputs clearly separated and reproducible:

- `configs/`
  - `base/` – Base configuration files (default settings, domain definitions, shared parameters).
  - `runs/` – One config file per experiment/run (e.g. per date, region, or sensitivity scenario).
- `scripts/`
  - `run_imi.sh` – Generic launcher script that runs IMI with a given config and writes logs/results to the corresponding folders.
- `logs/`
  - Text logs for each run (e.g. model output, stdout/stderr), grouped by run name.
- `results/`
  - Processed outputs for each run (e.g. posterior fields, diagnostics, evaluation files).

Additional directories (e.g. `src/`, `notebooks/`, `data/`) may be added as the project evolves.
