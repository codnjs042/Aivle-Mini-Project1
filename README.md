# Aivle-Mini-Project1

### 프로젝트 개요
이 프로젝트는 53가지의 답변이 가능한 챗봇을 구축하는 것을 목표로 합니다.  
챗봇은 일상대화 30가지와 에이블스쿨 관련 23가지 답변을 제공할 수 있습니다.

### 최종 모델 개발 과정

#### 전처리
- **맞춤법 검사:** Daum 사전 맞춤법 검사
- **토큰화:** Okt
- **추가 전처리:** 어간 추출, 정규화, 불용어 제거

#### 모델 학습
- **단어 임베딩:** Keras Embedding
- **시퀀스 패딩:** 
- **모델:** LSTM 딥러닝 모델

### 성능
최종 모델은 **정확도 84%** 를 달성했습니다.  

[![image](https://github.com/codnjs042/Aivle-Mini-Project1/assets/73993796/c43eb749-da5c-4d14-bd64-77d3705e5e58)](https://github.com/codnjs042/Aivle-Mini-Project1/blob/main/4%EA%B8%B0_3.%20Aivle%20%EC%8A%A4%EC%BF%A8%20%EC%A7%80%EC%9B%90%20%EC%A7%88%EB%AC%B8%2C%20%EB%8B%B5%EB%B3%80%20%EC%B1%97%EB%B4%87%20%EB%A7%8C%EB%93%A4%EA%B8%B0_%EB%AA%A8%EB%8D%B8%EB%A7%81.ipynb)

