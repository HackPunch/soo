1. git init
2. git add 파일이름 // 한개 파일
   git add .      //
   git add --all  // 이건 전체파일
3. git status // ADD가 잘 되었는지 확인
4. git commit -m "이전 버전에 대한 설명"
5. 원격 저장소 등록해 주지 않으면 push 불가능
   git remote add origin 서버주소
    -> origin은 등록해줄 이름
    ex) git remote add origin https://github.com/HackPunch/soo.git
   만약 remote add를 잘못 등록 했을 시 삭제 후 다시 등록한다
    -> git remote 입력하고 이름(origin) 확인 후 git remote rm 이름 입력
       git remote -v 는 등록한 원격저장소의 서버 주소를 보여준다
6. git push origin master 입력하면 username을 적으라고 한다
   닉네임은 HackPunch 비밀번호 입력은 깃허브 로그인 비밀번호 입력한다

5번 작업을 한번 해주었다면 다음 커밋땐 생략 가능
출처 : http://harbor.cz/stories/data-visualization-1/
