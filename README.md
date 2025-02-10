# AIFFEL-DLThon

## AIFFEL-DLThon??
  - AIFFEL 과정중 진행한 데이터톤(Datathon)을 의미
  - 총 6일간 진행(24.10.02~24.10.07)
  - 자세한 정보는 아래 이미지를 참조 
![image](https://github.com/user-attachments/assets/c2f375eb-40b6-4b7b-9dec-adab8fd00fdc)
![image](https://github.com/user-attachments/assets/3a2240e4-f036-4027-91d2-5b1f799fa587)

## 기여
  - 데이터톤 과정중 저는 사전 훈련 모델 선택, Wandb을 통한 사전 훈련 모델 Fine-tuning 및 Label 예측에 기여했습니다.

### 사전 훈련 모델 선택
  - 데이터셋이 한국말로 되어 있는 관계로 한국어 사전 훈련 모델 선택
    - klue-bert
    - KoELECTRA
  - 각 모델의 F1-score를 비교해 최종적으로 klue-bert 모델 선택

### Fine-tuning
  - Wandb를 사용한 하이퍼파리미터 튜닝
![image](https://github.com/user-attachments/assets/364c5698-de55-4691-ad27-c4bacfde0033)

## Leaderboard 순위
![image](https://github.com/user-attachments/assets/3109c422-4364-4d94-9c2f-000384ee4ccb)
  - 6개팀 중 3위로 마무리
