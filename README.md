# 김호영 | AI Engineer

데이터 품질 검증부터 모델 실험·평가, 추론 결과의 서비스 연동까지 경험한 AI 엔지니어입니다. 기계공학 연구에서 데이터 분석을 시작해 AI 모델과 서비스 구현으로 범위를 넓혔습니다.

## 기술 스택

| 영역 | 사용 기술 |
| :--- | :--- |
| **모델·데이터** | Python, PyTorch, MONAI, nnU-Net, SegResNet, NumPy |
| **추론·백엔드** | FastAPI, Django REST Framework, Celery, RabbitMQ |
| **운영·제품** | MLflow, Docker, Cloud Run, GCS, PostgreSQL, React, TypeScript |

## 대표 프로젝트

### BrainOn — 의료영상 AI 기반 임상 의사결정 지원 시스템

4인 팀 프로젝트 · CT·MRI·MRA 영상 분석 모델과 의료진 웹 연동

**담당 역할:** 데이터 품질 검증, 분할 모델 실험·평가, 추론 파이프라인과 분석 결과 연동

- **데이터:** CT 영상과 마스크의 방향·간격·레이블을 검증하고 전처리 결과를 점검
- **모델:** nnU-Net·SegResNet의 입력, 손실 함수, 샘플링 설정을 실험하고 작은 병변의 검출과 오탐을 함께 평가
- **추론:** FastAPI 모델 로딩·추론 API를 Django·Celery 분석 요청 및 GCS 저장 흐름에 연결
- **결과·관리:** 뷰어의 병변 마스크·확률 맵·XAI 연동, MLflow 모델 정보의 관리자 화면 동기화

[프로젝트 기술 요약](docs/brainon-ai.md) · [모델 연구 저장소](https://github.com/brainCDSS/model) · [팀 서비스 저장소](https://github.com/brainCDSS/BrainCDSS/tree/dev)  
*팀 저장소 2곳은 접근 권한이 필요합니다.*

## 학력·교육
- 한밭대학교 - 기계공학과 (3.87/4.5)
- MMM 연구실 학부연구생 (자기장 에너지 하베스팅 연구 - 2024.03 - 2025.06)
- Biomedical AI 과정 (2026.03–2026.09)

## 수상 이력

- 수상 내용 정리 중

## 자격증

- SQLD
- ADsP
