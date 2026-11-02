# 04-1. Interrupt & Trap

- Interrupt: 외부 하드웨어가 발생 (I/O 완료, 타이머), 비동기
- Trap/Exception: 실행 중인 명령어가 발생 (system call, 0으로 나누기, page fault), 동기
- 처리 흐름: 상태 저장 → 커널 모드 전환 → interrupt vector에서 handler 찾기 → handler 실행 → 상태 복원 후 복귀
