# Experiment protocol — residual reinforcement learning with linear priors

## Claim under test
A learned residual policy may improve finite-horizon performance over a matched nominal controller under controlled model mismatch. This is a hypothesis, not a current result.

## Staged experiments
1. Reproduce the scalar fixed-residual baseline in the companion code.
2. Add a trainable residual policy only after a declared environment and training objective are fixed.
3. Compare nominal-only, residual-only diagnostic, and hybrid policies.
4. Evaluate held-out disturbances and model parameters.
5. Repeat across fixed seeds and report uncertainty.

## Required controls
Same initial states, disturbance traces, action limits, episode horizons, and compute budgets across policies. Hyperparameters must be selected on validation conditions, not test conditions.

## Metrics
Cumulative cost, tracking error, peak state, action saturation, divergence/non-finite rate, and sample efficiency.

## Current evidence
The companion code is a deterministic scalar residual controller. No trained RL agent, robotic experiment, or performance result is claimed.
