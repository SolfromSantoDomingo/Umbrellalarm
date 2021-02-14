# Umbrellalarm(우산알라미) Project

#### **기획의도**

매일 기상하고 아침에 정신없이 준비하는 직장인들은 우천시에도 우산을 잊어버리고 안 가져가는 일이 비일비재하다. 

따라서 어플리케이션이 오전/오후/시간대 설정을 통해 강수확률이 높을 시 매일 아침 설정한 시간에 Dialog를 통해 우산을 가져가라는 Alarm을 준다면 실생활에 도움이 될 것이다.



#### **구현 화면** 

A.   로딩 화면 : 우산알라미 로고

B.   메인 화면 : 현재 설정된 알람 리스트 보여주기

C.   프래그먼트 : 알람 시간대, 알람에 요구되는 강수확률 및 시간대 설정 화면

D.   푸시 화면 : 우천시 alarm으로 뜰 Dialog Push Alarm 화면



#### **구현 기능 – 프론트 엔드**

A.   로딩 화면

\-   Thread : 로딩 -> 메인화면으로 넘어가는 시간 설정(3초)

B.   메인 화면

1)  현재 설정된 알람 내역 보여주기

2)  알람 수정/삭제버튼

C.   프래그먼트

1)  푸시알람을 원하는 요일을 선택하시오(라디오 버튼) : 월~일

2)  푸시알람이 기능하는 시간을 선택하시오 : ‘시계모양 디자인 구현’

3)  원하는 강수확률 및 오전/오후를 선택하시오(라디오버튼?)

4)  뒤로가기 버튼 : ‘설정중인 알람을 취소하시겠습니까?’다이얼로그



#### **구현 기능 – 백엔드**

1)  두번 클릭 시 종료 기능

2)  푸시알람 기능

3)  GPS 설정 기능

4)  GPS에 따른 강수확률 측정

5)  기상청 API?

6)  Preference 로 알람 저장