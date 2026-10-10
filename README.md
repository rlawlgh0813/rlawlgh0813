### Jiho Kim · 김지호

<p>운영체제·Linux 시스템 프로그래밍을 기반으로 <strong>Systems / Robotics / Automation</strong>을 다룹니다.<br>
현재 Robotics / Perception / System Integration을 경험하며, software success signal과 실제 결과를 분리해 측정하고 문제의 경계를 추적합니다.</p>

[Repositories ↓](#featured-repositories) · [Experience ↓](#experience--education) · [Tech Blog](https://jihodo.tistory.com) · [Problem Solving](https://velog.io/@rlawlgh) · [Solved.ac](https://solved.ac/profile/jihooo7)

## Tech Stack

<table width="100%">
<tr><td><strong>Languages</strong><br><code>C</code> <code>C++</code> <code>Python</code> <code>Java</code></td></tr>
<tr><td><strong>Robotics / Perception</strong><br><code>ROS 2</code> <code>MoveIt / MoveItPy</code> <code>OpenCV</code> <code>RealSense / RGB-D</code> <code>PyQt</code></td></tr>
<tr><td><strong>Systems</strong><br><code>Linux</code> <code>POSIX</code> <code>Docker</code> <code>CMake</code> <code>Git / GitHub Actions</code></td></tr>
<tr><td><strong>Backend / Infra</strong><br><code>Spring Boot</code> <code>JPA</code> <code>Spring Security</code> <code>MySQL</code> <code>Kubernetes</code></td></tr>
</table>

## Experience & Education

<table width="100%">
<tr><td>
<strong>ROBOTIS — Software Intern</strong> · Planning Team<br>
<sub>2026.06.23–2026.12.21 종료 예정</sub><br>
Robotics Software · RGB-D / Calibration · VLA Evaluation / Deployment<br>
ROS 2 / Linux / device communication 환경의 system integration과 troubleshooting.
</td></tr>
<tr><td>
<strong>COOP Robotics Track</strong><br>
<sub>2026.03–2026.05</sub><br>
ROS 2 · MoveIt · RealSense · Isaac Sim — manipulation / perception 실습.<br>
<a href="https://github.com/rlawlgh0813/robotics-practice">Robotics Practice →</a>
</td></tr>
<tr><td>
<strong>COOP Cloud Track</strong><br>
<sub>2025.09–2025.12</sub><br>
Linux · Kubernetes — container / infrastructure 실습.<br>
<a href="https://github.com/rlawlgh0813/kubernetes-cloud-practice">Kubernetes Cloud Practice →</a>
</td></tr>
<tr><td>
<strong>Soongsil University — Computer Science</strong><br>
<sub>숭실대학교 컴퓨터학부 · 2021.03–2027.02 졸업 예정 · GPA 4.26 / 4.5</sub>
</td></tr>
</table>

## Featured Repositories

<table width="100%">
<tr><td>
<h3><a href="https://github.com/rlawlgh0813/vla-robotics-lab">VLA Robotics Lab</a></h3>
<p><code>Robot Learning</code> <code>Perception</code> <code>Experiment</code><br>개인 학습·실험 / 공개 포트폴리오 재구성.</p>
<ul>
<li>LIBERO VLA 5-model evaluation · ARX5 deployment analysis</li>
<li>RGB-D: <strong>9/9 detection · 0.68 mm repeatability · bias +7.0 → +0.2 mm</strong></li>
<li>Raw results · validation scripts · plots · limitations</li>
</ul>
<p><sub>고정 조건 검출 · repeatability: 3D 1σ, 50 frames. 카메라 좌표계 측정이며 절대 로봇 좌표 정확도 검증이 아닙니다.</sub></p>
<p><code>Python</code> <code>OpenCV / RGB-D</code> · <a href="https://github.com/rlawlgh0813/vla-robotics-lab">View Repository →</a></p>
</td></tr>
<tr><td>
<h3><a href="https://github.com/MacGyvBot/macgyvbot">MacGyvBot</a></h3>
<p><code>Robot Software</code> <code>Operator Workflow</code><br>자연어 기반 로봇팔 공구 전달 · <strong>5인 팀 프로젝트</strong>.</p>
<ul>
<li><strong>내 기여:</strong> STT → rule parser → local LLM command pipeline</li>
<li>PyQt operator GUI · typed ROS interface · task cancel/status</li>
<li>Gripper control · handoff retry/fallback recovery · tests/error feedback</li>
</ul>
<p>Selected PRs: <a href="https://github.com/MacGyvBot/macgyvbot/pull/14">#14</a> · <a href="https://github.com/MacGyvBot/macgyvbot/pull/159">#159</a> · <a href="https://github.com/MacGyvBot/macgyvbot/pull/210">#210</a><br>
<code>Python</code> <code>ROS 2</code> <code>PyQt</code> · <a href="https://github.com/MacGyvBot/macgyvbot">View Repository →</a></p>
</td></tr>
<tr><td>
<h3><a href="https://github.com/rlawlgh0813/operating-systems">Operating Systems</a></h3>
<p><code>Kernel</code> <code>Memory</code> <code>Filesystem</code><br>xv6 기반 운영체제 수업 프로젝트.</p>
<ul>
<li>System calls · stride scheduler / CPU-share validation</li>
<li>Memory management · COW consistency</li>
<li>Filesystem snapshot · block-level COW / reference counting</li>
</ul>
<p><code>C</code> <code>xv6</code> · <a href="https://github.com/rlawlgh0813/operating-systems">View Repository →</a></p>
</td></tr>
<tr><td>
<h3><a href="https://github.com/rlawlgh0813/linux-system-programming">Linux System Programming</a></h3>
<p><code>Processes</code> <code>Signals</code> <code>Filesystem</code><br>프로세스 실행부터 raw filesystem 해석까지 다룬 수업 프로젝트.</p>
<ul>
<li>Custom shell · fork / execvp / waitpid</li>
<li>Daemon lifecycle · signal-based reload / shutdown</li>
<li>ext2 raw image parser · direct / indirect block traversal</li>
</ul>
<p><code>C</code> <code>Linux / POSIX</code> · <a href="https://github.com/rlawlgh0813/linux-system-programming">View Repository →</a></p>
</td></tr>
<tr><td>
<h3><a href="https://github.com/rlawlgh0813/algolog">AlgoLog</a></h3>
<p><code>Backend</code> <code>Authentication</code><br>알고리즘 풀이 기록 · Personal Backend MVP · Paused.</p>
<ul>
<li>Data modeling · JWT authentication / authorization · Spring Security</li>
<li>MySQL / Flyway · Docker Compose</li>
<li>Swagger / OpenAPI · GitHub Actions / Gradle CI</li>
</ul>
<p><code>Java</code> <code>Spring Boot / JPA</code> · <a href="https://github.com/rlawlgh0813/algolog">View Repository →</a></p>
</td></tr>
<tr><td>
<h3><a href="https://github.com/rlawlgh0813/algorithm-problem-solving">Algorithm Problem Solving</a></h3>
<p><code>Algorithms</code> <code>Data Structures</code><br>주로 C++로 작성한 문제 풀이 기록.</p>
<ul>
<li>Graph · DP · Segment / Fenwick Tree</li>
<li>Tree / LCA · Union-Find · Geometry</li>
<li>Backtracking · Implementation</li>
</ul>
<p><code>C++</code> · <a href="https://github.com/rlawlgh0813/algorithm-problem-solving">View Repository →</a></p>
</td></tr>
</table>

## What I've Worked On

**Robotics**<br>
`Command & operator workflow` · `RGB-D / calibration` · `VLA evaluation / deployment` · `ROS 2 integration`

**Systems / Backend / Infra**<br>
`Linux process / filesystem` · `OS scheduling / memory / COW` · `Authentication / data modeling` · `Kubernetes workloads / networking / storage`

---

<sub><strong>Awards / Certifications</strong><br>
2026 SCON 은상 · Silver Award / 정보처리기사 · 2026 / SQLD · 2025 / TOPCIT Level 3 · 466/1000</sub>
