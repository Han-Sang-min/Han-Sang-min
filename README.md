<div align="center">

<!-- Header Banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1a2e,50:16213e,100:0f3460&height=230&section=header&text=Han%20Sang-min&fontSize=45&fontColor=16c79a&fontAlignY=35&desc=Systems%20%7C%20Embedded%20%7C%20Infrastructure&descSize=18&descColor=cccccc&descAlignY=55&animation=fadeIn" width="100%" />

<br/>

<!-- Contact Badges -->
[![Gmail](https://img.shields.io/badge/ghtrm1037@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:ghtrm1037@gmail.com)
[![GitHub](https://img.shields.io/badge/Han--Sang--min-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Han-Sang-min)
[![Tech Notes](https://img.shields.io/badge/Tech_Notes-CS_%26_C++-16c79a?style=flat-square&logo=readthedocs&logoColor=white)](https://cs-cpp-notes-v2.pages.dev/)

</div>

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

## Projects

<table>
<tr>
<td width="50%" valign="top">

### [go-agent](https://github.com/Han-Sang-min/go-agent-core)
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

### [STM32 AI Camera](https://github.com/Han-Sang-min/STM32N6_AI)
**실시간 객체 인식**

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

### [Zoomies](https://store.steampowered.com/app/3009430/zoomies/)
**멀티플레이 FPS 게임 · Steam 출시**

![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-244C5A?style=flat-square&logo=google&logoColor=white)
![Unreal](https://img.shields.io/badge/Unreal-0E1128?style=flat-square&logo=unrealengine&logoColor=white)
![Steam](https://img.shields.io/badge/Steam-000000?style=flat-square&logo=steam&logoColor=white)

최대 4인 멀티플레이 FPS

- Host 기반 P2P 네트워크 구조
- Host Migration으로 세션 안정성
- protobuf 기반 RPC 통신 설계

</td>
<td width="50%" valign="top">

### 42 Seoul 프로젝트

**[MiniShell](https://github.com/Han-Sang-min/42-Seoul/tree/main/Minishell)** `C`
> Bash 모델 · 파이프, 리다이렉션, 시그널, history, PATH 환경변수 처리

**[IRC Chatting Server](https://github.com/Han-Sang-min/42-Seoul/tree/main/Ft_Irc)** `C++`
> 2인 프로젝트 · RFC 1459 명세 기반 채팅 서버 구현

**[Pong Game Server](https://github.com/42-42-transcendence/ft_transcendence)** `JS` `Docker`
> 5인 프로젝트 · 게임 서버 및 API 담당

</td>
</tr>
</table>

<!-- Footer -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1a2e,50:16213e,100:0f3460&height=120&section=footer" width="100%" />

</div>
