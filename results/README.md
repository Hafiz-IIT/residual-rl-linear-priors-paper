# Results directory

No empirical results are claimed yet. This directory is reserved for machine-readable outputs produced by the protocol in paper/EXPERIMENT_PROTOCOL.md.

Expected files:
- experiment_config.json — fixed plant, controller, seeds, and policy settings
- summary.csv — per-seed metrics for nominal-only and residual-enabled policies
- trajectories/ — optional per-episode state/action traces
- analysis.md — interpretation, negative findings, and deviations from protocol

Do not commit generated results until the experiment script, configuration, and raw outputs can reproduce them. Never substitute illustrative numbers for measured outputs.
