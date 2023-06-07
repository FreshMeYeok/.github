## Be CareFULL : 차량 블랙박스 영상을 통한 경량 Optical LSTM 기반 교통위험 탐지 서비스

## 1. 연구 배경 및 목표
자동차 수의 증가와 함께, 자동차 회사에서는 안전 관련 문제가 생겨나게 되었다. 이를 해결하고자 자동차 회사에선느 ADAS를 도입하였다. 그러나, ADAS의 Lidar와 같은 고비용의 외부센서는 자동차 회사의 입장에서 가격 경쟁력 확보에 어려움을 준다. 또한, 부품 교체 시 사용자 입장에서도 부담이 되는 편이다.
본 팀에서는 블랙박스를 이용하여 운전자에게 교통 위험정도를 알려주고자 한다.

블랙박스(웹 캠)와 Edge Device(Jetson Orin Nano), 스마트폰의 상호작용을 통해 운전자에게 교통 위험을 알려주는 서비스 개발을 목표로 한다.

## 2. System Architecture
![image](https://github.com/FreshMeYeok/.github/assets/39149858/365adb9a-0fd9-40aa-977a-4368051dba6a)


## 3. Model 구조
![image](https://github.com/FreshMeYeok/.github/assets/39149858/f3a4668e-ab5b-4a2b-8cd5-348178ae4ef7)


## 4. Be CareFULL 웹 페이지
### 4.1. 영상 업로드를 통한 Demo
![image](https://github.com/FreshMeYeok/.github/assets/39149858/1a5971b9-16a5-4e0a-904c-243024d272c1)
### 4.2. 실시간 블랙박스 영상 Demo (현재로서는 구현 중으로, 위험도 측정값은 랜덤값으로 대체)
![image](https://github.com/FreshMeYeok/.github/assets/39149858/262e0bcf-bf70-4ad2-9494-7ada6d8fadab)



## 4. Demo 및 발표 영상
[데모 영상 Youtube 링크](https://youtu.be/JEbsMDw48QM)
