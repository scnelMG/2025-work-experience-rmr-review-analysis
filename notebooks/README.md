# 노트북 안내

공개 노트북은 원본 실행 결과와 셀 실행 번호를 제거한 정리본입니다. 데이터 파일은 포함하지 않으며, 일부 노트북의 Colab·로컬 경로는 실행 환경에 맞게 수정해야 합니다.

## 권장 실행 순서

| 순서 | 노트북 | 목적 |
| --- | --- | --- |
| 1 | `01_naver_smartstore_crawling.ipynb` | 네이버 스마트스토어 제품 리뷰 수집 흐름 |
| 2 | `02_review_preprocessing.ipynb` | 리뷰 정제, 형태소 분석, 부정어 처리 |
| 3 | `03_gukbap_review_analysis.ipynb` | 돼지국밥 단일 제품 리뷰의 기초 분석 |
| 4 | `04_review_analysis_comparison.ipynb` | 제품군별 리뷰·맛 표현 비교 |
| 5 | `05_kimchi_jjigae_analysis.ipynb` | 김치찌개 제품군 분석 |
| 6 | `06_bulgogi_analysis.ipynb` | 불고기 제품군 분석 |
| 7 | `07_tteokgalbi_workflow.ipynb` | 떡갈비 제품군 전처리·분석 흐름 |
| 8 | `08_bibimbap_workflow.ipynb` | 비빔밥 제품군 전처리·분석 흐름 |
| 9 | `09_gukbap_taste_expressions.ipynb` | 국밥 제품별 맛 표현 시각화 |

`archive/10_preprocessing_draft.ipynb`는 당시의 전처리 초안입니다. 최신 실행 흐름의 기준으로 사용하지 않으며, 원본 작업 과정을 보존하기 위해 남겼습니다.

## 실행 전 확인

- 프로젝트 루트에서 Jupyter를 실행하거나, 노트북 안의 `./data/` 경로를 현재 작업 위치에 맞게 조정합니다.
- 크롤링은 대상 사이트의 이용약관·robots 정책·접근 제한을 확인한 뒤 수행합니다.
- 수집 결과에서 작성자 식별 가능 필드를 제거하고, 원본 리뷰 파일은 GitHub에 추가하지 않습니다.
