# test
깃 공부

1.git init / clone
- 로컬저장소 만들어서 원격저장소로 이동하거나 / 원격저장소를 로컬저장소로 가져오는 방법

2.push까지의 과정
파일 수정후 > add > commit , *)git status 사용하면 staged/unstaged 구분할수 있음

git add . (파일/폴더 상관없이 다 가능, .은 현재 디렉터리 기준 모든 파일 stage)

git commit -m "메세지"
git commit -a(add,commit 수행함 -> 단 한번도 add안됐으면 add 따로 해줘야함)

3.branch 만들기, 수정, 병합, 삭제

-생성 
git branch <브랜치명>

-브랜치 작업 위해 전환
git checkout <브랜치명>

-병합
> 메인 브랜치로 돌아오기 > git merge +)confilct 나면 한쪽으로 통합하기

-삭제
git branch -d <브랜치명>