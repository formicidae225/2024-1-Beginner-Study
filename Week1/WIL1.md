# 개발 입문 스터디 1주차 정리

## git 최초 설정
$ git config --global user.name “깃허브 이름”<br>
$ git config --global user.email “깃허브 이메일”<br>

		# git 사용에 앞서 github의 자신의 정보를 입력하는 것
## 디렉토리 만들기

git init 		<br>
		# git으로 폴더 관리하기 위함 <br>
		# 실행 후에 경로가 뜸<br>

git status	<br>
		# 만들어진 파일의 상태 확인

git add .	<br>
		# 현재 관리하고 있는 파일들을 git으로 관리<br>
		# 방금 만든 파일은 git status로 확인 시 untracked file로 확인됨<br>
		# git add . 후 git status로 확인 시 new file로 확인됨<br>

git commit –m “메시지” <br>
		# commit이란 저장소에 소스코드의 일부의 최신 변경사항을 추가하는 것<br>

git log<br>
		# commit이 잘 되었는지 확인<br>


git remote add origin https://github.com/formicidae225/2024-1-Beginner-Study.git<br>
		# 로컬 리포지토리와 연결하기 위함<br>
git branch –M main<br>
		# branch 이름을 main으로 바꾸기 위함 (잘 모르겠음)<br>
git push -u origin main<br>
		# local이 git hub에서 공유되게 하기 위함(초기에 한 번만 쓰임)<br>

git push origin main<br>
		# local이 git hub에서 공유되게 하기 위함