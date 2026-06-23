# AH-PC
Adaptive Horizon Predictive Coding for Universal EEG Representation Learning — SSL pre-training across sleep staging and seizure detection without task-specific architectural changes.

AH-PC extends predictive coding SSL for EEG by replacing the fixed 
single-step prediction horizon with a learnable Horizon Attention Module 
that dynamically weights predictions across multiple temporal scales 
(k = 1, 2, 4, 8 steps). Pre-trained on SEED-V emotion data and validated 
on PhysioNet Sleep-EDF (slow dynamics) and CHB-MIT seizure detection 
(fast/chaotic dynamics) — using one encoder, no task-specific changes.