# 05. Process

- Process: 실행 중인 프로그램 (text, data, heap, stack)
- 상태: new, ready, running, waiting, terminated
- PCB: 프로세스 상태, PC, 레지스터, 스케줄링 정보, 메모리 정보 등
- Context switch: 현재 상태를 PCB에 저장하고 다음 프로세스 상태를 복원
- fork(), exec(), wait(), exit() / zombie, orphan
