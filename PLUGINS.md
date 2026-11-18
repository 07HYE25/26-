# 디자인 플러그인 키트

이 저장소는 그 자체로 Claude Code 플러그인 마켓플레이스(`hye-design-kit`)다. `.claude/skills/`의 모든 스킬과 `.claude/agents/`의 에이전트를 `design-kit` 플러그인 하나로 묶는다.

## 이 저장소에서 작업할 때

설치할 것 없음. `.claude/skills/`와 `CLAUDE.md`가 자동으로 적용된다.

## 다른 저장소·대화에서 쓰기

Claude Code에서 한 번만 실행하면 사용자 전체에 설치된다.

```
/plugin marketplace add 07HYE25/26-
/plugin install design-kit@hye-design-kit
```

이 저장소의 스킬을 고치고 `main`에 머지한 뒤에는 `/plugin marketplace update hye-design-kit`로 갱신한다.

## 포함된 것

| 출처 | 스킬 |
|---|---|
| 직접 작성 | design-principles (칸 나누기 제한, 가독성, 조화) |
| pbakaus/impeccable | impeccable + 에이전트 4개 |
| Leonxlnx/taste-skill | taste-skill 외 13개 |
| heydamir/unslop | unslop |
| emilkowalski/skills | animate 외 14개 |
| VoltAgent/awesome-design-md | design-md (브랜드 84개) |
| ConardLi/web-design-skill | web-design-engineer |
| dragoon0x/optik | optik-design, optik-score, optik-layout-audit, optik-type-hierarchy, optik-harmonize |

VectorLab UI/UX Skills는 claude.ai 플러그인 목록에서 계정에 설치되어 있다.
