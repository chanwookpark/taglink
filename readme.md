개인적으로 개발중인 위키에서 사용하고자 개발한 간단한 태그 서비스이다

동작 방식은...

1. 클라이언트가 url과 태그들을 서버로 보냄
1. 등록안 url이면 등록
1. 태그들과 매핑되는 url을 검색
1. 매칭되는 url이 많은 순으로 정렬해 리턴
1. 클라이언트는 받아서 글 말미에 뿌리기
 
구현은...
1. url과 태그는 1:다
1. 클라이언트는 js로만
1. 스펙은 hal로 (4번 하면 내가 할게 없네 ㅎ)
1. 서버는 몽고에 spring data rest로 쉽게 만들기. 몽고랩이 공짜라서 몽고로..
1. boot 톰캣aws에 올려보자 (아니면 managed 서비스를 써 볼까..) 
1. 인증은...일단 안 한다 ㅎㅎ