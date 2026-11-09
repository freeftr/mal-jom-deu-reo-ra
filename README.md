# mal-zom-deul-a-ra

AI 모델(클로드)이 한국어 글에서 버릇처럼 쓰는 표현을 모은 사전이다.
문서·PR·이슈에 이런 표현이 섞이지 않게 거르는 용도로 쓴다.

목록은 [용어사전.md](./용어사전.md) 에 있다.

## Claude 스킬로 쓰기

이 리포가 그대로 Claude Code 스킬이다([SKILL.md](./SKILL.md)).

```bash
# 모든 프로젝트에서 쓰기
git clone https://github.com/freeftr/mal-zom-deul-a-ra.git ~/.claude/skills/mal-zom-deul-a-ra

# 한 프로젝트에서만 쓰기
git clone https://github.com/freeftr/mal-zom-deul-a-ra.git .claude/skills/mal-zom-deul-a-ra
```

한국어 글을 쓰거나 검토할 때 자동으로 불리고, `/mal-zom-deul-a-ra` 로 직접 부를 수도 있다.
목록을 새로 받으려면 설치한 폴더에서 `git pull` 한다.

## 제보

여기 없는 표현을 보셨다면 언제든 이슈나 PR 로 알려 주세요. 고맙게 받겠습니다.
