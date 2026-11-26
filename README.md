<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1B2A41,100:2F6B5A&height=210&section=header&text=Minah%20Yoo&fontSize=54&fontColor=FFFFFF&fontAlignY=36&desc=Statistics%20%C3%97%20Finance%20%C3%97%20Machine%20Learning&descSize=18&descAlignY=58" width="100%" alt="Minah Yoo"/>

고려대학교 통계학과 학석사연계과정 · 정윤서 교수 연구실 · KUSTAI 창립자

<a href="mailto:yoo6364@korea.ac.kr"><img src="https://img.shields.io/badge/Email-yoo6364%40korea.ac.kr-1B2A41?style=flat-square" alt="Email"/></a>
<a href="https://github.com/MinahYoo"><img src="https://img.shields.io/badge/GitHub-MinahYoo-2F6B5A?style=flat-square&logo=github&logoColor=white" alt="GitHub"/></a>

</div>

<br/>

## 👩‍💻 About Me

- 🎓 **고려대학교 통계학 석사과정** (2026.09 ~, 학석사연계) · 통계학 학사 (2026.08)
- 🔬 **정윤서 교수 연구실** — 머신러닝
- 💳 **관심 분야** — 신용 리스크 모델링 · 생존분석 · 인과추론 · 금융 데이터의 통계적 학습
- 🤝 **KUSTAI** (Korea University Statistical AI) 창립 · 동아리장
- 🧑‍🏫 통계 컴퓨터 소프트웨어(R 실습) 조교

<br/>

## 🛠 Tech Stack

**Languages**&nbsp;
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
<img src="https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white" alt="R"/>
<img src="https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white" alt="SQL"/>
<img src="https://img.shields.io/badge/LaTeX-008080?style=flat-square&logo=latex&logoColor=white" alt="LaTeX"/>

**ML & Stats**&nbsp;
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch"/>
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="scikit-learn"/>
<img src="https://img.shields.io/badge/CatBoost-FFCC00?style=flat-square&logoColor=black" alt="CatBoost"/>
<img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="pandas"/>
<img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" alt="NumPy"/>
<img src="https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white" alt="SciPy"/>
<img src="https://img.shields.io/badge/lifelines%20%C2%B7%20scikit--survival-2F6B5A?style=flat-square" alt="Survival Analysis"/>
<img src="https://img.shields.io/badge/CVXPY-1B2A41?style=flat-square" alt="CVXPY"/>

**Tools**&nbsp;
<img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" alt="Streamlit"/>
<img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white" alt="Jupyter"/>
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git"/>

<br/>

## 🔬 Featured Projects

### 🌲 숲BTI — 산림복지 수요 예측 & 시설 운영 최적화
**2026 K-DATA SCIENCE 해커톤 · 한국산림복지진흥원 과제** &nbsp;|&nbsp; 🏆 창의상 &nbsp;|&nbsp; 📝 학생논문발표대회 장려상

<table>
<tr>
<td width="44%">
<a href="https://minahyoo-forest-welfare-dashboard-app-2wa44b.streamlit.app/"><img src="https://raw.githubusercontent.com/MinahYoo/forest-welfare-dashboard/main/screenshots/02_regional.png" alt="숲BTI 대시보드"/></a>
</td>
<td>

- 승인통계 『2024 산림휴양·복지활동 조사』(11,949명 × 668문항)로 **개인 맞춤 추천 → 지역 우선확충지수 → 예산 배분**까지 "두 개의 의사결정"을 하나로 연결
- CatBoost 멀티라벨(원자료 515열) **Macro-F1 0.699**, TabPFN 2.5와 비교 · SHAP으로 추천 근거 설명
- PuLP로 2023 결산 63.2억 원 기준 운영 최적화, Streamlit 대시보드로 배포

[**Live Demo**](https://minahyoo-forest-welfare-dashboard-app-2wa44b.streamlit.app/) · [Analysis](https://github.com/MinahYoo/forest-welfare-kdata2026) · [Dashboard](https://github.com/MinahYoo/forest-welfare-dashboard)

</td>
</tr>
</table>

### 🗺️ 상권 생존 지도 — "소비는 있는데 왜 못 버티는가"
**BC카드 AI금융빅데이터플랫폼 소비데이터 경진대회 · 팀 프로젝트**

- LOCALDATA 점포 63.5만 개 × BC카드 소비데이터를 결합해 **Cox 비례위험모형 + RSF**로 지역×업종 폐업 위험을 요인별로 분해
- 학습에 쓰지 않은 미래 78일 전향 검증: **C-index 0.627**, 위험 상위 30% 점포가 실제 폐업의 **48.3%** 포착
- 이웃 지역 폐업률 변수 하나로 잔차의 공간자기상관 해소 (Moran's I 0.241 → 0.023)

[**Website**](https://ahnseo0000.github.io/BC_card/) · [Code](https://github.com/ahnseo0000/BC_card)

### 📈 Diffusion Covariance GMV — 생성모형으로 포트폴리오 위험 예측
**개인 연구 프로젝트**

- 조건부 DDPM으로 다음 달 **공분산 행렬의 분포**를 생성 → 표본공분산과 블렌딩해 long-only 최소분산(GMV) 포트폴리오 구성
- CRSP 미국 일별 주식 2000–2025 · 행렬로그 vech 표현 · 2021–2025 테스트 구간 완전 분리
- 벤치마크: 동일가중 · 표본공분산 · Ledoit-Wolf 축소 · 베이지안 Inverse-Wishart

[Code](https://github.com/MinahYoo/cov-diffusion-gmv)

<br/>

## 🧭 Research & Activities

| 활동 | 내용 |
|---|---|
| 🤝 **산학협력** | NICE평가정보 — 개인사업자 신용평가 모델링 연구 |
| 🤖 **IBM Bob 해커톤** (2026.11) | THE HIDDEN BIAS — 보고서 결론의 표본·무응답 편향과 심슨의 역설을 통계로 검증하는 반박형 검토 에이전트 |
| 🏛️ **KUSTAI** | 창립 멤버 16명 모집 · 6주 ML 커리큘럼 · 해커톤·스터디·세미나 운영 |
| 📈 **Find-Alpha** | 2026.01 ~ 현재 |
| 📊 **KUSEA** | 2025.12 ~ 2026.12 |
| 🗳️ **리서치 조교** | 정치 커뮤니케이션 연구 — 데이터 가공 · AI 시뮬레이션 |
| 📘 **교육** | PFC테크놀로지스 신용평가아카데미 4기 수료 |

<br/>

## 🏆 Awards & Certifications

| 날짜 | 구분 | 내용 |
|---|---|---|
| 2026.11 | 🎖️ 장려상 | 한국데이터정보과학회 추계 학생논문발표대회 |
| 2026.09 | 🏆 창의상 | 2026 K-DATA SCIENCE 해커톤 (팀 '결측치와 춤을') |
| 2025.09 | 📜 SQLD | 한국데이터산업진흥원 |
| 2024.09 | 📜 ADsP | 한국데이터산업진흥원 |

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1B2A41,100:2F6B5A&height=110&section=footer" width="100%" alt=""/>
