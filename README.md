<div align="center">

# 강민수 · Minsu Kang

**LLM 에이전트와 ML 시스템을 만들고, 실제로 돌아가는 서비스로 배포하는 AI 엔지니어입니다.**

법령 RAG 에이전트부터 망분리 환경의 위험 예측 플랫폼까지,<br>
모델을 만들고 검증해 사용자가 쓰는 화면으로 완성해 왔습니다.

<a href="https://minsu5452.github.io"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-minsu5452.github.io-2563EB?style=for-the-badge"></a>

<a href="mailto:daro980722@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-daro980722%40gmail.com-5B6770"></a>
<a href="https://dacon.io/myprofile/457768/home"><img alt="DACON" src="https://img.shields.io/badge/DACON-Profile-0052CC"></a>

</div>

## 🚀 Featured Projects

실무 과제에서 출발한 프로젝트를 공개 가능한 형태로 다시 만들었습니다. 두 개는 키 없이 바로 열어볼 수 있는 라이브 데모로 배포되어 있습니다.

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://korean-maritime-law-rag.vercel.app"><img src="assets/maritime-rag.png" alt="해양 법령 RAG 데모 화면"></a>
      <h3><a href="https://github.com/Minsu5452/korean-maritime-law-rag">해양 법령 RAG 에이전트</a></h3>
      해양 법령 105개(7,506개 조문)를 BM25·벡터·조문 관계 그래프로 함께 검색하고, 답변마다 근거 조문을 인용합니다. LangGraph 라우팅으로 질문 유형별 검색 전략을 고르고, 골드셋 180문항으로 검색 품질을 검증했습니다.<br><br>
      <a href="https://korean-maritime-law-rag.vercel.app"><b>🔗 라이브 데모</b></a> · <a href="https://github.com/Minsu5452/korean-maritime-law-rag">저장소</a><br>
      <sub>LangGraph · Qdrant · Neo4j · OpenAI API · FastAPI</sub>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/Minsu5452/driver-risk-web-platform"><img src="assets/driver-risk.png" alt="교통사고 위험 예측 플랫폼 대시보드 화면"></a>
      <h3><a href="https://github.com/Minsu5452/driver-risk-web-platform">교통사고 위험 예측 플랫폼</a></h3>
      운수종사자의 검사 결과와 사고 이력으로 위험도를 예측하고, 결과를 화면에서 조회·해석·관리하는 웹 플랫폼입니다. 모델 학습부터 서빙, 인터넷 없는 망분리 Windows PC에 포터블 zip 하나로 설치되는 배포까지 전 구간을 만들었습니다.<br><br>
      <a href="https://github.com/Minsu5452/driver-risk-web-platform"><b>저장소</b></a><br>
      <sub>LightGBM · SHAP · FastAPI · React · Nginx</sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://korean-marine-accident-risk.vercel.app"><img src="assets/marine-risk.png" alt="연안 해양사고 위험 지도 대시보드 화면"></a>
      <h3><a href="https://github.com/Minsu5452/korean-marine-accident-risk">연안 해양사고 위험 분석</a></h3>
      해양사고 28,935건과 해양기상 관측을 결합해 격자×시간 단위 위험도를 추정하고, 기상과 사고의 연관을 시간층화 case-crossover로 검증했습니다. 지도 대시보드는 실제 분석 실행 결과를 키 없이 재생합니다.<br><br>
      <a href="https://korean-marine-accident-risk.vercel.app"><b>🔗 라이브 데모</b></a> · <a href="https://github.com/Minsu5452/korean-marine-accident-risk">저장소</a><br>
      <sub>LightGBM · statsmodels · FastAPI · Next.js · MapLibre</sub>
    </td>
    <td width="50%" valign="top" align="center">
      <br><br><br><br>
      <b>더 많은 프로젝트</b><br><br>
      20개 프로젝트의 배경·접근·결과를<br>포트폴리오 사이트에 정리했습니다.<br><br>
      <a href="https://minsu5452.github.io/projects/">🌐 minsu5452.github.io/projects</a>
    </td>
  </tr>
</table>

## 💼 Experience

### 데이콘 · Data Science팀 매니저 <sub>2025.12 ~ 현재</sub>

공공 데이터 분석 과제 2건의 PL과 대회·해커톤 기획·운영을 맡고 있습니다.

| 구분 | 기간 | 프로젝트 | 내용 |
| --- | --- | --- | --- |
| 개발 | 2026.06 ~ 현재 | 수요기관 입찰 모니터링 모델 개발 | 행안부·NIA·조달청 데이터 분석 사업. 과제 PL로 진행 중 |
| 개발 | 2026.02 ~ 2026.04 | LLM 평가 시스템 | 여러 평가자 LLM의 합의(Council)로 제출물을 2단계 채점하는 비동기 평가 서버. FastAPI·Redis 큐로 LLM 호출을 병렬화하고 HMAC 서명 콜백으로 결과 반환 |
| 개발 | 2025.12 ~ 2026.04 | 운수종사자 위험 예측 플랫폼 | 행안부·NIA·한국교통안전공단 위탁사업. 모델 학습·서빙·망분리 현장 배포까지 전 구간 수행 |

### 슈어소프트테크 · AX응용기술팀 AI 개발자(인턴) <sub>2025.06 ~ 2025.11</sub>

해양수산부·해양경찰청 R&D 과제 2건의 개발 실무와 KT 에이전트 신뢰성 검증을 수행했습니다.

| 구분 | 프로젝트 | 내용 |
| --- | --- | --- |
| 개발 | 해양사고 위험 예측 시스템 | 해양수산부 AI융복합 과제. 격자×시간 단위 데이터 설계, 위험 예측 모델 학습, SHAP 해석 |
| 개발 | 해양 법령 도메인 RAG | 해양경찰청 CDX 과제. 법령 도메인 RAG DB 구축과 검색·답변 흐름 구성에 참여 |
| 검증 | KT 에이전트 신뢰성 검증 | 에이전트 검증 데이터셋 구축, 실성능 테스트, 화이트리스트 작성. KT와 공동 수행 |

## 🛠 Skills

| 영역 | 기술 | 실제로 한 일 |
| --- | --- | --- |
| LLM · Agent | ![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C) ![OpenAI API](https://img.shields.io/badge/OpenAI_API-412991?logo=openai&logoColor=white) ![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?logo=qdrant&logoColor=white) ![Neo4j](https://img.shields.io/badge/Neo4j-018BFF?logo=neo4j&logoColor=white) | 법령 RAG 에이전트의 질문 라우팅과 하이브리드 검색·리랭킹, LLM Council 평가 설계 |
| ML | ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white) ![LightGBM](https://img.shields.io/badge/LightGBM-5B6770) ![statsmodels](https://img.shields.io/badge/statsmodels-5B6770) | 위험 예측 모델 학습과 해석(SHAP·오즈비), 시간층화 case-crossover 통계 검증 |
| Serving · Infra | ![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white) | 예측 API 서빙, 망분리 포터블 배포, CI와 라이브 데모 운영 |
| Data · Web | ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-5B6770) ![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black) ![Next.js](https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white) | 데이터 파이프라인 구성, 관리 웹과 지도 대시보드 화면 |

## 🏆 Awards & Competitions

데이콘 플랫폼 대회에서 1위·2위를 포함해 8개 대회 상위권을 기록했습니다. 순위는 각 대회의 공개 리더보드에서 확인할 수 있습니다.

| 연도 | 대회 | 주제 | 결과 |
| --- | --- | --- | --- |
| 2025 | [제3회 국민대학교 AI빅데이터 분석 경진대회](https://github.com/Minsu5452/industrial-lead-lag-forecasting) | 산업 지표 lead-lag 예측 | 예선 상위 5.2% |
| 2025 | [운수종사자 인지적 특성 데이터를 활용한 교통사고 위험 예측 AI 경진대회](https://github.com/Minsu5452/driver-cognitive-risk-prediction) | 사고 위험 확률 예측 | 상위 7.8% |
| 2023 | [HD현대 AI Challenge](https://github.com/Minsu5452/ship-waiting-time-prediction) | 선박 대기시간 예측 | **예선 2위** · 본선 6위 |
| 2023 | [온라인 채널 제품 판매량 예측 AI 온라인 해커톤](https://github.com/Minsu5452/online-sales-forecasting) | 판매량 시계열 예측 | **예선 상위 1.6%** |
| 2023 | [2023 전력사용량 예측 AI 경진대회](https://github.com/Minsu5452/power-consumption-forecasting) | 건물별 전력사용량 예측 | 상위 8.7% |
| 2023 | [법원 판결 예측 AI 경진대회](https://github.com/Minsu5452/court-judgment-prediction) | 판결문 승소 당사자 분류 | **2위** |
| 2022–2023 | [유전체 정보 품종 분류 AI 경진대회](https://github.com/Minsu5452/genomic-breed-classification) | SNP 품종 분류 | **1위** |
| 2022 | [감귤 착과량 예측 AI 경진대회](https://github.com/Minsu5452/citrus-yield-prediction) | 착과량 예측 | 상위 6.6% |

## 📄 Publication

| 학술대회 | 논문 |
| --- | --- |
| AAiCON 2023 제2차 실용 인공지능 학술대회 | [SNP 정보를 활용한 유전체 품종 분류 모델링에 대한 연구](https://github.com/Minsu5452/snp-breed-classification-paper) |

## 🎓 Education

| 기간 | 학교 | 전공 | 학위 |
| --- | --- | --- | --- |
| 2018.03 ~ 2024.08 | 국민대학교 | AI빅데이터융합경영학과 (심화전공) | 학사 졸업 |

## 📜 Certifications & Languages

| 구분 | 명칭 | 취득·응시 |
| --- | --- | --- |
| 자격증 | 제60회 SQL 개발자 (SQLD) · 한국데이터산업진흥원 | 2026.03.27 |
| 자격증 | 제12회 빅데이터분석기사 (필기) · 한국데이터산업진흥원 | 2026.04.24 |
| 어학 | TOEIC Speaking Test · Intermediate Mid 3 (Speaking 130) | 2025.02.22 |

## 🌱 Activities

| 기간 | 기관 | 프로그램 | 역할 |
| --- | --- | --- | --- |
| 2023.10 ~ 2023.11 | 국민대학교 경영대학 | [연결고리 14기 (현업 동문 진로 멘토링)](https://github.com/Minsu5452/kookmin-mentoring-14th) | 멘티 |
| 2023.09 ~ 2024.03 | BDA (대학생 연합 빅데이터 학회) | 7기 데이터 분석 고급반 | 학회원 |
| 2023.07 ~ 2023.09 | LG AI Research | LG Aimers 3기 (LG 청년 AI 인재 양성) | 교육생 |
| 2023.03 ~ 2023.12 | D&A (국민대학교 빅데이터 분석 학회) | 딥러닝 세션 | 학회원 |
| 2022.03 ~ 2022.12 | D&A (국민대학교 빅데이터 분석 학회) | 머신러닝 세션 | 학회원 |
| 2021.12 ~ 2022.01 | D&A (국민대학교 빅데이터 분석 학회) | Python 기초 스터디 | 학회원 |

## 📚 Coursework

| 기간 | 과목 | 프로젝트 |
| --- | --- | --- |
| 2022.09 ~ 2022.12 | 딥러닝 | [이미지 컬러화 모델 비교](https://github.com/Minsu5452/dl-image-colorization) |
| 2022.09 ~ 2022.12 | 텍스트 마이닝 | [국민대·정릉시장 리뷰 토픽 모델링](https://github.com/Minsu5452/text-mining-review-topics) |
| 2022.03 ~ 2022.06 | 머신러닝 | [백화점 고객 구매 이력 분류 (수업 내 Kaggle 대회 2위)](https://github.com/Minsu5452/ml-department-store-classification) |
