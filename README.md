# 객체 탐지 및 이미지 분할 모델을 이용한 와이어 로프 이상 탐지
> KDBC 2024_객체 탐지 및 이미지 분할 모델을 이용한  와이어 로프 이상 탐지
---

#### 📖 개요
이 프로젝트는 YOLOv8와 이미지 세그멘테이션 모델 **SAM(Segment Anything Model)** 을 결합하여 와이어 로프 이상 탐지를 수행합니다. 와이어 로프의 손상을 조기에 감지하여 안전사고를 예방하는 데 기여합니다.

#### 📌 주요 내용
- 모델: YOLOv8, SAM
- 데이터셋: 3,500장의 와이어 로프 이상 이미지
  - 결함 유형:
  - Break (단선)
  - Thunderbolt (낙뢰 손상)
  - Wear (마모)
- 성과:
- YOLOv8: 객체 바운딩 박스 생성.
- SAM: 정밀한 객체 경계 분할.  

- Workflow
<img src="https://github.com/user-attachments/assets/6a69cae0-ee20-4a8e-9199-abb33b4857b5" width="300" height="200">


#### 🛠️ 활용 사례
- 엘리베이터 및 케이블카 와이어 로프 모니터링
- 산업 현장의 실시간 로프 상태 감지

#### ✔︎ 결과
- YOLOv8 + SAM  
<img src="https://github.com/user-attachments/assets/b938bc6e-0607-40e9-8cff-f8b5524ce58d" width="400" height="500">

- XAI : Grad-CAM  
<img src="https://github.com/user-attachments/assets/13bba9b0-d284-4591-be5d-822ea0b3aeac" width="400" height="300">

