깃 사용법 :

1. 커밋 : 커밋에 추가할 파일을 선택한다. ex ) git add README.txt (확장명)
            git commit -m "상세 설명" <- 큰 따옴표로 넣어야한다.
            [-m] 은 메세지의 약자
2. 커밋 확인 및 업데이트 : 커밋을 했던 내역을 확인한다
            git log : 최신 커밋이 제일 위에 나타난다
            이전 로그로 되돌리려면 git checkout 커밋아이디 (7자리이상)
            다시 최신 커밋으로 돌아가려면 git checkout 커밋아이디를 사용해도되지만
            git checkout -를 적어도 가능하다.
3. 원격 저장소에 커밋 올리기 : git remote add origin https://GitHub.com/유저이름/Repository name.git 로
            원격 저장소 주소를 입력하고 
            git push origin master 를 입력해서 커밋들을 저장소에 푸시한다.
4. 원격 저장소의 커밋 내려받기 : git clone https://GitHub.com/rjsdks/Repository name. git . < 마침표는
            현재 폴더에 내려받으라는 이야기이다. 마침표를 찍지않으면 폴더 안에 새로운 폴더를 생성해서 내려받는다.
5. 원격 저장소의 새로운 커밋을 로컬저장소에 갱신하기 : git pull origin master 명령어를 이용하면
             원격 저장소에서 새롭게 푸시한 커밋을 로컬 저장소에 내려받는다.