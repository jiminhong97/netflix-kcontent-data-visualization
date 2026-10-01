# Data

본 프로젝트는 **Netflix Tudum Top 10 공식 데이터**의 국가별 주간 순위 데이터를 기반으로 합니다.

## Public processed data

저장소에는 데이터페이지 제작을 위해 최종 가공한 CSV 4개를 포함합니다.

- `k_content_continent_summary_final.csv`  
  대륙별 진출 국가 수, 평균 K-콘텐츠 수, 평균 생존 주차, 총 국가-주를 요약합니다.

- `k_content_country_summary_final.csv`  
  94개 국가의 K-콘텐츠 수, 총 순위권 주차, 평균 생존 주차를 요약합니다.

- `k_content_country_level_final.csv`  
  국가×콘텐츠 단위의 3,265개 관측치로, 최초/최종 순위 진입 주, 최고 순위, 평균 순위, 최대 Top 10 생존 주차 등을 포함합니다.

- `k_content_top15_longrun_final.csv`  
  장기 생존한 주요 K-콘텐츠 15개의 진입 국가 수, 글로벌 누적 주차, 평균·최대 생존 주차를 정리합니다.

## Original source workbook

분석에 사용한 원본 파일:

```text
[원본] 2026-05-14_country_weekly.xlsx
```

원천 데이터 파일은 크기가 크고 원본 배포본이므로 이 포트폴리오 저장소에는 중복 업로드하지 않았습니다. 공개 저장소에는 프로젝트에서 직접 생성한 최종 가공 CSV만 포함합니다.
