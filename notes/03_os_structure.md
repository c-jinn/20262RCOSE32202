# 03. OS Structure

- System call: 사용자 프로그램이 커널 서비스를 요청하는 인터페이스 (trap으로 커널 모드 진입)
- 파라미터 전달: 레지스터 / 메모리 블록(테이블) / 스택
- Monolithic: 모든 기능이 하나의 커널에 (빠르지만 유지보수 어려움)
- Layered: 계층으로 분리 (검증 쉬움, 성능 오버헤드)
- Microkernel: 최소 기능만 커널에, 나머지는 사용자 공간 (메시지 전달 오버헤드)
- Loadable kernel module: 필요할 때 모듈을 동적으로 적재 (Linux)
