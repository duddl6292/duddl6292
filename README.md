<p align="center">
  <img src="./assets/profile-header.svg" alt="Hoyoung Kim — AI Engineer" width="100%" />
</p>

<h3 align="center">영상 데이터를 검증하고, 모델을 실험·개선하며, 추론 결과를 서비스로 연결합니다.</h3>

<p align="center">
  김호영 · AI Engineer<br/>
  의료영상 AI 프로젝트에서 데이터 품질 확인부터 모델 평가, 추론 API, 결과 시각화까지 경험했습니다.
</p>

<p align="center">
  <a href="#project">대표 프로젝트</a> ·
  <a href="#contribution">담당 역할</a> ·
  <a href="#stack">기술 스택</a>
</p>

<br/>

<a id="project"></a>

## ✦ Featured Project

### BrainOn · 뇌혈관질환 의료영상 AI 및 CDSS

> **CT · MRI · MRA 영상 분석을 의료진의 진료 흐름에 연결하는 4인 팀 프로젝트**

의료영상 분할 모델을 연구·실험하고, 추론 결과를 의료진 웹에서 확인할 수 있도록 연결했습니다. 저는 **데이터 품질 검증, 모델 실험·평가, 추론 파이프라인, 분석 결과 화면 연동**을 중심으로 작업했습니다.

| 01 · 모델 개발과 평가 | 02 · 추론과 서비스 연결 |
| :--- | :--- |
| CT 데이터 품질 점검과 전처리<br/>nnU-Net · SegResNet 분할 실험<br/>손실 함수·샘플링·입력 구조 비교<br/>작은 병변을 포함한 성능 분석 | FastAPI 공통 추론 인터페이스<br/>Django · Celery 분석 요청 연동<br/>GCS 모델·결과 저장 연동<br/>뷰어에 마스크·확률 맵·XAI 결과 표시 |

**코드 살펴보기** · [의료영상 모델 실험](https://github.com/duddl6292/stroke-model) · [BrainOn 팀 서비스](https://github.com/brainCDSS/BrainCDSS/tree/dev) <sub>(팀 저장소는 접근 권한이 필요할 수 있습니다)</sub>

<sub>두 저장소는 별도 프로젝트가 아니라 BrainOn의 모델 연구와 서비스 구현을 나누어 관리한 것입니다.</sub>

<a id="contribution"></a>

## ✦ My Contribution

- **데이터 검증** · CT 영상의 방향·간격·레이블을 점검하고 학습을 위한 전처리 기준을 정리했습니다.
- **모델 실험** · nnU-Net과 SegResNet을 기반으로 손실 함수와 샘플링 방식 등을 비교했습니다.
- **성능 분석** · Dice·Recall·Precision과 병변 크기별 결과를 살펴 실패 양상을 분석했습니다.
- **추론 구현** · 모델 로딩과 FastAPI 추론 API를 Django·Celery 및 GCS 흐름에 연결했습니다.
- **결과 전달** · 의료영상 뷰어에 병변 마스크, 확률 맵과 XAI 결과를 표시하고 MLflow 모델 정보의 관리자 화면 연동에 참여했습니다.

> 주력 경험은 **의료영상 AI**입니다. 영상 데이터를 다루는 모델 개발·평가·추론 경험을 다른 영상 분야에도 적용하고자 합니다.

<a id="stack"></a>

## ✦ Tech Stack

| 분야 | 사용 기술 |
| :--- | :--- |
| **AI & Data** | Python · PyTorch · MONAI · nnU-Net · SegResNet · NumPy |
| **Evaluation & MLOps** | Dice · Recall · Precision · MLflow |
| **Serving** | FastAPI · Django REST Framework · Celery · RabbitMQ · Docker · Google Cloud Run · Cloud Storage |
| **Interface & DB** | React · TypeScript · PostgreSQL |

<details>
<summary><b>Background & Credentials</b></summary>
<br/>

- 기계공학 전공 · MMM 연구실 학부연구생 (자기장 에너지 하베스팅 연구)
- Biomedical AI 과정 · 2026.03–2026.09
- SQLD · ADsP

</details>

<br/>

<p align="center">
  <b>데이터 검증 → 모델 실험 → 성능 분석 → 추론 서비스</b><br/>
  <sub>김호영 · AI Engineer</sub>
</p>
