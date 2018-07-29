# Cogi_Lion
1. Git 단기습득
2. 코드 단일화
---
# Git 단기습득

- git init - **현재 디렉터리에 Git 저장소를 만든다**

- git clone - **다른 프로젝트를 가져오거나 복사하고 싶을 때 사용한다**

- git status - **파일의 상태 확인하기** Git 저장소를 만들었거나 clone 한 후에 이 명령어를 실행하면 아래와 같은 문장을 볼 수 있다

  > $ git status
  On branch master
  nothing to commit, working directory clean

- git status - **코드를 수정하거나 파일을 만들었을 경우** 실행하면 아래와 같은 문장을 볼 수 있다

  >$ git status
  On branch master
  Untracked files:
  (use "git add <file>..." to include in what will be committed)

      README

- git add (파일명) - **파일 추적하기 및 Staged 상태 만들기**
  >$ git add README

- git status - **파일을 추적 및 Staged 상태로 만들었을 경우** 실행하면 아래와 같은 문장을 볼 수 있다

  >$ git status
  On branch master
  Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

      new file:   README

- git commit **-m**(넣어도 되고 빼도 된다) - **변경사항 커밋하기** Unstaged 상태의 파일은 커밋되지 않는다는 것을 기억해야 한다. git add 명령으로 추가하지 않은 파일은 커밋하지 않는다. 커밋하기 전에 git status 명령으로 모든 것이 Staged 상태인지 확인할 수 있다. 그리고 git commit을 실행하여 커밋한다.
