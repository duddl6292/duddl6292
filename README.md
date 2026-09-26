<p align="center">
  <img src="./assets/profile-header.svg" alt="Hoyoung Kim — From medical data to working software" width="100%" />
</p>

<p align="center">
  <strong>의료 데이터를 이해하고, AI 모델을 서비스로 연결하는 개발자 김호영입니다.</strong><br/>
  기계공학과 연구 경험을 바탕으로 데이터 분석에서 의료영상 AI, 추론 서비스 구현까지 경험을 넓혀왔습니다.
</p>

<p align="center">
  <a href="#featured-project">대표 프로젝트</a> ·
  <a href="#my-contribution">담당 역할</a> ·
  <a href="#tech-stack">기술 스택</a> ·
  <a href="https://github.com/brainCDSS/BrainCDSS/tree/dev">BrainOn 코드 보기 ↗</a>
</p>

<br/>

## About Me

- **관심 분야** · 의료영상 AI, 헬스케어 소프트웨어, 데이터 기반 문제 해결
- **개발 경험** · 데이터 품질 검증 → 모델 실험·평가 → 추론 API → 결과 시각화 → 클라우드 연동
- **중요하게 생각하는 것** · 기술 선택의 근거, 재현 가능한 실험, 사용자가 확인할 수 있는 결과

<br/>

<a id="featured-project"></a>
## Featured Project

### BrainOn · 뇌혈관질환 AI 임상 의사결정 지원 시스템

> **의료영상 AI 분석 결과를 의료진의 진료 흐름으로 연결하는 4인 팀 프로젝트**

CT 뇌출혈, MRI 허혈성 병변, MRA 뇌동맥류 분석을 대상으로 모델 개발과 추론 서비스, 의료진 웹의 결과 조회 흐름을 연결했습니다. 팀 서비스에서 **의료영상 모델 실험, 추론 파이프라인, 분석 결과 화면 및 모델 관리 연동**을 중심으로 담당했습니다.

<table>
<tr>
<td width="50%" valign="top">
<h4>01 / Medical Imaging AI</h4>
<p>의료영상 데이터 품질 검증과 전처리<br/>nnU-Net · SegResNet 기반 분할 실험<br/>손실 함수 · 샘플링 · 입력 구조 비교</p>
</td>
<td width="50%" valign="top">
<h4>02 / Inference &amp; Serving</h4>
<p>FastAPI 기반 공통 추론 인터페이스<br/>Django · Celery 분석 요청 연동<br/>GCS 모델·결과 저장 및 Cloud Run 연동</p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<h4>03 / Interactive Viewer</h4>
<p>의료영상과 병변 마스크 시각화<br/>DWI / ADC 채널 전환 및 병변 정보 표시<br/>확률 맵 · XAI 결과 조회 연동</p>
</td>
<td width="50%" valign="top">
<h4>04 / Model Management</h4>
<p>MLflow 실험·모델 메타데이터 관리<br/>Registry와 관리자 화면 동기화<br/>모델 버전 조회와 운영 관리 흐름 연결</p>
</td>
</tr>
</table>

**[서비스 저장소 ↗](https://github.com/brainCDSS/BrainCDSS/tree/dev)** &nbsp; · &nbsp; **[의료영상 모델 실험 저장소 ↗](https://github.com/duddl6292/stroke-model)**

<sub>모델 실험과 서비스 코드는 같은 BrainOn 프로젝트의 구성 요소이며, 저장소를 분리하여 관리합니다.</sub>

<br/>

<a id="my-contribution"></a>
## My Contribution

| 영역 | 직접 수행한 작업 |
| :--- | :--- |
| **데이터 및 모델** | CT 데이터 품질 점검·전처리, 분할 모델 학습 및 평가, 작은 병변 검출 개선을 위한 손실 함수·샘플링 실험 |
| **추론 파이프라인** | 공통 입출력 계약, 모델 로딩, FastAPI 추론 API, Django·Celery 및 GCS 연동 |
| **분석 화면** | React 기반 AI 분석 결과 화면, 병변 정보·확률 맵·XAI 데이터와 의료영상 뷰어 연결 |
| **모델 운영 연동** | MLflow Tracking·Registry 연결, 모델 버전·실험 메타데이터 동기화, 관리자 ML 화면 구현 |

<br/>

<a id="tech-stack"></a>
## Tech Stack

<sub>BrainOn에서 직접 활용한 기술을 중심으로 정리했습니다.</sub>

| 분야 | 기술 |
| :--- | :--- |
| **Language** | Python · TypeScript · SQL |
| **AI & Data** | PyTorch · MONAI · nnU-Net · SegResNet · NumPy |
| **Backend & Async** | Django REST Framework · FastAPI · Celery · RabbitMQ · MOSEC |
| **Frontend** | React · Vite |
| **Database & Cloud** | PostgreSQL · Google Cloud Run · Cloud Storage |
| **Experiment & Tools** | MLflow · Docker · Git · GitHub |

<br/>

## Background

| 구분 | 내용 |
| :--- | :--- |
| **전공** | 기계공학 |
| **연구 경험** | MMM 연구실 학부연구생 · 자기장 에너지 하베스팅 연구 |
| **교육** | Biomedical AI 과정 · 2026.03–2026.09 |
| **자격증** | SQLD · ADsP |

<br/>

---

<p align="center">
  <strong>데이터에서 모델로, 모델에서 서비스로.</strong><br/>
  <sub>김호영 · Medical AI &amp; Healthcare Software</sub><br/><br/>
  <a href="https://github.com/duddl6292">GitHub @duddl6292</a>
</p>
