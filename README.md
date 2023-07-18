# 🔭 아두이노 공기청정기
<div  align="center">

</div>
</br>
<h3 align="center">순환팬을 추가한 공기청정기 </h3> </br>
프로젝트명 : 아두이노 공기청정기</br>
프로젝트 소개 : 일반적인 공기청정기 상단에 상하좌우로 회전 가능한 팬을 추가한 제품</br>
프로젝트 기간 : 2022.04.20 - 2022.06.20</br>
공기청정기_설명서: https://drive.google.com/file/d/1L-VduW9BoMmlhmltkXlyI_Odiu6Gfo8c/view?usp=drive_link
</br>


### 🤔 프로젝트 설명
<div>
외관의 경우는 가공이 용이하면서 튼튼한 0.5cm 포맥스 사용(외관은 시트지로 마무리)</br>
외부 커버, 1차필터, 2차필터로 제작하여 외부의 경우 레이저 커팅기 사용</br>
모든커버는 분리 가능</br>
쿨러는 컴퓨터 시스템팬을 사용하였고 투명팬 뒷쪽에 네오픽셀을 사용하여 미세먼지수준을 직관적으로 표시</br>
상단 송풍팬의 경우 서보모터 2개를 사용하여 각 상하, 좌우를 담당</br>
12v 어뎁터를 사용하여 12v 쿨러2개 작동 및 서보모터 전원공급</br>
(서보모터 아두이노에서 직접 전압공급 가능하지만 2개 작동시 아두이노가 꺼지는 문제 발생)</br>
전압 강하모듈로 아두이노에 7v 로 강하하여 공급(12v도 가능하지만 지속 작동시 과열로 인하여 전압강하)</br>
미세먼지 센서는 pms7003 사용하였고 각 0~30, 30~80, 80~150, 150~900 으로 4단계로 나누어둔 값에 해당하면 </br>
네오픽셀에서 각 파랑, 초록, 주황, 빨강으로 점등. 
  lcd에서도 [ :-), :-|, :-\, :-( ] 등의 표정 이모티콘을 넣어 미세먼지 수치에 따른 직관성을 높임</br>

###  문제점
서보모터가 버벅이는 현상이 있는데 여러 수정결과 pwm 쿨러를 사용해서 쿨러의 속도를 </br>
  pwm신호로 조절하는데 이 pwm신호로 인하여 서보모터가 부드럽지 않은 현상이 발생하는것으로 결론
</div>
</br>





| 필터 분리 | lcd 표시 | 작동모습 |
| --- | --- | --- | 
| <img src = "https://github.com/sodalitz/arduino/assets/131415789/92a789ca-4790-48a0-9041-4762e80aa695"  width="200px" height="200"></a>  | <img src = "https://github.com/sodalitz/arduino/assets/131415789/80ba6a16-2a43-4540-aeca-f19816062933"  width="200px" height="200"></a>  | <img src = "https://github.com/sodalitz/arduino/assets/131415789/ee1bd25b-db58-48a9-81a5-9f082b10e214"  width="200px" height="200"></a>  | 


| 아두이노 코드 | 아두이노 코드 |
| --- | --- | 
| <img src = "https://github.com/sodalitz/arduino/assets/131415789/76725257-b840-478c-9636-9da4a598bf42"  width="500px" height="500"></a>  | <img src = "https://github.com/sodalitz/arduino/assets/131415789/35500a7d-4cc5-4cd7-a2df-6d3ed903c198"  width="500px" height="500"></a>  | 


| 아두이노 코드 | 아두이노 코드 |
| --- | --- | 
| <img src = "https://github.com/sodalitz/arduino/assets/131415789/78fee956-4a57-4262-a80a-9d9a1e47730c" width="500px" height="500"></a>  | <img src = "https://github.com/sodalitz/arduino/assets/131415789/d2f66555-1072-4dd8-892e-4def9d22e47e"  width="500px" height="500"></a>  | 


<br />




</br>
