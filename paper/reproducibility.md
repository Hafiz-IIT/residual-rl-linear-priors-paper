# Reproducibility

Run from the repository root:

```bash
python ../residual-rl-linear-priors/demo.py
python -m unittest discover -s ../residual-rl-linear-priors/tests -v
```

The companion implementation is intentionally deterministic. Future experiments should record environment parameters, seeds, controller coefficients, evaluation horizon, and raw trajectories.