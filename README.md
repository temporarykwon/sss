# Basic Workflow

```sh
git init
git status
git add .
git status
git commit -m 'asdf'

# github, bitbucket, gitlab etc.. remote repo를 생성
git remote add origin <REMOTE REPO URL.git>
git push -u origin master # 첫 번째만


#다른 컴퓨터라면,
git clone <REMOTE REPO URL.git> # downlozdZIP => .git 없음 ㅠ
# 작업작업
git add . && git commit -m 'MSG' && git push # 더 안전하다
git add . ; git commit -m 'MSG' ; git push

git pull
```

