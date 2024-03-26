# git prac

- 2024.03.19 ~ 03.20

Git 사용법의 심화과정?? 이라고 할 수 있겠다.  
branch 생성, 이동, 삭제, merge, pull request, Fork에 대해 학습하였다.

## Key Point

`branch`

```bash
# branch 확인
git branch

# branch 생성
git branch <name>

# branch 삭제
git branch -D <name>

# branch 이동
git switch <name>

# branch 생성 + 이동
git switch -c <name>
```

`push`

```bash
git push --set-upstream origin <name>
```

`merge`

```bash
git merge <name>
:q
git merge <name> -m <message>
```
