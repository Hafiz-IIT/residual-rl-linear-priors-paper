# Residual Reinforcement Learning with Linear Statistical Priors for Robotic Automation

**Status: manuscript in preparation; not submitted or published.**

This repository contains the LaTeX manuscript source and experiment protocol for studying residual policies around transparent linear control priors.

## Files
- paper/main.tex — manuscript source
- paper/EXPERIMENT_PROTOCOL.md — staged hypotheses, baselines, metrics, and controls
- paper/abstract.md, method.md, claims.md, limitations.md, reproducibility.md — modular research notes
- Makefile — local PDF build target

## Build
Requires a LaTeX installation with the geometry, AMS math, booktabs, and hyperref packages.

    make pdf
    make clean

## Evidence boundary
The companion repository currently implements a deterministic scalar residual-control prototype. It does not yet contain a trained RL policy, robotic experiment, or evidence of empirical superiority. The manuscript states this explicitly; results must not be invented to make it appear submission-ready.

Companion code: https://github.com/Hafiz-IIT/residual-rl-linear-priors
