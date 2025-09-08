폴더를 하나 새로 만들고 터미널에서 시작하기 클릭 후 
git config --global user.name "xx"
git config --global user.email "xx@gmail.com"
를 입력해서 계정등록
git init = 나의 작업폴더를 감시하기 시작하는 코드 (파일 만드는 거, 코드짜는 거 감시)

파일의 코드를 입력했으면 저장 후 git add 파일이름
                            git commit -m '메모'
이렇게 쓸때마다 저장하면서 add를 해놓으면 백업 가능

git add로 기록할 파일부터 고르고 고른 파일을 기록하고 싶으면 git commit
다시 정리하자면 git add 파일을 백업해놓는거고 git commit을 사용하면 파일을 저장하는 거임
그리고 git add 했을 때 파일이 있는 위치를 staging area라고 함 
commit 할 파일 후보 중 하나

여러 파일을 스테이징 하려면 git add 파일1, 파일2 / 그리고 git add . 을 쓰면 모든 파일을 스테이징함

git status = 지금 어떤 파일을 스테이징 해놨는지 알려줌
git log --all --oneline = 어떤 파일을 커밋했는지 알려줌

요즘은 웬만한 에디터에 모두 깃이 내장되어 있어 터미널을 쓰는 건 비효율적!

vscode의 깃 기능은 왼쪽 기능 중 3번쨰에 있는 깃모양 아이콘
변경해서 저장한 파일에 갖다대었을때 +는 add기능 -는 add취소
commit은 대놓고 있음

커밋하면서 파일 차이점을 확인하는 습관을 들이자
커밋을 작성할 때 전거랑 뭐가 달라졌는지 쓰면 굿

git diff = 최근 commit vs 현재파일의 차이점을 보여줌 q를 누르면 보기 종료