# Method

1. Define a scalar linear baseline controller.
2. Define a deterministic residual correction.
3. Compose baseline and residual actions.
4. Roll out the closed-loop system from a fixed initial state.
5. Compare baseline and residual trajectories.
6. Extend later to learned residuals, multiple seeds, controlled disturbances, and explicit safety constraints.

The current implementation is intentionally small enough to inspect line-by-line.