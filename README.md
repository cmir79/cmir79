<div align="center">

![header](https://capsule-render.vercel.app/api?type=waving&color=0:11998e,100:38ef7d&height=220&section=header&text=KINTAEIN&fontSize=62&fontColor=ffffff&animation=fadeIn&desc=Machine%20Vision%20%C2%B7%20Industrial%20Automation%20%C2%B7%20.NET&descSize=20&descAlignY=76)

### 산업 현장의 눈이 되는 소프트웨어를 만듭니다 👋

산업 현장의 검사·제어 소프트웨어를 개발합니다.<br/>
카메라로 보고 판단하는 머신 비전이 주력이고, PLC와 대화하는 설비 제어 HMI까지 만듭니다.

</div>

## 🏭 하는 일

- **머신 비전 검사** — Cognex VisionPro · OpenCV 기반 검사 시스템 (주력)
- **설비 제어 HMI** — WPF · Avalonia 데스크톱 애플리케이션 설계/개발 (MVVM)
- **PLC 통신** — Mitsubishi MC 프로토콜, Modbus/TCP 실시간 폴링
- **레거시 전환** — WinForms · VB.NET(.NET Framework) 설비 프로그램 다수를 WPF로 전환
- **설비 시뮬레이션** — Unity 기반 장비 시뮬레이터

## 🛠 기술 스택

**Languages & Frameworks**

<img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge" alt="C#"/> <img src="https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt=".NET"/> <img src="https://img.shields.io/badge/VB.NET-945DB7?style=for-the-badge" alt="VB.NET"/> <img src="https://img.shields.io/badge/WPF-68217A?style=for-the-badge" alt="WPF"/> <img src="https://img.shields.io/badge/WinForms-0078D4?style=for-the-badge" alt="WinForms"/> <img src="https://img.shields.io/badge/Avalonia-8B44AC?style=for-the-badge" alt="Avalonia"/> <img src="https://img.shields.io/badge/HandyControl-426AB3?style=for-the-badge" alt="HandyControl"/> <img src="https://img.shields.io/badge/DevExpress-FF7200?style=for-the-badge" alt="DevExpress"/> <img src="https://img.shields.io/badge/Unity-000000?style=for-the-badge&logo=unity&logoColor=white" alt="Unity"/> <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>

**Vision & Industrial**

<img src="https://img.shields.io/badge/Cognex%20VisionPro-0E7490?style=for-the-badge" alt="Cognex VisionPro"/> <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" alt="OpenCV"/> <img src="https://img.shields.io/badge/Mitsubishi%20PLC%20%C2%B7%20MC%20Protocol-E60012?style=for-the-badge" alt="Mitsubishi PLC · MC Protocol"/> <img src="https://img.shields.io/badge/Modbus%2FTCP-1F6FEB?style=for-the-badge" alt="Modbus/TCP"/> <img src="https://img.shields.io/badge/Zebra%20ZPL%2FSGD-000000?style=for-the-badge" alt="Zebra ZPL/SGD"/>

**Backend & Data**

<img src="https://img.shields.io/badge/ASP.NET%20Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt="ASP.NET Core"/> <img src="https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white" alt="MariaDB"/> <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite"/>
**Tools**

<img src="https://img.shields.io/badge/Visual%20Studio-5C2D91?style=for-the-badge" alt="Visual Studio"/> <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git"/>

## 📦 오픈소스

**[GevSharp](https://github.com/cmir79/GevSharp)** — 벤더프리 GigE 카메라 취득 라이브러리 [![NuGet](https://img.shields.io/nuget/v/GevSharp?style=flat-square&logo=nuget&logoColor=white&label=NuGet&color=004880)](https://www.nuget.org/packages/GevSharp)<br/>
벤더 SDK·네이티브 의존 없이 순수 관리 C#으로 GVCP 장치 제어 · GVSP 스트리밍(패킷 리센드) · GenICam XML 피처 제어<br/>
`netstandard2.0` `netstandard2.1` `net8.0` `Apache-2.0`

## 🗂 산업 현장 프로젝트

### 자동차 부품 제조 설비

**가공 라인 설비 제어 HMI · 시뮬레이터**<br/>
설비 운전 제어와 공정 데이터 관리를 통합한 HMI 2종을 주 개발자로 구축, 동작 검증용 Unity 시뮬레이터 포함<br/>
`C#` `WPF(MVVM)` `Avalonia` `Unity` `MC 프로토콜` `SQLite`

**멀티 카메라 조립 검사 시스템**<br/>
부품별 조립 상태·각도를 다중 카메라로 검사, 규칙 기반으로 가르기 어려운 경계 사례는 자체 구현한 HOG+SVM 학습·추론으로 병행 판정<br/>
`C#` `OpenCvSharp` `Cognex VisionPro` `HOG+SVM` `SQLite`

**검사 · 생산시점관리(POP) 통합**<br/>
부품 유무·컬러 판별에 ONNX 딥러닝 모델을 적용하고, 판정 결과를 생산시점관리와 하나의 흐름으로 연결. 프로그램 간 통신은 HTTP API, 실적·이력은 DB에 적재<br/>
`C#` `WPF` `DevExpress` `ONNX Runtime` `ASP.NET Core` `MariaDB`

**소재 방향 · 선단 위치 판별 비전**<br/>
가공 전 소재의 방향과 선단 위치를 비전으로 판별해 설비에 전달<br/>
`C#` `WPF` `WinForms` `Cognex VisionPro`

**성형 형상 측정 비전**<br/>
성형 후 형상·각도를 비전으로 측정해 합불 판정<br/>
`C#` `WinForms` `Cognex VisionPro` `OpenCvSharp`

**마킹 · 생산 이력 추적**<br/>
산업용 라벨 프린터를 직접 제어해 라벨·QR 마킹과 이력 기록을 연동한 시스템 2종<br/>
`VB.NET` `ZPL/SGD` `이력 추적`

**사내 공용 설비 소프트웨어 기반 구조**<br/>
여러 설비 프로그램이 공유하는 기반 라이브러리를 설계·유지 — PLC·카메라 등 장치 접근을 인터페이스로 추상화해 설비별 구현과 분리<br/>
`C#` `WPF` `포트-어댑터` `아키텍처 설계`

**레거시 설비 프로그램 유지 · 전환**<br/>
C++·VB.NET으로 작성된 기존 설비 프로그램을 운영하며 유지보수하고, 비전 검사 프로그램은 C#으로 포팅<br/>
`C++` `VB.NET` `WinForms` `DevExpress`

### 반도체·전자 조립 장비

**레이저 공정 장비 비전 소프트웨어**<br/>
마킹·드릴링·어블레이션 장비의 정렬용·검사용 비전을 개발<br/>
`C#` `WinForms` `Cognex VisionPro` `머신 비전`

**조립·가공 장비 제어 소프트웨어**<br/>
픽앤플레이스·솔더볼 어태치·절단 장비의 제어 소프트웨어 개발, 대형 통합 장비 프로그램의 초기 아키텍처 설계<br/>
`C#` `WinForms` `장비 제어` `아키텍처 설계`

## 🌱 탐구 중

- **AI · 딥러닝** — 머신 비전 검사에 접목하는 것이 목표

## 📫 연락처

[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:cmir79ss@gmail.com) [![Naver Mail](https://img.shields.io/badge/Naver%20Mail-03C75A?style=for-the-badge&logo=naver&logoColor=white)](mailto:cmir79@naver.com)

![footer](https://capsule-render.vercel.app/api?type=waving&color=0:11998e,100:38ef7d&height=100&section=footer)
