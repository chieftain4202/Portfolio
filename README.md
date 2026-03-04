# RTL & SystemVerilog Design Portfolio

Hardware Design / Verification Engineer Portfolio  
Focused on FSM-based RTL architecture and structured verification methodology.

---

## 1. Design Philosophy

- FSM 중심의 명확한 상태 전이 설계
- Timing-aware 구조 설계
- 모듈 간 인터페이스 명확화
- Verification을 고려한 설계 (Testability 중심)

---

## 2. Technical Skills

**HDL**
- Verilog
- SystemVerilog

**Verification**
- Class-based Testbench
- Random Stimulus
- Mailbox / Event 기반 동기화
- Functional Verification 전략 설계

**Simulation**
- ModelSim / Questa
- Waveform 분석 기반 Debug

**Hardware**
- FPGA Integration
- UART 기반 통신 테스트

---

## 3. Project Overview

### ① UART TX/RX Design & Verification
- FSM 기반 UART 송수신기 설계
- Baud Tick Generator 설계
- Class 기반 Testbench 구현
- Simulation Waveform 분석 및 Debug 경험

👉 [프로젝트 상세 보기](./uart/uart_overview.md)

---

### ② FIFO Design
- Pointer 기반 FIFO 구조 설계
- Full / Empty Flag 구현
- Timing 기반 데이터 안정성 검증
- Corner Case Simulation

👉 [프로젝트 상세 보기](./fifo/fifo_overview.md)

---

### ③ Stopwatch + UART Integration
- 다중 모듈 통합 설계
- 상태 전이 기반 제어 로직 설계
- UART 입력 기반 제어 구현
- FPGA 실구동 검증

👉 [프로젝트 상세 보기](./integration/system_architecture.md)

---

### ④ DHT11 FSM Controller
- 타이밍 기반 FSM 설계
- 1us Tick 기반 카운터 설계
- Bit-level 데이터 처리 로직 구현

👉 [프로젝트 상세 보기](./sensor/sensor_fsm.md)

---

## 4. Design Strength

- 복잡한 FSM을 구조적으로 분해 가능
- Debug 과정에서 Waveform 기반 원인 분석
- Multi-driven, Timing mismatch 문제 해결 경험
- 설계 의도와 Verification 전략을 동시에 고려

---

## 5. Future Direction

- UVM 기반 Verification 확장
- Assertion 기반 검증 강화
- SoC 단위 설계 구조 이해 확장
