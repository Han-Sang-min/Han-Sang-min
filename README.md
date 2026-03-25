<div align="center">

<!-- Header Banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1a2e,50:16213e,100:0f3460&height=230&section=header&text=Han%20Sang-min&fontSize=45&fontColor=16c79a&fontAlignY=35&desc=Systems%20%7C%20Embedded%20%7C%20Infrastructure&descSize=18&descColor=cccccc&descAlignY=55&animation=fadeIn" width="100%" />

<!-- Typing Animation -->
<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3000&pause=1000&color=16C79A&center=true&vCenter=true&multiline=true&repeat=true&width=600&height=80&lines=%2Fproc+%ED%8C%8C%EC%8B%B1%EB%B6%80%ED%84%B0+K8s+%EB%B0%B0%ED%8F%AC%EA%B9%8C%EC%A7%80;RTOS+%EC%8A%A4%EB%A0%88%EB%93%9C%EB%B6%80%ED%84%B0+gRPC+%EC%8A%A4%ED%8A%B8%EB%A6%BC%EA%B9%8C%EC%A7%80" alt="Typing SVG" /></a>

<br/>

<!-- Contact Badges -->
[![Gmail](https://img.shields.io/badge/ghtrm1037@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:ghtrm1037@gmail.com)
[![GitHub](https://img.shields.io/badge/Han--Sang--min-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Han-Sang-min)

</div>

---

## 🏢 현재

**태하메카트로닉스** 디스플레이 팀 · Software Engineer `2024.11 ~`

> ThreadX 기반 임베디드 시스템에서 센서 연동 · 멀티스레딩 아키텍처 설계 · 메뉴 UI 프레임워크 제작

---

## 🛠️ Tech Stack

<div align="center">

#### Languages
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)

#### Infrastructure & System
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)

#### Communication & Protocol
![gRPC](https://img.shields.io/badge/gRPC-244C5A?style=for-the-badge&logo=google&logoColor=white)
![Protocol Buffers](https://img.shields.io/badge/Protobuf-4285F4?style=for-the-badge&logo=google&logoColor=white)

#### Embedded & Game
![STM32](https://img.shields.io/badge/STM32-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white)
![Unreal Engine](https://img.shields.io/badge/Unreal_Engine_5-0E1128?style=for-the-badge&logo=unrealengine&logoColor=white)

</div>

---

## 🚀 Projects

<table>
<tr>
<td width="50%" valign="top">

### 🔭 [go-agent](https://github.com/Han-Sang-min/go-agent-core)
**모니터링 에이전트 시스템**

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-244C5A?style=flat-square&logo=google&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![K8s](https://img.shields.io/badge/K8s-326CE5?style=flat-square&logo=kubernetes&logoColor=white)

Linux / Container / K8s 환경의 메트릭 수집 시스템

- `RuntimeEnv` 인터페이스로 환경 추상화
- `/proc`, cgroup v2 직접 파싱
- gRPC 4개 RPC로 채널 분리 설계
- Simulator로 장애 시나리오 검증

</td>
<td width="50%" valign="top">

### 📷 [STM32 AI Camera](https://github.com/Han-Sang-min/STM32N6_AI)
**실시간 객체 인식** ⭐ 6

![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![STM32](https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white)

STM32N6570-DK + YOLOv2 + IMX335 Camera

- ThreadX 위 Camera/AI 스레드 분리
- MVP 패턴 · 더블 버퍼링 적용
- Hex 단위 모듈별 독립 플래싱
- 이벤트 기반 동기화 설계

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🎮 Zoomies
**멀티플레이 FPS 게임 · Steam 출시**

![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Unreal](https://img.shields.io/badge/Unreal-0E1128?style=flat-square&logo=unrealengine&logoColor=white)
![Steam](https://img.shields.io/badge/Steam-000000?style=flat-square&logo=steam&logoColor=white)

최대 4인 멀티플레이 FPS

- Host 기반 P2P 네트워크 구조
- Host Migration으로 세션 안정성
- protobuf 기반 RPC 통신 설계

</td>
<td width="50%" valign="top">

### 🎓 42 Seoul 프로젝트

**MiniShell** `C`
> Bash 모델 · 파이프, 리다이렉션, 시그널, history, PATH 환경변수 처리

**IRC Chatting Server** `C++`
> 2인 프로젝트 · RFC 1459 명세 기반 채팅 서버 구현

**Pong Game Server** `JS` `Docker`
> 5인 프로젝트 · 게임 서버 및 API 담당

</td>
</tr>
</table>

---

## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Han-Sang-min&show_icons=true&theme=tokyonight&hide_border=true&bg_color=1a1a2e&title_color=16c79a&icon_color=16c79a&text_color=cccccc&ring_color=16c79a" height="170" />
&nbsp;&nbsp;
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Han-Sang-min&layout=compact&theme=tokyonight&hide_border=true&bg_color=1a1a2e&title_color=16c79a&text_color=cccccc&langs_count=6" height="170" />

<br/><br/>

<!-- Streak Stats -->
<img src="https://github-readme-streak-stats.herokuapp.com?user=Han-Sang-min&theme=tokyonight&hide_border=true&background=1A1A2E&ring=16C79A&fire=16C79A&currStreakLabel=16C79A&sideLabels=CCCCCC&dates=888888&currStreakNum=FFFFFF&sideNums=FFFFFF" width="520" />

<br/><br/>

<!-- Activity Graph -->
<img src="https://github-readme-activity-graph.vercel.app/graph?username=Han-Sang-min&bg_color=1a1a2e&color=16c79a&line=0f3460&point=16c79a&area=true&area_color=16c79a&hide_border=true&custom_title=Contribution%20Graph" width="95%" />

</div>

---

## 🎓 Education

| | 기관 | 기간 | 내용 |
|---|---|---|---|
| 🏫 | **42 École (42 Seoul)** | 2022.07 ~ 2024.11 | CS 이론 · 공통/본과정 수료 |
| 🎓 | **경민대학교** | 2017 ~ 2022 | 정보통신과 졸업 |

---

<div align="center">

<!-- Profile Views Counter -->
![](https://komarev.com/ghpvc/?username=Han-Sang-min&color=16c79a&style=flat-square&label=Profile+Views)

<!-- Footer -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1a2e,50:16213e,100:0f3460&height=120&section=footer" width="100%" />

</div>
