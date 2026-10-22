# Image-Based Scientific AI — Part III: BioCulture

**Long-term scope:** Cell Culture Image Analysis and Experimental Optimization (equally weighted educational pillars). The v0.1.0 candidate contains the currently evidenced notebook work; a complete image-to-optimization closed loop is **not** claimed. A later version may add separately validated integrated optimization exercises.

**Status:** Early public educational release **candidate** `v0.1.0`; the larger multi-Part project remains in progress.

## Contents
19 notebooks (published copies have all saved outputs cleared for third-party data-rights caution) grouped into B01–B08 learning stages. B01–B05 use CTC mother-machine single-cell data; B06–B08 use **separate**, public medium-composition and OD600 growth datasets and are not the same biological samples as B01–B05. `docs/audit/` retains originally packaged validation records.

## Setup
```bash
conda env create -f environment.yml
conda activate bioimage-bioculture
jupyter lab
```
`environment.yml` is a **newly assembled dependency proposal** based on observed notebook imports, **not** an independently tested lockfile. B06 acquisition notebook also contains a `%pip install openpyxl` cell; environment and notebooks should be checked together.

## External data not included
- `data/bioculture/CTC.zip` for B01–B05.
- `data/bioculture/media_aida_ying_2025/` containing original spreadsheets (9 external Excel originals referenced in source records) for B06–B08.
- User-generated CSV/PNG/JSON outputs under `results/bioculture/` are not included.

You must procure external sources under their own use conditions and run the notebook stages in order; see `docs/DATA_AND_REPRODUCIBILITY.md` and `docs/DATA_RIGHTS_AND_RELEASE_GATE.md`.

**Public release gate:** CTC conditions may require explicit permission for public non-challenge scientific use. Publishing source code must not be interpreted as permission to redistribute CTC images or derivatives. Original Aida–Ying Excel provenance and rights remain unverified.

## Verification boundary
The canonical private package audit records indicate 19 notebooks with 160 active code cells and no recorded error outputs. **This does not establish an independent clean-machine end-to-end rerun with original external data.** Training-guide Word exercise code was not fully automatically executed. B08 prospective experiments were **proposals**, not conducted experiments.

## Licensing
Apache License 2.0 applies to the project's own code and original project documentation only. External dataset permissions are independent; source attribution and copyright review are required before redistribution.

## 한국어
Part III는 8개 학습 단계에 19개 Notebook이 있습니다. 실행 기록과 독립적인 재현 실험을 혼동하지 마십시오. 외부 데이터와 개인 결과 파일은 저장소에서 제외했습니다.


## Publication status
This is a **release candidate** pending the final data-rights and reproducibility gates. This Git repository may be published before a formal v0.1.0 GitHub Release is issued. See `docs/DATA_RIGHTS_AND_RELEASE_GATE.md`.
