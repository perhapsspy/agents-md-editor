# Agents MD Editor

[한국어](README.md) | [English](README.en.md)

## 요약

`agents-md-editor`는 `AGENTS.md`, `CLAUDE.md`, Cursor rules, Copilot instructions 같은 항상 읽히는 에이전트 지침 파일을 작고 오래가게 유지하는 스킬입니다.

항상 읽히는 파일에는 미래 세션의 에이전트 행동을 바꾸는 규칙만 남기고, 임시 상태·온보딩·상세 참고 자료·중복 정책은 더 알맞은 문서나 자동화 표면으로 분류합니다.

## 빠른 시작

**설치**

```bash
npx skills add perhapsspy/agents-md-editor
```

혹은 `skills/agents-md-editor` 폴더를 에이전트 스킬 디렉터리에 직접 복사합니다.

**바로 사용**

```text
$agents-md-editor 를 사용해서 이 AGENTS.md를 줄이고, 남길 내용과 옮길 내용을 먼저 리뷰해줘.
```

## 이런 때 사용

- `AGENTS.md`, `agents.md`, `CLAUDE.md` 같은 always-read instruction file을 만들거나 고칠 때
- 세션 기록, 임시 migration 상태, onboarding 설명이 항상 읽히는 지침에 섞였을 때
- 같은 규칙이 README, docs, scripts, CI, 다른 rule file에 중복돼 있는지 정리해야 할 때
- 바로 저장하기 전에 keep/move/remove 분류와 proposed diff를 먼저 보고 싶을 때

## 관련 스킬

이 스킬은 독립적으로 동작합니다. 작업 상태 보존은 [`project-context`](https://github.com/perhapsspy/project-context), 일반 문서 정리는 [`tighten-docs`](https://github.com/perhapsspy/tighten-docs)가 더 적합합니다.

## 지원

[![Buy Me A Coffee](https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png)](https://www.buymeacoffee.com/perhapsspy)

## 라이선스

[MIT](LICENSE)
