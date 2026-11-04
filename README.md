# Leakage, Shortcuts and Transfer in Public UAV Fault-Detection Datasets: A Leakage-Audited Benchmark of Classical Detectors

Data accompanying the article.

- `data/` openly licensed input data (UAV-FD files; DOIs for UAV-SEAD and ALFA, too large for GitHub); see `data/README.md`.
- `results/<experiment>/` numbers (`cifras*.json`) and tables (`tablas/*.csv`) of each experiment and post hoc analysis.
- `results/partitions/` saved group, vehicle and session partitions.
- `results/window_scores/` saved per-window out-of-fold scores (`.npz`; load with `numpy.load(..., allow_pickle=True)`).
- `results/screening/` title and abstract screening decisions of the literature search.
- `SHA256SUMS.txt` SHA-256 of every file.

Datasets: UAV-SEAD (https://doi.org/10.57967/hf/7772), ALFA (https://doi.org/10.1184/R1/12707963.v1) and UAV-FD
(https://doi.org/10.5281/zenodo.7648996), all CC BY 4.0. RflyMAD (https://doi.org/10.1177/02783649241305153) is under
a non-commercial licence and is not redistributed; obtain it from its authors. Derived results are released under CC BY 4.0.
