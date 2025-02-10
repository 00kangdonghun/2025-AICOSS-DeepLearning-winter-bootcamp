# 2025-AICOSS-Deep-Learning-winter-boot-camp
다양한 객체를 포함한 fine-grained multi-class 이미지 분류 딥러닝 모델 개발

![image](https://github.com/user-attachments/assets/51ad8013-5af5-4783-a484-cf3395afe3d5)

# Overview
## 2025 산학협력 실습중심 딥러닝 겨울 부트캠프 경진대회 ##
주어진 테스트 데이터셋을 분류하여라!

`팀원 끼리 하나의 팀을 생성하여 제출해주시기 바랍니다. (팀명을 부트캠프동안 사용하신 팀명으로 부탁드립니다.`

- # 경진대회 안내(1차 평가)
1.  데이터셋: 다양한 객체를 포함한 fine-grained multi-class 이미지(총 300 classes)
2.  과제 기한: ***25.01.14(화) 오후 18:00***
3.  과제 제출 방법: sample_submission.csv를 다운 받은 후, 각 이미지의 예측 결과를 채워서 제출(페이지 좌측 상단의 Summit Prediction 버튼 이용)
4.  하루 제출 제한: 팀별 일 10회
5.  *** *Pretrained Model모델은 사용 금지(timm 혹은 torchvision을 이용하여 모델을 불러오는 것은 허용하나 반드시 pretrained weights를 사용하지는 말 것!)* ***
6.  외부 데이터를 사용하시면 안됩니다. (제공된 학습 데이터만을 활용할 것!)
7.  경진대회 1차 평가 상위 5팀(Private Score 상위 5팀)에 대해 2차 평가가 이루어집니다. 그 후 1차 평가와 2차 평가의 점수를 통해 수상자가 결정됩니다.
   
총장상 (₩300만 x 1팀)

공과대학장상 (₩240만 x 2팀)

인공지능혁신융합대학사업단장상 (₩200 x 2팀)

- # Description
# 데이터셋 설명
# 다양한 객체가 포함한 fine-grained multi-class 이미지를 분류하는 데이터셋
Train Dataset: 9,797장

Test Dataset: 4,178장
# 레이블 수: 300
각 이미지의 레이블은 새, 차 혹은 항공기 중 하나에 속하게 되며, 대회 참여자 여러분들인 이미지의 세부 label을 예측해주셔야 합니다. 

각 이미지의 label이 어느 대분류에 속하는지는 저희가 제공하는 `label_info.csv`파일에서 자세히 확인 가능하십니다.

- # Evaluation
# 1차 평가
1차 평가에서는 모델의 성능을 평가합니다.

모델의 성능 평가는 F1-Score를 통해 이루어집니다.

전체 데이터의 30%에 대한 결과는 경진대회 진행중에도 공개가 되어 리더보드(Public)에서 확인이 가능합니다.

남은 70%의 데이터에 대한 결과는 경진대회 제출 마감 후, 당일 저녁 22시에 리더보드(Private)가 공개가 됩니다.

`※ 순위는 Private 성능을 기준으로 정해집니다.`

# 2차 평가
1차 평가(Private Leaderboard)의 상위 5팀에 대해 25년 1월 17일(금) 오후 2시에 2차 평가를 실시합니다.

전체 점수는 Private Score 40%와 발표 평가 점수 60%로 계산됩니다.
