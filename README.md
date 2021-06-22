<div align="center"><img src="https://user-images.githubusercontent.com/77145383/122884593-465dfb80-d379-11eb-89ae-c42852185212.png"></div>

<h1 align="center">DC 스마트 그리드 시스템</h1>

><p align="center"><i>2021-1 세종대학교 캡스톤 프로젝트<br>2021 세종대학교 창의설계경진대회 최우수상</i></p>

# Contributor
- 팀장 - [서지상](https://github.com/dovigod)
- 팀원 - [장현희](https://github.com/Huey-J)
- 팀원 - [박찬영](https://github.com/U-WangE)
- 팀원 - [조성우](https://github.com/whtjtjddn)
- 지도교수 - [양효식](http://home.sejong.ac.kr/~hsyang) (세종대학교 컴퓨터공학)
- 지도교수 - [이수정](http://home.sejong.ac.kr/~soojeonglee) (세종대학교 컴퓨터공학)

# Description
&nbsp;현재 전력 소비는 IT기기, LED조명, 디스플레이 기기 등 고밀도 DC전력을 중심으로 이루어지고 있다. DC는 특성상 송전 자체의 효율성이 AC보다 높고, 전압 변경기술의 발전으로 인해 DC의 단점이던 원거리 송전 부문에서도 DC의 우월성을 인정받고 있다. 하지만 우리나라는 현재 교류(AC)를 기반으로 한 전력 시스템을 사용하고 있어 **직류(DC)를 기반으로 한 전력 시스템으로 바꿀 필요**성이 있다. 또한, 전력 소비의 증가로 공급량을 맞추기 위해 많은 발전소가 지어지고 있는데, 현재 지어지고 있는 발전소들은 탄소 배출량이 많은 화석 연료를 사용하거나, 위험성이 높은 원자력 발전소 등을 사용하여 환경 오염 및 안전성 등에 대한 우려가 커지고 있다. 이러한 환경 오염 문제와 전력 부족 현상을 최소화하기 위해서는 현재의 **중앙집중형 에너지 분배 시스템을 개선할 필요**가 있다고 생각했다. 이에 우리는 공적으로 생산되고 있던 전기에너지를 **신재생 에너지를 활용하여 개개인이 생산**함으로써 발전소의 필요성을 낮춘다면, 공적 전력 소비를 줄일 수 있게 되고, 환경오염 문제 등에 대한 해결책이 될 수 있을 것이다.

&nbsp;우리는 앞의 결론에 의해 도출된 방안으로 DC 스마트 그리드 홈 네트워크 시스템을 개발하였다. 이는 기존의 AC-DC변환으로 인한 전력 손실을 DC-DC형태의 전력망으로 변경함으로써 에너지 효율을 2~10%정도 증가시킬 수 있을 것이고, 기존의 단방향 전력망에서 양방향 전송이 가능하게 하여 에너지 효율을 더욱 개선할 수 있다. 우리는 사용자의 접근성과 효과적인 전력 관리를 위해 웹 기반의 스마트 홈 기능을 적용하여 홈 네트워크에 연결된 **전자기기의 전원(On/Off)을 원격으로 제어**할 수 있고, **현재 사용하고 있는 전력량, 배터리의 잔량, 생산하고 있는 전력에 대한 정보를 제공**하여 사용자가 효율적으로 전력을 관리할 수 있도록 도왔다. 또한, 소규모 홈 네트워크 그룹을 구성하여 그룹 간의 자급자족 네트워크를 구성하여 **p2p 전력 거래**를 가능하게 하였다. 이러한 기능들은 사용자가 자신의 전력 상황을 빠르게 파악하고 관리할 수 있게 돕고, 이를 통하여 거래할 수 있게 함으로 전력의 과소비를 줄이는 효과와 개개인의 전력을 거래함으로써 잉여 전력의 낭비를 줄이는 효과를 기대할 수 있다.

# Environment
### Hardware
Arduino Uno (R3) 5V

### Software
node v14.15.4
npm 6.14.10
mongo DB v4.4

### Install
```
npm install
```
\+ Mongo DB 설치 필요 -> [https://www.mongodb.com/try/download/community](https://www.mongodb.com/try/download/community)

### Using
```
npm run dev:assetW	// window일 경우
npm run dev:assets	// mac일 경우
npm run dev:server
```
\+ 이메일 관련 기능은 따로 설정해야 함 (아이디, 비밀번호 등)

# Features

![하드웨어 완성](https://user-images.githubusercontent.com/77145383/122895659-4b27ad00-d383-11eb-8db0-76ec2fe08665.jpg)

### 1. 원격 기기 제어 (On/Off)

### 2. 전력 확인

### 3. P2P 전력거래

### 4. 기타 기능
#### 날씨 기능

#### 회원가입, 로그인, 로그아웃

#### 회원정보 수정


Give a ⭐️ if this project helped you!
