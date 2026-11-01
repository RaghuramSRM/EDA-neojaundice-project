# NeoJaundice

A retrospective research notebook for neonatal jaundice screening from photographs. It evaluates leakage-aware patient-level splits, within-dataset shifts, subgroup metrics, mitigation strategies, calibration, and metadata fusion.

This is a research study only, not a diagnostic tool.

## Run

Open `NeoJaundice_full_project.ipynb` in Google Colab, choose a T4 GPU runtime, and run the notebook from top to bottom. The notebook expects the NeoJaundice dataset archive and extracted files in Google Drive under `MyDrive/jaundice_project/data/neojaundice/`. It writes results to `MyDrive/jaundice_project/`.

The dataset is not included in this repository. Obtain it through its official source, confirm its license and citation requirements, and place it in the expected Drive folder before running the notebook. Do not upload patient images or identifiable records to this repository.

## Scope and limitations

The notebook documents a single-dataset retrospective analysis. Its within-dataset shift experiments are not external validation, and its metrics should not be interpreted as evidence of clinical readiness. See the notebook's limitations and submission checklist for further details.
