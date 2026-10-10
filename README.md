# Jiho Kim · 김지호

숭실대학교 컴퓨터학부에 재학 중이며, 현재 ROBOTIS에서 소프트웨어 인턴으로 일하고 있습니다.
운영체제와 Linux 시스템 프로그래밍을 공부해 왔고, 최근에는 로봇 소프트웨어와 인식·제어에 집중하고 있습니다.

## Tech Stack

**Languages**

![C](https://img.shields.io/badge/C-315A88?style=for-the-badge&logo=c&logoColor=white) ![C++](https://img.shields.io/badge/C%2B%2B-315A88?style=for-the-badge&logo=cplusplus&logoColor=white) ![Python](https://img.shields.io/badge/Python-315A88?style=for-the-badge&logo=python&logoColor=white) ![Java](https://img.shields.io/badge/Java-315A88?style=for-the-badge&logo=openjdk&logoColor=white)

**Robotics / Perception**

![ROS 2](https://img.shields.io/badge/ROS%202-42796B?style=for-the-badge&logo=ros&logoColor=white) ![MoveIt / MoveItPy](https://img.shields.io/badge/MoveIt%20%2F%20MoveItPy-42796B?style=for-the-badge) ![OpenCV](https://img.shields.io/badge/OpenCV-42796B?style=for-the-badge&logo=opencv&logoColor=white) ![RealSense / RGB-D](https://img.shields.io/badge/RealSense%20%2F%20RGB--D-42796B?style=for-the-badge) ![PyQt](https://img.shields.io/badge/PyQt-42796B?style=for-the-badge&logo=qt&logoColor=white)

**Systems**

![Linux](https://img.shields.io/badge/Linux-52657A?style=for-the-badge&logo=linux&logoColor=white) ![POSIX](https://img.shields.io/badge/POSIX-52657A?style=for-the-badge) ![Docker](https://img.shields.io/badge/Docker-52657A?style=for-the-badge&logo=docker&logoColor=white) ![CMake](https://img.shields.io/badge/CMake-52657A?style=for-the-badge&logo=cmake&logoColor=white) ![Git](https://img.shields.io/badge/Git-52657A?style=for-the-badge&logo=git&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-52657A?style=for-the-badge&logo=githubactions&logoColor=white)

**Backend / Infra**

![Spring Boot](https://img.shields.io/badge/Spring%20Boot-735987?style=for-the-badge&logo=springboot&logoColor=white) ![JPA](https://img.shields.io/badge/JPA-735987?style=for-the-badge) ![Spring Security](https://img.shields.io/badge/Spring%20Security-735987?style=for-the-badge&logo=springsecurity&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-735987?style=for-the-badge&logo=mysql&logoColor=white) ![Kubernetes](https://img.shields.io/badge/Kubernetes-735987?style=for-the-badge&logo=kubernetes&logoColor=white)

## Selected Projects

### [VLA Robotics Lab](https://github.com/rlawlgh0813/vla-robotics-lab)

VLA 모델 평가와 RGB-D 인식 실험을 공개 가능한 자료로 재구성한 개인 학습·실험 저장소입니다.

- LIBERO에서 VLA 모델 5종 비교 평가, ARX5 실물 로봇 배포 과정 분석
- RGB-D 원통 자세 추정: **9/9 검출 · repeatability 0.68 mm · bias +7.0 → +0.2 mm**
- 원시 결과, 검증 스크립트, 그래프, 실험의 한계를 함께 정리

검출은 고정 조건, repeatability는 3D 1σ·50 frames 기준입니다. 카메라 좌표계 측정이며 절대 로봇 좌표 정확도를 검증한 결과는 아닙니다.

**사용 기술:** Python · OpenCV / RGB-D

### [MacGyvBot](https://github.com/MacGyvBot/macgyvbot)

자연어 요청으로 로봇팔이 공구를 전달하는 **5인 팀 프로젝트**입니다. 저는 명령 처리와 운영자 인터페이스를 중심으로 개발했습니다.

- STT → rule parser → local LLM fallback으로 이어지는 명령 처리 경로
- PyQt 운영 GUI, typed ROS interface, 작업 취소·상태 표시
- Gripper 제어, handoff retry/fallback recovery, 테스트와 오류 피드백

기여 근거: [#14](https://github.com/MacGyvBot/macgyvbot/pull/14) · [#159](https://github.com/MacGyvBot/macgyvbot/pull/159) · [#210](https://github.com/MacGyvBot/macgyvbot/pull/210) — merged PRs

**사용 기술:** Python · ROS 2 · PyQt

### [Operating Systems](https://github.com/rlawlgh0813/operating-systems)

xv6를 확장하며 스케줄링, 메모리, 파일시스템을 구현한 운영체제 수업 프로젝트입니다.

- System calls, stride scheduler 구현 및 CPU 점유율 검증
- Physical frame 관리와 COW 일관성 처리
- Filesystem snapshot 생성·복원·삭제, block-level COW와 reference counting

**사용 기술:** C · xv6

### [AlgoLog](https://github.com/rlawlgh0813/algolog)

알고리즘 풀이와 반례를 기록하기 위해 만든 개인 backend MVP입니다. 현재 개발은 일시 중단한 상태입니다.

- User / Problem / SolutionRecord / CounterExample 도메인 설계
- Spring Security, BCrypt, JWT 기반 인증과 접근 권한 처리
- MySQL / Flyway, Docker Compose, Swagger / OpenAPI, smoke test와 Gradle CI

**사용 기술:** Java · Spring Boot / JPA · MySQL · GitHub Actions

## More Repositories

- **[Linux System Programming](https://github.com/rlawlgh0813/linux-system-programming)** — 수업 프로젝트. Custom shell과 fork/execvp/waitpid, daemon·signal lifecycle, ext2 raw image의 direct/indirect block 해석.
- **[Algorithm Problem Solving](https://github.com/rlawlgh0813/algorithm-problem-solving)** — 주로 C++로 작성한 풀이 기록. Graph, DP, Segment/Fenwick Tree, Tree/LCA, Union-Find, Geometry, Backtracking, Implementation.

## Experience

### ROBOTIS · Software Intern

Planning Team · 2026.06.23–2026.12.21 종료 예정

- 공개 VLA 모델의 simulation evaluation과 physical robot deployment 경험
- RGB-D perception, calibration, coordinate transform의 오류 분석
- ROS 2 / Linux / container / device communication 환경의 system integration과 troubleshooting
- Command와 measured state, software 성공 응답과 실제 장치 결과를 구분해 검증

### COOP Robotics Track

2026.03–2026.05

ROS 2, MoveIt, RealSense, Isaac Sim을 활용한 manipulation / perception 실습.
학습과 구현 기록은 [Robotics Practice](https://github.com/rlawlgh0813/robotics-practice)에 정리했습니다.

### COOP Cloud Track

2025.09–2025.12

Linux, Kubernetes 기반 container / infrastructure 실습.
학습 기록은 [Kubernetes Cloud Practice](https://github.com/rlawlgh0813/kubernetes-cloud-practice)에 정리했습니다.

## Education

**숭실대학교 컴퓨터학부 · Soongsil University, Computer Science**

2021.03 입학–2027.02 졸업 예정 · GPA 4.26 / 4.5

## Awards & Certifications

- 2026 SCON 은상 · Silver Award
- 정보처리기사 · 2026
- SQLD · 2025
- TOPCIT Level 3 · 466/1000

## Writing & Study

### [Tistory · 데이터 분석 학습](https://jihodo.tistory.com)

R을 활용한 데이터 분석을 공부하며 정리한 블로그입니다. 외부 데이터와 공공데이터를 다루는 학습 내용을 기록했습니다.

### [Velog · 알고리즘 풀이](https://velog.io/@rlawlgh)

백준 문제를 C++로 풀고, 사용한 알고리즘과 풀이 방법을 정리합니다. 세그먼트 트리, DFS, LCA 등 문제별 접근 과정을 글로 남겼습니다.

### [Solved.ac · 문제 풀이 현황](https://solved.ac/profile/jihooo7)

백준에서 해결한 문제와 알고리즘 학습 진행도를 확인할 수 있는 프로필입니다. 풀이 글과 별도로 전체 문제 해결 기록을 볼 수 있습니다.
