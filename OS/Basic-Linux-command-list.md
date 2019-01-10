

기본적인 리눅스 커맨드 목록
==========================
리눅스 유저인 저조차도 잘 몰라서 써봅니다. 서버 환경에서 작업하려니까 리눅스는 거의 필수더라고요.

  * 기초 리눅스 
    * cd /path/; moving to specific directoty 
    * ls; 특정 경로의 파일 목록 file list on the specific path 
    * ls -al; 특정 경로 파일의 소유권을 확인 
    * pushd = push directory ; 디렉토리 이동에 사용하는 리눅스 명령어  cd ../path/와 비슷한 원리로 활용한다.
    * popd = pop directory ; 디렉토리 이동에 사용하는 리눅스 명령어, 이전 경로로 돌아간다.


  * 복사하기
    * cp -p file name; 'file name'으로 지정한 파일 복사하기 
    * cp -pr; 파일에 걸려있는 권한까지 동일하게 지정하여 파일 복사하기 
    * cp -i; 복사할 때 뜨는 questions 보여주기 
   
  * 기타
    * ll -t f; 파일 리스트를 시간대별로 최신>과거 순으로 나열 (descending)
    * ll -F | grep (searching content) : 특정 키워드를 가진 파일목록 검색 
    * find (path) -name (file keyword in specific path) : 특정 경로 내 파일검색
    * vi fime_name; vi에서 file 편집하기 
    * chown username:groupname file_name.sh; 리눅스 파일 소유권 변경 

  * command A || Command B; 두 가지 종류의 리눅스 커맨드 동시에 실행하기  