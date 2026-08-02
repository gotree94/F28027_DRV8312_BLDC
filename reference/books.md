# 참고 도서 목록 (전력전자공학 · 전동기 제어)

F28027 + DRV8312 BLDC 모터 제어 프로젝트를 학습하면서 참고할 도서 목록입니다.
전력전자공학 이론 → 전동기 · 드라이브 → 모터 제어 · 센서리스 순서로 읽어가는 것을 권장합니다.

각 도서의 상세 소개(요약, 목차, 난이도)와 한국어 번역 자료는
문서 하단의 **[도서 소개 & 번역 로그](#도서-소개--번역-로그)** 에서 추후 순차적으로 추가합니다.

---

## 한국어 도서

### 1. 알기쉽게 풀어쓴 전력전자공학
- **저자** : 노의철, 정규범, 최남섭
- **출판사 / 발행** : 문운당 (2014)
- **분류** : 전력전자공학 입문
- **개요** :
  전력전자공학을 처음 접하는 학생을 위한 입문서. 스위칭 반도체 소자와
  DC-DC·DC-AC·AC-DC 변환기(컨버터/인버터)의 동작 원리를 알기 쉽게 설명합니다.
  이 프로젝트에서 DRV8312가 만드는 3상 인버터(120° 통전, PWM)의 동작 원리를
  이해하는 데 직접 도움이 되는 교재입니다.
- **상태** : 소개 및 번역 예정

> 추가 예정: 한국어 모터제어/전력전자 도서를 계속 모아서 아래에 추가합니다.

---

## 영어 도서 (English Books)

### A. Power Electronics — 전력전자 기초

| 제목 | 저자 | 출판사 / 판 | 비고 |
|----|----|----|----|
| Fundamentals of Power Electronics | R.W. Erickson, D. Maksimović | Springer, 3rd ed. (2020) | 전력전자 대학원 표준 교과서. 컨버터·인버터 설계의 정석 |
| Power Electronics: Converters, Applications, and Design | N. Mohan, T.M. Undeland, W.P. Robbins | Wiley, 3rd ed. (2003) | 가장 널리 쓰이는 전력전자 교과서 |
| Power Electronics | D.W. Hart | McGraw-Hill (2011) | 입문자용으로 비교적 쉬움. 한국어 입문서와 난이도 유사 |
| Power Electronics: Devices, Circuits, and Applications | M.H. Rashid | Pearson, 4th ed. (2014) | 소자부터 회로·응용까지 포괄적인 참고서 |

### B. Electric Machines & Drives — 전동기 · 드라이브

| 제목 | 저자 | 출판사 / 판 | 비고 |
|----|----|----|----|
| Electric Machinery Fundamentals | S.J. Chapman | McGraw-Hill, 5th ed. (2011) | 전동기 원리 입문. BLDC/PMSM 기본 개념 포함 |
| Analysis of Electric Machinery and Drive Systems | P. Krause, O. Wasynczuk, S. Sudhoff, S. Pekarek | Wiley-IEEE, 3rd ed. (2013) | 좌표변환(dq) 이론의 표준 참고서. FOC 기초 |
| Electric Motors and Drives: Fundamentals, Types and Applications | A. Hughes, B. Drury | Newnes, 5th ed. (2019) | 실무 친화적이고 읽기 쉬운 드라이브 개론 |
| Fundamentals of Electrical Drives | A. Veltman, D.W.J. Pulle, R.W. De Doncker | Springer, 2nd ed. (2016) | 시뮬레이션 기반으로 드라이브를 학습하는 구조 |

### C. Motor Control — 모터 제어 · 센서리스

| 제목 | 저자 | 출판사 / 판 | 비고 |
|----|----|----|----|
| Electric Motor Control: DC, AC, and BLDC Motors | Sang-Hoon Kim | Elsevier (2017) | DC/AC/BLDC 제어를 모두 다룸. 이 프로젝트와 가장 밀접 |
| Permanent Magnet Synchronous and Brushless DC Motor Drives | R. Krishnan | CRC Press (2009) | PMSM/BLDC 드라이브의 심화 레퍼런스 |
| Brushless Permanent-Magnet Motor Design | D. Hanselman | Magna Physics, 2nd ed. (2003) | BLDC 모터 설계와 역기전력(BEMF) 파형 이론. HDD 모터 특성화에 유용 |
| Sensorless Vector and Direct Torque Control | P. Vas | Oxford Univ. Press (1998) | 센서리스 제어 이론의 고전. 난이도 높음 |

### D. Simulation & Digital Control — 시뮬레이션 · 디지털 제어

| 제목 | 저자 | 출판사 / 판 | 비고 |
|----|----|----|----|
| Digital Control in Power Electronics | S. Buso, P. Mattavelli | Morgan & Claypool (2015) | DSP로 전력전자 디지털 제어루프를 설계하는 법. F28027 PI 구현에 직접 활용 |
| Power Electronics and Motor Drives: Advances and Trends | B.K. Bose | Academic Press, 2nd ed. (2020) | 전력전자 + 모터 드라이브 전체 트렌드 총망라 |

---

## 도서 소개 & 번역 로그

아래 표에 도서 소개(요약/목차/난이도)와 한국어 번역 진행 상황을 기록합니다.

| 날짜 | 도서 | 작업 내용 | 상태 |
|----|----|----|----|
| 2026-08-02 | 알기쉽게 풀어쓴 전력전자공학 (노의철 외) | 도서 목록에 등록 | 대기 |
| 2026-08-02 | 영어 도서 리스트 | 도서 목록에 등록 (A~D 분류) | 대기 |
