## CLI basic (Unix Commands)
`$`:프롬프트 터미널 명령어이다

``
`ctrl+c` : 취소하기 
``

## ctrl 명령어

- `ctrl + c` : 취소
- `ctrl + 1` : 클리어
- `↑↓` : 기존명령어 불러오기
- `tab` : 자동완성


## 명령어

-  `touch` : 파일생성
-  `ls` : 현재 폴더의 내용을 보여줌(list)
-  `ls -a` : 모든 내용
-  `rm` : 파일삭제
-  `rm -r` : 파일/폴더 모두삭제 (recursively)
-  `rm -rf` : 파일/폴더 강제삭제 (force)
-  `pwd` : 현재 작업 폴더 = 내 위치 (Present Working directory)
-  `mkdir` : 폴더생성
-  `rmdir` : 빈폴더 삭제
-  `cd` : 폴더 이동
-  `cp`: 파일복사
-  `cp -r`:파일/폴더복사
-  `mv` :파일/폴더 이동 + 이름바꾸기


## 경로관련

- `.` : 현재 폴더
- `..` : 상위 폴더
- `~` : 홈디렉토리
- `/` : root dir
- `.xxx`: `.`으로 시작 >> 숨긴 파일/폴더

  
  ## 깃 명령어
  - `git add` : 스테이지에 올리는 명령어
  - `touch` : 파일 생성 명령어
  

  ## 수업 과제
   1. d.md 를 생성한다.
   $ touch d.md
   
   2. d.md를 commit 한다(메시지 'create d.md')
   $ git add d.md
   $ git commit -m 'create d.md'
   
   3. 모든 마크다운 파일들을 수정한다 (내용은 자유자재)
   
   4. a.md, b.md 만 커밋한다 (메시지 'a, b')
   $ git add a.md b.md
   $ git commit -m 'a, b'
   
  5. c.md, d.md 만 커밋한다 (메시지 'c, d')
   $git add c.md d.md
   $git commit -m 'c,d'
   
  6.모든 마크다운 파일들을 수정한다.
  
  7. 모든 파일들을 한번에 커밋한다 (메시지 'all commit')
   $ git add .
   $ git commit -m 'all commit'
