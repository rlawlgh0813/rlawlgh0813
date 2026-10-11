# Jiho Kim · 김지호

숭실대학교 컴퓨터학부에 재학 중이며, 현재 ROBOTIS에서 소프트웨어 인턴으로 일하고 있습니다.
운영체제와 Linux 시스템 프로그래밍을 공부해 왔고, 최근에는 로봇 소프트웨어와 인식·제어에 집중하고 있습니다.

## Repositories

### [VLA Robotics Lab](https://github.com/rlawlgh0813/vla-robotics-lab)

VLA 모델 평가와 RGB-D 인식 실험을 공개 자료로 재구성한 개인 학습·실험 저장소입니다.

- **모델 평가:** LIBERO에서 VLA 모델 5종을 비교하고, ARX5 실물 로봇 배포 과정을 분석했습니다.
- **RGB-D 인식:** 원통 자세 추정 실험에서 **9/9 검출 · 반복성 0.68 mm · bias +7.0 → +0.2 mm**를 측정했습니다.
- **결과 검증:** 원시 결과, 검증 스크립트, 그래프와 함께 실험의 한계를 정리했습니다.

검출은 고정 조건, 반복성은 50프레임의 3D 1σ 기준입니다. 카메라 좌표계에서 측정한 결과이며, 절대 로봇 좌표 정확도는 검증하지 않았습니다.

자료: [실험 결과](https://github.com/rlawlgh0813/vla-robotics-lab/blob/main/experiments/rgbd-cylinder-pose/03-results.md) · [검증 범위와 한계](https://github.com/rlawlgh0813/vla-robotics-lab/blob/main/experiments/rgbd-cylinder-pose/05-limitations-and-next.md)<br>
**Stack:** Python · OpenCV / RGB-D

### [MacGyvBot](https://github.com/MacGyvBot/macgyvbot)

자연어 요청으로 로봇팔이 공구를 전달하는 **5인 팀 프로젝트**입니다. 저는 명령 처리와 운영자 인터페이스를 중심으로 개발했습니다.

- **명령 처리:** STT → 규칙 파서 → 로컬 LLM fallback으로 이어지는 처리 경로를 구현했습니다.
- **운영 GUI:** PyQt 기반 인터페이스와 작업 취소·상태 표시를 구현하고, typed ROS interface를 적용했습니다.
- **제어·복구:** 그리퍼 제어 패널, handoff 재시도·fallback 복구, 테스트와 오류 피드백을 개발했습니다.

기여 근거: [#14](https://github.com/MacGyvBot/macgyvbot/pull/14) · [#159](https://github.com/MacGyvBot/macgyvbot/pull/159) · [#210](https://github.com/MacGyvBot/macgyvbot/pull/210) — merged PRs<br>
**Stack:** Python · ROS 2 · PyQt

### [Operating Systems](https://github.com/rlawlgh0813/operating-systems)

xv6의 스케줄링, 메모리, 파일시스템을 확장한 운영체제 수업 프로젝트입니다.

- **스케줄링:** System calls와 stride scheduler를 구현하고, CPU 점유율을 검증했습니다.
- **메모리:** 물리 프레임 관리와 COW 일관성 처리를 구현했습니다.
- **파일시스템:** Snapshot 생성·복원·삭제, 블록 단위 COW와 참조 횟수 관리를 구현했습니다.

자료: [Stride scheduler 구현·검증](https://github.com/rlawlgh0813/operating-systems/blob/main/lab02/README.md)<br>
**Stack:** C · xv6

### [AlgoLog](https://github.com/rlawlgh0813/algolog)

알고리즘 풀이와 반례를 기록하는 개인 백엔드 MVP입니다. 현재 개발은 일시 중단한 상태입니다.

- **데이터 설계:** 사용자·문제·풀이 기록·반례 도메인을 설계하고, MySQL / Flyway로 스키마를 관리했습니다.
- **인증·권한:** Spring Security, BCrypt, JWT 기반 인증과 접근 권한 처리를 구현했습니다.
- **실행·검증:** Docker Compose 실행 환경, Swagger / OpenAPI 문서, smoke test와 Gradle CI를 구성했습니다.

자료: [API 명세](https://github.com/rlawlgh0813/algolog/blob/main/docs/api-spec.md) · [ERD](https://github.com/rlawlgh0813/algolog/blob/main/docs/erd.md)<br>
**Stack:** Java · Spring Boot / JPA · MySQL · GitHub Actions

**Other repositories**

- **[Linux System Programming](https://github.com/rlawlgh0813/linux-system-programming)** — 셸·데몬 구현과 ext2 이미지의 파일·블록 구조 분석을 다룬 수업 프로젝트.
- **[Algorithm Problem Solving](https://github.com/rlawlgh0813/algorithm-problem-solving)** — 그래프·DP·트리·Segment/Fenwick Tree 등을 다룬 C++ 문제 풀이 기록.

## Tech Stack

![C](https://img.shields.io/badge/C-315A88?style=flat-square&logo=c&logoColor=white) ![C++](https://img.shields.io/badge/C%2B%2B-315A88?style=flat-square&logo=cplusplus&logoColor=white) ![Python](https://img.shields.io/badge/Python-315A88?style=flat-square&logo=python&logoColor=white) ![Java](https://img.shields.io/badge/Java-315A88?style=flat-square&logo=openjdk&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-52657A?style=flat-square&logo=linux&logoColor=white) ![ROS 2](https://img.shields.io/badge/ROS%202-42796B?style=flat-square&logo=ros&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-52657A?style=flat-square&logo=docker&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring%20Boot-735987?style=flat-square&logo=springboot&logoColor=white)

## Background

### 💼 ROBOTIS · Software Intern

Planning Team<br>
2026.06.23–2026.12.21 종료 예정

공개 VLA 모델의 시뮬레이션 평가·실물 로봇 배포와 RGB-D 인식·보정·좌표 변환 오류 분석을 경험했습니다.
ROS 2·Linux·컨테이너·장치 통신 환경을 통합하고 디버깅했습니다.
명령값과 측정값, 소프트웨어 성공 응답과 실제 장치 결과를 구분해 검증했습니다.

### 🤖 COOP Robotics Track

2026.03–2026.05<br>
ROS 2, MoveIt, RealSense, Isaac Sim으로 로봇 조작과 인식을 실습했습니다.
학습·구현 기록: [Robotics Practice](https://github.com/rlawlgh0813/robotics-practice)

### ☁️ COOP Cloud Track

2025.09–2025.12<br>
Linux와 Kubernetes 기반 컨테이너·인프라를 실습했습니다.
학습 기록: [Kubernetes Cloud Practice](https://github.com/rlawlgh0813/kubernetes-cloud-practice)

### 🎓 숭실대학교 컴퓨터학부

Soongsil University · Computer Science<br>
2021.03 입학–2027.02 졸업 예정<br>
**GPA 4.26 / 4.5**

## Awards & Certifications

**[2026 SCON](https://sccc.kr/) 은상** · Silver Award — 숭실대학교 프로그래밍 대회

**정보처리기사** · 2026

**SQLD** · 2025

**TOPCIT Level 3** · 466/1000

## Notes & Links

<p>📝 <strong><a href="https://jihodo.tistory.com">Tistory</a></strong> · 데이터 분석 학습<br>
R을 활용한 데이터 분석과 외부·공공데이터 학습 내용을 정리했습니다.</p>

<p>🧩 <strong><a href="https://velog.io/@rlawlgh">Velog</a></strong> · 알고리즘 풀이 해설<br>
백준 C++ 풀이의 접근 과정과 구현을 기록합니다. 세그먼트 트리, DFS, LCA 등 문제에 적용한 알고리즘을 설명합니다.</p>

<p>📊 <strong><a href="https://solved.ac/profile/jihooo7">Solved.ac</a></strong> · 문제 해결 기록<br>
백준에서 해결한 문제 목록과 알고리즘별 풀이 기록을 확인할 수 있습니다.</p>
