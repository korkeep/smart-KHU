# KHU-Network
<img title="Architecture" alt="Overall" src="https://github.com/korkeep/PacketTracer/blob/master/Architecture/Overall.PNG" width="800"/>

경희대학교 국제캠퍼스가 하나의 큰 네트워크가 되는 'KHU-Network'프로젝트입니다. 네트워크는 ▲기숙사(제2기숙사, 우정원) ▲단과대(소프트웨어융합대학) ▲주차장(차고지 옆) ▲스마트팜(생명과학대학 연구동)으로, 4개의 클러스터로 구분했습니다. 프로젝트를 제작하기 위해 Cisco에서 제공하는 [Packet Tracer](https://www.netacad.com/portal//resources/packet-tracer) 툴을 이용했습니다.

## Smart Dormitory
<img title="Architecture" alt="Dormitory" src="https://github.com/korkeep/PacketTracer/blob/master/Architecture/Dormitory.PNG" width="600"/>

### 제공 기능
- 서버: AAA 보안
- DNS: dorm.khu.ac.kr
- 전등: 태양광 발전 이용
- 온도 조절: 서버에서 자동 제어
- 화재 감지: MCU 이용
- Wi-Fi: 각 호실마다 무선 라우터 연결

## Smart Department
<img title="Architecture" alt="Department" src="https://github.com/korkeep/PacketTracer/blob/master/Architecture/Department.PNG" width="600"/>

### 제공 기능
- 서버: AAA 보안
- DNS: software.khu.ac.kr
- 온도 조절: 서버에서 자동 제어
- 화재 감지: MCU 이용
- Wi-Fi: 각 층마다 무선 라우터 연결

## Smart Parking System
<img title="Architecture" alt="Parking" src="https://github.com/korkeep/PacketTracer/blob/master/Architecture/Parking.PNG" width="600"/>

### 제공 기능
- 서버: AAA 보안
- DNS: park.khu.ac.kr
- 주차 감지: MCU 이용
- CCTV: 서버에서 On, Off 기능

## Smart Farm
<img title="Architecture" alt="Farm" src="https://github.com/korkeep/PacketTracer/blob/master/Architecture/Farm.PNG" width="600"/>

### 제공 기능
- 서버: AAA 보안
- DNS: farm.khu.ac.kr
- 온도 조절: 서버에서 자동 제어
- 스프링클러: 서버에서 자동 제어
- 화재 감지: MCU 이용
- CCTV: 서버에서 On, Off 기능
- Cluster: 표고버섯, 애플수박, 상추