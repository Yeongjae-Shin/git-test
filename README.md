# 오늘 사용한 git 명령어 3가지

## 1. git init

- git 사용하기 위해서는 먼저 저장소를 만들어야 하는데, Remote repository를 clone 하는 방법과 `git init`을 이용해 직접 만드는 방법이 있다. `git init`으로 생성 후에는 반드시 `git remote add repo주소`를 입력하여 내 local과 연결해줘야 한다.

## 2. git add

- `git add`는 수정한 파일들 또는 새로 만든 파일들을 staging area에 올리는 과정이다. `git add`를 한다고 해서 변경 내역이 바로 반영되지는 않는다.

## 3. git commit

- `git commit`은 `git add`를 통해 staging area에 올라간 파일들의 변경 내역을 확정하는 단계이다.

## 4. git push

- `git push`를 하게 되면 최종적으로 내 local에서 작업한 파일들이 Remote repository로 합쳐진다.
