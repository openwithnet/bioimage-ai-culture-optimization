# Part I / Part III 공개 감사: 차이와 위험 등록부

**등록일:** 2026-10-21  | **상태:** 공개 전 후보 감사, 일부 후속 재검증 필요

| 항목 | Part I | Part III | 위험/완화 |
|---|---|---|---|
| 구조 | 8 notebook + `src` 모듈 + `scripts` + `tests` | 19 notebook, 외부 파일 및 선행 Notebook 출력 의존 | 파일 단위 코드 해설, 실행 순서 명시 |
| 환경 | 내부 `environment.yml` 보존 | 새롭게 유도한 초안 `environment.yml` | 의존성 드리프트; clean 환경 테스트 필요 |
| 원본 | BBBC039 `images.zip`, `masks.zip`, `metadata.zip` 미포함 | CTC.zip 및 9개 Excel 원본 미포함 | 외부 취득·이용 조건·checksum 필요 |
| 실행 검증 | v15 200개 영상 / 28 tests / 8 notebooks 감사 기록 | 19 notebooks, 160 active code cells 오류 출력 없음 | 독립 clean rerun과 결과 보고서를 구별 |
| 과학적 범위 | 픽셀 foreground mask 겹침, 통계·기술 회귀 | CTC 단일세포(B01–05)와 OD600 배지(B06–08) 서로 다른 실험 | 생물학적 인과·독립 검증 과장 방지 |
| 릴리스 | 내부 v15 → public v0.1.0 제안 | 내부 Frozen v1 → public v0.1.0 제안 | 버전 번호 혼동 금지 |

**사용 지침:** 이 문서는 GitHub `docs/`, 코드 해설서 앞부분 및 새 채팅 Handoff에 포함할 필수 기준 기록이다. 시간 경과 시 근거를 잊지 않도록 기록을 수정할 때 근거 파일/날짜/변경 이유를 남긴다.
