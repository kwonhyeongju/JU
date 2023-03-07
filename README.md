## git 시작하기

- 사용자 정보 입력

`git config --global user.name "이름"`

`git config --global user.email "메일 주소"`

- 디렉터리 생성

`mkdir 이름`

- vim(텍스트 편집기) 생성

`vim 이름.txt`      i 누르면 입력모드 , esc 누르면 ex모드

- git 저장소 디렉터리 만들기

`mkdir 폴더이름`

-깃에서 사용할 수 있게 디렉터리 초기화하기

`git init`

- 깃의 상태 확인

`git status`

## 버전 만들기

**작업 트리 → 스테이지 → 저장소**    (스테이지, 저장소 는 .git 디렉터리)

**untracked → unmodified → modified → staged**

- 스테이징

`git add 파일`

- 커밋

`git commit -m "message"`

- 한 번 커밋한 파일을 한꺼번에 스테이징,커밋 처리하기

`git commit -am "message"`

- 저장소에 저장된 버전 확인

`git log (--stat)`

(HEAD -> main) ; 이 버전이 가장 최신 버전이라는 뜻

영문,숫자로 이뤄진 긴 문자열 ; 커밋을 구별하는 아이디, git hash

- 커밋 메세지 수정하기

`


              
              
