# 김지호

컴퓨터학부 21학번 김지호입니다.

운영체제, Linux system programming, backend, cloud infrastructure를 기반으로 공부해 왔고, 최근에는 **ROS 2 기반 로봇 소프트웨어**에 가장 큰 관심을 두고 있습니다.  

## Now

- **Robotics**: 시스템 프로그래밍과 로봇 소프트웨어가 실제 하드웨어 제어로 이어지는 구조 학습
- **Backend**: Spring Boot 기반 알고리즘 풀이 기록 서비스 [AlgoLog](https://github.com/rlawlgh0813/algolog) 개발

## Projects

### Selected

| Project | What I did | Stack |
| --- | --- | --- |
| [MacGyvBot](https://github.com/MacGyvBot/macgyvbot) | ROS 2 기반 로봇팔 공구 전달 프로젝트. Command pipeline, LLM/local parser, PyQt operator GUI, chat/TTS/log UX를 담당했습니다. Organization 프로젝트라 별도 복제 repo 대신 원본 repository와 [presentation deck](https://github.com/MacGyvBot/macgyvbot-docs)을 연결합니다. | `ROS 2`, `Python`, `PyQt`, `MoveIt`, `RealSense`, `YOLO`, `VLM` |

### In Progress

| Project | Description | Stack |
| --- | --- | --- |
| [AlgoLog](https://github.com/rlawlgh0813/algolog) | 알고리즘 풀이 기록 서비스를 Spring Boot 기반으로 구현 중 | `Java`, `Spring Boot`, `JPA`, `MySQL` |

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

### Robotics

ROS 2 기반 로봇 소프트웨어 구조를 공부하고, 자연어 명령부터 인식, task orchestration, 로봇 제어, GUI까지 연결하는 프로젝트를 경험했습니다.

- ROS 2 node/topic/service/action/launch 구조 학습
- STT -> LLM/local parser -> ROS command topic pipeline 구현
- `ToolCommand`, `RobotTaskControl`, `RobotTaskStatus` 기반 runtime interface 사용
- PyQt 기반 operator GUI, chat/TTS feedback, task log 구성
- MoveIt 기반 로봇팔 task flow와 gripper control 연동
- RealSense, YOLO, VLM, hand grasp detection 결과를 task flow와 연결

### System

운영체제와 Linux 시스템 프로그래밍을 통해 프로그램이 커널, 프로세스, 파일 시스템, 메모리와 맞닿는 지점을 공부했습니다.

- xv6 system call path 구현
- Stride scheduling 구현
- physical frame tracking, virtual-to-physical address translation 실습
- filesystem snapshot / copy-on-write 구조 설계
- Linux daemon, signal, process control, ext2 image parsing 구현

### Backend

Spring Boot 기반 프로젝트를 통해 인증, 권한, 도메인 모델링, API 설계를 공부하고 있습니다.

- User / Problem / SolutionRecord / CounterExample 도메인 설계
- JWT 기반 인증 흐름 구현
- 작성자 권한, 공개/비공개 접근 제어 설계
- 예외 처리와 validation 정리

### Cloud / Infrastructure

Kubernetes 리소스를 직접 생성하고 연결하면서 서비스가 여러 컴포넌트로 나뉘어 배포되는 방식을 실습했습니다.

- Pod, Deployment, StatefulSet, Job, CronJob
- ConfigMap, Secret
- Service, Ingress
- PV, PVC, storage

## Tech Stack

| Category | Stack |
| --- | --- |
| Languages | `C`, `C++`, `Java`, `Python` |
| Robotics | `ROS 2`, `MoveIt`, `RealSense`, `YOLO`, `VLM`, `PyQt`, `colcon` |
| Backend | `Spring Boot`, `Spring Data JPA`, `Spring Security`, `JWT`, `MySQL` |
| System | `Linux`, `xv6`, `POSIX`, `Makefile` |
| Cloud / Infra | `Docker`, `Kubernetes`, `AWS` |
| Tools | `Git`, `GitHub`, `Gradle`, `Ollama` |

## Links

- Blog: [jihodo.tistory.com](https://jihodo.tistory.com)
- PS Log: [velog.io/@rlawlgh](https://velog.io/@rlawlgh)
- Solved.ac: [jihooo7](https://solved.ac/profile/jihooo7)
