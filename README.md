# PineScript-TradingView-_algorithmTradingSauce
PineScript(TradingView)_TradingAlgorithm

- 트레이딩 뷰 플랫폼에서 제공하는 pineScript 언어로 작성한 가상자산(비트코인) 거래 알고리즘 작성
- poabot(트레이딩 봇) 오픈소스 활용 
- 파이썬 라이브러리를 활용하여 거래 데이터 시각화 및 수익률 분석


3rsi 전략

- 3개의 rsi를 사용하는 지표와 가격 변동 추세를 파악하는 지표인 adxr, ema 선을 활용하여 3가지 지표의 특정 조건이 발생했을 시 롱 포지션에 진입하는 전략.

![3rsi전략_pinescript](https://github.com/user-attachments/assets/fbb43fe4-74c8-4ed8-9ace-6fa6aa5fd61c)


1. 사용 중인 3rsi의 성과 오버뷰 화면

- 해당 전략의 순익, 승률, 수익 팩터, 최대 손실폭(mdd) 등을 보여줍니다. 
![3rsi전략_오버뷰](https://github.com/user-attachments/assets/7e4c4f71-9438-4290-bead-cef0a3fffb1b)

2. 사용 중인 3rsi의 성과 요약 화면

- 해당 전략과 관련된 순익, 총수익 및 손실, 샤프 비율 , 소티노 비율 등의 지표를 제공하여 전략의 성과 및 실현 가능성에 대해 판단할 수 있습니다. 
![3rsi전략_성과요약](https://github.com/user-attachments/assets/8829812b-1e3a-428e-9777-0054d6cf5610)

3. 3rsi 전략 포지션 진입 시그널
   
- pinescript를 통해 작성한 특정 조건이 발생할 경우, 진입 시그널 발생
![3rsi전략_시그널](https://github.com/user-attachments/assets/27341928-a7f9-456d-983d-56ff5e08e2f4)


5. 3rsi 전략 얼러트
   
- 진입 시그널 발생 시 해당 시그널을 거래소와 연동한 가성 서버로 전달하기 위해 트레이딩 뷰에서 제공하는 기능인 얼러트를 사용합니다.
![3rsi전략_얼러트](https://github.com/user-attachments/assets/d92cd826-e93c-40ff-922e-6282f95186b0)


7. 실제 거래소와 연동하여 매매를 진행하는 클라우드 서버 (vultr)
![3rsi전략_클라우드서버(vultr)](https://github.com/user-attachments/assets/4ae4144b-d625-499f-ae11-4ced86886d6b)
