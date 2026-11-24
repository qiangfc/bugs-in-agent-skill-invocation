# Kappa Results and Interpretation

## Sample

For RQ1–RQ3, the 901 reports in [Full_Sample_Labels.csv](Full_Sample_Labels.csv) are divided into **452 Pilot** and **449 Reliability** reports. Within each repository, reports were sorted by issue number. Half of the reports, rounded up, were sampled without replacement for Pilot using Python’s `random.Random(42).sample`. The remaining reports formed the Reliability sample.

For RQ4, the **359 reports with codable corrective actions** were matched by issue URL to the current Pilot and Reliability assignments in the full-sample dataset. Of these, **181** are in the Pilot group and **178** are in the Reliability group. The RQ4 coefficient uses the 178 Reliability reports.

## Agreement on the Reliability Samples

### RQ1 and RQ2

- **Failure symptom** (RQ1, n = 449). The two rounds agreed on 386 reports and disagreed on 63. Observed agreement was 0.859688, expected agreement by chance was 0.070520, and **κ = 0.849043**.
- **Observation stage** (RQ1, n = 449). The two rounds agreed on 426 reports and disagreed on 23. Observed agreement was 0.948775, expected agreement by chance was 0.220669, and **κ = 0.934271**.
- **Root cause** (RQ2, n = 449). The two rounds agreed on 410 reports and disagreed on 39. Observed agreement was 0.913140, expected agreement by chance was 0.187598, and **κ = 0.893083**.
- **Root-cause stage** (RQ2, n = 449). The two rounds agreed on 418 reports and disagreed on 31. Observed agreement was 0.930958, expected agreement by chance was 0.251045, and **κ = 0.907815**.
- **Primary component** (shared by RQ1 and RQ2, n = 449). The two rounds agreed on 408 reports and disagreed on 41. Observed agreement was 0.908686, expected agreement by chance was 0.060178, and **κ = 0.902839**.

### RQ3

- **Task impact** (n = 449). The two rounds agreed on 402 reports and disagreed on 47. Observed agreement was 0.895323, expected agreement by chance was 0.381496, and **κ = 0.830758**.
- **User observability** (n = 449). The two rounds agreed on 417 reports and disagreed on 32. Observed agreement was 0.928731, expected agreement by chance was 0.523241, and **κ = 0.850512**.

### RQ4

- **Repair strategy** (n = 178). The two recorded coding passes agreed on 165 reports and disagreed on 13. Observed agreement was 0.926966, expected agreement by chance was 0.166519, and **κ = 0.912375**.

## Interpretation

Cohen’s κ measures agreement between two sets of labels after accounting for agreement expected by chance. It is calculated as **κ = (pₒ − pₑ) / (1 − pₑ)**. Here, pₒ is the proportion of matching labels and pₑ is the sum, across categories, of the products of the two rounds’ category proportions.

For each field, n is the number of reports with a valid label in both original coding rounds. The coefficients describe consistency between those rounds. The dataset contains the reviewed full-sample labels. 