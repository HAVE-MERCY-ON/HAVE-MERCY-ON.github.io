---
title : "2020-08-29 Study"
date : 2020-08-29 00:25:00 -0400
categories : Neural_Networks 최적화
---

Part 3
=============

## Regularization

#### Overfitting 해결을 위한 Regurlatization

통상적으로 ML, 통계적 추론 시에 Loss function 이 작아지는 쪽으로 진행하는데,
단순히 Loss 가 줄어드는 쪽으로 진행하다보면, 특정 가중치(w) 값들이 커지면서 오히려 결과를 나쁘게 한다.

아래는 regularization 을 통해서, 더 좋은 학습 결과를 가져오는 경우이다.

![image](https://user-images.githubusercontent.com/55482748/91588651-76c04d80-e993-11ea-988c-727e7321f2da.png)

그림(a) 에서 첫 빨간색 그래프의 경우 3차식이기에, 2차 그래프인 파란색 그래프보다 하나의 가중치(w)가 더 존재한다고 생각할 수 있는데, 정규화를 통해 하나를 줄였다고 생각하면 될 듯 하다.

#### L2 Regularization 의 수식


![image](https://user-images.githubusercontent.com/55482748/91587975-74a9bf00-e992-11ea-9494-a22997056ae9.png)

식은 위와 같고,




참고 사이트 : <https://blog.naver.com/laonple/220522735677>
