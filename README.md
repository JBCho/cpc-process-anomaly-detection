<h1>2-Stage Anomaly Detection for Fault Detection in Counter Pressure Casting (CPC) Process</h1>
Presented in INFORMS 2023, 'Data-driven Fault Detection for Counter Pressure Casting Process'.

<h2>개발 내용</h2>
CPC(Counter Pressure Casting, 차압주조) 공정은 챔버압력과 용광로압력의 차이를 이용해 액체 상태의 금속을 형성하는 주조 공법

![image](https://github.com/user-attachments/assets/ae59a32f-c04a-409d-9297-ee9ec9f471fd)

제안하는 2-stage AD 네트워크는 CPC 설비의 신호를 딥 러닝 네트워크를 이용해 분석, 정상 상태와 비가동 상태를 구분한 후 비가동 원인을 추정하여 설비 이상이 아닌 비가동 상태(설비 정지, 교체, 설비 세팅 값 변동 등)와 설비 이상으로 인한 비가동 상태(몰드 파손, 누수 등)를 구분
![image](https://github.com/user-attachments/assets/568238c5-5a23-4bd5-8456-d9984d50c4a8)

제안하는 방법은 일반적인 single-stage method보다 CPC 설비 이상 감지에 높은 성능을 보임
![image](https://github.com/user-attachments/assets/3404da6b-df91-487a-aa97-0d6f64002871)

이상 지수 시각화
![image](https://github.com/user-attachments/assets/8c3af1e4-74c5-4edc-8f45-ea9344adcf35)



<h2>파일 설명</h2>

- Preprocessor.ipynb: 데이터 전처리

- AnomalyDetection.ipynb: AD 모델 정의 및 학습

- Two-Stage Inference.ipynb: 2-stage AD 추론 및 평가
