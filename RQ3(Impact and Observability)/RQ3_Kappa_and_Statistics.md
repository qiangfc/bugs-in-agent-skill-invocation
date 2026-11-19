# Kappa Results and Interpretation

## Sample

The 901 retained reports are split into **452 Pilot** and **449 Reliability**. Within each repository, reports were sorted by Issue number, and half, rounded up, were sampled without replacement for Pilot using Python’s `random.Random(42).sample`. The remaining reports formed the Reliability sample.

## Agreement on the completed Reliability roster

- **Task impact:** Valid paired n=449; 402 agreements; 47 disagreements; observed agreement 0.895323; chance agreement 0.381496; Cohen’s κ=0.830758.
- **User observability:** Valid paired n=449; 417 agreements; 32 disagreements; observed agreement 0.928731; chance agreement 0.523241; Cohen’s κ=0.850512.

These coefficients describe agreement between the recorded rounds. The final full-sample classifications are separate from the inputs to this calculation. See the [per-Issue label comparison](Coding_Process/Original_Label_Comparison.csv).
