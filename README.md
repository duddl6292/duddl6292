# 김호영 | AI Engineer

데이터를 검증하고 모델을 실험·평가한 뒤, 추론 결과를 서비스에서 사용할 수 있도록 연결하는 데 관심이 있습니다. 기계공학 연구에서 데이터 분석을 시작해 AI 모델 개발과 서비스 구현으로 경험을 넓혀왔습니다.

## 기술 스택

| 영역 | 사용 기술 |
| :--- | :--- |
| **모델·데이터** | Python, PyTorch, MONAI, nnU-Net, SegResNet, NumPy |
| **추론·백엔드** | FastAPI, Django REST Framework, Celery, RabbitMQ |
| **운영·제품** | MLflow, Docker, Cloud Run, GCS, PostgreSQL, React, TypeScript |

## 대표 프로젝트

### BrainOn — 의료영상 AI 기반 임상 의사결정 지원 시스템

4인 팀에서 CT·MRI·MRA 영상 분석 모델과 의료진 웹을 연결한 프로젝트입니다. 저는 **데이터 품질 검증, 분할 모델 실험·평가, 추론 파이프라인, 분석 결과 화면 연동**을 중심으로 작업했습니다.

- **데이터 검증:** CT 영상의 방향·간격·레이블을 점검하고 전처리 기준을 정리했습니다.
- **모델 실험·평가:** nnU-Net과 SegResNet의 손실 함수·샘플링·입력 구성을 비교하고, Dice·Recall·Precision과 작은 병변 성능을 분석했습니다.
- **추론 연동:** 모델 로딩과 FastAPI 추론 API를 Django·Celery·GCS 흐름에 연결하고, 뷰어에서 병변 마스크·확률 맵·XAI 결과를 확인하도록 연동했습니다.
- **모델 관리:** MLflow 모델 정보를 관리자 화면과 연결하는 작업에 참여했습니다.

**자세히 보기:** [BrainOn AI 기술 요약](docs/brainon-ai.md) · [모델 연구 저장소](https://github.com/brainCDSS/model) · [팀 서비스 저장소](https://github.com/brainCDSS/BrainCDSS/tree/dev) (두 팀 저장소는 접근 권한 필요)

[초기 추론 API 시제품](https://github.com/duddl6292/stroke-model)은 별도로 공개했습니다. 최종 모델 실험 코드는 이 시제품에 포함되어 있지 않습니다.

## 배경

- 기계공학 전공 · MMM 연구실 학부연구생 (자기장 에너지 하베스팅 연구)
- Biomedical AI 과정 (2026.03–2026.09)
- SQLD · ADsP
