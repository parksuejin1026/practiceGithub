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

