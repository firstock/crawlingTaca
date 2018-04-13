실행방법

세팅
vscode, vscode plugin::python_4개, mariaDB_pw:ch11_port:3307 설치 후

mariaDB client에서 패스워드:ch11 입력하고
db.sql에 있는 코드 전체 복사> 붙여넣기

관리자::cmd에서
pip install selenium bs4 pymysql pymysql

vscode에서
폴더 열기> 해당 폴더를 선택
ctrl+` 누르고 나온 통합터미널에서 python run.py

- pymysql 관련 에러
pymysql	pip 가 최신 버전인지 확인 후,
	관리자::cmd에서
	pip install pymysql
	
	그래도 안 될 경우, pip uninstall pymysql
	하고 재설치
	한 후  OS잠금화면 봤다가 다시
	
	그래도 안 될 경우, mariaDB client 종료
	한 후 OS잠금화면 봤다가 다시
	
	그래도 빨간 줄이 쳐있다?
	무시하고 실행 ㄱㄱ. 실행은 잘 되는데 빨간줄만 쳐있는 것
	다 잘 되는 건데, 플러그인에 따라 멀쩡한데 빨간줄 치는 경우가 있음
