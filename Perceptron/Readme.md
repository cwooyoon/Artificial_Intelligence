# Perceptron

## Youtube
* How Your Nervous System Works & Changes | Huberman Lab Podcast
  - https://www.youtube.com/watch?v=H-XfCl-HpRM
  
  
## 개요

출처: 모두의딥러닝(조태호 저)

<img src="https://user-images.githubusercontent.com/54765256/90967431-2d4aab00-e51a-11ea-81b9-783cc25109da.png">

인간의 뇌는 치밀하게 연결된 약 1,000억 개의 뉴런으로 이루어져 있다. 
뉴런과 뉴런 사이에는 시냅스라는 연결 부위가 있는데,
신경 말단에서 자극을 받으면 시냅스에서 화학물질이 나와 전위 변화를 일으킨다.
전위가 임계값을 넘으면 다음 뉴런으로 신호를 전달하고, 임계값에 미치지 못하면 아무것도 하지 않는다.
이 메커니즘은 로지스틱 회귀와 유사하다.

<img src="https://user-images.githubusercontent.com/54765256/90967473-bc57c300-e51a-11ea-938a-278fc326a842.png">

신경망을 이루는 가장 중요한 기본 단위는 퍼셉트론(perceptron), 
퍼셉트론은 입력 값과 활성화 함수를 사용해 출력 값을 다음으로 넘기는 가장 작은 신경망 단위

