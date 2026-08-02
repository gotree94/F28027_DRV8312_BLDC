# PLECS 프로그램 정리

## 개요

PLECS는 스위스 취리히 소재 **Plexim GmbH**가 개발한 **전력전자 시스템용 시뮬레이션
소프트웨어**입니다. 회로 편집기 기반의 Top-Down 방식으로 전원·변환기·부하를 포함한
전체 시스템을 하나의 모델로 구성하며, Piecewise-Linear 기법 기반의 전용 솔버로
**빠르고 정확한 시뮬레이션**을 제공합니다.

- 공식 사이트 : https://www.plexim.com
- 개발사 : Plexim GmbH (Zurich, Switzerland)

## 제품 구성

| 제품 | 설명 |
|----|----|
| **PLECS Blockset** | MATLAB/Simulink 애드온. Simulink 환경에서 제어 로직과 함께 회로를 시뮬레이션 |
| **PLECS Standalone** | 단독 실행 버전. 회로 + 제어 시스템을 한 환경에서 모델링 |
| **PLECS Spice** | SPICE(.cir) 형식 회로와의 연동 지원 |
| **Web-Based Simulation** | 웹 브라우저/Python 인터페이스로 시뮬레이션 실행 |
| **PLECS Coder** | 시뮬레이션 모델을 ANSI-C 코드로 생성 (실시간 제어기·HIL용) |
| **PLECS RT Box** | 실시간 하드웨어인더루프(HIL) 시뮬레이터 하드웨어 |

## 주요 기능

- 전기 / 자기 / 열 / 기계 **다중 도메인** 컴포넌트 라이브러리
- IGBT·MOSFET·다이오드 등 반도체 모델과 스위칭 손실/온도(Thermal) 모델
- 토크·속도 센서, **BLDC / PMSM / DC 모터 모델** 내장
- Scope + FFT, THD 측정, Parameter Sweep, 배치(Batch) 시뮬레이션
- **C-Script 블록**으로 제어 알고리즘을 직접 코딩
- **PIL (Processor-in-the-Loop)** : 실제 C2000 보드 + 고충실도 ePWM/ADC 주변장치
  모델을 연결해 실기기에서 제어 코드를 검증 (별도 라이선스)

## 라이선스 (교육용 무료)

- **평가판(Trial)** : 30일 무료 평가판 제공
- **학생 라이선스** : 공인 대학/교육기관 소속 학생·교사는 무료 Student License
  (1년 유효, 개인 PC 1대, 교육/연구 목적 전용)
- 상용/기업은 유료 (영구 라이선스 또는 연간 임대)

## 이 프로젝트에서의 활용

- **DRV8312 3상 인버터 + BLDC 모터 + 120° 6-step 센서리스 제어기**를 PLECS로
  먼저 시뮬레이션하여 기동, 역기전력(BEMF) 검출, PI 속도 제어 로직을 검증
- F28027에 실제 코드를 올리기 전에 제어 파라미터(PI 게인, 통전 시퀀스)를 미리 튜닝
- PLECS Coder / PIL 기능을 사용해 생성 코드를 F28027에 적용하는 단계로 확장 가능

## 문서 / 튜토리얼

- 공식 문서 : https://www.plexim.com/documentation
- 튜토리얼 / 학습 : https://www.plexim.com/learn
- 데모 모델 : https://www.plexim.com/download/demo_models
- PLECS 관련 온라인 강좌(예: "Mastering Power Electronics using PLECS") : Udemy 등

---

## 관련 도서 소개 & 번역 로그 (추후 진행)

PLECS와 관련된 도서/강좌의 소개 및 한국어 번역 자료를 아래에 추가할 예정입니다.

| 날짜 | 자료 | 작업 내용 | 상태 |
|----|----|----|----|
| 2026-08-02 | PLECS 프로그램 정리 문서 생성 | 프로그램 개요·기능·활용 방안 정리 | 완료 |
