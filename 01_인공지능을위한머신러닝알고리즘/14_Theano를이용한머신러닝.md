

# ﻿﻿[Tacademy] 인공지능을 위한 머신러닝 알고리즘 - 14강 Theano를 통한 머신러닝 구현



## **# Theano**

**※ Theano란?**

  · Python 기반 오픈소스 패키지

  · 장점 : 간결하고 빠른 모델 구현 가능, Symbolic 미분 가능(따라서 역전파 등을 직접 구현할 필요가 없음), 동일한 코드로 CPU&GPU 모두 가능, 파이썬 패키지와 연동 가능

  · 단점 : 복잡하고 알기 어려운 에러 메시지



**※ Theano로 GPU 프로그래밍** 

  · shared 변수 : 데이터를 RAM에서 GUP의 VRAP으로 옮기는 명령어

  · givens 변수 : symbolic 변수에 shared 데이터를 대입

  · updates 변수 : GPU 연산 결과를 이용해 shared 데이터를 수정