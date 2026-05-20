# lab-server-status

[KimHands/lab-server](https://github.com/KimHands/lab-server) 서버의 public 상태 뱃지 저장소.

서버의 cron이 5분마다 Beszel API를 polling해서 shields.io endpoint 형식 JSON을 push.
실제 운영 코드(스크립트/compose)는 메인 repo에 있음.

![status](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/KimHands/lab-server-status/main/status.json)
![cpu](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/KimHands/lab-server-status/main/cpu.json)
![ram](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/KimHands/lab-server-status/main/ram.json)
![disk](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/KimHands/lab-server-status/main/disk.json)
![uptime](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/KimHands/lab-server-status/main/uptime.json)
![containers](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/KimHands/lab-server-status/main/containers.json)
