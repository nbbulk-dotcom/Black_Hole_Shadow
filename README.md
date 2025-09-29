# Black Hole Shadow - Finite Boundary Simulation

## Overview

This repository implements the finite boundary hypothesis for black holes, demonstrating that black holes have measurable, finite structures rather than infinite singularities. The simulation uses empirical data and quantum corrections to model black hole boundaries across multiple mass scales.

## Empirical Upgrades

This repository now includes empirical-only simulation codes for finite boundary proof completion. The empirical upgrades provide lab-reproducible protocols using only observable, measurable quantities.

### Usage

1. Install dependencies:
```bash
pip install -r requirements.txt
```

2. Run empirical shadow processor with lab/observatory data:
```bash
python empirical_upgrades/empirical_shadow_processor.py --input lab_shadow_data.csv --config empirical_upgrades/config.yaml
```

3. Expected input CSV columns:
- mass_ratio: Mass ratios from measurements
- observed_boundary: Observed boundary measurements
- expected_size: Expected size calculations
- temp_K: Temperature traces in Kelvin
- material_id: Material identifier
- time_s: Time series data in seconds
- fade_ratio: Phase fade measurements (measured/baseline)

4. Output: `empirical_shadow_proof.csv` with empirical boundary ratios and levitation energy metrics

### Lab Duplication
Process lab analog data (e.g., optical boundaries) for empirical finite proof. Use EHT-like interferometers or lab analogs to collect boundary measurement data matching the simulation inputs.

## Core Features

- Finite boundary calculations with quantum corrections
- Material-specific gravitational coupling analysis
- Phase fade modeling for levitation validation
- Empirical ratios eliminating mathematical constants
- Lab-reproducible measurement protocols

## Scientific Framework

The simulation demonstrates that black holes have finite, measurable boundaries that resolve fundamental physics problems like the information paradox. All calculations use ratios of observable quantities without relying on theoretical constructs or mathematical constants.
