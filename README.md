# mal-jom-deu-reo-ra

AI 모델(클로드)이 한국어 글에서 버릇처럼 쓰는 표현을 모은 사전이다.
문서·PR·이슈에 이런 표현이 섞이지 않게 거르는 용도로 쓴다.

목록은 [용어사전.md](./용어사전.md) 에 있다.

## Claude 스킬로 쓰기

이 리포가 그대로 Claude Code 스킬이다([SKILL.md](./SKILL.md)).

```bash
# 모든 프로젝트에서 쓰기
git clone https://github.com/freeftr/mal-jom-deu-reo-ra.git ~/.claude/skills/mal-jom-deu-reo-ra

# 한 프로젝트에서만 쓰기
git clone https://github.com/freeftr/mal-jom-deu-reo-ra.git .claude/skills/mal-jom-deu-reo-ra
```

한국어 글을 쓰거나 검토할 때 자동으로 불리고, `/mal-jom-deu-reo-ra` 로 직접 부를 수도 있다.
목록을 새로 받으려면 설치한 폴더에서 `git pull` 한다.

## 버전

판마다 git 태그(`v0.1.0` 등)와 [Releases](../../releases) 를 남긴다. 바뀐 내용은 [CHANGELOG.md](./CHANGELOG.md) 에 있다.

- 표현·버릇만 추가: 가운데 자리를 올린다 (0.1.0 → 0.2.0)
- SKILL.md 의 동작 규칙을 바꿈: 앞자리를 올린다 (0.x → 1.0.0)
- 오타·예시 문장만 고침: 끝자리를 올린다 (0.1.0 → 0.1.1)

특정 판에 고정하려면 설치한 폴더에서 `git checkout v0.1.0` 한다. 버전 번호는 관리자가 올리므로 기여 PR 에서는 건드리지 않아도 된다.

## 제보

여기 없는 표현을 보셨다면 언제든 이슈나 PR 로 알려 주세요. 고맙게 받겠습니다.
