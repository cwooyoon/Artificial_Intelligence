# Linear Algebra for AI

## References
* 프로그래머를 위한 선형대수(키즈유키)
  - www.gilbut.com/gilbut/006802
  - https://audioclip.naver.com/channels/196
  
## Generals
* 행렬은 사상(map)이다.
  - m x n 행렬 A에는 n차원 공간에서 m차원 공간으로의 mapping이다.
    - n 차원 공간의 점 x(n차원의 종벡터)를 m차원 공간의 점(m차원 종벡터) Ax 로 옮기는 사상이다.

* 우리는 3차원 공간에 살고있다.
  - 3차원 세계의 일을 다루기 위해서는 '공간'을 잘 기술할 수 있는 용어가 필요하다.
  - 벡터공간: 현실 공간의 성질을 특정 수준에서 추산화한 것
    - 3차원 공간 --> 2차원 평면

* 직선으로의 근사 수단
  - vector: 화살표 또는 공간 안의 점
  - Matrix: 공간에서 공간으로의 직교 사상
  - 행렬식: 위의 사상에 따른 부피 확대율
  
## Vector
* 선형공간 or 벡터공간: 덧셈과 정수배가 정의된 세계
  - 우리가 사는 현실공간의 어느 측면을 어느 수준에서 추상화한것
  - 이 세계에서는 영벡터만 측별하고, 그 외에는 어느 화살표도 대등하다.
  - 적용되는 것은 덧셈과 정수배 뿐
  - 뭐든지 직선이다.
  - 길이나 각도가 정의되어 있지 않다.
  - 다른 방향의 벡터끼리 대소를 비교하는 방법은 없다.
  - 회전(길이를 유지하면서 방향을 바꾸는)이라는 작업도 정의할 수 없다.


