<<<<<<< HEAD
test
=======
# test



# Vue LifeCycle



* state

  * 데이터 라고 생각!!!

* getters

  * 데이터를 가져오는 메서드다!!

* actions

  * 데이터 변동에 대한 요청보내기, 서버로 요청!
  * 비동기통신(서버와 통신)
  * dispatch로 호출한다.

* mutations

  * 데이터의 값을 넣는 메서드 -> 데이터 값을 직접 변동주는 곳

  * commit으로 호출! ( mutations에 있는함수 이름 쓰고, 세팅할 데이터 )

    



* 동작순서
  * (상황에 따라 다름, 페이지 생성 시 or 클릭 등등) actions로 서버와 통신해서 response(응답)을 받는다.
  * 받아온 데이터 값을 mutations을 통해서 state에 있는 변수에 담는다.
  * getters로 값을 가져와서 화면을 구성한다.
>>>>>>> 2fb16ec8083ce400f970e16c49751ecb91fc2187

