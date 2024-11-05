# 🌐 소외열대질환 약 개발을 위한 GCN 기반 모델 연구
리슈만편모충증, 아프리카수면병을 중심으로

## 요약
리슈만편모충증과 아프리카수면병은 세계보건기구(WHO)가 선정한 주요 글로벌 부담 질병 목록에 등재된 소외열대질환으로, 전 세계적으로 수백만 명에게 영향을 미친다. 하지만 이러한 소외열대질환에 대한 상업적 관심은 매우 제한적이다. 최근 약물 발견 환경이 변화하고 있으나, 기존의 인공신경망(ANN) 모델 및 일반적인 기계학습 모델은 질병과 약물 간의 복잡한 상호작용을 제대로 반영하지 못하는 한계가 있다. 본 연구는 그래프 합성곱 네트워크(GCN) 모델을 통해 다양한 단백질과 분자 변수 간의 복잡한 상호작용을 학습하여, 소외열대질환의 DTI 예측에서 높은 정확도를 보이는 것을 목표로 한다. 데이터 불균형 문제를 해결하고 풀링된 임베딩 벡터를 활용하는 실험을 통해, GCN 모델이 DTI 예측 성능 향상에 도움을 줄 수 있음을 확인하였다.

## Abstract
Leishmaniasis and African sleeping sickness are neglected tropical diseases included in the World Health Organization (WHO)’s list of major global health burdens, affecting millions of people worldwide. However, there is very limited commercial interest in these neglected tropical diseases. Although recent advancements in drug discovery have changed, traditional Artificial Neural Network (ANN) models and general machine learning models fail to adequately capture the complex interactions between diseases and drugs. This study aims to achieve high accuracy in predicting drug-target interactions (DTI) for neglected tropical diseases by utilizing Graph Convolutional Network (GCN) models to learn the intricate interactions between various protein and molecular variables. By addressing data imbalance issues and utilizing pooled embedding vectors, our experiments demonstrated that the GCN model significantly improves DTI prediction performance. 

## Proposed Model Architecture
![image](https://github.com/hufsproject/SNA/assets/172377969/c764b3b1-746a-418e-8720-77eca28499cc)


## PubChem 데이터
- 리슈만편모충증 데이터: [PubChem AID 1721](https://pubchem.ncbi.nlm.nih.gov/bioassay/1721)
- 아프리카수면병 데이터: [PubChem AID 485367](https://pubchem.ncbi.nlm.nih.gov/bioassay/485367)
