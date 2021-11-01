SockJS 연결은

서버주소 /api/socket/chat으로 하면됨

1. socket 주소 : 우리 서버주소/api/socket/chat



귀 열어놓는 주소 : /sub/자기회원고유id

보내는 주소 : /pub/id

Stomp : 귀 열어놓고 닫고 하는거



보내기 버튼 클릭 시 

내용 : 

내 id :

상대 id : 

sessionid : 

json으로 만들어서 보내줘야함

상대방(pub로) 보내는걸로 하면됨



user_id -> 해당 유저의 모든 채팅 목록 확인

session_id는 100개까지 보임

message_id 100개 이전꺼 확인할 때 확인할 수 있게함