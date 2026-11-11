# surface-code-memory-stim

Results. Using Stim’s rotated surface-code memory circuits with uniform circuit-level depolarizing noise, decoded with PyMatching, the d=3/5 and d=5/7 logical-error-rate curves cross at p ≈ 0.7% (interpolated from a coarse grid; estimated uncertainty about ±0.05%). Below the crossing, larger distance suppresses logical errors; above it, larger distance is worse.

Measurement-noise twist. I scaled measurement and reset error to 1x, 3x, and 10x the gate error. The d=3/5 crossing was ≈ 0.65%, ≈ 0.66%, and ≈ 0.35% respectively. There is no detectable change at 3x and a clear drop at 10x. This is an illustrative noise model, not a calibrated QuEra hardware model.

Limitations. Coarse p grid and linear interpolation of the crossing; logical error is per shot of d rounds, not per round; a single decoder; no leakage, correlated noise, or atom-loss modeling; modest shot counts.
