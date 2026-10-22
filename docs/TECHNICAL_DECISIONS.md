# 기술 결정 기록 — Part III

**2026-10-21 / GitHub 공개 후보 v0.1.0**

- **기준:** BioCulture B01–B08 Canonical Frozen v1 내부 패키지. Notebook 19개, training guide 19개.
- **공개 포함:** `notebooks/` 19개, 원본 패키지에 있던 일부 audit 증거, 기존 manifest와 검증 요약.
- **공개 제외:** CTC.zip, Aida–Ying Excel 원본, 사용자의 `results/bioculture/`, Word 교재·해설서 작업본.
- **이유:** 원본 데이터 사용조건 미확정 및 대용량/경로 독립성, 원본 실행 코드와 보고서의 역할 분리.
- **검증 증거:** Frozen 패키지 내 `audit_summary.json`, `verification_details.json`, `docs/audit/` 및 `SHA256_MANIFEST.json`. 저장된 실행 Notebook 구조 감사이며 clean-room 재실행은 아님.
- **확인 필요:** 실제 데이터 다운로드 지침과 라이선스, 환경 명세 clean 실행, 단계별 독립 재현, B06~B08 성장 메트릭 정의의 후속 과학적 검토.
- **중요:** 외부 실험 결과를 조합한 설명은 같은 표본을 추적한 것처럼 오해될 수 있음. 학습서·코드 해설서에 데이터 계통 차이를 명시.
