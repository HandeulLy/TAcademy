

# ﻿﻿[Tacademy] 인공지능을 위한 머신러닝 알고리즘 - 15강 Keras를 통한 딥러닝 구현 및 실습



## **# Keras**

**※ Keras의 특징**

  · 모델의 층들과 그것들의 입력과 출력으로부터 기본 아이디어가 시작

  · 입력 출력 데이터를 준비하고, 입력 데이터에 맞게 첫 번째 층을 생성

  · 입력 층과 출력 층 사이에 원하는 레이어를 생성

  · 출력 데이터에 맞게 마지막 층을 설정



**※ 층(Layer)**

  · Keras는 미리 구현되어 있는 다양한 층을 제공

  · Dense : 다층 퍼셉트론에서 사용되는 층, fully-connected 사이의 가중치 값을 결정

  · Reccurent, LSTM, GRU 등



**※ 활성 함수**

  · 간단한 모형 : Sigmoid, tanh, ReLu, softplus, hard_sigmoid, linear

  · 복잡한 모형 : LeakyReLu, PReLu, ELU, Parametric Softplus, Thresholded linear, Thresholded ReLu



**※ 목표 함수**

  · 에러 측정용 : rmse, mse, mae, mape, msle

  · 최대 마진 : squared_hinge, hinge

  · 분류용 : binary_crossentropy, categorical_crossentropy



**※ 모델 종류**

  · Sequential : 층을 Stack으로 쌓은 구조, CNN과 RNN과 같은 모델, 각 층은 다음 층에 입력 값을 제공해주는 객체 역할을 수행

  · Graph : 두 개 이상의 서로 다른 모델이 합쳐지거나 여러 모델러 나뉘어질 수 있음, 다양한 개수의 입력과 출력 가능, Sequential 보다 자유도가 높음



**※ Keras의 장/단점**

  · 장점 : 쉬운 모델 구현, 다양한 함수 제공, 커스터마이징 가능, GPU 활용 가능, 직관적 함수 제공, 커뮤니티

  · 단점 : 생성 모델의 부족, 라이브러리 난이도, Theano 사용에 따른 에러 분석이 어려움