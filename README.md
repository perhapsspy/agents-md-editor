# Agents MD Editor

[한국어](README.md) | [English](README.en.md)

## 요약

프로젝트를 열 때마다 읽히는 `AGENTS.md`, `CLAUDE.md` 같은 지침이 세션 기록과 상세 문서로 불어나지 않게 합니다. 앞으로도 계속 지켜야 할 규칙만 남기고 임시 상태, 온보딩과 중복 설명은 더 알맞은 문서나 자동화로 옮깁니다.

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

## 지원

[![Buy Me A Coffee](https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png)](https://www.buymeacoffee.com/perhapsspy)

## 라이선스

[MIT](LICENSE)
