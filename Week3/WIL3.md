#3주차 웹스터디 과제: "자기소개" 기능 만들기

1. 해야할 것
	-원본 레포지토리 Fork #깃허브 웹에서
	-Fork한 레포지토리를 로컬로 받아오기
	-로컬에서 branch 생성
	-해당 branch에서 폴더 생성
	-폴더 내에 README.md 생성 후 자기소개 내용 기입
	-remote 레포지토리로 생성한 branch push
	-원본 레포지토리에 Pull Request #깃허브 웹에서

2. Git CMD
	-Fork한 레포지토리를 로컬로 받아오기
		#명령어 형식: git clone [<options>] [--] <repo> [<dir>]
		ex) 'git clone https://github.com/shimminseo/webstudy-homework-minseo-2798.git'

	-branch 생성
		#먼저 원하는 레포지토리로 이동
		ex) 'cd C:\Users\rebec\webstudy-homework-minseo-2798'

		#명령어 형식: git branch [생성할 branch 이름]
		ex) 'git branch minseo#2798'

		#branch 확인 명령어: 'git branch -r' or 'git branch'

	-해당 branch에서 폴더 생성
		#branch 이동 명령어: 'git checkout [branch 이름]'
		
		#명령어 형식: mkdir [폴더명]
		ex) 'mkdir minseo#2798'

	-폴더 내에 README.md 생성 후 자기소개 내용 기입
		#VS로 README.md 작성

	-remote 레포지토리로 생성한 branch push
		#remote에 같은 이름의 branch가 존재할 때 명령어: 'git push'

		#아닌 경우, 명령어 형식: git push --set-upstream origin [브랜치명]
		ex) git push --set-upstream origin minseo#2798


3. Commit Message 구조
	-type(타입) : title(제목)

	-body(본문, 생략 가능)

	-Resolves : #issueNo, ...(해결한 이슈 , 생략 가능)

	-See also : #issueNo, ...(참고 이슈, 생략 가능)
 
	#참조 https://jane-aeiou.tistory.com/93