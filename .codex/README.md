# .codex Agent Workspace

에이전트 기반 프로젝트를 바로 시작할 수 있도록 구성된 작업공간입니다.

## 디렉토리 구조
- `agents/`: 역할별 에이전트 정의
  - `planner/README.md`
  - `researcher/README.md`
  - `executor/README.md`
- `prompts/`: 프롬프트 템플릿 (`system.md`)
- `memory/`: 단기/장기 메모리 및 운영 가이드
- `tools/`: 도구 스크립트/연동 코드
- `workflows/`: 실행 절차 (`default.md`)
- `config/`: 에이전트 설정 (`agents.yaml`)
- `logs/`: 실행 로그

## 시작 순서
1. `config/agents.yaml`에서 역할 설정
2. `prompts/system.md`에서 시스템 프롬프트 정의
3. `workflows/default.md` 기준으로 실행
