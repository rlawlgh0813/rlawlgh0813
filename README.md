# 김지호

컴퓨터학부 21학번 김지호입니다.

운영체제, Linux system programming, cloud infrastructure, backend, robotics를 공부하며 컴퓨터 시스템이 실제 서비스와 로봇 소프트웨어로 이어지는 과정을 경험하고 있습니다.

현재는 **AlgoLog** 백엔드 프로젝트와 **MacGyvBot** 로봇 프로젝트를 진행하고 있습니다.

## Now

- **Backend**: Spring Boot 기반 알고리즘 풀이 기록 서비스 [AlgoLog](https://github.com/rlawlgh0813/algolog) 개발
- **Robotics**: ROS 2 기반 음성 명령 로봇팔 어시스턴트 [MacGyvBot](https://github.com/MacGyvBot) 개발
- **Study**: 시스템, 클라우드, 로봇 소프트웨어를 연결해서 이해하는 방향으로 학습 중

## Projects

### In Progress

| Project | Description | Stack |
| --- | --- | --- |
| [AlgoLog](https://github.com/rlawlgh0813/algolog) | 알고리즘 문제 풀이, 오답 원인, 반례를 구조화해 기록하는 backend project | `Java`, `Spring Boot`, `JPA`, `Spring Security`, `JWT`, `MySQL` |
| [MacGyvBot](https://github.com/MacGyvBot) | 음성 명령으로 공구를 요청하면 로봇팔이 공구를 인식하고 전달하는 robot assistant project | `ROS 2`, `Python`, `PyQt`, `RealSense`, `YOLO`, `MoveItPy` |

### Completed / Course Projects

| Repository | What I did |
| --- | --- |
| [operating-systems](https://github.com/rlawlgh0813/operating-systems) | xv6 기반 system call, stride scheduler, memory management, filesystem snapshot 구현 |
| [linux-system-programming](https://github.com/rlawlgh0813/linux-system-programming) | Linux shell, daemon process, signal handling, ext2 filesystem image parser 구현 |
| [kubernetes-cloud-practice](https://github.com/rlawlgh0813/kubernetes-cloud-practice) | Kubernetes node, namespace, pod, deployment, service, ingress, storage 실습 |
| [user-interface-practice](https://github.com/rlawlgh0813/user-interface-practice) | Android 팀 프로젝트에서 Firebase 기반 로그인, 게시판, 채팅 데이터 흐름 담당 |
| [robotics-practice](https://github.com/rlawlgh0813/robotics-practice) | ROS 2 node, topic, service, action, launch, parameter 실습 |
| [algorithm-problem-solving](https://github.com/rlawlgh0813/algorithm-problem-solving) | BOJ 중심 C++ 알고리즘 문제 풀이 기록 |

## Areas

### System

운영체제와 Linux 시스템 프로그래밍을 통해 프로그램이 커널, 프로세스, 파일 시스템, 메모리와 맞닿는 지점을 공부했습니다.

- xv6 system call path 구현
- Stride scheduling 구현
- physical frame tracking, virtual-to-physical address translation 실습
- filesystem snapshot / copy-on-write 구조 설계
- Linux daemon, signal, process control, ext2 image parsing 구현

### Cloud / Infrastructure

Kubernetes 리소스를 직접 생성하고 연결하면서 서비스가 여러 컴포넌트로 나뉘어 배포되는 방식을 실습했습니다.

- Pod, Deployment, StatefulSet, Job, CronJob
- ConfigMap, Secret
- Service, Ingress
- PV, PVC, storage

### Backend

Spring Boot 기반 프로젝트를 통해 인증, 권한, 도메인 모델링, API 설계를 공부하고 있습니다.

- User / Problem / SolutionRecord / CounterExample 도메인 설계
- JWT 기반 인증 흐름 구현 예정
- 작성자 권한, 공개/비공개 접근 제어 설계
- 예외 처리와 validation 정리

### Robotics

ROS 2 기반 로봇 소프트웨어 구조를 공부하고, 음성 명령부터 인식, 제어, GUI까지 연결하는 프로젝트를 진행하고 있습니다.

- ROS 2 node/topic/service/action/launch 학습
- STT -> LLM command parsing -> ROS topic pipeline
- PyQt 기반 command GUI
- YOLO 기반 공구 인식
- RealSense depth camera, MoveItPy, robot arm control 실험
- VLM 기반 grasp point selection 확장 예정

## Tech Stack

| Category | Stack |
| --- | --- |
| Languages | `C`, `C++`, `Java`, `Python` |
| Backend | `Spring Boot`, `Spring Data JPA`, `Spring Security`, `JWT`, `MySQL` |
| System | `Linux`, `xv6`, `POSIX`, `Makefile` |
| Cloud / Infra | `Docker`, `Kubernetes`, `AWS` |
| Robotics | `ROS 2`, `MoveItPy`, `RealSense`, `YOLO`, `PyQt` |
| Tools | `Git`, `GitHub`, `Gradle`, `colcon` |

## Links

- Blog: [jihodo.tistory.com](https://jihodo.tistory.com)
- PS Log: [velog.io/@rlawlgh](https://velog.io/@rlawlgh)
- BOJ: [jihooo7](https://www.acmicpc.net/user/jihooo7)
