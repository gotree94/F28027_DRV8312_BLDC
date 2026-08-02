# 레퍼런스 링크 모음

이 프로젝트에서 사용하는 TI 공식 문서/소프트웨어 링크입니다.

## 소프트웨어 다운로드 (TI.com)

| 항목 | 툴/문서 번호 | 링크 |
|----|----|----|
| controlSUITE (DRV8312-C2-KIT 소스 포함) | `CONTROLSUITE` | https://www.ti.com/tool/CONTROLSUITE |
| Code Composer Studio | `CCSTUDIO` | https://www.ti.com/tool/CCSTUDIO |
| UniFlash (독립형 플래시 툴) | `UNIFLASH` | https://www.ti.com/tool/UNIFLASH |
| MotorWare (InstaSPIN, F28027F용) | `MOTORWARE` | https://www.ti.com/tool/MOTORWARE |
| C2000Ware (최신 SDK) | `C2000WARE` | https://www.ti.com/tool/C2000WARE |

## 하드웨어/제품 페이지

| 항목 | 링크 |
|----|----|
| DRV8312 제품 페이지 | https://www.ti.com/product/DRV8312 |
| DRV8312-C2-KIT (키트) | https://www.ti.com/tool/DRV8312-C2-KIT |
| TMS320F28027 제품 페이지 | https://www.ti.com/product/TMS320F28027 |
| TMS320F28027F (InstaSPIN용, 참고) | https://www.ti.com/product/TMS320F28027F |
| TMDSDOCK28027 (Experimenter Kit) | https://www.ti.com/tool/TMDSDOCK28027 |
| LAUNCHXL-F28027 (LaunchPad) | https://www.ti.com/tool/LAUNCHXL-F28027 |
| TIDM-THREEPHASE-BLDC-LC-INST (FOC 레퍼런스) | https://www.ti.com/tool/TIDM-THREEPHASE-BLDC-LC-INST |
| Nidec 스핀들 모터 소개 | https://www.nidec.com/en/technology/motor/glossary/item/spindle_motor |

## 데이터시트/매뉴얼 (직접 링크)

| 문서 | 번호 | 링크 |
|----|----|----|
| DRV8312-C2-KIT Hardware Reference Guide | TIDU318 | https://www.ti.com/lit/pdf/tidu318 |
| DRV83x2 Three-Phase PWM Motor Driver Data Sheet | SLES256 | https://www.ti.com/lit/pdf/sles256 |
| TMS320F2802x Piccolo Data Sheet | SPRS523 | https://www.ti.com/product/TMS320F28027#tech-docs |
| TMS320F2802x Technical Reference Manual | SPRUGE9 | https://www.ti.com/product/TMS320F28027#tech-docs |
| C2000 CPU & Instruction Set | SPRU430 | https://www.ti.com/lit/pdf/spru430 |
| controlSUITE Getting Started | SPRUGU2 | https://www.ti.com/lit/pdf/sprugu2 |
| ControlSUITE → C2000Ware 전환 가이드 | SPRUI45 | https://www.ti.com/lit/pdf/sprui45 |
| 소프트웨어 모듈화 전략 (DMC 구조) | SPRA701 | https://www.ti.com/lit/pdf/spra701 |
| 아날로그→디지털 제어 전환 | SPRA995 | https://www.ti.com/lit/pdf/spra995 |

## controlSUITE 설치 후 로컬 경로

```
C:\ti\controlSUITE\development_kits\DRV8312-C2-KIT_v128\
    ├── BLDC_Sensored\            # 홀센서 BLDC 프로젝트
    ├── GUI_project\              # GUI 연동 프로젝트
    ├── Hardware\                 # 스키매틱/아트웍/BOM
    └── ...
C:\ti\controlSUITE\device_support\f2802x\v230\
    ├── F2802x_Device.h
    ├── F2802x_GlobalVariableDefs.c
    ├── F2802x_DefaultIsr.c
    ├── F2802x_CpuTimers.c
    ├── F2802x_CodeStartBranch.asm
    ├── F28027_RAM_lnk.cmd
    ├── F28027.cmd
    └── examples...
C:\ti\controlSUITE\libs\math\IQmath\v160\
C:\ti\controlSUITE\libs\app_libs\motor_control\
```

## 커뮤니티

- TI E2E C2000 포럼: https://e2e.ti.com/support/microcontrollers/c2000-microcontrollers-group/
- TI E2E 모터 드라이버 포럼: https://e2e.ti.com/support/motor-drivers-group/
- 참고 스레드 예: "DRV8312-C2-KIT: BLDC Sensored Code to Flash"
  https://e2e.ti.com/support/microcontrollers/c2000-microcontrollers-group/c2000/f/c2000-microcontrollers-forum/769604

> 링크는 2026-08 기준입니다. 깨진 링크는 TI.com에서 제품명/툴명으로 재검색하세요.
