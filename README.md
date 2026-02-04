# AI-DX-Training

## 프로젝트 목적
본 프로젝트는 데이터 분석 실습에서 진행한 기본 시각화 실습 결과를 정리하기 위해 수행되었다.

## 사용 데이터
- 한국전력거래소 지역별 시간별 태양광 및 풍력 발전량

## 분석 및 시각화 내용
- 지역별 태양광 및 풍력 평균 전력거래량 ( 선그래프 작성 후 가독성이 떨어져 막대그래프 추가)
- 지역별 시간당 평균 전력거래량 (히트맵)
- 거래시간별 전력거래량 상관관계 (히트맵)
- 거래시간별 평균 전력거래량 (선그래프) / [히트맵으로 상관관계 분석 후 가시성 좋게 선그래프 추가]

## 사용 도구
- Python
- pandas
- matplotlib
- seaborn

## 결과 요약
- 지역별 발전: 전라남도는 태양광 발전이 압도적으로 높았고, '육지'와 '제주'는 풍력 발전의 주요 거점임을 확인했습니다.
- 시간대별 패턴: 전력거래량은 태양광 발전의 영향으로 낮 11시16시 사이에 가장 높으며, 새벽 1시6시에는 가장 낮은 뚜렷한 일일 패턴을 보였습니다.
- 상관관계: 인접한 낮 시간대 전력거래량은 강한 양의 상관관계를 가지며, 이는 태양광 발전의 유사한 생산 패턴 때문입니다.
결론: 전력거래량은 태양광 발전에 크게 좌우되는 계절적 및 일일 패턴을 보이며, 지역별 최적 발전원 구성이 중요합니다.

## 파일 구성
- 2주2일차.ipynb : 데이터 분석 코드 ( 이외 .ipynb는 seaborn이나 pandas 데이터셋을 이용한 시각화 실습 )
- README.md : 프로젝트 설명

<img width="1984" height="684" alt="다운로드 (4)" src="https://github.com/user-attachments/assets/bde38150-506f-46a4-9be5-1d9d77a943b0" />
<img width="1784" height="784" alt="다운로드" src="https://github.com/user-attachments/assets/da8ad517-b408-44f8-afb8-c267bc337baa" />
<img width="1385" height="784" alt="다운로드 (3)" src="https://github.com/user-attachments/assets/7140a6d1-6618-4420-91cc-5eb48747ad3d" />
<img width="1469" height="1184" alt="다운로드 (2)" src="https://github.com/user-attachments/assets/989f7d4c-0408-4c49-8ba5-7b4a37675bad" />
<img width="1484" height="684" alt="다운로드 (1)" src="https://github.com/user-attachments/assets/2b574b67-0d74-4f31-9cbc-d1b03c6bd3b0" />
