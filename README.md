# GET SHIT DONE (Gemini CLI Edition)

**Gemini CLI를 위한 강력한 메타 프롬프팅, 컨텍스트 엔지니어링 및 스펙 기반 개발 시스템.**

> [!CAUTION]
> **공지사항 (Disclaimer)**
> 이 프로젝트는 원작자(TÂCHES)의 명시적인 허락 없이 [get-shit-done-cc](https://www.npmjs.com/package/get-shit-done-cc) / [glittercowboy/get-shit-done](https://github.com/glittercowboy/get-shit-done)를 기반으로 하여 Gemini CLI 환경에 맞춰 개인적으로 수정한 버전입니다. 원작자의 요청이 있을 경우 이 저장소 및 관련 패키지는 즉시 삭제되거나 비공개로 전환될 수 있습니다.

## 설치 방법

이 도구는 [get-shit-done-gc](https://www.npmjs.com/package/get-shit-done-gc)라는 이름의 npm 패키지로 설치하여 사용할 수 있습니다:

```bash
npm install -g get-shit-done-gc
```

## 사용 방법

Gemini CLI에서 다음과 같이 GSD 명령어를 실행하여 프로젝트를 시작하거나 관리할 수 있습니다:

```
/gsd:new-project 실행해줘.
```

## 주요 특징
- **Gemini CLI 최적화**: Gemini의 도구 활용 능력과 컨텍스트 창을 최대한 활용하도록 설계되었습니다.
- **구조화된 워크플로우**: 프로젝트 초기화부터 로드맵 생성, 실행 계획 수립 및 자동 구현까지 일관된 프로세스를 제공합니다.
- **컨텍스트 엔지니어링**: AI가 품질 저하 없이 작업을 수행할 수 있도록 컨텍스트를 원자적으로 관리합니다.

## 시스템 구성
- `commands/gsd/`: 각 GSD 명령의 세부 로직이 마크다운 형식으로 정의되어 있습니다.
- `templates/`: 프로젝트 문서 생성에 사용되는 템플릿입니다.
- `workflows/`: 복잡한 작업을 수행하기 위한 단계별 가이드입니다.

## 상세 문서
- [프로젝트 개요](docs/overview.md)
- [시스템 아키텍처](docs/architecture.md)
- [핵심 원칙](docs/principles.md)
- [명령어 레퍼런스](docs/commands-ref.md)

---
*Original project by [TÂCHES](https://github.com/glittercowboy). Ported to Gemini CLI.*
