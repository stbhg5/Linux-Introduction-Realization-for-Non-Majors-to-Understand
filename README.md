# Linux-Introduction-Realization-for-Non-Majors-to-Understand
비전공자도 이해할 수 있는 리눅스 입문/실전

<br/><br/><br/>

<h2>1. 리눅스 기본 개념 / 리눅스 실습 환경 구축<h2/>
    <a href="https://stbhg5.tistory.com/566">리눅스(Linux)란?</a><br/>
    <a href="https://stbhg5.tistory.com/567">다양한 리눅스의 종류 / 리눅스 배포판</a><br/>
    <a href="https://stbhg5.tistory.com/566">리눅스(Linux)란?</a><br/>
    <a href="https://stbhg5.tistory.com/579">리눅스 환경 구축하는 방법 (feat. AWS EC2)</a><br/>
    <a href="https://stbhg5.tistory.com/580">[실습] AWS로 리눅스(Ubuntu) 환경 구축하기</a><br/>
    <a href="https://stbhg5.tistory.com/581">터미널(Terminal)이란 ?</a><br/>
    <a href="https://stbhg5.tistory.com/594">리눅스를 실행시키자마자 뜨는 첫 화면 해석하기 / 기본 조작법 익히기</a><br/>
    <br/>

<h2>2. 필수로 꼭 알아야 하는 기본 명령어<h2/>
    <a href="https://stbhg5.tistory.com/595">리눅스에서의 파일(file), 디렉터리(directory)의 의미</a><br/>
    <a href="https://stbhg5.tistory.com/597">폴더 이동하면서 파일 둘러보기 / 리눅스의 기본 폴더 구조 (pwd, cd, ls)</a><br/>
    <a href="https://stbhg5.tistory.com/598">파일 종류 확인 / 숨김 파일 조회 (ls -l, ls -a)</a><br/>
    <a href="https://stbhg5.tistory.com/599">리눅스 명령어들의 공통적인 패턴 - 옵션(Option)</a><br/>
    <a href="https://stbhg5.tistory.com/600">상대 경로, 절대 경로란? / 구분 방법</a><br/>
    <a href="https://stbhg5.tistory.com/602">경로에 물결 표시(~)는 무슨 의미일까?</a><br/>
    <a href="https://stbhg5.tistory.com/605">파일 및 디렉터리 생성 / 삭제 (touch, mkdir, rm)</a><br/>
    <a href="https://stbhg5.tistory.com/606">파일 및 디렉터리 복사 / 이동 / 이름 변경 (cp, mv)</a><br/>
    <a href="https://stbhg5.tistory.com/607">명령어를 일일이 다 칠 필요 없는 자동완성 기능 / 이전에 썼던 명령어 불러오기</a><br/>
    <a href="https://stbhg5.tistory.com/609">[연습문제] 지금까지 배운 명령어 실전처럼 써먹어보기</a><br/>
    <br/>

<h2>3. 파일을 작성/조회할 때 자주 사용하는 명령어<h2/>
    <a href="https://stbhg5.tistory.com/610">리눅스에서 가장 많이 사용하는 텍스트 에디터 (vim)</a><br/>
    <a href="https://stbhg5.tistory.com/611">vim 에디터 기본 사용법 - 1</a><br/>
    <a href="https://stbhg5.tistory.com/612">vim 에디터 기본 사용법 - 2</a><br/>
    <a href="https://stbhg5.tistory.com/616">파일에 작성된 내용 보기 (vim, cat)</a><br/>
    <a href="https://stbhg5.tistory.com/619">[연습문제] 지금까지 배운 명령어 실전처럼 써먹어보기</a><br/>
    <br/>

<h2>4. 리눅스에서 빈번하게 마주치는 권한 문제(Permission Denied)<h2/>
    <a href="https://stbhg5.tistory.com/621">Permission Denied 에러 마주치는 경우</a><br/>
    <a href="https://stbhg5.tistory.com/624">사용자(user), 슈퍼 사용자(super user)란?</a><br/>
    <a href="https://stbhg5.tistory.com/625">그룹(group)이란?</a><br/>
    <a href="https://stbhg5.tistory.com/627">권한(Permission)이란?</a><br/>
    <a href="https://stbhg5.tistory.com/628">[실습] 왜 Permission Denied 에러가 발생하는 지 원인 분석해보기</a><br/>
    <a href="https://stbhg5.tistory.com/633">권한 변경하는 방법 (chmod)</a><br/>
    <a href="https://stbhg5.tistory.com/634">[실습] 보안을 위해 파일 접근 권한 제한하기</a><br/>
    <a href="https://stbhg5.tistory.com/635">어떠한 제약도 없이 모든 기능을 사용할 수 있는 관리자 권한 (sudo)</a><br/>
    <br/>

<h2>5. 외부 프로그램을 설치할 때 사용하는 패키지 매니저 (apt)<h2/>
    <a href="https://stbhg5.tistory.com/636">패키지 매니저(Package Manager)란?</a><br/>
    <a href="https://stbhg5.tistory.com/637">자주 사용하는 apt 명령어 4가지</a><br/>
    <a href="https://stbhg5.tistory.com/638">[실습] apt를 활용해 Nginx 설치해보기</a><br/>
    <a href="https://stbhg5.tistory.com/639">[보충 자료] apt 명령어를 쓸 때 sudo를 써야 하는 이유</a><br/>
    <br/>

<h2>6. 로그 남길 때 많이 사용하는 표준 출력(stdout), 표준 에러 출력(stderr)<h2/>
    <a href="https://stbhg5.tistory.com/641">표준 출력(stdout)이란?</a><br/>
    <a href="https://stbhg5.tistory.com/644">[실습] 표준 출력(stdout) 활용해보기</a><br/>
    <a href="https://stbhg5.tistory.com/646">표준 에러 출력(stderr)이란?</a><br/>
    <a href="https://stbhg5.tistory.com/647">표준 출력(stdout)과 표준 에러 출력(stderr)의 추가 기능</a><br/>
    <a href="https://stbhg5.tistory.com/652">[실습] Spring Boot 서버가 출력하는 로그를 파일로 남기기</a><br/>
    <br/>

<h2>7. 실무에서 백엔드 서버를 운영할 때 자주 사용하는 명령어<h2/>
    <a href="https://stbhg5.tistory.com/656">특정 키워드가 들어간 문장만 찾고 싶을 때 (grep)</a><br/>
    <a href="https://stbhg5.tistory.com/658">리눅스에서 실행 중인 프로세스 조회하기 / 종료하기 (ps, kill)</a><br/>
    <a href="https://stbhg5.tistory.com/660">[실습] 실행시킨 Spring Boot 프로세스를 조회하고 종료해보기</a><br/>
    <a href="https://stbhg5.tistory.com/661">터미널 창을 끄더라도 프로그램이 계속 실행되도록 만들기 (nohup, &)</a><br/>
    <a href=""></a><br/>
    <br/>

