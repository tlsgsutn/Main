# git

## git 기본 명령어

- mkdir <폴더생성>

- cd <폴더이름>

- git init

- notepad <파일생성> (노트패드)

- git add <파일이름>

- git log    commit한과정을 볼때

- git branch 브랜치 확인

- git branch <브랜치생성>

- git branch -d <브랜치> 브랜치 삭제

- git checkout <브랜치> 

- git merge <브랜치> 다른 브랜치를 현재 브랜치로 합치기

- git add . 파일추가없이 수정만 했을 경우

- git commit -m "<바뀐내용>" 커밋:변경 사항을 저장하는것 

## github연동

> git config --global user.name "사용자이름"
>> git config --global user.email "github이메일"
>>> git config --list 설정되었는지 확인 방법

- git init

- git commit -m <변경내용>

- git remote add <원격저장소이름> https://github.com/사용자이름/project.git   github 사이트의 프로젝트 에 연동

- git push <원격저장소이름> <브랜치>