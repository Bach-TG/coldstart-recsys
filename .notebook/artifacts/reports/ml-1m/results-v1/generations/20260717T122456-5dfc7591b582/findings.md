# Results Summary

- **Best mean F1:** EmerG ranks first by mean F1 across phases. Evidence: mean F1=0.6692, mean ROC-AUC=0.7839
- **Cold-start phase:** DGD-Ablation:selected is the top Cold-phase model by notebook-07 ranking. Evidence: See phase_winners.csv and f1_by_phase.png.
- **Warm-up effect:** DGD Warm C minus Cold F1 is reported as an observed phase delta, not a causal claim. Evidence: DGD Warm C - Cold F1=0.0790
- **Ablation selection:** Validation-selected ablation variants are recorded per seed. Evidence: full_dgd
- **Warnings and coverage:** Upstream WARN/PARTIAL status is preserved in this report. Evidence: coverage=COMPLETE, source WARN runs=5, audit WARN checks=1

## Limitations
- Results depend on notebook 02's fixed MovieLens-1M protocol and notebook 07's verified aggregation.
- WARN or PARTIAL upstream status should be reported explicitly instead of treated as a clean final result.
- Notebook 08 formats evidence only; it does not introduce new dataset splits, training, or threshold selection.
