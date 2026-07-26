# 김지호

**Robotics Software · VLA · Systems**

컴퓨터학부 21학번 김지호입니다.
운영체제와 Linux 시스템 프로그래밍으로 기반을 쌓았고, 현재는 ROS 2 로봇 소프트웨어와 VLA의 실물 적용을 공부하고 있습니다.

현재 VLA 모델을 비교·분석하고, 학습된 정책을 실제 로봇에서 실행하기 위한 데이터와 제어 파이프라인을 경험하고 있습니다.
관련 학습과 실험은 [VLA Robotics Lab](https://github.com/rlawlgh0813/vla-robotics-lab)에 공개 가능한 형태로 정리하고 있습니다.

## Experience

### ROBOTIS · Internship

`2026.06 - Present` · VLA / Robot Learning

- [LIBERO 평가](https://github.com/rlawlgh0813/vla-robotics-lab/tree/main/experiments/libero)에서 VLA 모델 5종을 같은 태스크와 에피소드 수로 평가하고 결과의 해석 범위와 한계를 정리했습니다.
- [ARX X5 VLA 실물 실험](https://github.com/rlawlgh0813/vla-robotics-lab/tree/main/experiments/arx5-vla)에서 시연 수집, 데이터셋 변환, fine-tuning, 배포, 실물 추론까지 이어지는 흐름을 경험했습니다.
- 명령과 측정 상태를 분리해 동작 시점과 목표 오차를 분석하고, 버전별 실패 원인을 지표로 구분했습니다.
- ROS 2, Zenoh, CAN, 컨테이너로 구성된 실행 경로를 추적하며 연동 및 추론 문제를 진단했습니다.

## Selected Projects

| Project | Contribution | Stack |
| --- | --- | --- |
| [VLA Robotics Lab](https://github.com/rlawlgh0813/vla-robotics-lab) | VLA·로봇 제어 학습과 LIBERO 5모델 평가, ARX X5 실물 배포 실험을 공개 가능한 근거와 함께 정리했습니다. CSV 검증·그래프 생성 코드와 ROS 2 Control C++ 예제를 포함합니다. | `Python`, `C++`, `ROS 2 Control`, `LIBERO`, `MuJoCo`, `LeRobot`, `GR00T` |
| [MacGyvBot](https://github.com/MacGyvBot/macgyvbot) | 음성으로 요청한 공구를 로봇팔이 찾아 전달하는 프로젝트입니다. 명령 파이프라인, LLM/local parser, PyQt 운영 GUI, 작업 상태·취소·복구 흐름을 담당했습니다. | `ROS 2`, `Python`, `PyQt`, `MoveIt`, `RealSense`, `YOLO`, `VLM` |
| [AlgoLog](https://github.com/rlawlgh0813/algolog) | 알고리즘 풀이와 오답 원인, 반례를 구조화해 기록하는 백엔드 서비스입니다. 도메인 모델, 인증·권한, API 구조를 설계하고 있습니다. | `Java`, `Spring Boot`, `JPA`, `MySQL` |

## Foundations

| Repository | Focus |
| --- | --- |
| [operating-systems](https://github.com/rlawlgh0813/operating-systems) | xv6 system call, stride scheduler, memory management, filesystem snapshot |
| [linux-system-programming](https://github.com/rlawlgh0813/linux-system-programming) | Linux shell, daemon, signal handling, ext2 filesystem image parser |
| [robotics-practice](https://github.com/rlawlgh0813/robotics-practice) | ROS 2 node, topic, service, action, launch, parameter, MoveIt |
| [kubernetes-cloud-practice](https://github.com/rlawlgh0813/kubernetes-cloud-practice) | Kubernetes workload, networking, configuration, storage |
| [algorithm-problem-solving](https://github.com/rlawlgh0813/algorithm-problem-solving) | C++ 기반 알고리즘 문제 풀이 |

## Skills

| Category | Tools |
| --- | --- |
| Languages | `C`, `C++`, `Python`, `Java` |
| Robotics | `ROS 2`, `ROS 2 Control`, `MoveIt`, `RealSense`, `YOLO`, `PyQt`, `Zenoh` |
| VLA / Experiment | `LeRobot`, `LIBERO`, `MuJoCo`, `GR00T`, `Pi0/Pi0.5` |
| Systems / Infra | `Linux`, `Docker`, `Kubernetes`, `AWS` |
| Backend | `Spring Boot`, `Spring Data JPA`, `Spring Security`, `MySQL` |
| Tools | `Git`, `GitHub`, `GitHub Actions`, `colcon`, `CMake`, `Gradle` |

## Links

- [Tech Blog](https://jihodo.tistory.com)
- [Problem Solving Log](https://velog.io/@rlawlgh)
- [Solved.ac](https://solved.ac/profile/jihooo7)
