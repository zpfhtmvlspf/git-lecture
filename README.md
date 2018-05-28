# Git CLI Study 

## Linux(bash/shell) 기본 명령어

- 디렉토리 이동 : cd
  ```bash
  cd ..         # 상위 디렉토리 이동
  cd ./images   # 현재 디렉토리의 하위 images 디렉토리로 이동
  ```
- 파일 목록 보기 : ls
  ```bash
  ls            # 현재 디렉토리의 파일 목록 보기
  ls -a         # 현재 디렉토리의 모든 파일 목록 보기 (숨김파일 포함)
  ```
- 디렉토리 생성 : mkdir
  ```bash
  mkdir git-example     #현재 디렉토리에 'git-example' 디렉토리 생성
  ```
- 파일 삭제 : rm
  ```bash
  rm README.md          # README.md 파일 삭제
  rm ./images/ -r       # images 디렉토리 삭제
  ```
- 빈 파일 생성 : touch
  ```bash
  touch README.md       # 0byte README.md 파일 생성
  ```

## vi(m) 에디터 사용 방법

### vi 시작하기

bash(shell prompt)에서 `vi {filename}` 입력

```bash
vi index.html         # index.html 편집창 열림
```

### vi 명령모드 

vi 에디터 상태에서 `ESC`키 누름

### vi 명령어
| 키 | 기능 |
|:--:|:--:|
|i|현재 커서 위치에 입력하기|
|I|현재 줄 맨 앞에 Insert하기|
|a|현재 커서 다음 칸에 입력하기|
|A|현재 줄 맨 뒤에 Insert하기|
|dd|현재 줄 삭제|
|yy|현재 줄 복사하기|
|P|현재 행 위에 복사된 행 삽입|
|p|현재 행 아래에 복사된 행 삽입|
|u|실행취소|
|:w|저장|
|:q|닫기|
|:q!|저장하지 않고 닫기|
|:wq|저장하고 닫기|
|:숫자|지정한 줄 번호로 이동|

## Study Chapter Index
- Chapter 1
  - What is Git?
  - Why Use Git?
  - Installing Git
  - Configuring Git

- Chapter 2
  - Creating Git Repository
  - Ignoring Files

- Chapter 3
  - Git Three States
    - basic Git workflow
    - Working Directory
    - Staging Area
    - Local Repository
  - File LifeCycle
    - Getting an Overview
    - Getting Ready to Commit
    - Committing
  - Inspecting the Commit History

- Chapter 4
  - Git branch
    - Creating & Inspecting Branch
    - Checking out branch
    - Working on new branch
  - Merging Changes
    - Dealing with Conflicts
      - Undoing Merge
      - Solve Merge Conflict
  - Deleting Branches

- Chapter 5
  - Git Stash
    - Getting Overview of Stash
    - Saving Changes Temporarily with name
    - Applying Stash
      - git stash pop
      - git stash apply
    - Remove Stash Entry
      - git stash drop
      - git stash clear

- Chapter 6
  - Checking out Certain Commit
    - Creating Branch based on a Certain commit
  - Undoing Local Changes
    - Unstaging Staged Files
    - Discarding Modified Files
  - Undoing Committed Changes
    - Undoing Certain Commit
    - Restoring the Last Commit
  - Rewriting History
    - Changing the Last Commit
    - Git Rebase
      - Changing Multiple Commit Messages
      - Modifying Previous Commits
      - Reordering Commits
      - Squashing Commits
      - Removing Commits

- Chapter 7
  - Remote Repositories
  - Git Hosting Services
  - Connecting a Remote Repository
    - Creating new Repository on Github
    - Publishing a Local Branch
    - Inspecting a Local & Remote Branch
    - Integrating Remote Changes
    - Deleting Remote Branch
  - Cloning Repository from Remote

- Chapter 8
  - Contributing to a Project on GitHub
    - Forking Projects
    - The GitHub Flow
    - How to open pull request