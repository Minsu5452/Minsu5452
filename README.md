# 강민수 | Minsu Kang

데이터 분석과 모델링을 서비스 형태로 연결하는 일을 해왔습니다. 최근에는 LLM 평가 시스템, 한국어 RAG, 교통·해양 안전 도메인의 예측 모델을 주로 다루고 있습니다.

[이메일](mailto:daro980722@gmail.com) · [DACON](https://dacon.io/myprofile/457768/home)

## 관심 분야

- LLM 평가 자동화: 다중 LLM 채점, queue/worker 구조, HMAC 기반 API 연동
- RAG / GraphRAG: 공개 문서 수집, 조문 단위 parsing, retrieval workflow 구성
- 예측 모델 서비스화: tabular/time-series 모델링, SHAP 분석, FastAPI/Streamlit/React 연동
- 경진대회 솔루션 정리: 재현 가능한 notebook, modular pipeline, public README 정리

## 주요 프로젝트

| 프로젝트 | 설명 | 기술 |
| --- | --- | --- |
| [LLM 평가 시스템](https://github.com/Minsu5452/LLM_Evaluation_System) | 해커톤 제출물을 다중 LLM으로 평가하고 callback으로 결과를 반환하는 FastAPI 서비스 | FastAPI, Redis, asyncio, Docker |
| [운수종사자 사고 위험 예측 웹 플랫폼](https://github.com/Minsu5452/Driver_Risk_Web_Platform) | 검사 데이터 업로드부터 위험 예측, SHAP 설명, 관리자 재학습, Windows 배포까지 연결한 풀스택 데모 | React, Spring Boot, FastAPI, SHAP |
| [해양 도메인 RAG](https://github.com/Minsu5452/Marine_Domain_RAG) | 국가법령정보 API 기반 해양 법령 수집·파싱·검색·질의응답 파이프라인 | LangGraph, FAISS, GraphRAG |
| [해양사고 위험 예측](https://github.com/Minsu5452/Marine_Accident_Risk_Prediction) | 공개 사고·격자·기상 데이터를 결합한 격자×시간 단위 사고 위험 예측 데모 | LightGBM, SHAP, FastAPI, Streamlit |
| [운수종사자 인지 특성 위험 예측](https://github.com/Minsu5452/Driver_Cognitive_Risk_Prediction) | 인지검사 시퀀스와 과거 이력을 활용한 교통사고 위험 예측 경진대회 솔루션 | LightGBM, CatBoost |
| [산업 지표 Lead-Lag 예측](https://github.com/Minsu5452/Industrial_Lead_Lag_Forecasting) | 산업 품목별 월간 시계열에서 선행·후행 관계를 찾고 follower 값을 예측 | DTW, PageRank, LightGBM |

## 수상 및 경진대회

| 구분 | 결과 |
| --- | --- |
| 유전체 정보 품종 분류 AI 경진대회 | 1st / 716팀 |
| 법원 판결 예측 AI 경진대회 | 2nd / 506팀 |
| HD현대 AI Challenge | 예선 2nd / 330팀, 본선 6th / 11팀 |
| 온라인 채널 제품 판매량 예측 해커톤 | 예선 Top 1.6%, 본선 진출 |
| 제3회 국민대학교 AI빅데이터 분석 경진대회 | Top 5.2% |
| 운수종사자 인지 특성 교통사고 위험 예측 | Top 7.8% |
| 전력사용량 예측 AI 경진대회 | Top 8.7% |
| 감귤 착과량 예측 AI 경진대회 | Top 6.6% |

## 저장소 지도

<details>
<summary>2025-2026 프로젝트</summary>

- [LLM_Evaluation_System](https://github.com/Minsu5452/LLM_Evaluation_System): LLM 평가·채점 서버
- [Driver_Risk_Web_Platform](https://github.com/Minsu5452/Driver_Risk_Web_Platform): 교통안전 위험 예측 웹 플랫폼
- [Driver_Cognitive_Risk_Prediction](https://github.com/Minsu5452/Driver_Cognitive_Risk_Prediction): 운수종사자 인지 특성 위험 예측 파이프라인
- [Industrial_Lead_Lag_Forecasting](https://github.com/Minsu5452/Industrial_Lead_Lag_Forecasting): 산업 지표 lead-lag 예측
- [Marine_Accident_Risk_Prediction](https://github.com/Minsu5452/Marine_Accident_Risk_Prediction): 해양사고 위험 예측 데모
- [Marine_Domain_RAG](https://github.com/Minsu5452/Marine_Domain_RAG): 해양 법령 RAG 파이프라인

</details>

<details>
<summary>2023 프로젝트</summary>

- [Ship_Waiting_Time_Prediction](https://github.com/Minsu5452/Ship_Waiting_Time_Prediction): HD현대 AI Challenge 솔루션 아카이브
- [LG_Online_Sales_Forecasting](https://github.com/Minsu5452/LG_Online_Sales_Forecasting): LG Aimers 온라인 판매량 예측
- [Power_Consumption_Forecasting](https://github.com/Minsu5452/Power_Consumption_Forecasting): 건물 단위 전력사용량 예측
- [Smart_Farm_Yield_Energy_Prediction](https://github.com/Minsu5452/Smart_Farm_Yield_Energy_Prediction): 스마트팜 수확량·에너지 예측
- [Court_Judgment_Prediction](https://github.com/Minsu5452/Court_Judgment_Prediction): 법률 NLP 경진대회 솔루션
- [Traffic_Accident_Prediction](https://github.com/Minsu5452/Traffic_Accident_Prediction): 날씨 기반 교통사고 분석
- [AI_Frenz_2023_Publication](https://github.com/Minsu5452/AI_Frenz_2023_Publication): SNP 품종 분류 학술대회 기록
- [Supporting_Marginalized_Communities](https://github.com/Minsu5452/Supporting_Marginalized_Communities): 청각장애인 지원 AI 아이디어 프로토타입
- [Kookmin_Mentoring_14th](https://github.com/Minsu5452/Kookmin_Mentoring_14th): 멘토링 활동 아카이브

</details>

<details>
<summary>2022 프로젝트</summary>

- [Genomic_Data_Breed_Classification](https://github.com/Minsu5452/Genomic_Data_Breed_Classification): DACON 유전체 분류 1위 솔루션
- [Citrus_Yield_Prediction](https://github.com/Minsu5452/Citrus_Yield_Prediction): 감귤 착과량 회귀 예측
- [Lotte_Members_Customer_Analytics](https://github.com/Minsu5452/Lotte_Members_Customer_Analytics): L.POINT 고객 데이터 분석
- [ML_Team_Project](https://github.com/Minsu5452/ML_Team_Project): 머신러닝 수업 과제와 Kaggle 경진대회
- [DL_Team_Project](https://github.com/Minsu5452/DL_Team_Project): 이미지 컬러화 fine-tuning 프로젝트
- [Restaurant_Topic_Modeling](https://github.com/Minsu5452/Restaurant_Topic_Modeling): 맛집 리뷰 토픽 모델링

</details>

## 기술

| 구분 | 기술 |
| --- | --- |
| 언어 | Python, SQL |
| ML / DL | PyTorch, scikit-learn, LightGBM, XGBoost, CatBoost, SHAP |
| LLM / RAG | LangChain, LangGraph, Hugging Face, FAISS |
| 백엔드 / 인프라 | FastAPI, Spring Boot, Docker, Redis, Nginx |
| 프론트엔드 / 데이터 앱 | React, Vite, Mantine, Streamlit |
| 데이터 처리 | Pandas, NumPy, Matplotlib |

## 경력

| 기간 | 소속 | 역할 |
| --- | --- | --- |
| 2025.12 - 현재 | 데이콘 Data Science팀 | 매니저 |
| 2025.06 - 2025.11 | 슈어소프트테크 AX응용기술팀 | AI 개발자 인턴 |

## 학력 및 자격

- 국민대학교 AI빅데이터융합경영학과 학사
- SQLD, 한국데이터산업진흥원
- 빅데이터분석기사 필기, 한국데이터산업진흥원
- TOEIC Speaking Intermediate Mid 3
