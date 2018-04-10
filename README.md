# TransSum00
Translate and Summarize Articles base repository


< What TO DO >
* 5명이 1 team으로 작업
+ 조장(1) , 조원(나머지)
+ 20 pages 내외의 영문 문서를 5부분(각 조의 인원) 으로 구분하여 각자가  한글 요약본( 1page 내외)을 입력한후 – initial version
+ 전체의 내용이 일관성이 있도록 전체 조원이 review를 하면서 수정

+ 모든 조원이 read 를 할 수 있으나, push  할때는 conflict resolve 함
+ 초기 버전의 등록, review에 의한  update를 진행함
+ Review 과정에는 모든 사람이 참여할 수 있음
+ Review 과정은 조장이 관리한다
+ 최종 version의 완료 판단도 조장이 함

< This file contains >

이 파일은 번역 실습 과제 관련사항에 대한 게시 입니다.

과제는 조편성이 확정되는 4월 5일 부터 시작하여 2주간
진행되어서 4월 19일까지 완료 하십시오.

각조에게 repository를 하나씩 배정할 것인니 그 repository에
해달 결과물을 저장하시면 됩니다.
진행 사항 및 정리할 내용 관련 report는 해당 조의 repository
내에 작성하는 README.md 파일에 기록하십시오.

과제 결과는 별도의 내용을 제출할 필요 없으며
보고할 내용은 조 repository의 README.md 파일에
번역/요약 결과는 동일 repository에 파일을 작성하면됩니다.
물론 각 파일에 대한 변경 history응 github에 저장이 되어
있으니 작업만 제대로 하시면 됩니다.

< User Registration >

아래의 site를 연결하여 본인자신의
github 계정 관련 사항은 입력해 주시기 바랍니다.

사용자 등록 구글 폼 생성
https://goo.gl/forms/u0T74DCxGdgfYNSz1

< Guide >

1. github organization 승인
  위와 같은 이메일이 도착하면 "Join 다빈치 오픈소스 소프트웨어 센터"를 클릭한 뒤 그룹에 가입한다.  
 ![승인](https://i.imgur.com/J5KnhfN.png)

2. github 프로젝트 승인
 위와 같은 이메일이 도착하면 프로젝트를 승인하여 그 프로젝트에 대한 collaborators로 등록한다.
![프로젝트 승인](https://i.imgur.com/5b0GNSq.png)

3. github 프로젝트 시작
![프로젝트 시작](https://i.imgur.com/GbvFrni.png)
 자신의 repository로 이동하면 위와 같은 화면이 나온다.

  아래와 같이 입력하면 자신의 GitHub 프로젝트를 시작할 수 있다.

![프로젝트 생성](https://i.imgur.com/xL6dAy7.png)

> 간단 설명
```bash
 mkdir project                 : 현재 디렉토리에 project라는 이름을 가진 폴더 생성
 cd project                    : project 디렉토리로 이동
 echo "내용" >> README.md       : "내용"을가진 README.md 파일을 생성
 git config --local user.email & user.name "내용": 커밋할 때 기록 될 신상정보 정의  
 git commit -m "커밋 메시지"      : 커밋
 git remote add origin https:~  : 원격 저장소의 주소 설정
 git push -u origin master      : 푸쉬

 ```

  프로젝트가 GitHub에 정상적으로 들어간다면 다음과 같은 화면을 볼 수 있다.

  ![프로젝트](https://i.imgur.com/0790thZ.png)

  이제 프로젝트를 시작하면 된다!
