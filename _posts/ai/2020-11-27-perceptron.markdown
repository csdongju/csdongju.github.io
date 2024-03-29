---
layout: post
title:  "Perceptron 퍼셉트론"
date:   2020-11-27 00:00:00 +0530
categories: Deep learning Basics
tags: perceptron
---
- 프랑크 로젠 블라트가 1957년에 고안한 알고리즘

- 다수의 입력, 하나의 출력

- 뉴런에서 보내온 신호의 총합이 **정해진 한계**를 넘어설 때, 1을 출력

  - 이를 **뉴런이 활성화** 한다 라 표현하기도 한다.

- 퍼셉트론에서 매개 변수 값을 정하는 것은 컴퓨터가 아니라 **인간**이다.

- 기계학습 문제는 이 매개변수의 값을 정하는 작업을 컴퓨터가 자동으로 하도록 함

- **학습** 이란 적절한 매개변수 값을 정하는 작업 

- 사람은 퍼센트론의 구조(모델)을 고민하고 컴퓨터에 학습할 데이터를 주는 일이다.

  > 똑같은 구조의 퍼셉트론은 매개변수의 값만 적절히 조정하면 AND, NAND, OR로 변신 하는 것이다.

- 편향의 도입

  - 임계값(theta|세타): ***𝞱***

  - 편향(bias|바이어스): ***b***

  - 임계값과 편향과의 관계

    > 𝞱 = - ***b***



### References

- 밑바닥부터 시작하는 딥러닝, 한빛미디어