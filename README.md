# Benzene–Toluene Distillation Column Simulation

Process simulation of a continuous binary distillation column separating a 
Benzene–Toluene mixture, built in DWSIM. Applies mass/energy balance principles 
and the NRTL thermodynamic model to achieve >98% target distillate purity, 
validated against the classical McCabe–Thiele graphical method.

## Tools
DWSIM · NRTL Property Package · Rigorous Distillation Column (Wang–Henke Bubble-Point solver)

## Key Results
| Stream | Composition |
|---|---|
| Feed | 50% Benzene / 50% Toluene |
| Distillate | 97.5% Benzene |
| Bottoms | 98.7% Toluene |

- Condenser Duty: 1091.99 kW
- Reboiler Duty: 1223.05 kW
- Converged in 74 iterations (Wang–Henke Bubble-Point method)

## Methodology
- 12-stage column, feed at Stage 6, 70% Murphree tray efficiency
- Reflux ratio = 5, total condenser, partial reboiler
- Sensitivity analysis on feed-stage efficiency and feed composition
- Validated against McCabe–Thiele graphical method (~11 theoretical stages 
  vs. ~8.4 effective stages from DWSIM) — see full report for details

## Full Report
See [Distillation_Column_Report.pdf](Distillation_Column_Project_Report.docx) for 
complete methodology, results, sensitivity analysis, and McCabe–Thiele validation.

## Author
Kislay Kumar — B.Tech Chemical Engineering, NIT Warangal
