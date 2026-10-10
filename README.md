# Jiho Kim · 김지호

운영체제와 Linux 시스템 프로그래밍을 기반으로 Systems / Robotics / Automation을 다룹니다.
현재 Robotics / Perception / System Integration을 경험하며, software success signal과 실제 결과를 분리해 측정하고 문제의 경계를 추적합니다.

## Tech Stack

- **Languages:** C · C++ · Python · Java
- **Robotics / Perception:** ROS 2 · MoveIt / MoveItPy · OpenCV · RealSense / RGB-D · PyQt
- **Systems:** Linux · POSIX · Docker · CMake · Git / GitHub Actions
- **Backend / Infra:** Spring Boot · JPA · Spring Security · MySQL · Kubernetes

## Experience & Education

### ROBOTIS — Software Intern

Planning Team · 2026.06.23–2026.12.21 종료 예정

Robotics Software, RGB-D / Calibration, VLA Evaluation / Deployment를 경험하고 있습니다.
ROS 2 / Linux / device communication 환경에서 system integration과 troubleshooting을 수행합니다.

### COOP Robotics Track

2026.03–2026.05

ROS 2, MoveIt, RealSense, Isaac Sim을 활용한 manipulation / perception 실습.
[Robotics Practice](https://github.com/rlawlgh0813/robotics-practice)에 학습과 구현 기록을 정리했습니다.

### COOP Cloud Track

2025.09–2025.12

Linux, Kubernetes 기반 container / infrastructure 실습.
[Kubernetes Cloud Practice](https://github.com/rlawlgh0813/kubernetes-cloud-practice)에 정리했습니다.

### Soongsil University — Computer Science

숭실대학교 컴퓨터학부 · 2021.03–2027.02 졸업 예정 · GPA 4.26 / 4.5

## Featured Repositories

### [VLA Robotics Lab](https://github.com/rlawlgh0813/vla-robotics-lab)

Robot Learning / Perception을 다루는 개인 학습·실험 및 공개 포트폴리오 재구성 저장소입니다.

- LIBERO VLA 5-model evaluation · ARX5 deployment analysis
- RGB-D: **9/9 detection · 0.68 mm repeatability · bias +7.0 → +0.2 mm**
- Raw results · validation scripts · plots · limitations

고정 조건 검출이며 repeatability는 3D 1σ, 50 frames 기준입니다. 카메라 좌표계 측정으로, 절대 로봇 좌표 정확도 검증이 아닙니다.

**Stack:** Python · OpenCV / RGB-D

### [MacGyvBot](https://github.com/MacGyvBot/macgyvbot)

자연어 기반 로봇팔 공구 전달 시스템을 만든 **5인 팀 프로젝트**입니다. 아래는 본인의 기여입니다.

- STT → rule parser → local LLM command pipeline
- PyQt operator GUI · typed ROS interface · task cancel/status
- Gripper control · handoff retry/fallback recovery · tests/error feedback

대표 PR: [#14](https://github.com/MacGyvBot/macgyvbot/pull/14) · [#159](https://github.com/MacGyvBot/macgyvbot/pull/159) · [#210](https://github.com/MacGyvBot/macgyvbot/pull/210)

**Stack:** Python · ROS 2 · PyQt

### [Operating Systems](https://github.com/rlawlgh0813/operating-systems)

xv6 기반 운영체제 수업 프로젝트입니다.

- System calls · stride scheduler / CPU-share validation
- Memory management · COW consistency
- Filesystem snapshot · block-level COW / reference counting

**Stack:** C · xv6

### [Linux System Programming](https://github.com/rlawlgh0813/linux-system-programming)

프로세스 실행부터 raw filesystem 해석까지 다룬 수업 프로젝트입니다.

- Custom shell · fork / execvp / waitpid
- Daemon lifecycle · signal-based reload / shutdown
- ext2 raw image parser · direct / indirect block traversal

**Stack:** C · Linux / POSIX

### [AlgoLog](https://github.com/rlawlgh0813/algolog)

알고리즘 풀이 기록을 위한 Personal Backend MVP · Paused.

- Data modeling · JWT authentication / authorization · Spring Security
- MySQL / Flyway · Docker Compose
- Swagger / OpenAPI · GitHub Actions / Gradle CI

**Stack:** Java · Spring Boot / JPA

### [Algorithm Problem Solving](https://github.com/rlawlgh0813/algorithm-problem-solving)

주로 C++로 작성한 알고리즘 문제 풀이 기록입니다.

- Graph · DP · Segment / Fenwick Tree
- Tree / LCA · Union-Find · Geometry
- Backtracking · Implementation

## What I've Worked On

- **Robotics:** Command & operator workflow · RGB-D / calibration · VLA evaluation / deployment · ROS 2 integration
- **Systems / Backend / Infra:** Linux process / filesystem · OS scheduling / memory / COW · authentication / data modeling · Kubernetes workloads / networking / storage

## Awards / Certifications

- 2026 SCON 은상 · Silver Award
- 정보처리기사 · 2026
- SQLD · 2025
- TOPCIT Level 3 · 466/1000
